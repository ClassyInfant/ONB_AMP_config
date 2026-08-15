# AMP Instance config for ONB [OpenNetBattle](https://github.com/TheMaverickProgrammer/OpenNetBattle).

Installs a generic ONB Linux server

Separately downloads ezlib by Keristero a VERY useful library for ONB creation

https://github.com/Keristero/ezlibs-scripts

# Installation

Log into your AMP Web management 

Configuration > Instance Deployment > Instance Management > Configuration Repositories

Edit

Add: "ClassyInfant/ONB_AMP_config:main"

Fetch Latest

Now when deploying an instance there should be an options for ClassyInfant - ONB


# Notice

I mainly threw this together just so I could host my own server where I already host the rest of my games servers. Any issues are unlikely to be resolved unless I am directly affected (sorry). AMP requires you to make a setup config for hosting so I figured it might as well work with little fuss.

If you fork this repo and want it to have a different default server setup edit the onbupdates.json file this controls the git-clones from my generic server repo and Keristero's ezlib repo


