
# F0SS_Fl0X
Hello guys :vanakkam
---
Are you stuck in the Dependency hell!!! , Tired!!  of Using Docker To ship YOUR machine Env.

I know a tool called flox which will help you by introducing a TERM Called **ENVIRONMENT AS CODE (EAC)** -- it is a new term {let it be..... }

use this link to install flox in your system https://flox.dev/docs/install-flox/install/
---


## Workshop {Flox_0}
  Let me demonstrate the capabilities of Flox by setting up the ClamAV antivirus engine along with Cowsay in a properly configured isolated environment.

## Disclaimer

**Important:** Kindly install Flox in your machine before jump into the Workshop

Let's start,
 
  1. create a directory  :

  ```bash
    git init Floxtest1 && cd Floxtest1

```  
2. Initialize Flox in This Directory

```bash
flox init
```
3. gonna  install ClamAV and Cowsay

```bash
flox install clamav cowsay
```
4. 🔒 Let's Activate the Isolated Shell
```bash
flox activate
```
5. Run this command to check does it work
```bash 
 clamscan / | tail -n 6 | cowsay -f dragon
```
---
or 
Download my isolated env from the Floxhub
```

