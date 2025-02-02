# MIGRATION TO TERRAFORM & DRIFT DETECTION


provider "aws" {
            region = "us-east-1"
}

import {
  id = " "  ## resources ID
  to = aws_instance.phamop
}

# run this command after terraform init "terraform plan -generate-config-out=generated_resources.tf"



https://youtu.be/-4IMy5ihiiU
