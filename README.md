
# F0SS_Fl0X
Hello There !!! 
---
Are you stuck in the Dependency hell!!! , Tired!!  of Using Docker To ship YOUR machine Env.

I know a tool called **[flox]( https://flox.dev/)** which will help you by introducing a TERM Called **ENVIRONMENT AS CODE (EAC)** -- it is a new term {let it be..... }

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
 clamscan / | cowsay -f dragon
```
```bash 
by using the cowsay -cowsay -l {List all available art}
```
---
or 
Download my pre-configured isolated env from the Floxhub

**just two steps After creating a Directory**

1. Download my Pre-configured ENV from Floxhub
```bash
flox pull patrick1904-s/floxtest
```
2. Activate The Environment
```bash
flox activate
```
---



## Preconfigured  Environment

In the [flox  example environment](https://flox.dev/environments/) , They have shipped a bunch of preconfigured environments .
## Featured Environments

Below is a list of some of the key environments and their primary uses:

* **OpenAI:** Includes the **OpenAI Python library** to help you integrate ChatGPT into your workflows.
* **PostgreSQL:** Contains the popular **open-source PostgreSQL database**.
* **Flox AI Modeling (FLAIM):** Tailored for **training and inference with Diffusers and Transformers**.
* **Ollama:** Designed for **pulling and running Large Language Models (LLMs)** locally.
* **Anthropic:** Provides access to the **Claude API**.
* **Metabase:** A great environment for **data analytics**.
* **Direnv:** Automatically **activates environments** as you navigate between different directories.
* **Jupyter Notebook:** A simple way to **start a notebook server**.
## Reference
1. FLox installation : https://flox.dev/docs/install-flox/install/
2. Flox Documentation : https://flox.dev/docs/ 
3. Clamav Documentation : https://docs.clamav.net/
4. Awesomeness of nix : https://github.com/nix-community/awesome-nix
5. cowsay Documentation : https://pypi.org/project/cowsay/
