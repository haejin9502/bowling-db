# bowling-db

Bowling ball database crawled from [bowwwl.com](https://www.bowwwl.com/bowling-ball-database).

## Data

| File | URL |
|------|-----|
| balls.json | https://haejin9502.github.io/bowling-db/balls.json |
| version.json | https://haejin9502.github.io/bowling-db/version.json |

## Fields

Each ball object contains:
- id, brand, name, releaseDate
- coverstock, coverType, factoryFinish
- coreName, coreType
- specs (weight-by-weight RG / Diff / MB Diff)
- isDiscontinued, isOverseas
- sourceUrl, crawledAt

## Update

Data is crawled from bowwwl.com. Re-run the crawler to update.
