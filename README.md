#Ticks

solidity can't support floating-point numbers.

Ticks -> represent token prices of a pair

Conceptually -> smallest amount possible by which the price of an asset can move up or down

if actual tick = 0.6 for example
ticks are spaced at intervals of 1

we round the actual tick to either 'tickLower' or 'tickUpper' 0 and 1 respectively
