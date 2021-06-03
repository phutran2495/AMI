# AMI
change the values on vars.json file with the 4 key names according to your AWS account values:  "aws_access_key", "aws_secret_key", "subnet_id"

after cloning the folder to your local folder, run the following command line in your terminal
    cd packer
    packer build -var-file vars.json ami.json

Waiting for the processing finnished, the AMI id will appear. Copy the AMI id for the infrastructure project.
