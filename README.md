# openshift-install

## v3.10.34

### Install notes.

#### Metrics

Incorrect image tag in metrics RC's

Changed all to v3.10 and deleted pods.

#### Logging

Reduced the ElasticSearch INSTANCE_RAM from 16GB to 8GB. Also had to deploy the 
infra node as m4.2xlarge to get the ES pod to schedule.


