# Awesome Galoy ⚡ [![Awesome](https://awesome.re/badge-flat.svg)](https://awesome.re)

A curated list of the [**galoy**](https://galoy.io/) set of apps & services that can be combined to offer Bitcoin-based community banking.

The **galoy** system allows someone to setup a system of bitcoin on-chain and lightning network wallets and an internal account system to support offering bitcoin-based accounts to end users.

With a **galoy**-based account, users are able to:
- [x] send/receive bitcoin on-chain
- [x] send/receive bitcoin over the Lightning Network
- [x] send/receive bitcoin to other Galoy instance users at little to no cost
- [x] track Bitcoin price activity
- [x] find merchants to spend with on a local area map

![Image of community banking](images/home-image-03.jpg)


## Tech components

A collection of the various tools and repos available for setting up your own bitcoin community-based bank.

### Backend

A collection of repos that can be used to deploy the backend components required to support a bitcoin community bank.

- [**`galoy`**](https://github.com/GaloyMoney/galoy)


  The backend application that interacts with the bitcoin and accounting layers to enable sending, receiving and holding balances.

- [**`galoy-infra`**](https://github.com/GaloyMoney/galoy-infra)

  ...

- [**`charts`**](https://github.com/GaloyMoney/charts)

  ...

- [**`price`**](https://github.com/GaloyMoney/price)

  ...

- [**`dealer`**](https://github.com/GaloyMoney/dealer)

  ...

### API
- [**`galoy`**](https://github.com/GaloyMoney/galoy)

  A GraphQL API that exposes the internal functions 
  of the galoy application.

- [**`api-docs`**](https://github.com/GaloyMoney/api-docs)

  Documentation for the galoy GraphQL API

### Frontend
- [**`galoy-tips`**](https://github.com/GaloyMoney/galoy-tips)

  A single page for each user of a galoy instance, that consumes the instance's GraphQL Api to present a QR code users can share for receiving payments via the Lightning Network. 

- [**`admin-panel`**](https://github.com/GaloyMoney/admin-panel)

  A dashboard that can be used to do various administrative functions by the admins of a given galoy instance.

- [**`galoy-mobile`**](https://github.com/GaloyMoney/galoy-mobile)

  A mobile app to be used as a wallet by end-user, that consumes the GraphQL Api of a given galoy instance.


## Galoy in the wild

_Examples of deployed galoy instances._

### 🏄 Bitcoin Beach Wallet Project

A community project deployed in the surfing village of El Zonte in El Salvador.

#### Mobile app
...

#### Tips pages
...
