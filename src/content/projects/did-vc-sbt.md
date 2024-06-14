---
title: "DID/VC SBT プロジェクト"
meta_title: ""
lang: "ja"
description: "DID や VC などの相互運用性を向上する"
date: 2022-04-04T05:00:00Z
image: ""
author: "Hal Seki"
draft: false
---

## Purpose

- 国に依存しない相互運用性を可能にしたVerfiable Credentialのモデル実装
- 各国政府等が参照可能なOSSの提供

## Roadmap

- 秘密分散ウォレット: 完了
- DAOメンバーに対してVerifiable Credentialの配布: 完了
- 具体的な外部プロジェクトへの適応: 検討中

## Sub Project

### 秘密分散Discordウォレット開発

今後Dig DAOとしてリリースするスマートコントラクトのオーナーウォレットや将来的にはトレジャリー管理のための、「DAOで」所有するウォレットとして、Gnosis Safeなどのマルチシグウォレットを使用するのではなく、セルフカストディな形で秘密鍵を保持しつつ、その管理を分散化させて、DAOとしてよく使用するツールの中で使える仕組みを作る。

### Open Credential Verifier: Verifiable Credentials の相互運用性を高める

![Open Credential Verifier 概要](/images/open-verifier-image.jpg)

- Issuerが発行する証明書の相互運用性の確立のための検証ページの公開
- [https://verifier.digdao.jp/](https://verifier.digdao.jp/)
