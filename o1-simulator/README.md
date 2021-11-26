# Build O-DU/O-RU simulator base images
Generate base docker images using in O-DU/O-RU simulator.

## Features
The original source code release from O-RAN-SC perform netconf call-home feature to establish the netconf session between SDN-C(ODL) and PNF(O-DU/O-RU).
Here we modify the call-home feature to establish session between SDN-C(ONOS) and O-DU/O-RU.

## Usage
```
cd ntsimulator/
sudo ./nts_build.sh
``` 
After building docker images will generate several docker images:
```
o-ran-sc/nts-ng-blank                                                        1.3.2                             bdb088145625   3 days ago      95.1MB
o-ran-sc/nts-ng-o-ran-du                                                     1.3.2                             26686645bacc   3 days ago      95.2MB
o-ran-sc/nts-ng-o-ran-ru-fh                                                  1.3.2                             61bb6fe12f62   3 days ago      97MB
o-ran-sc/nts-ng-o-ran-fh                                                     1.3.2                             065b470dceb8   3 days ago      96.3MB
o-ran-sc/nts-ng-x-ran                                                        1.3.2                             fac526f06f5a   3 days ago      96.1MB
o-ran-sc/nts-ng-manager                                                      1.3.2                             1928e1fc1c78   3 days ago      95.2MB
o-ran-sc/nts-ng-base                                                         latest                            a7bf1f491473   3 days ago      95MB
```

Source from https://gerrit.o-ran-sc.org/r/gitweb?p=sim/o1-interface.git;a=tree;h=refs/heads/dawn;hb=refs/heads/dawn
