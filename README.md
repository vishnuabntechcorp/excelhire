#!/bin/bash
# Update package lists and install Git
sudo apt update -y
sudo apt install -y git                                                        

# Clone the repository
git clone https://github.com/vishnuabntechcorp/excelhire.git /home/ubuntu/excelhire

# Change to the repository directory and make the script executable
cd /home/ubuntu/excelhire
chmod +x install_jenkins.sh

# Run the script to install Jenkins
./install_jenkins.shserdate script







