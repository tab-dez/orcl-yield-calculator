# ORCL^D Yield Calculator

Interactive yield calculator for Oracle Series D Mandatory Convertible Preferred Stock.

## Deployment

Upload the original calculator as `index.html` in the repository root. In repository Settings > Pages, select GitHub Actions as the source. The included workflow deploys on pushes to `main`.

Expected website address after successful deployment:
https://tab-dez.github.io/orcl-yield-calculator/

The website is not live until Pages is enabled and deployment succeeds.

## Model limitations

This calculator is educational, not investment advice. Dividends are aggregated at conversion rather than modeled as quarterly cash flows. Conversion scenarios represent the conversion-period VWAP; anti-dilution adjustments are not modeled. The uploaded financial assumptions have not been independently reverified during deployment.

## License

MIT.
