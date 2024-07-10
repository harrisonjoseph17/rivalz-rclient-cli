# rivalz-rclient-cli
Rivalz AI
#(Using a VPS, or Ubuntu LTS.)

curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.39.1/install.sh | bash 

export NVM_DIR="$HOME/.nvm"
[ -s "$NVM_DIR/nvm.sh" ] && \. "$NVM_DIR/nvm.sh"  

nvm install 20.5.0

nvm use 20.5.0

npm install -g npm@latest

npm i -g rivalz-node-cli

rivalz run
