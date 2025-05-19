# ✨ Changelog (`v1.124.1`)

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## Version Info

```text
This version -------- v1.124.1
Previous version ---- v1.116.0
Initial version ----- v1.67.0
Total commits ------- 13
```

## [v1.124.1] - 2025-04-01

### 🆕 Added

- PoliticalAssemblyPastLocked
- PoliticalAssemblyArchived
- PoliticalAssemblyArchiveDateUpdated
- enum PoliticalAssemblyState
- ArchivePoliticalAssemblyRequest

## [v1.124.0] - 2025-03-27

### 🆕 Added

- add domain of influence franking licence away number

## [v1.123.0] - 2025-03-25

### 🆕 Added

- add e-collecting settings on dois

## [v1.122.0] - 2025-03-14

### 🆕 Added

- add country, street and house number to election candidate

## [v1.121.2] - 2025-03-11

### 🔄 Changed

- revert changes in color scheme since enum values must be retained for event replay consistency

## [v1.121.1] - 2025-03-07

delete Colors in VotingCardColor

## [v1.121.0] - 2025-02-28

### 🔄 Changed

- Replace change streams with generic event change stream

## [v1.120.0] - 2025-02-24

### 🆕 Added

- add e-collecting flag

## [v1.119.1] - 2025-02-20

### 🔄 Changed

- add blank row count to majority election ballot group entry step

## [v1.119.0] - 2025-02-18

### 🆕 Added

- enable multiple electoral registers on domain of influence

## [v1.118.0] - 2025-02-14

### :new: Added

- added canton setting to hide the occupation title

## [v1.117.0] - 2025-02-14

### 🆕 Added

- e-counting flag on counting circle

## [v1.116.1] - 2025-02-10

### 🔄 Changed

- fix(VOTING-5377): update max length for short and official descriptions in ballot to align with eCH-0155 v4.0 specification.

## [v1.116.0] - 2025-02-06

### :new: Added

- add hide lower domain of influences in reports field

## [v1.115.0] - 2024-12-13

### 🆕 Added

- add secondary majority election protocols

## [v1.114.0] - 2024-12-11

### 🆕 Added

- domain of influence voting card flat rate owner

## [v1.113.0] - 2024-12-10

### 🔄 Changed

- majority election candidate optional date of birth and optional sex

## [v1.112.1] - 2024-11-28

### 🔄 Changed

- move resolve contest import from grpc to rest

## [v1.112.0] - 2024-11-26

### ❌ Removed

- removed allowed candidates from secondary majority elections

### 🆕 Added

- feat(VOTING-4526): allow overwriting of candidate number for majority election candidate references

### 🆕 Added

- publish results option on domain of influence

## [v1.111.0] - 2024-10-24

### 🆕 Added

- add political business summaries

## [v1.110.0] - 2024-10-17

### 🔄 Changed

- add STISTAT municipality flag to domain of influence

## [v1.109.0] - 2024-10-15

### 🔄 Changed

- allow candicate locality and origin to be optional

## [v1.108.0] - 2024-10-15

### 🆕 Added

- superior authority domain of influence

## [v1.107.3] - 2024-10-11

### 🔄 Changed

- change list union descriptions to simple string

## [v1.107.2] - 2024-10-04

### 🔄 Changed

- update input validation for person name properties from simple to complex single line text.

## [v1.107.1] - 2024-10-03

### ❌ Removed

- remove zh feature flag

## [v1.107.0] - 2024-09-23

### 🔄 Changed

- foreigner and minor voters

## [v1.106.2] - 2024-09-18

### 🔄 Changed

- election candidate number validation

## [v1.106.1] - 2024-09-10

### 🔄 Changed

- federal identification on ballot question

## [v1.106.0] - 2024-09-06

### 🆕 Added

- add federal identification

## [v1.105.1] - 2024-08-28

🔄 Changed

update bug bounty template reference
patch ci-cd template version, align with new defaults

## [v1.105.0] - 2024-08-28

### 🆕 Added

- optional individual candidates on majority elections

## [v1.104.0] - 2024-08-22

### 🆕 Added

