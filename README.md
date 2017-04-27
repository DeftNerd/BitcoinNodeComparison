# BIPs implemented by various different Bitcoin full-node implementations.

## Nodes
- pbtc (Rust)
- core (C++)
- unlimited (C++)
- bcoin (NodeJS)
- btcsuite (Go)

## Key 

- :heavy_multiplication_x: not implemented

- :heavy_check_mark: implemented

- :question: unknown

- :clock3: work in progress


| BIP                | Title                                    |           pbtc           |           core           |        unlimited         |       bcoin        |         btcsuite         |
| ------------------ | ---------------------------------------- | :----------------------: | :----------------------: | :----------------------: | :----------------: | :----------------------: |
| [BIP 9][BIP9]      | Version bits with timeout and delay      |         :clock3:         |    :heavy_check_mark:    |    :heavy_check_mark:    | :heavy_check_mark: |    :heavy_check_mark:    |
| [BIP 11][BIP11]    | M-of-N Standard Transactions             |    :heavy_check_mark:    |    :heavy_check_mark:    |    :heavy_check_mark:    | :heavy_check_mark: |    :heavy_check_mark:    |
| [BIP 13][BIP13]    | Address Format for pay-to-script-hash    |    :heavy_check_mark:    |    :heavy_check_mark:    |    :heavy_check_mark:    | :heavy_check_mark: |    :heavy_check_mark:    |
| [BIP 14][BIP14]    | Protocol Version and User Agent          | :heavy_multiplication_x: |    :heavy_check_mark:    |    :heavy_check_mark:    | :heavy_check_mark: |    :heavy_check_mark:    |
| [BIP 16][BIP16]    | Pay to Script Hash                       |    :heavy_check_mark:    |    :heavy_check_mark:    |    :heavy_check_mark:    | :heavy_check_mark: |    :heavy_check_mark:    |
| [BIP 21][BIP21]    | URI Scheme                               |    :heavy_check_mark:    |    :heavy_check_mark:    |    :heavy_check_mark:    | :heavy_check_mark: | :heavy_multiplication_x: |
| [BIP 22][BIP22]    | getblocktemplate - Fundamentals          |    :heavy_check_mark:    |    :heavy_check_mark:    |    :heavy_check_mark:    | :heavy_check_mark: |    :heavy_check_mark:    |
| [BIP 23][BIP23]    | getblocktemplate - Pooled Mining         |    :heavy_check_mark:    |    :heavy_check_mark:    |    :heavy_check_mark:    | :heavy_check_mark: |    :heavy_check_mark:    |
| [BIP 30][BIP30]    | Duplicate transactions                   |    :heavy_check_mark:    |    :heavy_check_mark:    |    :heavy_check_mark:    | :heavy_check_mark: |    :heavy_check_mark:    |
| [BIP 31][BIP31]    | Pong message                             |    :heavy_check_mark:    |    :heavy_check_mark:    |    :heavy_check_mark:    | :heavy_check_mark: |    :heavy_check_mark:    |
| [BIP 32][BIP32]    | Hierarchical Deterministic Wallets       |    :heavy_check_mark:    |    :heavy_check_mark:    |    :heavy_check_mark:    | :heavy_check_mark: |    :heavy_check_mark:    |
| [BIP 34][BIP34]    | Block v2, Height in Coinbase             |    :heavy_check_mark:    |    :heavy_check_mark:    |    :heavy_check_mark:    | :heavy_check_mark: |    :heavy_check_mark:    |
| [BIP 35][BIP35]    | mempool message                          |    :heavy_check_mark:    |    :heavy_check_mark:    |    :heavy_check_mark:    | :heavy_check_mark: |    :heavy_check_mark:    |
| [BIP 37][BIP37]    | Connection Bloom filtering               |    :heavy_check_mark:    |    :heavy_check_mark:    |    :heavy_check_mark:    | :heavy_check_mark: |    :heavy_check_mark:    |
| [BIP 42][BIP42]    | A finite monetary supply for Bitcoin     |    :heavy_check_mark:    |    :heavy_check_mark:    |    :heavy_check_mark:    | :heavy_check_mark: |    :heavy_check_mark:    |
| [BIP 44][BIP44]    | Multi-Account Hierarchy for Deterministic Wallets | :heavy_multiplication_x: | :heavy_multiplication_x: | :heavy_multiplication_x: | :heavy_check_mark: |    :heavy_check_mark:    |
| [BIP 61][BIP61]    | Reject P2P message                       |        :question:        |    :heavy_check_mark:    |    :heavy_check_mark:    | :heavy_check_mark: |    :heavy_check_mark:    |
| [BIP 65][BIP65]    | OP_CHECKLOCKTIMEVERIFY                   |    :heavy_check_mark:    |    :heavy_check_mark:    |    :heavy_check_mark:    | :heavy_check_mark: |    :heavy_check_mark:    |
| [BIP 66][BIP66]    | Strict DER signatures                    |    :heavy_check_mark:    |    :heavy_check_mark:    |    :heavy_check_mark:    | :heavy_check_mark: |    :heavy_check_mark:    |
| [BIP 68][BIP68]    | Relative lock-time using consensus-enforced sequence numbers |         :clock3:         |    :heavy_check_mark:    |    :heavy_check_mark:    | :heavy_check_mark: |    :heavy_check_mark:    |
| [BIP 70][BIP70]    | Payment Protocol                         |    :heavy_check_mark:    |    :heavy_check_mark:    |    :heavy_check_mark:    | :heavy_check_mark: | :heavy_multiplication_x: |
| [BIP 71][BIP71]    | Payment Protocol MIME types              |    :heavy_check_mark:    |    :heavy_check_mark:    |    :heavy_check_mark:    | :heavy_check_mark: | :heavy_multiplication_x: |
| [BIP 72][BIP72]    | bitcoin: uri extensions for Payment Protocol |    :heavy_check_mark:    |    :heavy_check_mark:    |    :heavy_check_mark:    | :heavy_check_mark: | :heavy_multiplication_x: |
| [BIP 90][BIP90]    | Buried Deployments                       |    :heavy_check_mark:    |    :heavy_check_mark:    |    :heavy_check_mark:    | :heavy_check_mark: |        :question:        |
| [BIP 111][BIP111]  | NODE_BLOOM service bit                   |        :question:        |    :heavy_check_mark:    |    :heavy_check_mark:    | :heavy_check_mark: |    :heavy_check_mark:    |
| [BIP 112][BIP112]  | CHECKSEQUENCEVERIFY                      |         :clock3:         |    :heavy_check_mark:    |    :heavy_check_mark:    | :heavy_check_mark: |    :heavy_check_mark:    |
| [BIP 113][BIP113]  | Median time-past as endpoint for lock-time calculations |         :clock3:         |    :heavy_check_mark:    |    :heavy_check_mark:    | :heavy_check_mark: |    :heavy_check_mark:    |
| [BIP 125][BIP125]  | Opt-in Full Replace-by-Fee Signaling     |    :heavy_check_mark:    |    :heavy_check_mark:    |    :heavy_check_mark:    | :heavy_check_mark: | :heavy_multiplication_x: |
| [BIP 130][BIP130]  | sendheaders message                      |        :question:        |    :heavy_check_mark:    |    :heavy_check_mark:    | :heavy_check_mark: |    :heavy_check_mark:    |
| [BIP 133][BIP133]  | feefilter message                        |        :question:        |    :heavy_check_mark:    |        :question:        | :heavy_check_mark: |    :heavy_check_mark:    |
| [BIP 141][BIP141]  | Segregated Witness (Consensus layer)     | :heavy_multiplication_x: |    :heavy_check_mark:    | :heavy_multiplication_x: | :heavy_check_mark: |         :clock3:         |
| [BIP 143][BIP143]  | Transaction Signature Verification for Version 0 Witness Program | :heavy_multiplication_x: |    :heavy_check_mark:    | :heavy_multiplication_x: | :heavy_check_mark: |         :clock3:         |
| [BIP 144][BIP144]  | Segregated Witness (Peer Services)       | :heavy_multiplication_x: |    :heavy_check_mark:    | :heavy_multiplication_x: | :heavy_check_mark: |         :clock3:         |
| [BIP 145][BIP145]  | getblocktemplate Updates for Segregated Witness | :heavy_multiplication_x: |    :heavy_check_mark:    | :heavy_multiplication_x: | :heavy_check_mark: |         :clock3:         |
| [BIP 147][BIP147]  | Dealing with dummy stack element malleability | :heavy_multiplication_x: |    :heavy_check_mark:    |        :question:        | :heavy_check_mark: |         :clock3:         |
| [BIP 150][BIP150]  | Peer Authentication                      |        :question:        |        :question:        |        :question:        | :heavy_check_mark: | :heavy_multiplication_x: |
| [BIP 151][BIP151]  | Peer-to-Peer Communication Encryption    | :heavy_multiplication_x: | :heavy_multiplication_x: | :heavy_multiplication_x: | :heavy_check_mark: | :heavy_multiplication_x: |
| [BIP 152][BIP152]  | Compact Block Relay                      | :heavy_multiplication_x: |    :heavy_check_mark:    |        :question:        | :heavy_check_mark: | :heavy_multiplication_x: |
| [BUIP001][BUIP001] | Extensions to the Bitcoin Client         |                          |                          |    :heavy_check_mark:    |                    |                          |
| [BUIP002][BUIP002] | Multi-BIP Scaling Enabler                |                          |                          |    :heavy_check_mark:    |                    |                          |
| [BUIP004][BUIP004] | RBF/double spending support              |                          |                          |    :heavy_check_mark:    |                    |                          |
| [BUIP005][BUIP005] | Settings information via coinbase-txn & user-agent |                          |                          |    :heavy_check_mark:    |                    |                          |
| [BUIP010][BUIP010] | Xtreme Thinblocks                        |                          |                          |    :heavy_check_mark:    |                    |                          |
| [BUIP013][BUIP013] | Upgrade alert system                     |                          |                          |    :heavy_check_mark:    |                    |                          |
| [BUIP023][BUIP023] | Miner block creation latency optimization |                          |                          |    :heavy_check_mark:    |                    |                          |
| [BUIP033][BUIP033] | Parallel Validation                      |                          |                          |    :heavy_check_mark:    |                    |                          |
| [BUIP040][BUIP040] | Emergent Consensus Parameters and Defaults for Large (>1MB) Blocks |                          |                          |    :heavy_check_mark:    |                    |                          |

