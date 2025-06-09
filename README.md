 ## 📝 Overview :
"A Blockchain-Based Question Paper System uses decentralized ledger technology to securely store, distribute, and track exam question papers. This prevents unauthorized access, tampering, and leaks, ensuring transparency and integrity in the examination process."

![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)

## 🚩 Summary :
## Objective:
To secure question papers using blockchain to eliminate leaks, tampering, and unauthorized access.

## Technology Used:

Blockchain Platform: Ethereum / Hyperledger

Smart Contracts: Automate locking/unlocking of papers

Encryption: AES/RSA for added security

Access Control: Role-based via smart contracts

 ## Key Features:

🔒 Immutability: Once uploaded, question papers cannot be altered.

📈 Traceability: All access and changes are recorded on-chain.

⏱️ Timed Access: Papers unlock at a predefined date/time via smart contracts.

👤 Role Management: Different roles for admin, examiner, and centers.

🧾 Auditability: Every transaction is logged and verifiable.

## ⚙️ Working Process
Paper Creation: Examiner creates and encrypts question paper.

Upload to Blockchain: Paper is hashed and stored using IPFS/Swarm with hash on blockchain.

Smart Contract Deployment: Smart contract holds the hash and sets access time.

Paper Distribution: On exam day, access is unlocked based on time-triggered contract.

Verification & Access: Only authorized centers can retrieve and decrypt the file using private keys.

## 🧠 Benefits
✅ Eliminates human error and unauthorized leaks

✅ Transparent and traceable paper handling

✅ Reduces dependency on physical logistics

✅ Enables real-time monitoring of paper access

## ⚠️ Challenges
⚙️ Need for blockchain infrastructure in institutions

🧑‍🏫 Training staff to use decentralized tools

🔑 Managing secure private keys and access recovery

📶 Dependence on reliable internet connectivity

## 🧪 Use Cases
University Exams

Government Competitive Exams

Online Certification Tests

Private Institution Assessments


![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)


