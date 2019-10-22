# app-correios

[![CodeFactor](https://www.codefactor.io/repository/github/ecomclub/app-correios/badge)](https://www.codefactor.io/repository/github/ecomclub/app-correios)
[![license mit](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

E-Com Plus app to integrate Correios calculator

[Changelog](https://github.com/ecomclub/app-correios/blob/master/CHANGELOG.md)

## Reference

### About "Correios offline"

1. https://github.com/victorhramos/correios-offline-opencart/blob/master/src/KauserCorreios/Correios.php
2. https://suporte.boxloja.pro/article/82-correios-calculo-frete

## Environment variables sample

Variable              | Value
---                   | ---
`LOGGER_OUTPUT`       | `~/app/log/logger.out`
`LOGGER_ERRORS`       | `~/app/log/logger.err`
`LOGGER_FATAL_ERRORS` | `~/app/log/_stderr`
`PORT`                | `3000`
`APP_BASE_URI`        | `https://correios.ecomplus.biz`
`DB_PATH`             | `~/app/db.sqlite`
`ECOM_AUTH_DB`        | `~/app/db.sqlite`
`ECOM_AUTH_UPDATE`    | `enabled`

## Production server

Published at https://correios.ecomplus.biz

### Continuous deployment

When new version is **production ready**,
[create a new release](https://github.com/ecomclub/app-correios/releases)
(or `npm run release`) to run automatic deploy from _master_ branch
and (re)publish the app.
