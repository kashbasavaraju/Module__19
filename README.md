# Module_19: Fintech Finder

# Exercise:

In this exercise, we were ask to develop an app called Fintech Finder. Fintech Finder is an applicaiton an application that its customers can use to find fintech professionals from among a list of candidates, hire them, and pay them.

This application uses both the fintech_finder.py and crypto_wallet.py.

The mnemonic seed phrase was provided from Ganache, a platform that allows for a safe testing environment of the application.

The application allows for the consumer to generate an Ethereum account using a mnemonic seed phrase. It then retrieves and displays the account balance, calculates the value of the Ethereum transaction, and digitally signed a transaction. The transaction was validated by checking the hash code associated with the transaction and checking the transaction log in Ganache.

# Imports

Fintech Finder -

import streamlit as st
from dataclasses import dataclass
from typing import Any, List
from web3 import Web3

Crypto Wallet - 

import os
import requests
from dotenv import load_dotenv
load_dotenv()
from bip44 import Wallet
from web3 import Account
from web3 import middleware
from web3.gas_strategies.time_based import medium_gas_price_strategy

# Home Screen

![Alt text](https://github.com/kashbasavaraju/Module__19/blob/main/Screenshots/Home_Screen.jpg)

# Transaction

![Alt text](https://github.com/kashbasavaraju/Module__19/blob/main/Screenshots/Transaction_Lane_3hr.jpg)

# Validation

![Alt text](https://github.com/kashbasavaraju/Module__19/blob/main/Screenshots/Transaction_log.jpg)

![Alt text](https://github.com/kashbasavaraju/Module__19/blob/main/Screenshots/Validate%20Transaction%20Hash.jpg)

# Usage

Streamlit, Python, and Visual Studio were used to edit and run the software.

# Contributors

Kaushik Basavaraju