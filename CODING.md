# Functional thinking
FProgrammers see 3 things
1. actions: buying a stock, changing a state, UI update
    - Running it twice will not give same output
2. calculations: making a decision, input Average True Range 20 days(Stock) , output decision: buy, sell, hold
    - always gives same output regardless of how many times run
    - Calculating (percentage)
3. data: the bytes in message
    - Meaningful wihout being run
    - Current porfolio value

# 3 rules of distributed systems
1. Messages arrive OUT of order 
2. Each messages may arrive 0,1, or more times
3. If you don't hear back, you have no idea what happened.

[TRADING]
Changes frequently
--- (Business rules)
Trading Strategy
--- (Domain rules)
Calculating signals etc...
--- (Tech Stack)
Python data structures
---
Changes seldom

[NOTELYST]
Changes frequently
--- (Business rules)
UI rules, functionalities, features...
--- (Domain rules)
Structure of a message etc...
--- (Tech Stack)
Swift data structures
---
Changes seldom

Each piece of code is built on a more stable foundation
By building our software this way, we ensure that we will make code changes as easy as possible

Once she has more than one robot working, she has a distributed system

