# swift-wiki2ics

## Ideation

A service, that takes a Wikipedia-Page with a table (e.g. [Upcoming Falcon 9 and Falcon Heavy Launches](https://en.wikipedia.org/wiki/List_of_Falcon_9_and_Falcon_Heavy_launches#2019)) and makes an ics-Feed available.

### Steps
- [ ] read Wikipedia page by name or url
- [ ] parse tables
- [ ] detect date/string/number columns
- [ ] let user pick (compatible) table to use and which columns to include in output
- [ ] generate ics-feed from table

## Possible Components
- HTML Parsing: https://github.com/tid-kijyun/Kanna
- ICS-Feed: Use https://github.com/kiliankoe/iCalKit
