# Challenge Creation Guidelines

## Types of CTF Challenges

A challenge could be created in either of the following forms:
1. Text only, e.g. OSINT challenges
2. Static file, e.g. Steganography challenges
3. Web hosting required, e.g. Web challeneges

## Supporting Documentation

For every challenge, following supporting files should be created:
1. **description.txt** should contain challenge description. This description will be copied to CTFd.
2. **flag.txt** should contain modifiable flag value
3. **README.md** should contain following:
    * Challenge Name
    * Points
    * Difficulty level
    * Category name
4. **blog.md** should contain the challenge writeup
5. **deploy.md** should contain challenge deployment steps (if applicable)

## General Guidelines

* All **static files** should be named in following format _<challenge_name>.<extension>_
* All challenges that need hosting should contain **Dockerfile** and **docker-compose.yml**
