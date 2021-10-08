# SharkPhish
## Table of contents
* [General info](#general-info)
* [Technologies](#technologies)
* [Features](#features)
* [ML Models](#ml-models)
* [Features to be added](#features-to-be-added)
* [Setup](#setup)


## General info
Shark Phish is a website that uses machine learning to detect if a given website is phishing, legitimate or suspicious.

## Technologies:
1. Python             3.9.6
2. beautifulsoup4     4.9.3
3. Flask              1.1.2
5. ipaddress          1.0.23
6. urllib3            1.25.10
7. tldextract         3.1.2
8. whois              0.9.13
9. scikit_learn       0.24.2
10. numpy             1.21.2
11. pandas            1.3.2
12. HTML              5
13. CSS               4.15  

## Features:
1. Extracts domain based features:<br />
     a. having_IP_Address<br />
     b. Redirect, Prefix_Suffix<br />
     c. having_sub_domain<br />
     d. Domain_registration_length<br />
     e. HTTPS_token<br />
     f. Request_URL<br />
     g. URl_of_Anchor<br />
     h. Links_in_tags<br />
     i. age_of_domain<br />
     j. DNSRecord<br /><br />
2. Extracts url based features:<br />
     a. URL_Length<br />
     b. having_At_Symbol<br />
     c. double_slash_redirecting<br />
     d. web_traffic<br />
     e. Shortening_Service<br /><br />
3. Extracts JS features:  <br />
     a. Submitting_to_email<br />
     b. on_mouseover<br />
     c. RightClick<br />
     d. Iframe<br />
     e. Favicon<br />

## ML Models:
1. SVM
2. KNN
3. Random Forest
4. Decision Tree
5. Naive Bayes<br />
Random Forest gave the maximum accuracy of 97.47%, maximum precision of 97.88% and minimum false positive rate of 0.03.

## Features to be added:
1. Database to store searched queries.
2. Removing saved queries after specific time, to keep a check on the legitimacy of the website.

## Setup
To run this project, install libraries given above:

```
$ cd SharkPhish/
$ flask run
```
![image](https://user-images.githubusercontent.com/69465478/136519014-a6914f4f-5f8f-4dcd-843e-d8170a86de2d.png) 
![image](https://user-images.githubusercontent.com/69465478/136519242-ff537b2d-c02f-4521-83a5-77d8523ed429.png)
![image](https://user-images.githubusercontent.com/69465478/136519299-6dd830e9-9ca6-4c63-9c89-a31a38890e21.png)
