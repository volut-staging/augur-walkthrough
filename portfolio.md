# Testing Portfolio:

This section focuses on the Portfolio sections. Portfolio is mostly reviewing results of user actions. These are the portfolio sections:

  * Positions
  * My Markets
  * Favorites
  * Transactions
  * Reporting


## Positions

Positions includes trade positions, open orders and profit/loss. Trades will need to be made to produce positions and open orders.

- [ ] Verify that the null state is shown if user doesn't have any positions or open orders
- [ ] Verify correct market card shows when position and/or open orders is created
- [ ] Create a new order. Verify that the open order's Quantity and Average Price are correct.
- [ ] Create a new position. Verify that the position's Quantity, Average Price, and Last Price are correct.
- [ ] Verify "My Positions" and "Open Orders" can be toggled open and closed.
- [ ] Verify realized, unrealized and total profit/loss update correctly when a position is created.
- [ ] Verify realized, unrealized and total profit/loss update correctly when a position is closed.
- [ ] Verify realized, unrealized and total profit/loss update correctly when an order is added to a position.
- [ ] Verify position can be closed by clicking "Close".
- [ ] Verify open order can be canceled by clicking "Cancel".
- [ ] Verify account balance updates correctly when position is closed
- [ ] Verify account balance updates correctly when open order is canceled
- [ ] Verify profit/loss chart in header displays correct information based on user trading activity (talk to Paul about what this should display)
- [ ] Verify user can't claim their unrealized profits during waiting period
- [ ] Verify user can claim their unrealized profits when the market is finalized and waiting period is over

## My Markets

My markets is strictly for markets crated by the user account.

- [ ] Verify this view is empty if user hasn't create any markets
- [ ] Verify all user account created market is in this section 
- [ ] Verify the market's volume updates correctly when trades occur
- [ ] Verify the market's collected returns updats correctly when trades occur
- [ ] Verify Open section only shows markets that haven't expired
- [ ] Verify In Reporting section only shows markets that have expired
- [ ] Verify Finalized section only shows markets that have been finalized

## Favorites

- [ ] Verify view is blank if user hasn't marked any markets as favorite
- [ ] Verify only markets marked as favorite show up

## Transactions

- [ ] Verify view is blank if user hasn't created any transactions
- [ ] Verify create market transaction show when market is successfully created
- [ ] Verify transfer transactions show then ETH is successfully transferred
- [ ] Verify transfer transactions show then tokens are successfully transferred
- [ ] Verify trade transactions show when user makes successful trade
- [ ] Verify all sub trades are included as linked trades in trade transactions
- [ ] Verify open order transactions get created when user creates open orders


## Reporting

Currently this section is for claiming ETH/REP from market trading fees, market creation bonds, open reporting no-show REP bonds, REP from successful disputes and ETH from reporting fees from participation tokens 

### Market Creator

- [ ] Verify market creator can claim settlement fees based on market settlement percentage
- [ ] Verify market creator can reclaim no-show bond when designate reporter reports
- [ ] Verify market creator can't reclaim no-show bond when designate reporter doesn't reporter
- [ ] Verify market creator can reclaim reporter gas bond when designated reporter reports
- [ ] Verify market creator can't reclaim reporter gas bond when designate reporter doesn't repoert
- [ ] Verify market creator can reclaim validity bond when their market resolves not invalid
- [ ] Verify market creator can't reclaim validity bond when their market resolves as invalid

### Open Reporters

- [ ] Verify open reporter can claim no-show bond in REP
- [ ] Verify open reporter can claim reporter gas bond in ETH
- [ ] Verify open reporter can claim settlement fees for reporting in fee window
- [ ] Verify open reporter can reclaim REP on finalized markets where their outcome won
- [ ] Verify open reporter can't reclaim REP on finalized markets where their outcome lost

### Designate Reporters

- [ ] Verify designate reporter can claim settlement fees for reporting in fee window
- [ ] Verify designate reporter can reclaim REP on finalized markets where their outcome won
- [ ] Verify designate reporter can't reclaim REP on finalized markets where their outcome lost

### Dispute Contributor

- [ ] Verify contributor can claim settlement fees for contributing to successful dispute in fee window
- [ ] Verify contributor can claim settlement fees for contributing to not successful dispute in fee window
- [ ] Verify contributor can claim REP from finalized markets that resolve on same outcome as their successful dispute rounds
- [ ] Verify contributor can reclaim REP on dispute bonds that didn't make
- [ ] Verify contributor can't claim REP from finalized markets that resolve on different outcome as their successful dispute rounds



[Back to Main Menu/Intro](https://github.com/AugurProject/augur-walkthrough/)
