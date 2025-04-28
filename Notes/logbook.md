# Logbook
This will be a log of everything I look up/research. I will report any major findings from my work and use this logbook as a notebook for my own notes to assist in my learning. I will consolidate all things here and hope to have a standardized format for note-taking.
> quoated text will be for asides on topics that do not relate to current option 
* **BOLD** will be used for either keywords, emphasis or when there are multiple options and I chose one of the paths


## Project 1
### Prereqs
* Opened a new folder in WSL for setting up Kubernetes
* Created a new AWS account
* Installed AWS on WSL
* Configured AWS (There are 2 ways to do this)
    * **Using AWS configure command**
        * stroes credentials in a file at `~/.aws/credentials` and output config in `~/.aws/config`
        * This prompts me for:
            * AWS Access key ID
            * AWS Secret access Key
            * Default region name
            * Default output format
        * Easy setup and persistent across shell sessions BUT can get messy with multiple profiles

    * Using CLI environ variables

### Installing the client tools
