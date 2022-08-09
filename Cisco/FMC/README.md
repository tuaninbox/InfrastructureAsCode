# Managing Distributed Cisco FTD Instances Using Cisco FMC
This directory contains code for module 5
which focuses on Cisco FMC automation using Python and `requests`.
The `data_ref/` directory contains sample output files for reference.
This project was tested and demonstrated using these versions:
  * FTD: 6.3
  * Python: 3.7.3
  * requests: 2.23.0

Environment variables can be exported and use the `build_from_env_vars()` method:
  * `FMC_USERNAME`: username for FMC
  * `FMC_PASSWORD`: password for FMC
  * `FMC_HOST`: FMC IP/hostname (defaults to `fmcrestapisandbox.cisco.com`)

Edit, copy, and paste the commands below to speed things up:
```
export FMC_USERNAME=$user
export FMC_PASSWORD=$pass
export FMC_HOST=$FMCIP
```
