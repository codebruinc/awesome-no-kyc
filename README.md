# Awesome No-KYC [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

[![GitHub stars](https://img.shields.io/github/stars/codebruinc/awesome-no-kyc?style=social)](https://github.com/codebruinc/awesome-no-kyc/stargazers)
[![GitHub forks](https://img.shields.io/github/forks/codebruinc/awesome-no-kyc?style=social)](https://github.com/codebruinc/awesome-no-kyc/network/members)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](https://github.com/codebruinc/awesome-no-kyc/pulls)
[![License: CC0](https://img.shields.io/badge/License-CC0-lightgrey.svg)](https://creativecommons.org/publicdomain/zero/1.0/)
[![Last Commit](https://img.shields.io/github/last-commit/codebruinc/awesome-no-kyc)](https://github.com/codebruinc/awesome-no-kyc/commits/main)

> A curated list of services that respect your privacy by not requiring identity verification, account creation, or personal data collection.

**Know Your Customer (KYC)** regulations require businesses to verify customer identities. While intended for anti-money laundering, KYC creates privacy risks: data breaches, identity theft, surveillance, and exclusion of the unbanked. This list catalogs services that operate without requiring personal information.

## Contents

- [What Makes a Service "No-KYC"?](#what-makes-a-service-no-kyc)
- [Financial Services](#financial-services)
  - [Exchanges & Swaps](#exchanges--swaps)
  - [Wallets](#wallets)
  - [Debit Cards](#debit-cards)
  - [Payment Processing](#payment-processing)
- [Communication](#communication)
  - [Email](#email)
  - [Messaging](#messaging)
  - [Phone & SMS](#phone--sms)
  - [eSIM & Mobile Data](#esim--mobile-data)
- [VPN & Privacy Tools](#vpn--privacy-tools)
- [Domain & Hosting](#domain--hosting)
- [Cloud Storage](#cloud-storage)
- [Shopping](#shopping)
- [Travel](#travel)
- [Development Tools](#development-tools)
- [Contributing](#contributing)

---

## What Makes a Service "No-KYC"?

Services on this list meet most or all of these criteria:

| Criteria | Description |
|----------|-------------|
| **No ID Upload** | No government ID, passport, or driver's license required |
| **No Account Required** | Can use the service without creating an account, or account is optional |
| **No Email Required** | No email needed, or accepts disposable emails |
| **No Phone Verification** | No SMS verification or phone number required |
| **Crypto Accepted** | Accepts Bitcoin, Monero, or other cryptocurrencies |
| **Minimal Data Collection** | Collects only what's technically necessary |

> **Legend:**
> - ⭐ = Exceptional privacy (meets all criteria)
> - 🧅 = Tor/.onion available
> - ⚡ = Accepts Lightning Network
> - 🟠 = Accepts Bitcoin
> - ⬛ = Accepts Monero

---

## Financial Services

### Exchanges & Swaps

Peer-to-peer and decentralized exchanges that don't require identity verification.

| Service | Description | Payment Methods |
|---------|-------------|-----------------|
| [Bisq](https://bisq.network/) | Decentralized P2P exchange. No registration. Desktop app required. | 🟠 BTC, Cash, Bank transfer |
| [Robosats](https://robosats.com/) 🧅 | Lightning-based P2P exchange over Tor. No account needed. | ⚡ Lightning |
| [Hodl Hodl](https://hodlhodl.com/) | P2P Bitcoin trading with multisig escrow. Email-only registration. | 🟠 BTC |
| [Peach Bitcoin](https://peachbitcoin.com/) | Mobile P2P Bitcoin exchange. No ID required for small amounts. | 🟠 BTC |
| [AgoraDesk](https://agoradesk.com/) 🧅 | P2P exchange for BTC and XMR. Tor available. | 🟠 ⬛ BTC, XMR |
| [LocalMonero](https://localmonero.co/) 🧅 | P2P Monero exchange. No ID required. Tor available. | ⬛ XMR |
| [eXch](https://exch.cx/) 🧅 | No-account instant exchange. Tor available. | 🟠 ⬛ Multiple |
| [Trocador](https://trocador.app/) 🧅 | Exchange aggregator with no logs. Tor available. | 🟠 ⬛ Multiple |
| [TradeOgre](https://tradeogre.com/) | Simple exchange with email-only registration. No KYC. | 🟠 ⬛ Multiple |
| [Majestic Bank](https://majesticbank.sc/) 🧅 | No-account instant swaps. Tor available. | 🟠 ⬛ Multiple |
| [FixedFloat](https://fixedfloat.com/) | Instant exchange with no registration for small amounts. | 🟠 ⚡ Multiple |
| [SideShift.ai](https://sideshift.ai/) | No-account instant swaps. | 🟠 ⬛ Multiple |
| [Haveno](https://haveno.exchange/) | Decentralized Monero DEX (Bisq fork). Desktop app. | ⬛ XMR |

### Wallets

Self-custody wallets that don't require personal information.

| Wallet | Platform | Description |
|--------|----------|-------------|
| [Sparrow Wallet](https://sparrowwallet.com/) | Desktop | Full-featured Bitcoin wallet with excellent privacy features |
| [Samourai Wallet](https://samouraiwallet.com/) | Android | Privacy-focused Bitcoin wallet with Whirlpool mixing |
| [BlueWallet](https://bluewallet.io/) | Mobile | Bitcoin & Lightning wallet. No account required. |
| [Electrum](https://electrum.org/) | Desktop/Mobile | Lightweight Bitcoin wallet. Tor support. |
| [Wasabi Wallet](https://wasabiwallet.io/) | Desktop | Bitcoin wallet with built-in CoinJoin |
| [Cake Wallet](https://cakewallet.com/) | Mobile | Multi-coin wallet (XMR, BTC, LTC). No account. |
| [Feather Wallet](https://featherwallet.org/) | Desktop | Lightweight Monero wallet |
| [Monero GUI](https://getmonero.org/downloads/) | Desktop | Official Monero wallet |
| [Phoenix](https://phoenix.acinq.co/) | Mobile | Self-custodial Lightning wallet |
| [Muun](https://muun.com/) | Mobile | Bitcoin & Lightning wallet. Non-custodial. |
| [Zeus](https://zeusln.com/) | Mobile | Lightning node management & wallet |
| [Envoy](https://foundation.xyz/envoy/) | Mobile | Bitcoin wallet by Foundation Devices |

### Debit Cards

Crypto-funded cards with minimal or no KYC (limits may apply).

| Service | Description | KYC Threshold |
|---------|-------------|---------------|
| [Paywithmoon](https://paywithmoon.com/) | Virtual Visa cards funded with Bitcoin/Lightning | No KYC for virtual cards |
| [The Bitcoin Company](https://thebitcoincompany.com/) | Lightning-funded gift cards and virtual Visa | No KYC for gift cards |
| [CoinCards](https://coincards.com/) ⭐ | Buy gift cards with Bitcoin, Lightning, Monero. No account. | No KYC |

### Payment Processing

Accept crypto payments without KYC requirements for merchants.

| Service | Description | Coins Supported |
|---------|-------------|-----------------|
| [BTCPay Server](https://btcpayserver.org/) ⭐ | Self-hosted payment processor. Full control. | 🟠 ⚡ ⬛ BTC, Lightning, XMR, more |
| [LNbits](https://lnbits.com/) | Lightning payment tools. Self-hostable. | ⚡ Lightning |
| [SatSale](https://github.com/SatSale/SatSale) | Self-hosted payment processor | 🟠 ⚡ BTC, Lightning |

---

## Communication

### Email

Email services that don't require personal information to sign up.

| Service | Description | Registration |
|---------|-------------|--------------|
| [ProtonMail](https://proton.me/mail) | Encrypted email. May require verification. | Email or phone (sometimes) |
| [Tutanota](https://tutanota.com/) | Encrypted email from Germany. | No verification for basic |
| [Guerrilla Mail](https://guerrillamail.com/) ⭐ | Disposable email addresses. | No registration |
| [SimpleLogin](https://simplelogin.io/) | Email aliasing service. Can use crypto. | Email only |
| [AnonAddy](https://anonaddy.com/) | Email aliasing. Open source. | Email only |
| [Disroot](https://disroot.org/) | Privacy email & cloud. | Minimal info |
| [RiseUp](https://riseup.net/) | Activist email & VPN. Invite or request. | Invite system |
| [Cock.li](https://cock.li/) 🧅 | Anonymous email. Tor available. | No verification |
| [DNMX](https://dnmx.su/) 🧅 | Anonymous email on Tor. | No verification |

### Messaging

Private messaging without phone numbers or real identity.

| Service | Description | Registration |
|---------|-------------|--------------|
| [Signal](https://signal.org/) | End-to-end encrypted messaging. | Phone number required |
| [Session](https://getsession.org/) ⭐ | Decentralized messenger. No phone number. | No personal info |
| [Briar](https://briarproject.org/) ⭐ | P2P messenger over Tor. No server. | No personal info |
| [SimpleX](https://simplex.chat/) ⭐ | No user IDs. Maximum privacy. | No personal info |
| [Matrix/Element](https://element.io/) | Decentralized chat. Some servers no-KYC. | Varies by server |
| [XMPP/Jabber](https://xmpp.org/) | Federated messaging. Some servers anonymous. | Varies by server |
| [Jami](https://jami.net/) ⭐ | P2P calls and messaging. No central server. | No registration |
| [Tox](https://tox.chat/) ⭐ | P2P messaging. No servers. | No registration |

### Phone & SMS

Virtual phone numbers and SMS services without identity verification.

| Service | Description | Payment Methods |
|---------|-------------|-----------------|
| [Silent.Link](https://silent.link/) ⭐ | Anonymous eSIM with SMS capability. | 🟠 ⬛ BTC, XMR |
| [JMP.chat](https://jmp.chat/) | Phone number via XMPP/SIP. | 🟠 BTC, Credit card |
| [Crypton.sh](https://crypton.sh/) | Cloud SIM for SMS. Encrypted. | 🟠 ⬛ BTC, XMR, Card |
| [SMSPool](https://smspool.net/) | One-time SMS verification numbers. | 🟠 Crypto, Card |
| [TextVerified](https://textverified.com/) | SMS verification service. | 🟠 Crypto, Card |
| [MoneroSMS](https://monerosms.com/) ⭐ | SMS service, Monero payments. | ⬛ XMR |

### eSIM & Mobile Data

Mobile data and eSIMs without account requirements or identity verification.

| Service | Description | Payment Methods |
|---------|-------------|-----------------|
| [PikaSim](https://pikasim.com/) ⭐ | Privacy eSIM for 170+ countries. No account, no ID, no email with crypto. | 🟠 ⚡ ⬛ BTC, Lightning, XMR |
| [Silent.Link](https://silent.link/) ⭐ | Anonymous eSIM with data, SMS, and calls. | 🟠 ⬛ BTC, XMR |
| [ESIM.me](https://esim.me/) | Physical eSIM card. Can pay with crypto. | 🟠 BTC via BTCPay |

---

## VPN & Privacy Tools

VPN services and privacy tools that don't require personal information.

| Service | Description | Payment Methods |
|---------|-------------|-----------------|
| [Mullvad VPN](https://mullvad.net/) ⭐ | No email. Account is a random number. | 🟠 ⬛ BTC, XMR, Cash |
| [IVPN](https://ivpn.net/) ⭐ | No email required. Privacy-focused. | 🟠 ⬛ BTC, XMR, Cash |
| [ProtonVPN](https://protonvpn.com/) | Free tier available. Part of Proton suite. | 🟠 BTC |
| [AirVPN](https://airvpn.org/) | Accepts crypto. Tor-friendly. | 🟠 ⬛ BTC, XMR |
| [Cryptostorm](https://cryptostorm.is/) | Token-based VPN. Anonymous. | 🟠 BTC |
| [OVPN](https://ovpn.com/) | No-logs VPN. Crypto accepted. | 🟠 BTC |
| [1984 Hosting](https://1984.hosting/) | Iceland-based. Privacy focused. | 🟠 BTC |
| [Njalla VPN](https://njal.la/) | From the Pirate Bay founder. | 🟠 ⬛ BTC, XMR |
| [Tor](https://torproject.org/) ⭐ | Free anonymity network. | Free |
| [I2P](https://geti2p.net/) ⭐ | Anonymous network layer. | Free |
| [Lokinet](https://lokinet.org/) ⭐ | Decentralized onion routing. | Free |

---

## Domain & Hosting

Domain registration and web hosting without identity verification.

| Service | Description | Payment Methods |
|---------|-------------|-----------------|
| [Njalla](https://njal.la/) ⭐ | Privacy domain registration. They're the owner. | 🟠 ⬛ BTC, XMR |
| [1984 Hosting](https://1984.hosting/) | Iceland hosting. Privacy-focused. | 🟠 BTC |
| [OrangeWebsite](https://orangewebsite.com/) | Iceland hosting. Crypto accepted. | 🟠 BTC |
| [FlokiNET](https://flokinet.is/) | Privacy hosting. Multiple locations. | 🟠 ⬛ BTC, XMR |
| [Hostinger](https://hostinger.com/) | Mainstream host accepting crypto. | 🟠 BTC |
| [Namecheap](https://namecheap.com/) | Domains with Bitcoin payment option. | 🟠 BTC |
| [Bitlaunch](https://bitlaunch.io/) | VPS with instant crypto payment. | 🟠 ⚡ BTC, Lightning |
| [Servers Guru](https://servers.guru/) | VPS accepting Monero. | ⬛ XMR |

---

## Cloud Storage

Encrypted cloud storage without requiring personal information.

| Service | Description | Payment Methods |
|---------|-------------|-----------------|
| [Filen](https://filen.io/) | Zero-knowledge encrypted storage. | 🟠 BTC, Card |
| [Tresorit](https://tresorit.com/) | End-to-end encrypted storage. | 🟠 BTC |
| [Nextcloud](https://nextcloud.com/) ⭐ | Self-hosted cloud. Full control. | Self-hosted |
| [MEGA](https://mega.io/) | Encrypted cloud with free tier. | Card, some crypto resellers |
| [Proton Drive](https://proton.me/drive) | Part of Proton suite. Encrypted. | 🟠 BTC |
| [Cryptee](https://crypt.ee/) | Encrypted docs and photos. | 🟠 BTC |
| [Internxt](https://internxt.com/) | Decentralized cloud storage. | 🟠 BTC |

---

## Shopping

Ways to shop online while preserving privacy.

| Service | Description | Payment Methods |
|---------|-------------|-----------------|
| [CoinCards](https://coincards.com/) ⭐ | Buy gift cards with crypto. No account. | 🟠 ⚡ ⬛ BTC, Lightning, XMR |
| [Bitrefill](https://bitrefill.com/) | Gift cards and mobile top-ups. | 🟠 ⚡ BTC, Lightning |
| [The Bitcoin Company](https://thebitcoincompany.com/) | Gift cards via Lightning. | ⚡ Lightning |
| [Purse.io](https://purse.io/) | Amazon shopping with Bitcoin discount. | 🟠 BTC |
| [ShopInBit](https://shopinbit.com/) | EU shopping with crypto. | 🟠 ⬛ BTC, XMR |
| [Travala](https://travala.com/) | Travel booking with crypto. | 🟠 Multiple |

---

## Travel

Travel services that accept cryptocurrency or don't require full KYC.

| Service | Description | Payment Methods |
|---------|-------------|-----------------|
| [PikaSim](https://pikasim.com/) ⭐ | Privacy eSIM for travel. 170+ countries. | 🟠 ⚡ ⬛ BTC, Lightning, XMR |
| [Travala](https://travala.com/) | Hotels and flights with crypto. | 🟠 Multiple |
| [Bitcoin Holidays](https://bitcoin-holidays.com/) | Vacation rentals with Bitcoin. | 🟠 BTC |
| [CheapAir](https://cheapair.com/) | Flights with Bitcoin. | 🟠 BTC |
| [LockTrip](https://locktrip.com/) | Hotels with crypto. | 🟠 Multiple |

---

## Development Tools

Developer services that respect privacy.

| Service | Description | Payment Methods |
|---------|-------------|-----------------|
| [Codeberg](https://codeberg.org/) ⭐ | Git hosting. No tracking. EU-based. | Free / Donation |
| [Sourcehut](https://sr.ht/) | Minimal git hosting. | Crypto option |
| [Bitlaunch](https://bitlaunch.io/) | VPS for developers. Instant setup. | 🟠 ⚡ BTC, Lightning |
| [1984 Hosting](https://1984.hosting/) | Developer-friendly. Iceland. | 🟠 BTC |

---

## Contributing

Contributions welcome! Please read the [contribution guidelines](CONTRIBUTING.md) first.

### Criteria for Inclusion

To be listed, a service should:

1. **Not require government ID** for basic use
2. **Accept cryptocurrency** or cash payment
3. **Minimize data collection** - only what's necessary
4. **Have a reasonable reputation** - no known scams
5. **Be currently operational** - no dead projects

### How to Contribute

1. Fork this repository
2. Add your suggestion to the appropriate category
3. Follow the existing format
4. Submit a pull request

---

## Disclaimer

This list is for educational purposes. Services change their policies. Always verify current requirements before use. The maintainers don't endorse illegal activity. Know and follow the laws in your jurisdiction.

---

## License

[![CC0](https://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, the contributors have waived all copyright and related rights to this work.

Maintained by [CodeBru](https://codebru.com)
