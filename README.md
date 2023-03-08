#Vampire $VAMP
## Inspiration
The emergence of lottonomics within smart contracts has served as a catalyst for the development of VAMP - our groundbreaking innovation in the realm of money games. These games offer a unique method for driving new capital into the token economy, and our team recognized an opportunity to create a completely verifiable, on-chain jackpot game that could succeed where others have failed. While many lottery and jackpot tokens have struggled with implementing proper smart contracts, we believe that our approach, which involves a buyback and burn when the jackpot is won, will guarantee the appreciation of the token's value and increase the price floor over time.

## What it does
VAMP is a cryptocurrency that offers a unique jackpot system where the last buyer within a 10-minute window wins the jackpot. The jackpot has a cap of $100,000, and if the cap is reached, 70% of the funds are used to buy VAMP tokens, 20% goes to the jackpot, and 10% goes to the team.

When a jackpot is won, 50% of its amount is rewarded to the winner, while the remaining 50% is split between the team (10%), the jackpot (20%), and VAMP tokens burned (10%). This system ensures that the price floor of the VAMP token increases as jackpots are won and the jackpot limits are hit, making it an attractive investment for users.

## How we built it
### Contract
The VAMP.sol contract was written with Solidity. To protect against attacks, the contract was designed with several security measures, such as:

Access control: The contract includes access control mechanisms to safely fine tune VAMP's jackpot mechanism.

SafeMath library: The SafeMath library from OpenZeppelin was used to prevent integer overflow and underflow errors in mathematical operations, which could potentially lead to attacks such as a reentrancy attack.

External Contract Interactions:  In order to gather FTM, it interacts with the SpookySwap Router from within the contract. 

Overall, the contract was built with security in mind, using industry-standard practices and techniques to protect against known attack vectors and prevent unauthorized access or modifications to the contract.

### DashBoard 
We built a user-friendly dashboard for VAMP, a lottery cryptocurrency, using Next.js and React. The dashboard had key features, including winner tracking, jackpot holdings, and statistics, timer until the next winner, and the amount of VAMP burned. After gathering requirements, we designed a UI using Next.js and React that reflected VAMP's brand identity and ensured easy navigation. We developed front-end components to display real-time information from VAMP's API, including a winner tracking component, jackpot holdings and statistics component, timer until the next winner component, and the VAMP burned component. These features provided users with valuable information, creating trust in the platform's long-term viability.

### Bots 
we used Nextcord, a Discord API wrapper for Python, to build the Discord bot. We used Nextcord's API to  display information about the project, such as its price and burn and supply, who is the current leader of the jackpot and what the winnings are.

We built a Telegram bot, using requests.py, that informed the user about the timing of jackpot. what it held, and when the Jackpot events fired.

We utilized Web3.py to query and display blockchain data, such as the current balance of the project's wallet and the total supply of the project's tokens. We also used Web3.py to execute smart contract functions, such as distributing tokens to users.
## Challenges we ran into


## Accomplishments that we're proud of
### Game theory 
We are proud of the game theory for VAMP because it provides a fair and transparent way for players to participate in the lottery and win rewards. The game theory ensures that the jackpot is won by the last buyer within a given period, creating an element of excitement and competition for players.

Moreover, the jackpot's capped amount ensures that the system remains sustainable, and the 70% reinvestment of funds into buying and burning VAMP tokens promotes the platform's long-term viability. The distribution of rewards to the team, jackpot, and token burn aligns with the project's overall goals and vision, while also incentivizing desirable behaviors among players.

Overall, we believe that the game theory for VAMP provides a robust and effective model for creating a successful lottery cryptocurrency that benefits players and supports the platform's growth.
### Technology
We are proud of the dashboard and bots we built for the project as they provided users with valuable information and tools to interact with the project and stay informed about its activities. The dashboard was user-friendly, visually appealing, and responsive across all devices, while the bots were reliable, efficient, and provided real-time information to users. These tools helped establish VAMP's credibility and trustworthiness, making it a trustworthy and reliable platform. Overall, we are proud of the work we did and the impact it had on the success of the project.

## What we learned
We learned a lot(to) about game theory, we are constantly looking at feedback from the community to see what we can do to improve VAMP.

## What's next for Vampire
The coding is largely done, but that doesn't mean it is the end for VAMP. By playing with a variety of variables, we can fine tune VAMP's protocols to provide the best investment and entertainment oppurtunities to our investors. We are actively looking for other high quality tokens or projects that bring consistent value to their investors to collaborate with.
