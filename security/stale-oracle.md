# Stale Oracle

DeltaFi smart contracts make sure the oracle price is up-to-date by comparing the current timestamp `clock.slot` with the Pyth Network valid slot `price.valid_slot`. If the oracle becomes stale, DeltaFi protects liquidity provider and traders by stopping trades.
