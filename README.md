# aosipov-astra-linux_infra
aosipov-astra-linux Infra repository

# dz5
For connect to someinternalhost through bastion use `ssh -t -i ~/.ssh/appuser -A appuser@178.154.200.5 "ssh 10.130.0.6"`
You also use an alias: `alias someinternalhot='ssh -t -i ~/.ssh/appuser -A appuser@178.154.200.5 "ssh 10.130.0.6"'` in your files ~/.bashrc or ~/.bash_aliases
