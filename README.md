# GCP EGRESS NAT INGRESS LB

This repository consists of Terraform templates to bring up a F5XC GCP sites with Ingress LB and Egress NAT GW and SMG.

## Usage

- Clone this repo with: `git clone --recurse-submodules https://github.com/lesleycw/f5xc-gcp-smg-nat`
- Enter repository directory with: `f5xc-gcp-smg-nat`
- Obtain F5XC API certificate file from Console and save it to `cert` directory (need to create cert dir)
- Pick and choose from below examples and add mandatory input data and copy data into file `main.py.example`.
- Rename file __main.tf.example__ to __main.tf__ with: `rename main.tf.example main.tf`
- Initialize with: `terraform init`
- Apply with: `terraform apply -auto-approve` or destroy with: `terraform destroy -auto-approve`

## GCP Egress NAT Ingress LB module usage example

````hcl
````
