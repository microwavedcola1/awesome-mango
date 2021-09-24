# Reading material
* [Technical Intro to Mango Markets](https://marred-ragamuffin-111.notion.site/Technical-Intro-to-Mango-Markets-15a650e4799e41c8bfc043fbf079e6f9)


# Project idea list
This guide lists a projects as concepts or WIPs, and related resources

### Integrations
* REST API
    * https://github.com/microwavedcola1/mango-v3-service/blob/master/mango-service-v3/README.md
### Trading products
* dedicated borrowing+lending app on top of mango markets
    * clean borrowing experience 
        * borrowing based on exactly one asset as collateral which is available in spl wallet, 
        * paying back loans gradually to avoid liquidation
    * clean lending experience
        * transparency into how much one can earn, computing accurate APY from APR
    * loans for trading
        * hedge yield farming IL by borrowing one asset
        * interest rate arbing
* index funds
    * a very good example is piedao
* new derivatives: Quarterly Futures, Options
* market making funds
    * need to declutter the steps to run market making bots for everyone
* mango perp funds
    * decentralized funds trading solely on mango markets
### Misc
* exchanging deposited tokens for proxy tokens which could be used for staking, governance, etc....needs to be be though how this would work with liquidations

### Decentralization
* incentive model for gui hosters
* incentive model for keepers / cranks (possibly in collaboration with serum)
* fee sharing model to encourage protocols to build over mango markets

