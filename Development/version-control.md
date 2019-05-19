## Magento

We use a simple branching model with the following structure: 
- Master branch - where production servers pull their updates
- dev-* branches - where staging servers pull the updates

Each developer has his own dev-* branches where they commit updates. The commit description should be verbose enough to be easily understood, like adding the ticket number and describing the task done by the developer.

dev-* branches will be merged to master branch after all testing has passed in the staging server.


## Wordpress

We use the VersionPress plugin to track changes automatically and manually, rollback to previous states, selectively undo changes, and merge databases. 

## Shopify
[tbd]