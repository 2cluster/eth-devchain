FROM node:14

WORKDIR /usr/src/app

RUN git clone https://github.com/2cluster/eth-devchain.git

WORKDIR /usr/src/app/eth-devchain

RUN npm install

EXPOSE 8545

CMD [ "npx", "hardhat", "node" ]