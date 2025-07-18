# 3. Donate

The Protocol Guild’s funding mechanism was designed to remove friction associated with supporting Ethereum’s core protocol development, by providing a single onchain address which vests funds directly to active core protocol contributors over time. 

Note that there are different donation addresses depending on if you're donating on Ethereum mainnet or L2s / other chains!

All donations can be seen in Protocol Guild's [Dune Dashboard](https://dune.com/protocolguild/protocol-guild).

## 3.1 Mainnet

<b>[theprotocolguild.eth](https://app.splits.org/accounts/0x25941dc771bb64514fc8abbce970307fb9d477e9)<br>
[0x25941dC771bB64514Fc8abBce970307Fb9d477e9](https://app.splits.org/accounts/0x25941dc771bb64514fc8abbce970307fb9d477e9)</b>

[![Donate](https://github.com/cheeky-gorilla/documentation/assets/76262359/5b690222-f61c-4f6d-9dfd-d3b4972fd4aa)](https://app.splits.org/accounts/0x25941dc771bb64514fc8abbce970307fb9d477e9)

The Guild’s mainnet donation address is an immutable vesting contract which trustlessly vests donated funds over 4 years. Vested funds get pushed into a [pass-through wallet](https://app.splits.org/accounts/0x25941dc771bb64514fc8abbce970307fb9d477e9/), which in turn sends funds to a [split contract](https://app.splits.org/accounts/0xd4ad8daba9ee5ef16bb931d1cbe63fb9e102ec10/) for distribution to the membership. You can read more about this smart contract architecture [here](https://protocol-guild.readthedocs.io/en/latest/03-onchain-architecture.html). 

Important: The vesting contract only works with ETH and ERC20 tokens, and cannot claim funds. For other tokens, or if donations need to be claimed on mainnet, then please use this multisig instead: [0xdddd576bAF106bAAe54bDE40BCac602bB4a7cf79](https://app.safe.global/settings/setup?safe=eth:0xdddd576bAF106bAAe54bDE40BCac602bB4a7cf79)

## 3.2 L2s / Other Chains

Apart from Ethereumn mainnet, vesting contracts have been deployed on Arbitrum, Base and Optimism. For other L2s / chains, 6/10 multisigs have been deployed to receive donations. Multisig funds will be periodically bridged into vesting contracts. 

### Arbitrum
- Vesting Contract (ETH + ERC20 only): [0x7F8DCFd764bA8e9B3BA577dC641D5c664B74c47b](https://app.splits.org/accounts/0x7F8DCFd764bA8e9B3BA577dC641D5c664B74c47b/?chainId=42161)
  - Multisig (if funds need to be claimed): [0xdddd576bAF106bAAe54bDE40BCac602bB4a7cf79](https://app.safe.global/balances?safe=arb1:0xdddd576bAF106bAAe54bDE40BCac602bB4a7cf79)

### Base
- Vesting Contract (ETH + ERC20 only): [0xd16713A5D4Eb7E3aAc9D2228eB72f6f7328FADBD](https://app.splits.org/accounts/0xd16713A5D4Eb7E3aAc9D2228eB72f6f7328FADBD/?chainId=8453)
  - Multisig (if funds need to be claimed): [0xdddd576bAF106bAAe54bDE40BCac602bB4a7cf79](https://app.safe.global/balances?safe=base:0xdddd576bAF106bAAe54bDE40BCac602bB4a7cf79)

### Optimism
- Vesting Contract (ETH + ERC20 only): [0x58ae0925077527a87D3B785aDecA018F9977Ec34](https://app.splits.org/accounts/0x58ae0925077527a87D3B785aDecA018F9977Ec34/?chainId=10)
  - Multisig (if funds need to be claimed): [0xdddd576bAF106bAAe54bDE40BCac602bB4a7cf79](https://app.safe.global/balances?safe=oeth:0xdddd576bAF106bAAe54bDE40BCac602bB4a7cf79)

### Polygon
- Multisig: [0xdddd576bAF106bAAe54bDE40BCac602bB4a7cf79](https://app.safe.global/balances?safe=matic:0xdddd576bAF106bAAe54bDE40BCac602bB4a7cf79)

### Scroll
- Multisig: [0xdddd576bAF106bAAe54bDE40BCac602bB4a7cf79](https://app.safe.global/balances?safe=scr:0xdddd576bAF106bAAe54bDE40BCac602bB4a7cf79)

### Shape
- Multisig: [0x700fccD433E878F1AF9B64A433Cb2E09f5226CE8](https://safe.shape.network/balances?safe=shape:0x700fccD433E878F1AF9B64A433Cb2E09f5226CE8)

### zkSync
- Multisig: [0x9fb5F754f5222449F98b904a34494cB21AADFdf8](https://app.safe.global/balances?safe=zksync:0x9fb5F754f5222449F98b904a34494cB21AADFdf8)

### Zora
- Multisig: [0x32e3C7fD24e175701A35c224f2238d18439C7dBC](https://safe.optimism.io/balances?safe=zora:0x32e3C7fD24e175701A35c224f2238d18439C7dBC)

## 3.3 Protocol Guild Pledge

Protocol Guild's long-term mission is to make contributing to Ethereum L1 R&D economically rational on a risk-adjusted basis, while avoiding capture. To get there, we aim to normalize that projects built on Ethereum donate 1% of their native token to the Protocol Guild. 

You can read about the Protocol Guild Pledge here: 
[https://tim.mirror.xyz/srVdVopOFhD_ZoRDR50x8n5wmW3aRJIrNEAkpyQ4_ng](https://tim.mirror.xyz/srVdVopOFhD_ZoRDR50x8n5wmW3aRJIrNEAkpyQ4_ng)

You can see projects that have already taken the pledge here: 
[https://dune.com/protocolguild/protocol-guild#protocol-guild-pledge](https://dune.com/protocolguild/protocol-guild#protocol-guild-pledge)

### How to take the Pledge?

Projects that don't have a token yet can take the pledge by making a public commitment to donate 1% of a future token to the Protocol Guild. You can see an example of this [here](https://x.com/taikoxyz/status/1755609928167981330).

Projects that already have a token can take the pledge by donating 1% of its supply to one of the donation addresses indicated above. 

If you have questions about taking the pledge, please reach out on [Discord](https://discord.com/invite/HaUhXYsMyC), [Twitter](https://x.com/ProtocolGuild) or [Farcaster](https://warpcast.com/protocolguild).
