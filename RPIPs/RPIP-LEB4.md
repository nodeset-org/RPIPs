---
rpip: Unassigned
title: LEB4s
description: Provide the option for 4 ETH bonded minipools using a similar framework as LEB8s from RPIP-8
author: Mike Leach (GH: VVander | Discord: wander1), Nick Steinhilber (Discord: nicks11)
discussions-to: TBD
status: Draft
type: Protocol
category: Core
created: 2024-03-21
---

# LEB4s

## Notice
This proposal is mutually exclusive and should be not be confused with the sub-linear bonding proposal in [RPIP-48](RPIP-48.md).

## Abstract

We propose the introduction of LEB4s as a 

## Specification

An LEB4 is defined as a validator created under a megapool with 4 ETH REQUIRED to be supplied by the node operator

The proposed specification for LEB4s is nearly identical to the LEB8 proposal outlined in [RPIP-8](https://github.com/nodeset-org/RPIPs/blob/main/RPIPs/RPIP-8.md), with the following exceptions:

- A minimum bond of 1.6 ETH worth of RPL staked in the node at the time of creation for each LEB4 is REQUIRED
