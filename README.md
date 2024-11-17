# PayPal Checker

A Python script to check PayPal accounts and extract account information.

### Features
------------

* Checks PayPal accounts using provided email and password
* Extracts account information such as:
	+ Phone number
	+ Balance
	+ Cards
	+ Bank status
	+ Last four digits
	+ Restricted status
	+ Locked status
	+ Crypto enabled status
* Supports proxy usage for anonymous checking
* Saves successful hits to a file named `hits.txt`

### Usage
-----

1. Create a file named `accounts.txt` with each line containing an email and password separated by a colon (e.g. `email:password`)
2. Run the script using Python (e.g. `python checker.py`)
3. The script will check each account and save successful hits to `hits.txt`

### Requirements
--------------

* Python 3.x
* `requests` library
* `beautifulsoup4` library

### Installation
--------------

1. Install Python 3.x from the official website
2. Install the required libraries using pip: `pip install requests beautifulsoup4`

### Disclaimer
-------------

This script is for educational purposes only. Do not use it to illegally access or exploit PayPal accounts.
