# RFCs

## Submit RFC

- Copy `0000-template` as `rfcs/0000-feature-name`, where `feature-name` is the descriptive name of the RFC. Don't assign an number yet.

Nervos RFCs should follow the keyword conventions defined in [RFC 2119](https://tools.ietf.org/html/rfc2119), [RFC 6919](https://tools.ietf.org/html/rfc6919).

## Gitbook

Complex RFC can use Gitbook.

Install gitbook cli tool:

    npm install gitbook-cli -g

Build in RFC directory:

    gitbook build

Edit and preview locally:

    gitbook serve