# JLCPCB Fabrication Files

Manufacturing and assembly inputs for the two powerboard connector variants.

## Files

- `C6P_bom.csv`: BOM for the C6P input connector variant
- `C6P_positions.csv`: Pick-and-place for C6P variant
- `R7BF_bom.csv`: BOM for the R7BF input connector variant
- `R7BF_positions.csv`: Pick-and-place for R7BF variant

## How To Use

1. Choose one variant only (`C6P` or `R7BF`).
2. Go to: https://cart.jlcpcb.com 
3. Upload the matching Gerbers.
4. Upload the matching BOM and positions CSV from this folder.
5. Verify connector footprints and rotations before confirming assembly.

## Important

- Do not mix BOM and positions across variants.
- The input connector differs between variants; rest of the design is largely shared.
