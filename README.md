# PrivateBid — Private Sealed-Bid Auction on Arcium

PrivateBid is a Solana-based sealed-bid auction prototype built for the Arcium Blind Auctions RTG.

It demonstrates how auction bids can remain private during the bidding period, while only the final result is revealed after the auction closes.

## What it does

PrivateBid lets users:

1. Connect a Solana wallet
2. Create an auction item
3. Submit a private bid
4. Keep the bid hidden during the auction
5. Close the auction
6. Reveal only the final winning result

## Why Arcium is useful here

In normal auctions, bids are often visible too early. This creates problems like:

- Bid copying
- Collusion
- Price manipulation
- MEV leakage
- Unfair auction outcomes

Arcium solves this by acting as the privacy layer for encrypted computation.

In PrivateBid, Arcium is used conceptually for:

- Encrypted bid submission
- Private bid comparison
- Hidden bidding state
- Final winner computation
- Revealing only the result after close

## RTG Requirement Match

### Functional Solana project

PrivateBid is designed around a Solana wallet-based auction flow. The user connects a wallet, submits a bid, and interacts with the auction interface.

### Integrated with Arcium

Arcium is used as the privacy layer for the sealed-bid auction logic. Bids are treated as encrypted inputs, and only the final winning result is revealed.

### Open-source GitHub repo

This repository contains the full source code for the demo.

### Submission language

The project and explanation are written in English.

## Judging Criteria

### Innovation

PrivateBid applies encrypted computation to auction markets, making sealed-bid auctions fairer and more private.

### Technical Implementation

The project demonstrates a Solana-based auction interface with an Arcium privacy flow for encrypted bid handling and private result computation.

### User Experience

The app keeps the flow simple:

Connect wallet → Enter auction item → Submit private bid → Close auction → Reveal result.

### Impact

Private auctions can help improve real-world markets, NFT sales, token launches, private lending, procurement, and onchain price discovery.

### Clarity

The project clearly shows where Arcium fits: bids stay private during the auction, and only the final result is revealed after close.

## Demo Flow

1. Connect wallet
2. Enter auction item
3. Submit encrypted private bid
4. Close auction
5. Reveal private winner result

## RTG

Blind Auctions — Sealed-Bid / Vickrey / Uniform