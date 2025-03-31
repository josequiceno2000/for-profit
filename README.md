# For Profit
A game about maximizing store profit while maintaining a healthy stock of items

## Game Loop
30 days, 1 day at a time
1. Choose discounts for the day
2. Sell to customers
    - Decide when to apply discounts (they may buy more or come back!)
    - Make sure not to promise them more than you have in stock!
    - Make as much profit as you can
3. Review stock and put in orders for the next day to keep your supply healthy
    - Also be able to view upcoming VIP's that are looking for specific things (people who called ahead of time or come in regularly)

## Win Conditions
- Make some profit
- The higher the profit, the better the store does!

## Features
- Menu-driven interfact to allow players to select items for customers
- Ability to add, remove, and modify items in customer cart before checkout
- Discount system
- Payment simulation

- Limited stock count for each item
- Out of stock items cannot be added to customer cart
- Restocking feature

- Webpage UI using Flask
- Generates PDF or other file of each transaction
- Generates downloadable PDF of high score
- Saves transaction history for business records