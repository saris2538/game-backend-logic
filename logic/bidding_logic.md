# Bidding Logic

## Inputs
- Bid values per team per block
- Budget constraint per team

## Validation
- Total bids must not exceed budget
- Invalid inputs are flagged immediately

## Winner determination
- For each block:
  - Identify the highest bid
  - If a single team has the highest bid → sole winner
  - If multiple teams tie → shared ownership

## Outputs
- Winner list per block
- Tie count per block (used downstream)