## 🚩 General Features and Interfaces:
Feature | Images
------------ | -------------
 **Hompage**  
 Fast, easy to use, and incredibly convenient with a minimalistic UI! | ![homepage](https://github.com/Pjahanavi/Blockchain/blob/5b37683504d39c89d5173395a478c04e0d980bff/images/Screenshot%202025-04-06%20130408.png)
**Contributor Dashboard** 
All the accepted questions are shown here|![registrationPage](https://github.com/Divijkatyal0406/CrowdQuest/blob/resolved/images/c_dashboard.png)
**Add Question Section**
Stakeholders can add questions throught this interface with ease |![professor](https://github.com/Pjahanavi/Blockchain/blob/9aac9a8f4423fc59400e0bca57c0241fe1b927d9/images/Screenshot%202025-03-14%20120355.png)
**OCR and voice input**
Stakeholders can opt to upload image from book or can speak out the question |![professor](https://github.com/Divijkatyal0406/CrowdQuest/blob/resolved/images/ocr.png)
**Virtual keyboard**
Virtual mathematical keyboard to ease the process of typing any mathematical equation |![professor](https://github.com/Divijkatyal0406/CrowdQuest/blob/resolved/images/virtual.png)
**Sample papers**
Sample paper sets with various difficulties for practice |![professor](https://github.com/Divijkatyal0406/CrowdQuest/blob/master/images/sample.png)
**Discussion Forum**
Discussion section to share doubts and discuss something meaningful with the world |![professor]()

![-----------------------------------------------------](https://github.com/Pjahanavi/Blockchain/blob/e81fffa4317941432a482d770f8fe8ac154daa65/images/Screenshot%202025-04-06%20124823.png)

## 🚩 Features of Question Paper Generation:
Feature | Images
------------ | -------------
**Supervision** The expert generating the paper and previewing it will be under supervision | ![facenot](https://github.com/Divijkatyal0406/CrowdQuest/blob/master/images/webcam.png)
**Cell Phone Detection** If any expert tries to click pictures via phone, the tensorflow model detects it and immediately denies the access for later interaction | ![cell phone detection](https://github.com/Divijkatyal0406/CrowdQuest/blob/resolved/images/phone_detect.png) 
**Disabled Copy/Paste** Disabled copy/paste for entire paper generating process
**Prohibited Object Detection!** Any object that will block the view of camera or if person is not visible, the system simply denies the access to the system
**Multilingual Paper Support!** Paper can be generated in both English/Hindi Language | ![booldetect](https://github.com/Divijkatyal0406/CrowdQuest/blob/resolved/images/hindi_q.png)
**Highly Flexible!** Full flexibility is provided to generate the paper in terms of difficulty and inaccordance with current syllabus | ![booldetect](https://github.com/Divijkatyal0406/CrowdQuest/blob/resolved/images/paper.png)
**Editable!** The paper generated automatically is also manually editable according to board's needs | ![booldetect](https://github.com/Divijkatyal0406/CrowdQuest/blob/resolved/images/manual.png)

![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)

## 🚩 Features of Question Paper Encryption:
Feature | Images
------------ | -------------
**Setting examination** Techer can schedule an examination with the generated paper and proceed for paper encryption | ![facenot](https://github.com/Divijkatyal0406/CrowdQuest/blob/resolved/images/schedule.png)
**Encrypting the paper** The examination paper is encrypted using AES & RSA algorithm and send to IPFS network for furthur distribution | ![cell phone detection](https://github.com/Divijkatyal0406/CrowdQuest/blob/resolved/images/encrypt.png) 
**Registration for examination** Teacher's can share this link with the CBSE examination centres who can then register for their respective paper | ![ctrlkey](https://github.com/Divijkatyal0406/CrowdQuest/blob/resolved/images/exam_html.png)
**Auto Download** The paper will be auto downloaded in the registered centre's system just in time to avoid any compounding risk of paper leakage | ![booldetect](https://github.com/Divijkatyal0406/CrowdQuest/blob/resolved/images/exam_html-1.png)

![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)


**Other Features :**
1. Email updates on expert's email id about questions summary on expert's dashboard.
2. Reward notifications to the person who contributed the question.
3. Report functionality to send the question again back for review.
4. Subject filters.
5. Question search functionality.
6. Question text to speech reader.

![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)

## 🔐 Expert authentication system
Expert's authentication can be the primary security breach to the board's question paper generation and distribution.
The diagram below shows all steps to generate the expert's login data hash from the username, the password, the 6 digit code (that will be provided by respective board to each teacher expert) and the ethereum address. To register the user must fill a form to provide the username, the password and the 6 digit code, the ethereum address is retrieved directly from the wallet. This address is associated to the username to generate a signature via the web3 function sign, the generated signature is hashed (hash1). The password is associated with the 6 digit code to generate another hash (hash2). The two hashes are combined to generated the final hash that is stored in the smart contract(Refer Authentication.sol). To login, the user must be connected to the Blockchain with the same address used during registration, and fill the login form with right username, password and the 6 digit code. The back-end solidity code then generates the hash with this login information and compares it with the hash that was stored in the smart contract by the ethereum address which request the login, if the two hashes match, then the user is authorized to login, if not, the access is denied.
![auth-diagram](https://github.com/Divijkatyal0406/CrowdQuest/blob/master/images/login_encrypt.png)


![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)


## 🌐 Web flow
![Flowchart](https://github.com/Pjahanavi/Blockchain/blob/f7f64fe4596d69ee3bcd9c5d5149ea214f4a81c6/images/webflow.png)
![Flowchart](https://github.com/Pjahanavi/Blockchain/blob/da3957fc398ab2362390e4f4df3470635bd7c450/images/dataflow1.png)

![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)

## ⛓️ Encryption Model
![Flowchart](https://github.com/Divijkatyal0406/CrowdQuest/blob/resolved/images/ipfs_encrypt.png)

![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)


##  🚩 Technologies used:

#### Programming Languages : Solidity, Javascript, HTML, CSS
#### Face Recognition Model :  TensorflowJS
#### Database : Polygon (Ethereum Layer-2) Blockchain
####  Frameworks/Libraries/Tools : Bootstrap, FreeOCR, Google Transalate, Truffle, Ganache, VSCode, IPFS, Moralis, Web3, Tokenizer
#### Version Control : Git
###### You can also see the list of dependencies in the package.json file.

![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)

## 🚩Installation/Environment Setup 

  #### Login Credentials 
       Username - "Jaanu" password - "$%Rfth7" passcode - "123456"
       Ethereum address - "0xED620CdD26E4adfae79Ea12f5fadd2c4c6ab54a4"
       
 
 #### 1. Install node packages
  * Move to the parent/root directory (Questionpaper) cd Questionpaper
  * Write the following command and press enter to download all required node modules.
 
   ```
   $ cd Questionpaper
   $ npm install 
  ```
  
#### 2. Ganache
  - Open Ganache and click on settings in the top right corner.
  - Under **Server** tab:
    - Set Hostname to 127.0.0.1 -lo
    - Set Port Number to 8545
    - Enable Automine
  - Under **Accounts & Keys** tab:
    - Enable Autogenerate HD Mnemonic

#### 4. IPFS
  - Fire up your terminal and run `ipfs init`
  - Then run 
    ```
    ipfs config --json API.HTTPHeaders.Access-Control-Allow-Origin "['*']"
    ipfs config --json API.HTTPHeaders.Access-Control-Allow-Credentials "['true']"
    ipfs config --json API.HTTPHeaders.Access-Control-Allow-Methods "['PUT', 'POST', 'GET']"
    ```

    > Note: If you face any issues with the above command on windows, try using command prompt and escape sequences or git bash.
#### 5. Metamask
  - After installing Metamask, click on the metamask icon on your browser.
  - Click on __TRY IT NOW__, if there is an announcement saying a new version of Metamask is available.
  - Click on continue and accept all the terms and conditions after reading them.
  - Stop when Metamask asks you to create a new password. We will come back to this after deploying the contract in the next section.
  
#### 6. Smart Contract

1. Install Truffle using `npm install truffle -g`
2. Compile Contracts using `truffle compile`

#### 7. Starting your local development blockchain
  - Open Ganache.
  - Make sure to configure it the way mentioned above.
    7.1. Open new Terminal and deploy contracts using `truffle migrate`

#### 8. Local server

1. Install Node lite-server by running the following command on your terminal `npm install -g lite-server`

#### 9. Run Locally
  * Move back to the parent directory by cd..
  * While you are still inside the cloned folder, write the following command to run the website locally.
 
 ```
   $ npm run dev
 ```
 
 
 ###### NOTE: After performing all the steps give a few seconds for frontend to load and the port by default will be ```http://localhost:3000/```
