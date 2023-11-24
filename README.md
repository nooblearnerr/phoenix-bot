Overview
This repository contains a TypeScript script that serves as a trading bot for the Solana blockchain. The trading bot interacts with the Ellipsis Labs Phoenix SDK to perform trading operations on a specific Solana market.

Features
Market Trading: The bot places bid (buy) and ask (sell) orders on a specified Solana market.
Setup and Configuration: The bot handles the setup and configuration required for market trading, including creating a new maker account if necessary.
Order Management: The bot cancels all outstanding orders before placing new bid and ask orders.
Withdrawal: After a specified number of trading iterations, the bot withdraws funds from the exchange.
