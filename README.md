# Timestamp Microservice freeCodeCamp

Full stack JavaScript service that checks whether a string contains either a unix timestamp or a natural language date. A [FreeCodeCamp](https://www.freecodecamp.org/challenges/timestamp-microservice) project.

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

### Installing

```
git clone https://github.com/kelvinabella/timestamp-microservice.git
cd timestamp-microservice
yarn install
yarn start
```

```
User Stories:
1) I can pass a string as a parameter, and it will check to see whether that string contains either a unix timestamp or a natural language date (example: January 1, 2016)
2) If it does, it returns both the Unix timestamp and the natural language form of that date.
3) If it does not contain a date or Unix timestamp, it returns null for those properties.
```

```
Usage:
https://localhost/December%2015,%202015
https://localhost/1450137600

Example output:
{ "unix": 1450137600, "natural": "December 15, 2015" }
```

## License

This project is licensed under the MIT License.

## Acknowledgments

*FreeCodeCamp
