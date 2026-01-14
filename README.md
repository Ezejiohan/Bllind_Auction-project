🔨 Silent Auction – Python Bidding Program

This is a Python console application that simulates a silent auction. Multiple users can place bids anonymously, and at the end of the auction, the program determines and announces the highest bidder.

🎯 Objective

To collect bids from multiple participants and identify the highest bidder without revealing bids during the auction process.

🧠 How the Program Works

The program displays a logo imported from the art module.

Users are prompted to enter:

Their name

Their bid amount

Each bid is stored in a dictionary in the format:

{name: bid_amount}


After each bid, the program asks if there are more bidders:

Typing yes clears the screen (simulated with new lines) and continues bidding.

Typing no ends the auction.

Once bidding ends, the program compares all bids and announces the winner and highest bid
