# CD12352 - Infrastructure as Code Project Solution
# MINAL

## Spin up instructions
./create.sh network network.yml network-parameters.json
./create.sh udagram udagram.yml udagram-parameters.json
./update.sh network network.yml network-parameters.json
./update.sh udagram udagram.yml udagram-parameters.json
## Tear down instructions
./delete.sh network
./delete.sh udagram
## Other considerations
Link == > http://udagra-webap-2b7yct5183di-1710369065.us-east-1.elb.amazonaws.com/