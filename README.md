# ami build configuration
#comment
# AMI
#comment
## Packer

1. sudo wget https://releases.hashicorp.com/packer/0.12.0/packer_0.12.0_linux_amd64.zip
2. unzip packer_0.12.0_linux_amd64.zip -d packer

3. sudo mv packer /usr/local/
	


4. Packer takes JSON files for validaiton and building of images


5. packer validate example.json


6. packer build -var-file example.json


Packer will produce and save the image on aws as well as a private ami on prod account
