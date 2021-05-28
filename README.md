# github-dapp
this is a project to build a platform that allows entreprenuers to incentivise action on their projects and offer rewards to devs and users that contribute to github projects


**Community** 🥇 
- [ ] a way for participants to cultivate stature. recording contributions, issues, pull_requests, merges, to allow for basic appraisal

Issues raised that get tagged for further action get points, PRs that get merged get points, Issues that get closed by PRs get points etc etc (This maybe best achieved through leveragin github's existing functionality ??

**Github** 🥇
- [ ] Repo owners can create a webhook on the target repo from the dapp
- [ ] Webhook end point checks hash
- [ ] webhook end point matches the actor (the person performing an action that may or may not be remunerated) and action against the smart contract
- [ ] webhook calls the smart contract with the actor and action which results in payment

**Smart Contract** 🥇
- [ ] Each GitHub Project gets a smart contract when registered by the project owner. This contract contains payable events and amounts per payable event, e.g. Issue labeled 'bug' 1 shannon, pull_request merged 1 szasbo, Issue labeled bounty and PR merged 1 finney.
- [ ] Each Account gets a smart contract to store token balance. This should be multi token so that project owners can utilise whatever token they choose to incent. If they choose a scamcoin then they are less likely to get contributions, if they use eth then they will probably get more

**Flowverview**
Login with github
Link my wallet address to my github-dapp account
Link a repo from a list of my repos
From my list of webhook verified repos, create a SmartContract with defined objectives
Query github-dapp projects by language, objective values
