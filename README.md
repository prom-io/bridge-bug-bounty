# Prom Bridge Bug Bounty Program

## Scope
This bug bounty program is focused on Prom Bridge smart contracts and is focused on preventing:

- Thefts and freezing of Prom tokens of any amount
- Unexpected sandwiching or manipulation of user deposits and admin's withdrawls
- Any Access Control's malicious manipulations

Bugs on Smart Contract level or Backend level are considered valid. Bugs on frontend side are not part of the scope.

At the current version gas price fee is static, which might lead to project receiving less funds during gas spikes. The bug is known and therefore not subject to reward.

## Reward system
Payouts are handled by the PROM DAO team directly and are denominated in USD. However, payouts are done in USDC.

- Critical level (800 - 3500$): Bugs that could lead to a significant loss of funds or their freezing, complete loss of system availability, miner-extractable value. Proof of Concept is required.
- High level (200 - 2000$): Bugs that will not directly result in the loss of funds but can be exploited under certain conditions, theft or freezing of unclaimed fees. Temporary freezing of funds.  Proof of Concept is required.
- Medium level (100 - 500$): Bugs that might cause high compute consumption by validator/mining nodes. Proof of Concept is required.

## How to report a bug
Please submit a bug report in an email to tech@prometeus.io
In your report please make sure to have the following:
- Severity of the bug found.
- Steps to reproduce and impact of the found bug.
- Wallet address that will be used to receive funds in case you are eligible for the reward


## Deployment Addresses
Prom Bridge is a bridge deployed on following addresses:
- Ethereum Mainnet: 0x821c7B87537d5c9eAd755a28C735123D67b18379
- BSC Mainnet: 0x8bdd3e77aD7843838cB0F0c19842764e353C2076

## Rules
Breaking the following rules might result into receiving less reward or complete loss of it for finding a bug (inspired by Immunefi):
- Any testing with mainnet or public testnet contracts
- Misrepresenting severity: claiming that a bug report is critical when it clearly is not
- Misrepresenting assets in scope: claiming that a bug report impacts/targets an asset in scope when it does not
- Whitehacking with intent to save user or protocol funds without the express written consent of the project
- Attempting phishing or other social engineering attacks against protocols developers
- Requesting gas fees from the project
- Attacks based on personal characteristics
- Threats of violence
- Threatening to publish or publishing people’s personal information without their consent
- Extortion/blackmail or threats of extortion/blackmail
- Reporting a bug that has already been publicly disclosed
- Publicly disclosing a bug report--or even the existence of a bug report for a specific project--before it has been fixed and paid
- Placeholder bug submissions, i.e., bugs that have a vague title, very few details, and no reproducible steps
- Submitting spam/very low-quality bug reports and submitting information that is not a bug report
- Submitting a bug report in a language other than English











