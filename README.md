# Supply Chain Management
	
 	
 ------------------------		

Supply chain management on blockchain.

### Prerequisite

1. Node.js
2. IPFS
(
  for windows : https://docs.ipfs.io/introduction/install/#windows
  for linux and mac :https://docs.ipfs.io/introduction/install/#mac-os-x-and-linux
  )
3. Truffle Framework (`sudo npm install -g truffle` or on windows use ` npm install -g truffle`)
4. Testrpc (`sudo npm install -g ethereumjs-testrpc` or on windows use ` npm install -g ethereumjs-testrpc`)

### Part 1


1. `cd supply-chain-management`
2. `npm install`
3. `sudo npm install -g @angular/cli@latest`
(windows users might have to do: `npm install -g @angular/cli@latest`)

### Part 2

4. Open a new terminal and start IPFS daemon with `ipfs daemon`
6. Start testrpc in new terminal with `testrpc -l 47000000000000`.
7. From inside the project directory run `truffle compile` to compile your contracts
8. And `truffle migrate` to deploy those contracts to the network
9. Now finally, start the project with `npm start`. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.
10. Make sure there are no errors in browser console

### Login

1. This project uses your keystore file to login to the application.
2. For now, the accounts that can login are hardcoded in `auth.service.ts` with there role.
3. You can find the keystore for default accounts and there password in 'keys' folder.

### URLs

1. `/login`
2. `/retailer`
3. `/distributor`
4. `/manufacturer`
5. `/supplier`

## Acknowledgments

* [Nikhil Bhaskar](https://github.com/Nikhil22) for [Angular CLI + Truffle Starter Dapp](https://github.com/Nikhil22/angular4-truffle-starter-dapp)
* [MyEtherWallet](https://github.com/kvhnuke/etherwallet)


## License

[GNU GPLv3](./LICENSE)
