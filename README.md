# Programming Quotes API

**Programming Quotes REST API for open source projects.**

https://baza-podataka.herokuapp.com

See client app: [Programming Quotes React app](https://github.com/skolakoda/programming-quotes).

## API endpoints

GET `/quotes`

POST `/quotes`
- required: `token`, `author` and one language (`en` or `sr`)
- optional: `source` and other language

PUT `/quotes`
- required: `token`, `_id`,`author` and one language (`en` or `sr`)

DELETE: `/quotes`
- required: `token` and `_id`

## Development

### Prerequisites

- Intall Node.js
- Set [environment variables](https://github.com/skolakoda/baza-podataka/wiki/Environment-variables)

### Start

```
npm i
npm run dev
```

### Deploy

Deploy will be done automatically after merge into master branch.

### TODO

- add /random endpoint
- add pagination
- add voting