[BIP9]: https://github.com/bitcoin/bips/blob/master/bip-0009.mediawiki
[BIP11]: https://github.com/bitcoin/bips/blob/master/bip-0011.mediawiki
[BIP13]: https://github.com/bitcoin/bips/blob/master/bip-0013.mediawiki
[BIP14]: https://github.com/bitcoin/bips/blob/master/bip-0014.mediawiki
[BIP16]: https://github.com/bitcoin/bips/blob/master/bip-0016.mediawiki
[BIP21]: https://github.com/bitcoin/bips/blob/master/bip-0021.mediawiki
[BIP22]: https://github.com/bitcoin/bips/blob/master/bip-0022.mediawiki
[BIP23]: https://github.com/bitcoin/bips/blob/master/bip-0023.mediawiki
[BIP30]: https://github.com/bitcoin/bips/blob/master/bip-0030.mediawiki
[BIP31]: https://github.com/bitcoin/bips/blob/master/bip-0031.mediawiki
[BIP32]: https://github.com/bitcoin/bips/blob/master/bip-0032.mediawiki
[BIP34]: https://github.com/bitcoin/bips/blob/master/bip-0034.mediawiki
[BIP35]: https://github.com/bitcoin/bips/blob/master/bip-0035.mediawiki
[BIP37]: https://github.com/bitcoin/bips/blob/master/bip-0037.mediawiki
[BIP42]: https://github.com/bitcoin/bips/blob/master/bip-0042.mediawiki
[BIP44]: https://github.com/bitcoin/bips/blob/master/bip-0044.mediawiki
[BIP61]: https://github.com/bitcoin/bips/blob/master/bip-0061.mediawiki
[BIP65]: https://github.com/bitcoin/bips/blob/master/bip-0065.mediawiki
[BIP66]: https://github.com/bitcoin/bips/blob/master/bip-0066.mediawiki
[BIP68]: https://github.com/bitcoin/bips/blob/master/bip-0068.mediawiki
[BIP70]: https://github.com/bitcoin/bips/blob/master/bip-0070.mediawiki
[BIP71]: https://github.com/bitcoin/bips/blob/master/bip-0071.mediawiki
[BIP72]: https://github.com/bitcoin/bips/blob/master/bip-0072.mediawiki
[BIP90]: https://github.com/bitcoin/bips/blob/master/bip-0090.mediawiki
[BIP111]: https://github.com/bitcoin/bips/blob/master/bip-0111.mediawiki
[BIP112]: https://github.com/bitcoin/bips/blob/master/bip-0112.mediawiki
[BIP113]: https://github.com/bitcoin/bips/blob/master/bip-0113.mediawiki
[BIP125]: https://github.com/bitcoin/bips/blob/master/bip-0125.mediawiki
[BIP130]: https://github.com/bitcoin/bips/blob/master/bip-0130.mediawiki
[BIP133]: https://github.com/bitcoin/bips/blob/master/bip-0133.mediawiki
[BIP141]: https://github.com/bitcoin/bips/blob/master/bip-0141.mediawiki
[BIP143]: https://github.com/bitcoin/bips/blob/master/bip-0143.mediawiki
[BIP144]: https://github.com/bitcoin/bips/blob/master/bip-0144.mediawiki
[BIP145]: https://github.com/bitcoin/bips/blob/master/bip-0145.mediawiki
[BIP147]: https://github.com/bitcoin/bips/blob/master/bip-0147.mediawiki
[BIP150]: https://github.com/bitcoin/bips/blob/master/bip-0150.mediawiki
[BIP151]: https://github.com/bitcoin/bips/blob/master/bip-0151.mediawiki
[BIP152]: https://github.com/bitcoin/bips/blob/master/bip-0152.mediawiki
[BUIP001]: https://github.com/BitcoinUnlimited/BUIP/blob/master/001.mediawiki
[BUIP002]: https://github.com/BitcoinUnlimited/BUIP/blob/master/002.mediawiki
[BUIP004]: https://github.com/BitcoinUnlimited/BUIP/blob/master/004.mediawiki
[BUIP005]: https://github.com/BitcoinUnlimited/BUIP/blob/master/005.mediawiki
[BUIP010]: https://github.com/BitcoinUnlimited/BUIP/blob/master/010.mediawiki
[BUIP013]: https://github.com/BitcoinUnlimited/BUIP/blob/master/013.mediawiki
[BUIP023]: https://github.com/BitcoinUnlimited/BUIP/blob/master/023.mediawiki
[BUIP033]: https://github.com/BitcoinUnlimited/BUIP/blob/master/033.mediawiki
[BUIP040]: https://github.com/BitcoinUnlimited/BUIP/blob/master/040.mediawiki
