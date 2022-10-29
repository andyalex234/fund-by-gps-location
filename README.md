
<h1 align="center"><img src="https://github.com/andyalex234/admin/blob/main/public/logo.png?raw=true" height="128"><br>Fund By GPS Location</h1>
<p align="center"><strong>A dApp that Fund employee eth  based on fund by Location Smart Contract and Ethereum blockchain</strong></p>


**Table of Content**
* [Project Overview](#project-overview)
* [Installation Guide](#installation-guide)
* [Project Structure](#project-structure)
* [LICENCE](#licence)
* [Contributers](#contributors)
* [Acknowledgement](#acknowledgement)

## Project Overview
The refund by location smart contract is aimed to be used when one party, for example an employer, agrees to pay another party, for example an employee, for being present in a certain geographic area for a certain duration. The employee’s phone sends its GPS location to a smart contract at a certain interval. Based on the pre-agreed contract codified in an Ethereum smart contract, a cryptocurrency payment is executed when all the agreed conditions are met.  
If, at any point, the GPS sensor indicates that an employee is outside the range of the agreed GPS area, the contract state will be updated to indicate that it is out of compliance.  
By the end of this project, you should produce an Ethereum based dApp that has both the smart contract tested and deployed in a testnet and a front end that will allow monitoring of the status.


## Installation Guide
The this repo There are two sub-modules: admin and fbl_client_dapp.
```
git clone https://github.com/andyalex234/fund-by-gps-location.git
cd fund-by-gps-location
```
### Admin dApp - Next.js + Contract
please follow the README.md file in the admin folder
## Project Structure
<pre>
  |fund-by-gps-location
  |----> admin
  |   |----->README.md
  |----> fbl_client_dapp
      |----->README.md
</pre>
### LICENCE
 MIT
#### Contributors

<a href = "https://github.com/andyalex234">
  <img src="https://contrib.rocks/image?repo=andyalex234/logistic-optimization" />
  Andenet Alexander
</a>

> any type of contribution is welcomed. [Fork](https://github.com/andyalex234/fund-by-gps-location/fork), apply your changes and make a [pull request](https://github.com/andyalex234/fund-by-gps-location/pull).

## Acknowledgement
This project was given by [10Academy](https://www.10academy.org/) as a challange for the trainees 
