# bonding_pool_abi
An open source interface for the CCN bonding pool protocol

#### fundingFactory contract address in Huygens
0xB2f46617537ec2E54602119AB3b078B021568a95

#### fundingFactory contract explained
* createFunding - Miner create a bonding contract

#### funding contract explained
* addPromoter - Add a new promoter
* deletePromoter - Remove a promoter
* promoterCount - Number of promoters
* promoterList - List of the promoters
* funderCount - Total number of stakers in the bonding contract
* funderList - List of the stakers in the bonding contract
* getFunderInfo - Get the staker information
* getFundersInfo - Get stakers infomation in batch
* getFundingInfo - Get the bonding contract information
* getFundingState - Get the bonding contract status. 0 -> Funding has not started yet. 1 -> early terminated. 2 -> publish. 3 -> start mining. 4 -> mining is over.
* getMachineOnFundingInfo - Get the staking amount of a machine.
* getRewardsAmount - Get the total reward and locked reward of a staker.
* getUnlockedAmount - Get the unlocked reward of a staker.
* payFunding - Put stake in a bonding contract.
* submitOneMachine - Add a machine to a bonding contract.
* submitMachine - Add machines to a bonding contract in a batch.
* terminateOneMachine - Remove manchines from a bonding contract.
* terminateMachines - Remove machines from a bonding contract in a batch.
* transferFundsToMachine - Transfer the stake in the pool to a machine.
* transferFundsToMachines - Transfer the stake in the pool to machines in a batch.
* withdrawAmount - Stakers or promoter withdraw unlocked funds from the pool.
