Single-Asset-Staing: Provide one of the two tokens in a pair to provide liquidity. 

Basic example:
lets say tokenC pair = tokenA + tokenB,

1) Alice provides 100 tokenA to tokenC, however there is insufficient tokenB (0)
2) Bob provides 150 tokenB to tokenC, triggering a function to create a tokenC for 100 tokenA and 100 tokenB, with 50 tokenB remaining, stored as reservesB.
3) The tokenC is used in a farm and tokenB awaits tokenA for a new pairing.
4) The farm rewards are split between ownership of the token, in this case 50%/50%.

