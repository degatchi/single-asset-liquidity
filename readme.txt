Single-Asset-Liquidity: Provide one of the two tokens in a pair to provide liquidity. 

Why would anyone use this?
If you are hodling a single token and don't want to provide liquidity by splitting up your bag into 2 tokens, you can contribute to tokenA or tokenB of a liquidity pool pair, waiting for someone else to contribute to the other half. This way, you're providing liquidity while hodling your heavy bag. It's the best of both worlds. You get to get lp fees, farm rewards and hodl a single token (i.e, the dapp's native token). The only downside would be getting 50% of the rewards, but that's better than nothing!

Basic example:
lets say tokenC pair = tokenA + tokenB,

1) Alice provides 100 tokenA to tokenC, however there is insufficient tokenB (0).
2) Bob provides 150 tokenB to tokenC, triggering a function to create a tokenC for 100 tokenA and 100 tokenB, with 50 tokenB remaining, stored as reservesB.
3) The tokenC is used in a farm and tokenB awaits tokenA for a new pairing.
4) The farm rewards are split between ownership of the token, in this case 50%/50%.


SoulSwap example:
lets say SOUL/SEANCE pair = SOUL + SEANCE,

1) Alice stakes 100 SOUL and gets 100 SEANCE.
2) Alice provides 100 SEANCE as a split for the SOUL/SEANCE lp pair.
3) Bob is an arbitrager and buy is selling and buying SEANCE but decides to put some towards singe-asset-liquidity, providing 150 SEANCE.
4) The 100 SOUL + 100 SEANCE combines to mint 1 SOUL/SEANCE token with 50 SEANCE in reserves, waiting for a SOUL provider.
5) Contributors get their share of the token, in this case Alice gets 50% of the rewards and the same goes for Bob