- add counting circle and proportional election list change listener

## [v1.103.0] - 2024-08-13

### 🔄 Changed

- Change validation type of DOI/counting circle code from "alphanumeric whitespace" to "simple single line text"

## [v1.102.0] - 2024-08-13

### 🆕 Added

- add party for proportional election list

## [v1.101.1] - 2024-08-12

### 🔄 Changed

- deprecated sex type undefined

## [v1.101.0] - 2024-08-07

### :new: Added

- added political business sub type

## [v1.100.0] - 2024-07-29

### :new: Added

- added variant ballot on multiple ballots

## [v1.99.0] - 2024-07-25

### 🔄 Changed

- Make DOI short name optional
- Increase max length of DOI/counting circle code to 20 from 12

## [v1.98.0] - 2024-07-17

### 🔄 Changed

- canton settings with publish results before audited tentatively

## [v1.97.0] - 2024-07-16

### 🆕 Added

- set counting circle e-voting at a specific date

## [v1.96.1] - 2024-06-26

### 🔄 Changed

- plausibilisation configuration should be optional

## [v1.96.0] - 2024-06-26

### 🔄 Changed

- add internal plausibilisation canton settings

## [v1.95.0] - 2024-06-25

### 🆕 Added

- add create contest on highest hierarchical level canton settings

## [v1.94.0] - 2024-06-21

### 🆕 Added

- PoliticalAssemblyPastLocked
- PoliticalAssemblyArchived
- PoliticalAssemblyArchiveDateUpdated
- enum PoliticalAssemblyState
- ArchivePoliticalAssemblyRequest

### 🆕 Added

- add domain of influence franking licence away number

### 🆕 Added

- add e-collecting settings on dois

### 🆕 Added

- add country, street and house number to election candidate

### 🔄 Changed

- revert changes in color scheme since enum values must be retained for event replay consistency

delete Colors in VotingCardColor

### 🔄 Changed

- Replace change streams with generic event change stream

### 🆕 Added

- add e-collecting flag

### 🆕 Added

- enable multiple electoral registers on domain of influence

### :new: Added

- added canton setting to hide the occupation title

### 🆕 Added

- e-counting flag on counting circle

### 🔄 Changed

- fix(VOTING-5377): update max length for short and official descriptions in ballot to align with eCH-0155 v4.0 specification.

### :new: Added

- add hide lower domain of influences in reports field

### 🆕 Added

- add secondary majority election protocols

### 🆕 Added

- domain of influence voting card flat rate owner

### 🔄 Changed

- majority election candidate optional date of birth and optional sex

### 🔄 Changed

- move resolve contest import from grpc to rest

### ❌ Removed

- removed allowed candidates from secondary majority elections

### 🆕 Added

- feat(VOTING-4526): allow overwriting of candidate number for majority election candidate references

### 🆕 Added

- publish results option on domain of influence

### 🆕 Added

- add political business summaries

### 🔄 Changed

- allow candicate locality and origin to be optional

### 🆕 Added

- superior authority domain of influence

### 🔄 Changed

- change list union descriptions to simple string

### 🔄 Changed

- update input validation for person name properties from simple to complex single line text.

### ❌ Removed

- remove zh feature flag

### 🔄 Changed

- election candidate number validation

### 🆕 Added

- add federal identification

🔄 Changed

update bug bounty template reference
patch ci-cd template version, align with new defaults

### 🆕 Added

- optional individual candidates on majority elections

### 🆕 Added

- add counting circle and proportional election list change listener

### 🔄 Changed

- Change validation type of DOI/counting circle code from "alphanumeric whitespace" to "simple single line text"

### 🆕 Added

- add party for proportional election list

### 🔄 Changed

- deprecated sex type undefined

### :new: Added

- added political business sub type

### :new: Added

- added variant ballot on multiple ballots

### 🔄 Changed

- Make DOI short name optional
- Increase max length of DOI/counting circle code to 20 from 12

### 🆕 Added

- set counting circle e-voting at a specific date

### 🔄 Changed

- plausibilisation configuration should be optional

### 🆕 Added

- add create contest on highest hierarchical level canton settings
