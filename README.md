# ReBirth

A blockchain explorer to cita.

## build status

  - develop branch 
    [![Build Status](https://travis-ci.org/cryptape/ReBirth.svg?branch=develop)](https://travis-ci.org/cryptape/ReBirth)
    
## Code Coverage
  [![codecov](https://codecov.io/gh/classicalliu/cita-scan/branch/develop/graph/badge.svg)](https://codecov.io/gh/classicalliu/cita-scan)

## packages

  - postgresql 9.4 and above
    
## Initial Project

```shell
rails db:create db:migrate

or just

rails db:setup
```

## Running test
```shell
rails spec
```

## Run Project
```shell
rails s

# start sync process
rails daemons:sync:start 
# run `rails daemons:sync:stop` to stop it
# run `rails daemons:sync:restart` to restart it
# run `rails daemons:sync:status` to see status
```

## Build Doc

```shell
bundle exec yard doc
bundle exec yard server
```
