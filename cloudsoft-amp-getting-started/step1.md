This is your first step.

## Get AMP

First you must download and run a docker image that contains the latest version of Cloudsoft AMP.

To do so, run this **command**

`docker run -t -i -p 8081:8081 -p 8101:8101 -p 8443:8443 murdoaird/amp-karaf-docker:latest `{{execute}}

## Check it is up-and-running

Run this command 

`bundle:list `{{execute}}


You know AMP is up-and-running when the last entry in the list is similar to this:

320 | Active   |  90 | 0.10.0.20161115_1945          | Brooklyn OSGi init
 
The key bits are that the **Brooklyn OSGi init** bundle is **Active**

You are now ready to use AMP...