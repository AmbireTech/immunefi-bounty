# Ambire Bug Bounty 

We are glad to announce that we are teaming up with Immunefy for an Ambire bug bounty campaign. 

The bug bounty is focused on our smart contracts, and on the following items in particular: 

* Thefts and freezing of principal of any amount 
* Thefts and freezing of unclaimed yield of any amount
* Theft of governance funds 
* Governance activity disruption 

## Rewards

Rewards are distributed according to the impact of the vulnerability based on [the Immunefi Vulnerability Severity Classification System](https://immunefi.com/severity-updated/). This is a simplified 5-level scale encompassing everything from consequence of exploitation to privilege required to likelihood of a successful exploit. 

_**Rewards for Smart Contracts and Blockchain**_


| Bug severity  | Reward | 
| ------------- | ------------- | 
| Critical | $50,000 | 
| High | $30,000 | 
| Medium | $10,000 | 
| Low | $3,000 | 


All High and Critical Smart Contract bug reports require a PoC and a suggestion for a fix to be eligible for a reward. All Low and Medium Smart contract bug reports require a suggestion for a fix to be eligible for a reward. 


## Assets in Scope 

| Target  | Type | 
| ------------- | ------------- | 
| https://etherscan.io/address/0xBf07a0Df119Ca234634588fbDb5625594E2a5BCA | Smart Contract - IdentityFactory | 
| https://etherscan.io/address/0x2A2b85EB1054d6f0c6c2E37dA05eD3E5feA684EF | Smart Contract - Identity - base | 
| https://etherscan.io/address/0xfF3f6D14DF43c112aB98834Ee1F82083E07c26BF | Smart Contract - QuickAccManager | 
| https://etherscan.io/address/0x460fad03099f67391d84c9cc0ea7aa2457969cea | Smart Contract - Batcher| 

\
All smart contracts of Ambire can be found at https://github.com/AmbireTech/adex-protocol-eth. However, only those in the Assets in Scope table are considered as in-scope of the bug bounty program.

Please note that the following vulnerabilities are **not eligible for a reward**: https://github.com/AmbireTech/code4rena#known-tradeoffs.

## Impacts in Scope

Only the following impacts are accepted within this bug bounty program. All other impacts are not considered as in-scope, even if they affect something in the assets in scope table.

**Smart Contracts/Blockchain**:

* Loss of user funds staked (principal) by freezing or theft
* Loss of governance funds
* Theft of unclaimed yield
* Freezing of unclaimed yield
* Temporary freezing of funds for any amount of time
* Unable to call smart contract
* Smart contract gas drainage
* Smart contract fails to deliver promised returns
* Vote manipulation
* Incorrect polling actions

## Bug bounty rules

The following activities are prohibited by this bug bounty program:

* Any testing with mainnet or public testnet contracts; all testing should be done on private testnets
* Any testing with pricing oracles or third party smart contracts
* Attempting phishing or other social engineering attacks against our employees and/or customers
* Any testing with third party systems and applications (e.g. browser extensions) as well as websites (e.g. SSO providers, advertising networks)
* Any denial of service attacks
* Automated testing of services that generates significant amounts of traffic
* Public disclosure of an unpatched vulnerability in an embargoed bounty





