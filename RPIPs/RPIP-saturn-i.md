---
rpip: Unassigned
title: KISS Saturn Upgrades
description: Use existing parameters and well-researched mechanics to make simple, safe changes for efficiency
author: Mike Leach (GH: VVander | Discord: wander1), Nick Steinhilber (Discord: nicks11)
discussions-to: TBD
status: Draft
type: Informational
created: 2024-03-21
---

# KISS Saturn Upgrades

## Motivation

The recent slide in the RPL/ETH ratio has caused pain across the entire Rocket Pool (RP) community. In response, the pDAO has reawakened tokenomics discussions with the goals of improving efficiency and attractiveness of RP, with seemingly anything on the table. The quantity of ideation is impressive, but there are significant and serious risks associated with full tokenomics transformations, and we believe there are better paths available to pursue the same objectives.

## Abstract

We propose using existing protocol parameters alongside well-understood ideas to upgrade the protocol as follows:

1. Megapools[[1](RPIP-43.md),[2](https://github.com/rocket-pool/rocketpool-research/blob/ef5b5627f02a2307e11915236f98b130ef779cf1/Megapools/megapools.md)]
2. A flat application of LEB4 minipools
3. On-chain exits for offline validators
4. Introduction of reduced commission for undercollateralized nodes

Together, the proposed changes make up a "Saturn I" protocol upgrade, with future potential changes in "Saturn II" and "Saturn III" suggested, although the specifications for these are left for future documents.

## Specification

### Megapools

The proposed specification for Megapools is defined in [RPIP-43](RPIP-43.md). In addition, we recommend adjusting this specification to include consideration of [EIP-7251](https://github.com/ethereum/EIPs/blob/master/EIPS/eip-7251.md).

The proposed specification for LEB4s is defined in [RPIP-LEB4](RPIP-LEB4.md). This specification is mutually exclusive and should not be confused with that of [RPIP-48](RPIP-48.md).

The specification for our proposed implementation of contract-enforced validator exits is defined in [RPIP-forced-exits](RPIP-forced-exits.md).

The specification for our proposed LEB4 implementation is defined in [RPIP-LEB4](RPIP-undercollateralized-rewards.md).

## Rationale

### Megapools

Megapools are well-understood and represent an uncontested and obvious method for improving gas efficiency for node operators.

### LEB4s

### Forced Exits for Underperforming Validators

### RPL Rewards for Undercollateralized Nodes

Rocket Pool currently incentivizes node operators to perform well by applying the penalty

## Risk Analysis

### Dependency Upon Etheruem Updates

Two components of the suggested features are dependent upon upgrades to Ethereum. Specifically,

### Technical Risks

As always, when editing existing contracts which are live on mainnet, there is a significant technical risk of exploitation, bugs, or other unintentional errors in execution. We recommend the community continue to maintain high standards by engaging multiple third-party auditors before effectuating these changes. However, the changes presented here are well-studied and minimal, especially compared to competing proposals such as [RPIPs 42 through 48 -- SPECIFY MORE].

## Suggested Development Roadmap

### Saturn I

### Saturn II

### Saturn III
