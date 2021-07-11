# yarn-add-alch-alchemy-web3
yarn add @alch/alchemy-web3
npm install @alch/alchemy-web3
web3.eth.getAccounts().then(accounts => {
  web3.eth.sendTransaction({
    from: accounts[0],
    to: "0x6A823E…",
    value: "1000000000000000000",
  });
});
