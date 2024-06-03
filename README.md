# CVE-2024-27348 🪶

CVE-2024-27348 Proof of concept Exploit RCE in Apache HugeGraph Server

Unauthenticated users can execute OS commands via Groovy injection in Apache HugeGraph Server. 


## Usage 🛠 

Exploit multiple targets ☣️
```
python3 CVE-2024-27348.py -f targets.txt -c "command to execute"
```

Exploit single target 🗡
```
python3 CVE-2024-27348.py -t http://target.tld:8080 -c "command to execute"
```

## Parameters 🧰 

Parameter | Description | Type
------------ | ------------- | -------------
-c/--comand |  Command to execute on target | String
-t/--target | URL, Single target  | String
-f/--file | Multiple targets | File


## Contact Me📇

[Twitter - Milan Jovic](https://twitter.com/milanshiftsec)

[LinkedIn - Milan Jovic](https://www.linkedin.com/in/milan-jovic-sec/)

#### Educational purposes only and cannot be used for law violation or personal gain.
#### The author of this project is not responsible for any possible harm caused by the materials of this project.

