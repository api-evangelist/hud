# HUD - US Department of Housing and Urban Development

APIs.json profile for the U.S. Department of Housing and Urban Development (HUD) public REST APIs.

## APIs Covered

- **Fair Market Rents API** — FMR data by state, county, and metro area (Section 8 payment standard basis)
- **Income Limits API** — AMI thresholds at 30/50/80% for housing program eligibility
- **USPS ZIP Code Crosswalk API** — ZIP-to-census geography mapping (tracts, counties, CBSAs, congressional districts)
- **CHAS API** — Comprehensive Housing Affordability Strategy data from ACS custom tabulations
- **Housing Counselor Search API** — Find HUD-approved housing counseling agencies by location

## Authentication

HUD User dataset APIs require a free bearer token. Register at https://www.huduser.gov/hudapi/public/register

The Housing Counselor Search API is publicly accessible with no authentication required.

## Rate Limits

- HUD User APIs: 1,200 requests per minute per token
- Housing Counselor API: unspecified limit; HTTP 429 returned when exceeded

## Resources

- Developer Portal: https://www.huduser.gov/portal/dataset/api.html
- Data Catalog: https://data.hud.gov/datasets
- Terms of Service: https://www.huduser.gov/portal/dataset/api-terms-of-service.html
- Contact: OpenData@hud.gov
