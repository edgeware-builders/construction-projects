# Ethereum light-client offchain worker
### Builders
[Drew](https://github.com/drewstone), [Jake](https://github.com/jnaviask)

### Construction Site
https://github.com/hicommonwealth/substrate-eth-light-client

## Description
A substrate based offchain worker that functions as an ethereum light-client. The offchain worker will poll RPCs of Ethereum nodes to ask for block headers and then subsequently validate the headers with full proof of work verification.

## Project Blueprints
- Create an offchain worker that queries an INFURA node for the latest header.
- Initialises the state or adds new headers depending on state of pallet.
- Should efficiently verify block headers and fit into the Edgeware runtime given the existing constraints around extrinsic weight.
- Should support backtracking if offchain workers fall behind.
- Should support multiple RPC destinations, defined by workers themselves.

## Working Requirements
- Should post weekly updates
- Should define a timeline.
- Should refine spec publicly and seek feedback from community.

## Delivery Requirements
- Should be live for 1 week
- Should be signed off by at least 1/2 of the Builder's Council.
