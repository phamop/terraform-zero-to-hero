
#secanrio 2

/*
 How to determined if any changes happened in the infrastructure  that are not made by Terraform.
 Terrafrom refresh.
 Resolution:  set up a lambda function that detect that change and send notification.
*/


/*

# MIGRATION TO TERRAFORM & DRIFT DETECTION


provider "aws" {
            region = "us-east-1"
}

import {
  id = " "  ## resources ID
  to = aws_instance.phamop
}

# run this command after terraform init "terraform plan -generate-config-out=generated_resources.tf"
# copy the config and add it to main .tf 
#run this  command "terraform import aws_instance.phamop resources ID
# terraform plan
#

*/

https://youtu.be/-4IMy5ihiiU
