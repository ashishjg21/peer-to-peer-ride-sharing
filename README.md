#Peer-To-Peer Ride Sharing System
## Inspiration



## Challenges we ran into

One of the most challenging things that we had to do was bug fix the incredibly complicated Smart Contract backend. There was so much undocumented features that we had to pratically invent from scratch, in terms of Solidity concepts. We also had to deal with the very very very bad error handling. Node and Solidity EVM errors were extremely vague and thus difficult to diagnose. Also, the infrastructure itself was a huge pain to keep track of and build. There were so many components and processes going on that we had to really focus on to make sure it all worked together. I highly recommend looking at the Git Repo and checking the contracts (Main.sol) as well as the routes folder to just see how comedical the amount of features and processes we had.


## What we learned

During this 24 hour hackathon, our team went through many challenges and overcame most of them. Let's start off with our main smart contract that was written in Solidity. Solidity’s syntax and language was built in such a way we cannot loop through the keys in a hashmap. Because our application stores all of the users on a hash map, it was NECESSARY for us to loop through all possible drivers and send them to the passenger. We need to code our own function to do this, and it allows us to access any key value pair in the hashmap. Next we implement the InterPlanetary File System Protocol, or IPFS, which utilizes the Peer-2-Peer network methodology of decentralized file sharing. We used this to update the drivers that updated their cars, and locate the latitude and longitude of our users and store it in a decentralized manner. None of us had that much experience with IPFS, but through grit and hard work we overcame this challenge with a fully functional decentralized system. Lastly, the most important concept that we learned was to call Smart Contract functions from the front-end. We had enough experience with calling Smart Contract functions in the backend, but since we needed the current user’s balance to transfer the ether, we needed to call it through the injected Web3 in the frontend. This task was very difficult, as it took away 3 hours of time and all 4 members on our team were working on this. All in all, we learned a lot through this hackathon regarding smart contracts and the IPFS decentralized protocol.


