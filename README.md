# tweak-unifi-gateway


### To enable RTSP Conntrack in the Unifi USG ###

### Create directory /config/scripts/pre-config.d ###
```mkdir /config/scripts/pre-config.d```

### Open and edit the init script ###
```vi load_nat_rtsp_module.sh```

### Paste the contents of the load_nat_rtsp_module.sh file in the repo following: ###

### Close and save the file (esc + :wq) ##
### Restart the USG OR run the following command to start the service ###
```sudo modprobe nf_nat_rtsp```
