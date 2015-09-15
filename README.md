#CloudPassage API Examples

Version: *1.0*
<br />
Author: *Tim Spencer* - *tspencer@cloudpassage.com*

These ruby and Python scripts include examples of calling the CloudPassage API for basic purposes 
such as authentication, submitting a GET request to retrieve information, and submitting a PUT 
request to write information back to Halo.


##Requirements and Dependencies

To run, these scripts require

* Ruby installed on the host that runs the scripts.
* Ruby gems: oauth2, rest-client, json
* A read-only (for GETs) or full-access (For PUTs) Halo API key; copy it from the Halo Portal


##List of Files

* **apiget.py**  -  Python script that authenticates to Halo, then retrieves server info and prints hostnames
* **apiget.rb**  -  Ruby script that authenticates to Halo, then retrieves server info and writes back server address + hostname strings
* **apiusers.rb**  -  Ruby script that authenticates to Halo, then retrieves user info and prints usernames
* **README.md**  -  This ReadMe file
* **LICENSE.txt**  -  License from CloudPassage



##Usage

1. Copy the two-part Halo API key from the Halo Portal into the proper location in any of the scripts.
2. Execute the script.

##Acknowledgements
Thanks to W. Stearns for providing the proxy-support code for apiget.rb.

<!---
#CPTAGS:community-supported api-example
-->
