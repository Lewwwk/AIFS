# [DRAFT] How to DAO - A Practical Intro to Krause House Governance

The function of this system is to:
1. Organize the DAO around one "source of truth" representing governance.
2. Allow Jerry's to fork this source of truth, and propose their own to the DAO.

**How does it work?**

Krause House owns `krausehouse.eth`, an Ethereum Name Service domain.  With that name, the DAO (the smart contract treasury and source of truth) 
is able to *point* to any resource that represents how we do governance on and off-chain.

Any proposal that proposes an update must provide a link to a new document.  

If that proposal passes, `krausehouse.eth` will update it's `governance` ENS pointer to that resource.

#### How do I suggest a change?

Proposed changes will be sent to Snapshot for voting.  For that proposal, you will need an updated representation of governance.

There's a few ways to do that:
1. Recommended: Fork this Github repository, make desired edits, and link to the specific git commit.  Think of a git commit as a snapshot or freeze frame of a project at some point in time.  This is **crucial**, as the DAO is only agreeing to that specific "snap"/commit, and *not* to any future changes that may occur on that project.
2. Publish a document on IPFS, and provide a link to that.  IPFS links, like git commits, are "frozen", meaning they cannot be updated after the fact.
