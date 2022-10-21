# fakedata
A library to generate fake data for testing with focus on customization

[![CircleCI](https://dl.circleci.com/status-badge/img/gh/fakedata-js/fakedata/tree/main.svg?style=svg)](https://dl.circleci.com/status-badge/redirect/gh/fakedata-js/fakedata/tree/main)


## Types of data
### Basic
- Boolean
- Integer
  - Range (default: [-10000000, 10000000])
- Floating point number
- Character
- String
  - Length (default undefined)
  - Range (default [2, 10])
  - Character set
    - Lower alpha (default true)
    - Uppaer alpha (default true)
    - Digits (default true)
    - Special chars  (default false)
    - Punctuation  (default false)
  - Hex
    - uppercase (default false)
- Array
  - Length (required)
  - Generator (required)
    - Existing types
    - Custom generators
- Object
  - Custom and existing generators
  - Nesting
  - Constant values
### Date
- Date
- Day
- Month
- Year
- Weekday
- Today
- Tomorrow
- Yesterday
- Between
- Future
- Past
- Month and leap year
### Time
- Current
- Hour
- Minute
- Second
- Millisecond
- Between
- Future
- Past
- 12 vs 24 hr format
### Person
- Name
- First name
- Middle name
- Last name
- Title
- Gender
- DOB
### Internet and communication
- Mobile number
- Landline number
- Country code
- STD code
- Email
- IPv4
- IPv6
- Domain
- Domain name
- port
### Location
- Address
- Building no.
- Floor no.
- Street
- Block
- City
- State and state code
- Country and country code
- ZIP code
### Currency
- INR
- US Dollar
## Customization
- Character set
- Locale
## Choice
