# 02 Data Sources and Techniques: 
# NASDAQ TotalView-ITCH Order Book 
--- 
- Native Protocol to NASDAQ (instead of FIX)
- Allows *Reconstruction of Order Book* that keeps track of the list of active-limit buy and sell orders for a specific security or financial instrument 
- Order Book reveals **market depth** throughout the day via volume and price 
    - also participants for buy and sell orders unless anonymous
    - **Market Depth**: key liquidity indicator + potential price impact for large market orders 
- Auctions or Crosses: execute large number of trades at open/close
> ### LARGE DATASET ~16GB
> - not essential in remainder of book 


## Step 1: clean [message_types.xlsx](message_types.xlsx) file and save to `.csv`
- Load Message Types -> Sort By `'id'` -> Drop `'id'`
- Clean Message Types -> 
- 

## Step 2: Parse ITCH Data