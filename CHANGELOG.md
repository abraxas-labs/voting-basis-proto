# ✨ Changelog (`v1.106.2`)

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## Version Info

```text
This version -------- v1.106.2
Previous version ---- v1.93.0
Initial version ----- v1.67.0
Total commits ------- 20
```

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

- add political business finalize canton settings

## [v1.93.0] - 2024-05-29

### 🆕 Added

- add publish results enabled canton setting

## [v1.92.0] - 2024-05-22

### 🆕 Added

- add ballot question type

## [v1.91.0] - 2024-05-06

### 🆕 Added

- proportional election update mandate algorithm

## [v1.90.0] - 2024-05-03

### 🔄 Changed

- move Stimmregister flag from canton settings to DOI

## [v1.89.0] - 2024-04-19

### 🆕 Added

- add state plausibilised enabled canton setting

## [v1.88.0] - 2024-04-18

### 🆕 Added

- add counting circle result state descriptions

## [v1.87.0] - 2024-04-15

### :new: Added

- added voting card color

## [v1.86.1] - 2024-04-08

### 🔄 Changed

- admin management service contains the return address of dois now

## [v1.86.0] - 2024-04-03

### 🆕 Added

- add evoting flag to counting circle

### ❌ Removed

- remove contest counting circle options

## [v1.85.0] - 2024-03-28

### :new: Added

- added view partial counting circle results flag to domain of influence

## [v1.84.0] - 2024-03-14

### 🆕 Added

- add virtual top level domain of influence

## [v1.83.1] - 2024-03-13

### 🔄 Changed

- update input validation for vote attribute

## [v1.83.0] - 2024-03-11

### 🆕 Added

- add vote result algorithm popular and counting circle majority

## [v1.82.0] - 2024-03-05

### 🆕 Added

- add political assembly

## [v1.81.0] - 2024-02-16

### :new: Added

- added canton to counting circle

## [v1.80.0] - 2024-02-02

### 🔄 Changed

- double proportional election mandate algorithms

## [v1.79.0] - 2024-01-29

### 🆕 Added

- Add counting circle electorates

## [v1.78.0] - 2024-01-26

### 🆕 Added

- add candidate check digit

## [v1.77.0] - 2024-01-10

### :new: Added

- added permission service

## [v1.76.0] - 2024-01-04

### 🆕 Added

- add new zh features flag

## [v1.75.0] - 2023-12-20

### 🆕 Added

- Add counting machine flag to canton settings

## [v1.74.0] - 2023-12-19

### 🆕 Added

- allow multiple vote ballots

## [v1.73.0] - 2023-08-31

### 🔄 Changed

- political first name of candidate from simple text to complex text

## [v1.72.2] - 2023-08-18

### ❌ Removed

- remove franking licence away number

## [v1.72.1] - 2023-08-17

### 🔄 Changed

- rename swiss post order number to franking licence number away

## [v1.72.0] - 2023-08-10

### 🔄 Changed

- add party mapping on import

## [v1.71.0] - 2023-07-25

### 🔄 Changed

- add swiss post data to domain of influence

## [v1.70.2] - 2023-07-18

### 🆕 Added

- Add domain of influence voting card shipping choice

## [v1.70.1] - 2023-06-13

### 🔄 Changed

- change input validation for doi party short description from simple to complex type

### 🔄 Changed

- electoral registration on canton settings

### 🆕 Added

- Added domain of influence sap customer order number

### 🔄 Changed

- revert removing fields from event data

### ❌ Removed

- remove internal description, invalid votes and individual empty ballots allowed from elections

### 🆕 Added

- add domain of influence canton

### 🆕 Added

- Added event signature

### 🔒 Security

- define input validation rules for service request models.

### 🆕 Added

- add new admin management services

### 🆕 Added

- add new admin management services

### 🆕 Added

- Name for protocol for domain of influence and counting circle
- Sortnumber for counting circle
- Protocol sort types for domain of influence and counting circle

### 🆕 Added

- added review procedure and enforce for counting circle property for vote, majority election and proportional election

### 🔄 Changed

- Allow to edit the political business number of a secondary majority election after the testing phase has ended

### 🆕 Added

- Events to notify political businesses and political business unions about a contest merge

### 🆕 Added

- add domain of influence external printing center eai message type

### 🆕 Added

- added voting documents e-voting message type to canton settings

## [v1.70.0] - 2023-05-01

### 🔄 Changed

- electoral registration on canton settings

## [v1.69.4] - 2023-04-25

### 🆕 Added

- Added domain of influence sap customer order number

## [v1.69.3] - 2023-01-17

### 🔄 Changed

- election candidate locality and origin is allowed to be empty

## [v1.69.2] - 2023-01-04

### 🔄 Changed

- revert removing fields from event data

## [v1.69.1] - 2023-01-03

### ❌ Removed

- remove internal description, invalid votes and individual empty ballots allowed from elections

## [v1.69.0] - 2022-12-21

### 🔄 Changed

- add export provider

## [v1.68.1] - 2022-12-16

### 🆕 Added

- add domain of influence canton

## [v1.68.0] - 2022-12-02

### 🔄 Changed

- add origin for election candidates

## [v1.67.0] - 2022-11-28

### 🎉 Initial release for Bug Bounty
