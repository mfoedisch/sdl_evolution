
# SDL out of the container

* Proposal: [SDL-NNNN](NNNN-out-of-container.md)
* Author: Mike Foedisch
* Status: **Awaiting review**
* Impacted Platforms: [Core / iOS / Android / Web / RPC / Protocol]

## Introduction

We'd like to propose to "get SDL out of the container" and take the integration with the host IVI system even further. 

## Motivation

One important difference between a CarPlay-like approach and SDL lies in SDL's ability to actually integrate with the host IVI system. Instead of just providing access to the full screen or a part of it, SDL is an integrated part of the IVI's feature set.

Currently, however, "apps" are still the main entry point to functionality, meaning the user first has to select the app from the apps list and then trigger a function from within the "app's area" within the HMI. 

We'd like to propose to "get SDL out of the container" and integrate with the host IVI system even further. This could be considered a paradigm shift from an "apps-based approach" to a "function-based approach".

It should be possible to attach an apps' functionality to appropriate areas within the HMI, for example:

1)	a weather app could show its data (temperature and weather condition) in a standard "weather widget" without the user having to trigger the app. Wherever the widget is placed, the content would be visible.
2)	common functionality of certain apps could be tied to central HMI elements, e.g. a "Help" button tied to a function of an "Owners' app" could be placed somewhere centrally in the HMI.


## Proposed solution



## Potential downsides

There is a risk of increasing overall complexity.

## Impact on existing code

It should be possible to just add the new feature without altering exisiting ones. Headunits and apps that don't use the new approach should not be impacted by it.

## Alternatives considered

Describe alternative approaches to addressing the same problem, and why you chose this approach instead.

    Contact GitHub API Training Shop Blog About 

    © 2017 GitHub, Inc. Terms Privacy Security Status Help 

