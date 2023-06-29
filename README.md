# Apprendre React: Développez facilement votre première application avec TypeScript !
# Installation

git clone https://github.com/awesome-reactjs/react-pokemons-app.git

cd public
git clone https://github.com/PokeAPI/sprites.git


# Installtion modules
rm -rf node_modules package-lock.json
npm i
npm audit fix
npm audit fix --force

# Execution

# Prerequis
sudo -s
https_proxy=...
http_proxy=...
export https_proxy http_proxy
npm install -g json-server

Console 1
export PATH=$PATH:/usr/local/lib/nodejs/node-v18.12.1-linux-x64/bin
npm run start:api


Console 2
npm start

Browser
http://localhost:3000/
