# Domain-Generation-Algorism
### Classification of Domain Generation Algorithm based Malware using Ensemble and Deep Hybrid Learning. 
This work focus was on designing efficient models for the detection and 
classification of DGA-based malware based on the reliability and accuracy of predictions in both 
binary and multiclass classification by using ensemble and deep hybrid learning (ML+DL) 
algorithms. 
## Domain Generation Algorithm
- A domain generation algorithm (DGA) is an algorithm that serves as a tool for attackers to generate a massive, random domain name. The generated domain names are used as a
rendezvous point and create a command-and-control channel between the attackers and malware. So, hackers can send any command to the malware to do their wish.
- DGA detection is one of the major challenges in DNS security areas. Since malware uses different seeds and tries to imitate the pattern of normal domain names by concatenating pseudo-randomly chosen English dictionary words, to get domain names and achieve the effect of concealment and confrontation
https://www.springerprofessional.de/en/classification-of-dga-based-malware-using-deep-hybrid-learning/26964632 
## Dataset 
1. **Benign Dataset:** Alexa Top 1M as legitimate datasets https://www.kaggle.com/datasets/cheedcheed/top1m 
2. **Malicious Dataset:** Netlab360 DGA Feeds https://blog.netlab.360.com
3. **Unseen Datasets:** are datasets  to test our model on unseen malware families. These domain family data were extracted from DomCop Top 1M and DGArchive.
## Dataset preprocessing
* Data Labeling
* Data cleaning
* Encoding Technique
* Feature engineering
- Length: length of domain names based on the character sequence.
- Entropy: Entropy (impurity) measurements in a domain.
- First digit index: first digit in the domain.
- Vowel-to-consonant ratio: ratio of vowel to consonants in the domain.
- Vowel-to-character ratio: the ratio of vowels to total domain character.
- Consonant to character ratio: the ratio of consonants to total domain character.
- Domain level number: the level of domains separated by dots.
- Shannon entropy: character randomness in a domain.
- Alexa gram: Alexa algorithms to measure word grams.
- Word gram: number of n-grams in a domain.
## Machine learning model used
* **Ensemble learning**
- Random Forest (RF)
- Extra tree classifier
- XGBoost classifier
- AdaBoost (AB)
- Voting ensemble classifier
- Stacking ensemble classifier
* **Deep Hybrid Learning (DHL)**
  - Deep Hybrid Learning is the result of fusion networks, which can be obtained by combining Deep Learning and Machine Learning techniques.
  - CNN and LSTM deep learning algorithms were was fused with 7 machine learning algorithms; DT, LR, NB, RF, AB, XGB, and ET.
## Software tools 
* Goggle co-laboratory
