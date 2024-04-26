- open a terminal
- install homebrew ([docs](https://brew.sh/))  
  `/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"`
- install fastly, terraform and other cli tools  
  `brew install fastly terraform vegeta jq`
- install npm ([docs](https://github.com/nvm-sh/nvm#installing-and-updating))  
  `curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.39.4/install.sh | bash`  
  `export NVM_DIR="$HOME/.nvm"`  
  `[ -s "$NVM_DIR/nvm.sh" ] && \. "$NVM_DIR/nvm.sh"`  
  `nvm install node`
- clone this repo and cd into it
- copy the variables file to start your own (which will be ignored by git)  
  `cp terraform.tfvars.example terraform.tfvars`
- `terraform init`