# AMP Instance config for ONB [OpenNetBattle](https://github.com/TheMaverickProgrammer/OpenNetBattle).

Installs a generic ONB Linux server that runs over p:3000

Separately downloads ezlib by Keristero and setups up folders

https://github.com/Keristero/ezlibs-scripts

# Installation

Log into your AMP Web management 

Configuration > Instance Deployment > Instance Management > Configuration Repositories

Edit

Add: "ClassyInfant/ONB_AMP_config:main"

Fetch Latest


Now when deploying an instance there should be an options for ClassyInfant - ONB


# NOTICE

Due to how git-clone and AMP operate I was not able to make this instance set the binary to be executable. You will have to set this yourself after the instance runs once and fails.

Sometimes the download of ezlibs fails. If this happens the server is still functional and can be fixed manually
