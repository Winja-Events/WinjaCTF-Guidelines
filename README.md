# Challenge Creation Guidelines

## Types of CTF Challenges

A challenge could be created in either of the following forms:
1. Text only, e.g. OSINT challenges
2. Static file, e.g. Steganography challenges
3. Web hosting required, e.g. Web challenges

## Supporting Documentation

For every challenge, following supporting files should be created:
1. **description.txt** should contain challenge description. This description will be copied to CTFd.
2. **flag.txt** should contain modifiable flag value.
3. Avoid hardcoding the flag value in the challenge. Try to import it from the **flag.txt** file if possible.
4. Create the flag using the below python script by giving the phrase related to the challenge.  
https://gist.github.com/Aravindha1234u/2d670d43b1668343ef0bbd981ff264a8
5. **README.md** should contain following:
    * Challenge Name
    * Points
    * Difficulty level
    * Category name
6. **blog.md** should contain the challenge writeup
7. **deploy.md** should contain challenge deployment steps (if applicable)

## General Guidelines

* All **static files** should be named in following format _<challenge_name>.<extension>_
* All challenges that need hosting should contain **Dockerfile** and **docker-compose.yml**
* Create the **deployment** and **service** kubernetes files after creating the **docker-compose.yml** file
* you can find more details in **K8sInfo.md** file for creating k8s files from the **docker-compose.yaml** file
