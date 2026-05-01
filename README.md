# PrivateBid — Private Sealed-Bid Auction on Arcium

PrivateBid is a sealed-bid auction demo built for the Arcium Blind Auctions RTG.

It shows how bids can stay private during an auction, while only the final winning result is revealed after the auction closes.

## Why this matters

Normal auctions expose bids publicly. This can lead to bid copying, collusion, unfair price manipulation, and MEV leakage.

PrivateBid demonstrates how Arcium can act as a privacy layer for encrypted bid handling and private result computation.

## Features

- Create a simple auction item
- Submit a private encrypted bid
- Keep bid amount hidden during the auction
- Close the auction
- Reveal only the final result

## Arcium Privacy Use Case

Arcium enables private computation for sealed-bid auctions.  
In this demo, bids are treated as encrypted/private inputs, and only the winning result is revealed at the end.

## RTG

Blind Auctions — Sealed-Bid / Vickrey / Uniform

## Demo Flow

1. Connect wallet
2. Enter auction item
3. Submit private bid
4. Close auction
5. Reveal winner result