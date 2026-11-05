# Security policy

## Reporting a vulnerability

Please report vulnerabilities privately. Do not open a public issue, discussion or pull request.

- Use the **Report a vulnerability** button on the affected repository's Security tab, or
- email **security@usebrainchain.com**.

Include the affected contract or component, the impact you see, and steps or a test that reproduce it. A failing test is the most useful form.

## What to expect

- We acknowledge reports within **3 business days**.
- We send an assessment and a planned fix date within **10 business days**.
- We credit reporters in the advisory unless they prefer otherwise.

Please give us reasonable time to fix an issue before disclosing it, and do not test against networks or funds you do not own.

## Bounty

A confirmed vulnerability that could take or lock funds pays up to $1,000, depending on its impact. That includes a bug in BrainChain's tools that sends, signs or approves something its user did not ask for, or that exposes a key. Bugs in the tools, docs and site that cannot take or lock funds go through the [bug hunt](https://docs.usebrainchain.com/bug-hunt). Terms: https://docs.usebrainchain.com/security#bounty.

## Scope

In scope: code and documented behaviour in any public repository of the usebrainchain organization.

Out of scope:

- issues that require a compromised guardian key, or a compromised brain key (the key that records Jev's decisions) beyond what the contracts bound;
- scanner findings without a demonstrated impact;
- third-party services.

## Status

BrainChain mainnet is live and holds task bounties in escrow. The contracts in usebrainchain/brainchain are open source and have not had an external audit.
