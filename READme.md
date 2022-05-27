# Amazon-Redshift-Cluster-setup-using-Terraform

This repo will create the following

        1. A new VPC for the redshift cluster.
        2. Defining the default Security Group for our VPC.
        3. Creating a couple of subnets for cluster.
        4. A Redshift Subnet Group for cluster.
        5. The IAM role (allows our cluster to read and write to S3)
        6. Redshift Cluster

## Apply the terraform script

1. First configure the aws credentials using aws-cli

        aws configure --profile terraform

2. Now, from the current directory run the following command to validate the script.

        terraform validate

3. To check the plan for the terraform

        terraform plan

4. Applying the terraform script

        terraform apply
