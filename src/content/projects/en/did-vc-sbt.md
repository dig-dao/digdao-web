---
title: "DID/VC SBT Project"
meta_title: ""
lang: "en"
description: "Improve interoperability of DIDs, VCs, etc."
date: 2024-06-09T05:00:00Z
image: ""
author: "Takeru Nakao"
draft: false
---

## Purpose

- Implementation model of Verifiable Credential enabling interoperability independent of countries
- Provision of OSS (Open Source Software) that can be referred to by various governments

## Roadmap

- Secret Sharing Wallet: Completed
- Distribution of Verifiable Credentials to DAO members: Completed
- Application to specific external projects: Under consideration

## Sub Project

### Secret Sharing Discord Wallet Development

As an owner wallet for smart contracts to be released by Dig DAO in the future, and eventually as a wallet owned by the DAO for treasury management, instead of using multisig wallets like Gnosis Safe, we aim to create a system where the private keys are held in a self-custodial manner, while decentralizing the management, and making it usable within commonly used tools in the DAO.

### Open Credential Verifier: Verifiable Credentials の相互運用性を高める

![Open Credential Verifier 概要](/images/open-verifier-image.jpg)

- Publication of a verification page to establish the interoperability of certificates issued by issuers
- [https://verifier.digdao.jp/](https://verifier.digdao.jp/)
