# Twitter identity scraper offchain worker
### Builders
[Drew](https://github.com/drewstone), [Jake](https://github.com/jnaviask)

### Construction Site
https://github.com/hicommonwealth/twitter-scraper-worker

## Description
A substrate based offchain worker for scraping data from Twitter mentions, specifically mentions incident on a specific Twitter account such as @heyedgeware. The worker should validate that the data included in each mention follows a specific schema as well as the contents of each schema section are validated against their spec.

## Project Blueprints
- Create an offchain worker that queries the Twitter API for mentions to an account.
- Document how to set/get offchain storage for Twitter OAUTH keys.
- Handle validation of returned response and filter spam.
- Parse valid tweets from this list and validate that each tweet contains a public key and signature to link one's Twitter account to their Edgeware account, including signature verification.
- Fire an event for failed and successful identity verifications.
- Fund the key submitted in the Tweet with a certain amount of native tokens (for PoC).

## Working Requirements
- Should post weekly updates
- Should define a timeline.
- Should refine spec publicly and seek feedback from community.

## Delivery Requirements
- Should be live for 1 week
- Should be signed off by at least 1/2 of the Builder's Council.
