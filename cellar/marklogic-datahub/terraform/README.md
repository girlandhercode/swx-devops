# marklogic-datahub terraform

This is a Nifi + Marklogic instance in AWS.

# Note:

This was built using terraform v0.11.1 - if you use a newer version, please have everyone update at the same time to retain sanity.

Before running `terraform`, you will need to have a `.terraform` directory with the shared tfstate from s3.

Either run:

    make

or run this:

    terraform init --backend-config="key=marklogic/datahub/terraform.tfstate"

