# Protocol Name KyberSwap
## Category: Defi Project 
## Smart Contract: KNC token

## Function Analysis

The function I am focusing on is the `KNCToken::delegateBySig` function.

The Block Explorer Link: https://etherscan.io/address/0x6131B5fae19EA4f9D964eAc0408E4408b66337b5#code

The `abi.encodePacked` is the method of scrutiny

## Detailed Explanation of the function, its use of encoding and the impact on the KNC token Contract

This function `KNC Token::delegateBySig` enables holders of KNC tokens to stake their tokens on KyberSwap and earn rewards in the form of KNC itself. This encourages KNC holders to follow the protocol and fosters the expansion of the ecosystem as a whole.`abi.encodePacked` helps to promotes a modular design. The KNC token contract doesn't need to have explicit logic for reward distribution; it simply handles the token transfer.                                                                                  
The reward logic resides within the KyberSwap contract, making it easier to manage and update.The KyberSwap contract's functionality is increased with `abi.encodePacked`, going beyond simple token swaps. It makes the protocol capable of implementing reward systems and token staking, which enhances and enriches the ecosystem.
The `KNCToken::delegateBySig` contributes to the overall health and growth of the KyberSwap protocol by creating a positive feedback loop. Users are rewarded for participating, attracting more users and further strengthening the platform.
