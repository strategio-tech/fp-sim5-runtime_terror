
# Team Runtime Terror Startegio Final Project: Wallet Share

Wallet Share is a virtual wallet application. Users will have the ability to send money virtually to one another through their virtual wallet.
In addition, users can use their virtual wallet to complete transactions to pay for goods. Each user will have the ability to create their 
own wallet and connect their credit card to their virtual wallet account from an external "banking" API that our system uses. With added security, users can feel safe sending money without
having to worry about exposing their credit card information.

## Acknowledgements
 - Original Project Creator: Petar Bivolarski at Telerik Academy
 - [Original Project Link](https://github.com/PetarBivolarski/Virtual-Wallet-Fintech-Web-Application)
 

## Features

- Email confirmation for new users.
- Email confirmation for large transactions with an expiry period.
- Multiple cards (edit/delete) and wallets ("make primary wallet" feature).
- Referral system, where users can refer their friends by having our system
  send a registration link via an e-mail and receive 20 euro bonus, if the registration is completed within the expiry period
- Detailed Transaction History, where users can filter Transactions by Date, Direction (Incoming/Outgoing), Counterparty,
  and sort by Amount and Date.
- Under the "My profile" page, the user can see his personal information, his default wallet and total balance, latest 3 transactions and a bonus feature of "inspirational quotes". Users can edit their personal details and change passwords.
- Donation feature, where users can choose to donate a euro upon topping-up (just like with some Bulgarian ATMs). The money go to a specifically created Donation Project User Account, and the total gathered sum from donations is visible on the homepage.

## Tech Stack

**Frontend:**  Spring MVC Framework with Thymeleaf template engine, JavaScript and jQuery custom functions, CSS template

**Backend:** Java, Spring MVC, Spring Boot Framework, Hibernate, Spring security

**CI/CD:** AWS Elastic Beanstalk, AWS CodeBuild, AWS CodeCommit, AWS Pipeline 

**Build:** Gradle, AWS CodeBuild

**Monitor:** AWS CodePipleline, AWS CloudWatch

**Database:** AWS RDS, MySQL
![image](https://user-images.githubusercontent.com/62210528/203384067-da834391-7fdd-4864-8476-bde4ccaf56b9.png)



## Installation

 - Download Repo:
```bash
  git clone [Repo URL]
```
 
 - Update the neccessary login credentials in the application.properties file located under VirtualWallet\src\main\resources.
 - The scripts for creating the database schema can be found in VirtualWallet\src\main\resources\sql\schema.sql.
 - The test data with all SQL scripts can be found in VirtualWallet\src\main\resources\sql\schema-data.sql.
 - To build and run the project, simply run VirtualWalletApplication.class located under VirtualWallet\src\main\java\a16team1\virtualwallet.
 - Under MySQL connections click the + button
 - Add your DB connection name
 - Under parameters tab update the host name to the database endpoint
 - Update the user and password credentials to be able to access the database endpoint
 - Connect to database

    
## Screenshots

```bash
                    HomeScreen
```
![App Screenshot](https://github.com/PetarBivolarski/Virtual-Wallet-Fintech-Web-Application/raw/master/application-screenshots/home/1.PNG)

```bash
                    Filter & Sort
```
![App Screenshot](https://github.com/PetarBivolarski/Virtual-Wallet-Fintech-Web-Application/blob/master/application-screenshots/home/3.PNG?raw=true)

```bash
                Transaction History
```
![App Screenshot](https://github.com/PetarBivolarski/Virtual-Wallet-Fintech-Web-Application/raw/master/application-screenshots/my-profile/2.PNG)

