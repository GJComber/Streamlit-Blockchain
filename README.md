# Streamlit-Blockchain
## PyChain: 
A Streamlit UI enabling users to enter data and store it in a blockchain. 
### Libraries and dependancies
import pandas as pd;
from typing import Any, List;
import datetime as datetime;
import streamlit as st;
from dataclasses import dataclass;
import hashlib;
* pip install streamlit
* From within the directory where this code resides, open Streamlit using `streamlit run pychain.py`.

## Synopsis
This project utilising Streamlit, allows a user to create and review a simple Blockchain called PyChain. The interface is designed to easily input data into 'blocks' that are added to form a simple expression of a Blockchain and review its component parts. It runs a cached version of Streamlit. It will hold the data information for as long as the project remains open in the browser.
### In the main panel:
* There are user inputs for sender, reciever and amount of 'Eth' sent. 
* Input fields can be retained to modify for next transaction or cleared for new inputs
* Each transaction records onto a block of the blockchain.
* Block data such as input data record, timestamp, previous hash and nonce value are recorded and displayed.
* The validity of block transactions can be verified at a click.
!['image of valid transaction'](pychain_valid.png)
### On the side panel: 
* There is a slider to adjust the difficulty of the 'Proof of work' requirements
* A drop down selector to choose individual blocks and inspect their contents
!['image of selections'](pychain_inspector_options.png)
!['image of block contents'](pychain_clear_record.png)


