# core-models



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

