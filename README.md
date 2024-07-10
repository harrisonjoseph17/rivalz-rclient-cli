# rivalz-rclient-cli CODE TO RUN RIVALZ-RCLIENT-CLI
# Rivalz AI Incentives
#(Using a VPS, or Ubuntu LTS.)

curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.39.1/install.sh | bash 

export NVM_DIR="$HOME/.nvm"
[ -s "$NVM_DIR/nvm.sh" ] && \. "$NVM_DIR/nvm.sh"  

nvm install 20.5.0

nvm use 20.5.0

npm install -g npm@latest

npm i -g rivalz-node-cli

rivalz run

# If code runs well you will see this, put in your information:

# Enter wallet address (EVM):  Your wallet address used to connect on the dashboard
# Enter CPU cores number you want to use (Max 8):  
# Enter Ram size you want to use (GB, Max 24 GB):  
# Select disk type you want to use:  SS
# Select disk serial number you want to use (Enter if no option):  
# Enter Disk size of drive-scsi0 (SSD) you want to use (GB, Max 1200 GB): 
