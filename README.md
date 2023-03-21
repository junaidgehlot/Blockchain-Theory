1. Banks used to use illegal methods to make money, leading to bankruptcy.
2. Government used to bail them out.
3. In 2008, government did not bail out a bank, fearing this can lead to economic repercussions, government saved other banks.
4. Dilemma arises on which banks to save or which to let go.
5. Banks engage in shady practices and are still saved by government.
6. This leads to question on why government has control over currency.
7. Mathematicians begin thinking of solutions, leading to the creation of bitcoin.
8. Gold was originally used for transactions, but was replaced by currency due to convenience.
9. Currency was pegged to gold initially.
10. As the dollar grew stronger, it was no longer pegged to gold, leading to inflation.
11. Government now has full control over printing money, leading to increased inflation.
12. Cryptocurrency is introduced as a solution not controlled by a single entity.
13. Cryptocurrency uses "Proof of Work" algorithm.
14. Proof of Work algorithm shares work between machines (mines).
15. These machines keep a global state of data, which invalidates any changes made by one machine.
16. Changes to the data would require 50% of machines to collude, making it improbable.
17. Miners are willing to expend resources to mine data in cryptocurrency, as they receive incentives in bitcoin. While it is resource-intensive to mine data, the reward of receiving bitcoin motivates miners to continue the process.
18. Bitcoin can be considered a type of digital gold because it has a limited supply and can be mined at a set rate. 
19. Additionally, one advantage of Bitcoin over physical gold is that it is easier to carry due to its digital nature.
20. Bitcoin is a decentralized digital currency facing scalability issues.
21. As Bitcoin's popularity grows, so does the number of transactions on its network.
22. The current infrastructure is unable to handle the volume of transactions, leading to slow transaction times and high fees.
23. This raises concerns about Bitcoin's viability as a currency for everyday transactions compared to traditional payment systems.
24. Efforts are being made to address these issues through solutions such as Lightning Network and Segregated Witness, but they are still in development and not widely adopted.
25. While Bitcoin is a useful store of value and popular investment asset, it faces challenges in becoming a mainstream payment system.
26. Hence, we need new algorithms(better and faster) .
27. Ethereum is a blockchain similar to Bitcoin.
In Ethereum, machines hold a long database containing who owns Ethereum.
28. Ethereum allows programming on the blockchain, which is not possible with Bitcoin.
29. This programming feature allows developers to create decentralized applications (DApps) on the Ethereum blockchain.
30. DApps can range from financial contracts to games and other applications.
31. This programming feature is enabled by Ethereum's native programming language, Solidity.
32. Overall, Ethereum's blockchain allows for more flexibility and functionality than Bitcoin's.
33. Ethereum solves the problem of creating decentralized applications (DApps) that run on a blockchain network.
34. Traditional programming involves applications running on a centralized server or cloud, which can be vulnerable to attacks and censorship.
35. Ethereum's blockchain technology enables developers to create DApps that run on a decentralized network of computers, making them more secure and resistant to censorship or downtime.
36. Ethereum's programming language, Solidity, allows for the creation of smart contracts, which are self-executing contracts with terms written into lines of code.
37. Smart contracts on Ethereum are executed automatically when certain conditions are met, streamlining and automating business processes like supply chain management, financial agreements, and legal contracts.
38. Ethereum's blockchain technology and programming language offer a new way of creating applications that are more secure, transparent, and efficient than traditional centralized systems.
39. Etherium is also slow as of now Because it use "proof of work".
40. Some L1 blockchains eg Solana are faster as they introduced new consensus  algorithm(similar to Proof of work)
41. In Solana. You need a user Wallet(end user, consumer), Bank Wallet(Authority, govt.) and smart Contract.
42. First step is you create user wallet(BackPack.app).
43. It will have empty address initially.
44.  Using the bank Wallet you can interact with smart contract and create a money printer(mint).
45. Effectively, Whenever you call a function on a smart contracts, SmartContract returns you a address just like public address which is a mint.
46. Mint is also a unique way to identify the token.
47. When we create a mint, initial supply of mint token is 0.
48. Then bank wallet can call another function on contract, which will hit another account called "Associated token account" or "Bank Account".
49. Every bank account can only contain similar type of currency. increase in type of currency will increase the number of bank accounts
50. If bank wallet creates a new currency then a bank account will be created.
51.  And even user wallet will also have a bank account called "Associated token account"
52.  Then bank wallet can distribute the token to user wallet from bank "Associated token account" to user  "Associated token account".
53. Install Solana cli
54. create a bank wallet private key by "Solana-keygen new --force"
55. it gives public key and 12 word phrase which can be used to access private key.
56. solana has testnet were we can get free solana(without monetery value) for dev purpose.
57. chose devnet in solana explorer
58. run command solana config set --url https://api.debnet.solana.com
59. It will connect all three of connection to devnet blockchain
60.  to access private key we can use ~/.config/solana/id.json
61. then call the contract by spl-token create
62. use solana  airdrop <No of token>
63.  While creating a token we will get  token<mint> and program <Id of contract>
64. Then create a bank account "spl-token create account"
65. then we can mint a amount of token  by a command "spl-token <bank address> <amount of token>"
66. Then distribute to user wallet
67. User command spl-token transfer  <public key> <token amount> --some security commands
