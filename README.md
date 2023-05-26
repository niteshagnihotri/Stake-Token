# Stake-Token
Smart Contract
<ul>
  <li>All the ERC20 functions are implemented</li>
  <li>The <b>unstake</b> function allows users to unstake their tokens and claim their reward. It calculates the reward based on the staked amount and duration. The total amount (staked tokens + reward) is transferred back to the user, and the staking data is reset. </li>
  <li>The <b>calculateRewards</b> function calculates the reward based on the staked amount and duration, using the reward rate per second.</li>
  <li>The <b>claimRewards</b> function allows users to claim their reward without unstaking their tokens. The rewards are added to the rewardsEarned variable for the user.</li>
  <li>The <b>getStakerData</b> function is a utility function that returns the staking-related data (stakedAmount, startTime, rewardsEarned) for a specific staker.</li>
 </ul>
