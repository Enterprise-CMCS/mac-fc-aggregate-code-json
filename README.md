# mac-fc-aggregate-code-json

This repo is the target for [automation in the MAC-FC cost-analysis repo](https://github.com/Enterprise-CMCS/mac-fc-macbis-cost-analysis/tree/main/cmd/aggregate-code-json) that aggregates `code.json` files from all private and internal repositories in a GitHub organization to create a consolidated inventory for ShareIT Act compliance. This allows the Open Source Program Office to access the copied files in this public repo.

The automation:

- Creates `data/raw/` directory with individual `code.json` files from each private and internal repository
- Generates `data/code.json` with aggregated inventory in SHARE IT Act format
