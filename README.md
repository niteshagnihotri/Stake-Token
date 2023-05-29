# Stake-Token
Smart Contract - 0xe3882D7Eb223a8a6c02d9d25C7a0d5839b5844A7
<ul>
  <li>All the ERC20 functions are implemented</li>
  <li><b>unstake</b> function -  allows users to unstake their tokens and claim their reward. It calculates the reward based on the staked amount and duration. The total amount (staked tokens + reward) is transferred back to the user, and the staking data is reset. </li>
  <li><b>calculateRewards</b> function - calculates the reward based on the staked amount and duration, using the reward rate per second.</li>
  <li><b>claimRewards</b> function - allows users to claim their reward without unstaking their tokens. The rewards are added to the rewardsEarned variable for the user.</li>
  <li><b>getStakerData</b> function - returns the staking-related data (stakedAmount, startTime, rewardsEarned) for a specific staker.</li>
 </ul>
