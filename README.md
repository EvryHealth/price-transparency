# Evry Health Price Transparency

## Transparency in Coverage
The Department of the Treasure, Labor, and Health and Human Servcies have issued the Transparency in Coverage final rules (85 FR 72158) on November 12, 2022. The final rules require non-grandfathered group health plans and health insurance issuers in the individual and group markets (plans and issuers) to disclose certain pricing information. Under the final rules a plan or issuer must disclose in-network negotiated rates, and billed and out-of-network allowed through two machine-readable files posted on an internet website.

## Keeping Up To Date
Github allows for people to track and keep up-to-date with any changes for any repository. If you wish to follow and track the changes that happen on this repo, please leverage the "Watch" feature found at the top of the repository and select "All activity". This will email the user that has "watched" the specific repository.

## Repository Structure and File Naming Convension
This public repository is use to store the In-Network Rates for our providers. Inside the Rates folder there will be a folder for each year which will contain a folder for each month. Starting in July 2022. The Rates for that month and year will be placed in that folder and have the following naming convention: `<YYYY-MM-DD>_<payer or issuer name><file type name>.<file extension>`

For example `Evry Health` would produce a JSON file with the following name:

- `2022-07-01_Evry-Health_in-network-rates.json`
- `2022-07-01_Evry-Health_allowed-amounts.json`

## Versioning
We will use [SemVer 2.0.0](https://semver.org/) versioning structure. Which will be located in the VERSION.md file.

## File Formats And Schema
Our Transparency in Coverage docuemnts uses the [JSON](https://www.json.org/) file format. 

For information on the schema used please see the [CMSgov Price Transparency Guide Repo](https://github.com/CMSgov/price-transparency-guide).

- [In-Network Rates Schema](https://github.com/CMSgov/price-transparency-guide/tree/master/schemas/in-network-rates)
- [Allowed Amounts Schema](https://github.com/CMSgov/price-transparency-guide/tree/master/schemas/allowed-amounts)