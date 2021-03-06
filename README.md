

# Decentralized Exchange 

  While this project was more for educational purposes then actually a product meant for deployment, I would like to add a matching engine to the
  Dex to expand its functionality and make it more realistic. In order to trade using this Dex, you have to click on specific orders in the orderbook 
  to trade.  There is nothing that stops the orderbook from crossing markets (ie. a limit order submission will not fill even if your limit order is 
  through the current best bid/ask).

  Below is a flow chart of the general architecture of the Dex and how it was built.  There is a fair amount of frameworks used in the making
  of the DAPP.  They are outlined below.  The 'ganache' branch is the set of code that was used for development where as the 'master' branch is
  used for deployment on the rinkeby testnet.  

  - You can see the current deployed version [here](https://rinkeby-dex.herokuapp.com/)
  - Add Rinkeby ETH from [here](https://faucet.rinkeby.io/)
  - Add Rinkeby LINK from [here](https://rinkeby.chain.link/)



## User Interface

![](public/UI.png)


## TODO

- [ ] Balances don't refresh when running loading script
- [ ] Balance doesn't refresh when you fill an order from the orderbook
- [ ] Update account balance based on pending orders in orderbook; update balance if orders(s) are cancelled or filled
- [ ] Y axis prices are not displaying on chart after version upgrade of apex charts
- [ ] Merge helper.js files
- [ ] Convert to a stable coin market (ie. Dai)
- [ ] Create a matching engine for autofilling orders (0x Protocol)


## Dapp Architecture

![](public/chart.png)
