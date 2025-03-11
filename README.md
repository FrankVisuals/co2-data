# Co2 Data

This repository contains example data that can be requested via an API call.

## Footprints

[https://frankvisuals.github.io/co2-data/footprints.json](https://frankvisuals.github.io/co2-data/footprints.json)

With response Type

```ts
Array<{
  identifier: string;
  country: string;
  description: string;
  footprint_value: number;
  footprint_unit: string;
}>
```

## Transport

[https://frankvisuals.github.io/co2-data/transport.json](https://frankvisuals.github.io/co2-data/transport.json)

With response Type

```ts
Array<{
  identifier: string;
  factor: number;
  origin_country: string;
}>
```