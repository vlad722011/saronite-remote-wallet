# Sumo LITE Wallet

Copyright (c) 2018, Sumokoin.org

# Installation & running from source codes

1. Clone the repo:
		
		git clone https://github.com/saronite/saronite-remote-wallet

2. Install dependencies (with Python 2.7):

	* Generally, you can use Python `pip` to install required components:
		
			pip install PySide, requests, psutil
	
	* or
			
			pip install -r requirements.txt 
	
	* On some OSes, PySide may be required to install from pre-built packages. For example, on Ubuntu 16.04, install PySide with the following command:
			
			sudo apt install python-pyside


3. Build/download Saronite binaries from [Saronite repo](https://github.com/saronite) and put them to `Resources/bin` sub-directory.

4. Run the wallet (Python 2.7):
		
		cd /path/to/Saronite-RW
		python wallet.py
