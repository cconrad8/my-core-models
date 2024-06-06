# core-models

conda create -n 'schematicpy' python=3.10

conda init bash

conda activate schematicpy

pip install schematicpy

wget https://raw.githubusercontent.com/Sage-Bionetworks/schematic/main/config_example.yml

short term fix for verison issue: 

``pip3 install ipython==8.18.1``


$ echo $SCHEMATIC_SERVICE_ACCT_CREDS | base64 -d > creds.json

$ schematic manifest -c config.yml get -t 'test' -s

$ schematic schema convert DUO-terms.jsonld

$ schematic manifest -c config.yml get -t 'test' -s -dt DUOTemplate


# using schematic

start schematic: 

``$ schematic`` 

To make the schematic service account credential file:

``$ echo $SCHEMATIC_SERVICE_ACCT_CREDS | base64 -d > creds.json``

To test creating a google sheet:

``$ schematic manifest -c config_copy.yml get -t 'test' -s``

To convert jsonld to jsonld with schematic friendly formatting:

``$ schematic schema convert DUO-terms.jsonld``

To generate a google sheet manifest:

``$ schematic manifest -c config_copy.yml get -t 'test' -s -dt DUOTemplate``

