# [DRAFT] How to DAO - A Practical Intro to Krause House Governance

The function of this system is to:

1. Organize the DAO around one "source of truth" representing governance.
2. Allow Jerry's to fork this source of truth, and propose their own to the DAO.

**How does it work?**

Krause House owns `krausehouse.eth`, an Ethereum Name Service domain. With that name, the DAO (the smart contract treasury and source of truth)
is able to _point_ to any resource that represents how we do governance on and off-chain.

Any proposal that proposes an update must provide a link to a new document.

If that proposal passes, `krausehouse.eth` will update it's `governance` ENS pointer to that resource.
