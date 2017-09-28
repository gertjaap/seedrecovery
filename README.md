# seedrecovery

Tries to recover a 12-word recovery seed from 10 known words by brute force.

To use:

- Clone this repo
- run `npm install`
- edit the index.js and enter the known 10 words and the first address from the wallet you're trying to recover

If any of the possible 2048 * 2048 combinations is valid, it will print out the correct seedphrase
