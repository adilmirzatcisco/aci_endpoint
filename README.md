## What is this?
This is the aci endpoint search tool python 3.6.

## Installation and Run
#### 1. Clone the repo
	git clone https://github.com/JungnamKim-dev/aci_endpoint.git

#### 2. change into directory
	cd aci_endpoint

#### 3. Create the virtual environment in a sub dir in the same directory
	python3 -m venv venv

#### 4. Start the virtual environment and install requirements.txt from the 
	pip install -r requirements.txt 

## Run

#### change of the config (DevNet SendBox)
file : endpint.py
	
	# Setting
	APIC_IP = "sandboxapicdc.cisco.com"
	APIC_ID = "admin"
	APIC_PWD = "ciscopsdt"

<img src="./image/config.png">

#### DevNet Sandbox
Cisco has an 'always on' APIC [here](https://sandboxapicdc.cisco.com/) you can test this sript on. 

It really does work;

#### cli example
	python3 endpoint.py

<img src="./image/run.png">

## License
This project is licensed under the Apache License 2.0 - see the [LICENSE](./LICENSE).   file for details.
