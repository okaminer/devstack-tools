# devstack-tools

A few utility scripts to setup and test a devstack deployment

There are several scripts in the bin directory:
* run-*  
These scripts run tests (tox, tempest)
* setup-*  
These scripts setup a devstack system on a host
* test-*  
Small little scripts to test a specific thing in devstack

## setup-devstack

This is the main script to setup devstack, while it can be called manually the usage instructions are lacking at this stage. The original intent was to be invoked as part of the https://github.com/eric-young/deploy-and-configure container (which is responsible for argument parsing and invoked setup-devstack correctly).
