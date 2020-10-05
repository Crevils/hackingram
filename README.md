# Hackingram v1.2
## Author: github.com/crevils
## Credits : @thelinuxchoice
## IG: instagram.com/hackZec
### Don't copy this code without give me the credits, bitch! 
HackinGram is an Shell Script to perform multi-threaded brute force attack against Instagram, this script can bypass login limiting and it can test infinite number of passwords with a rate of +400 passwords/min using 20 threads.

### Features
- Multi-thread (400 pass/min, 20 threads)
- Save/Resume sessions
- Anonymous attack through TOR
- Check valid usernames
- Default password list (best +39k 8 letters)
- Check and Install all dependencies

### Usage:
```
git clone https://github.com/crevils/hackingram
cd instashell
chmod +x instashell.sh
service tor start
sudo ./instashell.sh
```

### Install requirements (Curl, Tor, Openssl):

```
chmod +x install.sh
sudo ./install.sh
```

### How it works?

Script uses an Android ApkSignature to perform authentication in addition using TOR and rotating the ip address to avoid blocking. 
