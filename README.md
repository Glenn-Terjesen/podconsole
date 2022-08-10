# podconsole
Script for entering kubernetes pod shell for debugging etc

Steps:
- copy file to ie to /usr/local/bin/podconsole
- run: chmod +x /usr/local/bin/podconsole
- make sure you are connected to the kubernetes cluster
- run: podconsole

NB: will not work if "/bin/sh" is missing on the pod or shell access is restricted

