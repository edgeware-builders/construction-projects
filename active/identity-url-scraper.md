# Identity URL scraper offchain worker
### Builders
[Drew](https://github.com/drewstone), [Jake](https://github.com/jnaviask)

### Construction Site
https://github.com/hicommonwealth/identity-worker

## Description
A substrate based offchain worker for scraping data from third-party identity providers using submitted URLs by external users to the pallet. Certain third-party identity providers supported from the beginning are Github and Twitter, using gists and tweets respectively.

## Project Blueprints
- Create an offchain worker that maintains a queue of proposals to verify.
- Each proposal contains a URL, specifies metadata such as public key and signature, and targets a specific identity provider.
- The offchain worker should pull from this queue and validate data returned from the URL.
- Handle validation of the returned responses and verification of the identity links.
- Fund each successful verification with some native token.

## Working Requirements
- Should post weekly updates
- Should define a timeline.
- Should refine spec publicly and seek feedback from community.

## Delivery Requirements
- Should be live for 1 week
- Should be signed off by at least 1/2 of the Builder's Council.
