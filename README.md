---
description: Nexex a toolkit to create your own decentralized exchange.
---

# Overview

Nexex is s next-generation decentralized exchange toolkit on ethereum network. It allows anyone to become a relayer, publishing and listening any interested orders from other relayers.

## Why Nexex?

Nexex highly values relayers' contribution to the ecosystem, more than any other DEX solutions in the market. We consider the current market is fragmented, while more DEX appear, end user's trading intentions are distributed in more platforms and make it harder to get them matched. This harms the whole ecosystem. 

So we build Nexex toolkit with several core features

1. Everyone can become a relayer, and all relayers are connected via a decentralized message channel.
2. When an order is taken by order taker, both the relayer who helped order maker to publish and distributed the order and the relayer who helped taker to trade this order will be awarded for their contributions.
3. we provide basic components helping new relayer join the network, which brings value to the ecosystem not harming it. The components including:
   1. nexex smart contract depolyed in kovan and mainnet.
   2. a orderbook service which is designed to be able to configure to scale out for different needs.
   3. api sdk to interact with our smart contract
   4. orderbook client sdk which can talk to orderbook service
   5. a cmd-line tool to query and trade in our network.
   6. a web trading site can be rebranded to suit relayers need freely. \(coming soon\)

