#Testing
forge coverage --fork-url $SEPOLIA_RPC_URL
forge test --fork-url $SEPOLIA_RPC_URL
forge test --fork-url $SEPOLIA_RPC_URL --coverage



#Forge
forge fmt # Format code

Contract: 0x27A5Cef07fE12dBC45f44Ccf89B8f8672f35ECd6

forge script script/Interactions.s.sol:FundFundme


 forge install ChainAccelOrg/foundry-devops --no-commit


Testing Foundary


cast send 0x6c4791c3a9E9Bc5449045872Bd1b602d6385E3E1 "solveChalleng(string,string)" "orange,@btwit71" --rpc-url $SEPOLIA_RPC_URL --private-key $PRIVATE_KEY 


cast call 0x6c4791c3a9E9Bc5449045872Bd1b602d6385E3E1 "attribute()" --rpc-url $SEPOLIA_RPC_URL --private-key $PRIVATE_KEY 



cast call CONTRACT "func(string,string)" "(TEST1,TEST2)" --rpc-url $SEPOLIA_RPC_URL --private-key $PRIVATE_KEY


cast send --ledger 0x... "deposit(address,uint256)" 0x... 1



cast send --gas-limit 500000 --rpc-url <rpc_url> 0x123456789abcdef "solveChallenge(string,string)" "Chocolate,@examplehandle"


forge install smartcontractkit/chainlink-brownie-contracts@0.6.1 --no-commit
