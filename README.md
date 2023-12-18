# nostreet
A reddit styled forum with nostr login and Zaps for tipping.

app.txs is the app entry point, found in: nostreet-app/app/app.tsx

https://www.youtube.com/watch?v=KOSvDlFyg20

Journaling:
npx ignite-cli@latest new nostreet-app
com.github.victorieeman.nostreet

//This following way of installing might become depreciated. Worked for me though...
curl -fsSL https://deb.nodesource.com/setup_16.x | sudo -E bash -
sudo apt-get install -y nodejs

//Due to conflict, I did an override
sudo dpkg -i --force-overwrite /var/cache/apt/archives/nodejs_16.20.2-deb-1nodesource1_amd64.deb
sudo apt-get install -f

Using Node Version 16, follow these instructions for future install: https://github.com/nodesource/distributions#ubuntu-versions

Might be needed:
yarn add --dev ts-node
yarn add v1.22.21

First time setup, from start to running the Expo GO test project took: 2:22:22, including debugging and troubleshooting to also setup the system correctly with yarn, NodeJS, Expo-Go install and all of correct version for ignote to work.