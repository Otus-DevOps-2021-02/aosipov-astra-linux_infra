# aosipov-astra-linux_infra
aosipov-astra-linux Infra repository

# dz5
For connect to someinternalhost through bastion use `ssh -t -i ~/.ssh/appuser -A appuser@178.154.200.5 "ssh 10.130.0.6"`
You also use an alias: `alias someinternalhot='ssh -t -i ~/.ssh/appuser -A appuser@178.154.200.5 "ssh 10.130.0.6"'` in your files ~/.bashrc or ~/.bash_aliases

# For connect
bastion_IP = 178.154.200.5
someinternalhost_IP = 10.130.0.6

# dz6
testapp_IP = 178.154.201.99
testapp_port = 9292

After deploy VM you can run scripts to deploy app. Or just wait.
