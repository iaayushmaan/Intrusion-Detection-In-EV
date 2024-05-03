# Intrusion detection in EV

This project aims to enhance the security of vehicular communication by developing an intrusion detection system for CAN (Controller Area Network) buses.

Dataset 1 is a collection of 461,341 network traffic examples categorized into four classes: DoS attacks, fuzzy attacks, impersonation attacks, and normal traffic. These datasets were collected from the Kia Soul car by logging CAN traffic via the OBD-II port during message injection attacks.

Dataset 2 is a collection of 313,930 network traffic examples with four classifications: flooding attacks, fuzzy attacks, malfunction attacks, and normal traffic. These datasets were collected from the Chevrolet Spark car using the same method as Dataset 1.





## Step-by-step procedures to develop the Intrusion Detection System

  1. Clone the project

```bash
  git clone https://github.com/iaayushmaan/Intrusion-Detection-In-EV.git
```

2. Go to the project directory

```bash
  cd ./Intrusion-Detection-In-EV
```

3. Download Datasets from the drive link (https://drive.google.com/drive/folders/1jV-IxfUfVqG-5OiLjVOTk9Qy3RLSmtzb?usp=sharing)

4. Copy the datasets in the main directory

5. You are good to go!




## Observations

DT demonstrated the highest accuracy for intrusion detection in both Dataset 1 and Dataset 2. When we analyze the precision values of SVM, DT, and KNN classifiers on Dataset 1, we notice that they perform differently for different types of attacks. SVM shows high precision for all attacks, while DT performs exceptionally well for DoS and attack-free states. However, KNN struggles a bit with impersonation detection.

