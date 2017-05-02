
# SDL out of the container

* Proposal: [SDL-NNNN](NNNN-out-of-container.md)
* Author: Mike Foedisch
* Status: **Awaiting review**
* Impacted Platforms: [Core / iOS / Android / Web / RPC / Protocol]

## Introduction

We'd like to propose to "get SDL out of the container" and take the integration with the host IVI system even further. 

## Motivation

Describe the problems that this proposal seeks to address. If the problem is that some common pattern is currently hard to express, show how one can currently get a similar effect and describe its drawbacks. If it's completely new functionality that cannot be emulated, motivate why this new functionality would help SDL mobile developers or OEMs provide users with useful functionality.

## Proposed solution


One important difference between a CarPlay-like approach and SDL lies in SDL's ability to actually integrate with the host IVI system. Instead of just providing access to the full screen or a part of it, SDL is an integrated part of the IVI's feature set.

Currently, however, "apps" are still the main entry point to functionality, meaning the user first has to select the app from the apps list and then trigger a function from within the "app's area" within the HMI. 

We'd like to propose to "get SDL out of the container" and integrate with the host IVI system even further. This could be considered a paradigm shift from an "apps-based approach" to a "function-based approach".

## Potential downsides

Describe any potential downsides or known objections to the course of action presented in this proposal, then provide counter-arguments to these objections. You should anticipate possible objections that may come up in review and provide an initial response here. Explain why the positives of the proposal outweigh the downsides, or why the downside under discussion is not a large enough issue to prevent the proposal from being accepted.

## Impact on existing code

Describe the impact that this change will have on existing code. Will some SDL integrations stop compiling due to this change? Will applications still compile but produce different behavior than they used to? Is it possible to migrate existing SDL code to use a new feature or API automatically?

## Alternatives considered

Describe alternative approaches to addressing the same problem, and why you chose this approach instead.

    Contact GitHub API Training Shop Blog About 

    © 2017 GitHub, Inc. Terms Privacy Security Status Help 

