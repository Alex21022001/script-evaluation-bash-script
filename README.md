# Script-evaluation-bash

This repository includes bash script (application) that is used for initializing,
running the script-evaluation app and cleaning the working directory afterwards.

Before start look up **env.sh** script and change the environment variables which will be
used by the main script if you don't do it the default values will be used otherwise.

### The main script (application) includes:

1) help param - show the possible arguments.
2) init - initialize the working space for the app.
3) run - run the app via docker compose.
4) clean - stop docker containers and clean the working directory.

### How to use

1) In order to use this bash script you need to have Docker running on your PC.
2) Clone this repository.
3) Go to the obtained directory.
```bash
 cd script-evaluation-bash
```
4) Run the script with help arg to see possible params
```bash
   ./application help 
```