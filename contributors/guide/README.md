---
title: "Getting Started"
weight: 1
aliases: [ "/guide" ]
description:
  A small list of things that you should read and be familiar with before you
  get started with contributing. This includes such things as signing the
  Contributor License Agreement, familiarizing yourself with our Code of Conduct,
  and more.
---

# Welcome

Have you ever wanted to contribute to the coolest cloud technology?
This guide will help you understand the overall organization of the Kubernetes project, and direct you to the best places to get started contributing.
You'll be able to pick up issues, write code to fix them, and get your work reviewed and merged.

This document is the single source of truth for how to contribute to the code base.
Feel free to browse the [open issues](https://github.com/kubernetes/community/issues?q=is%3Aissue+is%3Aopen+label%3Aarea%2Fcontributor-guide) 
and file new ones, all feedback is welcome!

## Contributor Guide

Welcome to Kubernetes! This guide is broken up into the following sections. 
It is recommended that you follow these steps in order: 

- [Welcome](#welcome) - this page 
- [Prerequisites](#prerequisites) - tasks you need to complete before you can start contributing to Kubernetes
- [Your First Contribution](first-contribution.md) - things you'll need to know before making your first contribution
- [Contributing](contributing.md) - the main reference guide to contributing to Kubernetes

## Resources Available

- [Kubernetes Contributor Playground](#kubernetes-contributor-playground)
- [Contributor Workshops](#contributor-workshops)
- [Community](#community)
  - [Communication](#communication-1)
  - [Events](#events)
    - [Meetups](#meetups)
  - [Mentorship](#mentorship)
- [Advanced Topics](#advanced-topics)

# Prerequisites

Before submitting code to Kubernetes, you should first complete the following prerequisites.
These steps are checked automatically by [a bot](https://github.com/k8s-ci-robot) during your first submission. 
Completing these steps will make your first contribution easier: 

## Sign the CLA

Before you can contribute to Kubernetes, you will need to sign the [Contributor License Agreement](/CLA.md).  

## Code of Conduct

Please make sure to read and observe the [Code of Conduct](/code-of-conduct.md) and [Community Values](/values.md)

## Setting up your development environment

It is not required to set up a developer environment in order to contribute to Kubernetes.

If you plan to contribute code changes, 
review the [developer resources](/contributors/devel/README.md#setting-up-your-dev-environment-coding-and-debugging) page for how to set up your environment.

## Community Expectations and Roles

Kubernetes is a community project.
Consequently, it is wholly dependent on its community to provide a productive, friendly and collaborative environment.

- Read and review the [Community Expectations](expectations.md) for an understanding of code and review expectations.
- See [Community Membership](/community-membership.md) for a list the various responsibilities of contributor roles. 
- You are encouraged to move up this contributor ladder as you gain experience.

# Kubernetes Contributor Playground

If you are looking for a safe place, where you can familiarize yourself with the pull request and issue review process in Kubernetes, 
then the [Kubernetes Contributor Playground](https://github.com/kubernetes-sigs/contributor-playground/) is the right place for you.

## Contributor Workshops

A [Youtube playlist](https://www.youtube.com/playlist?list=PL69nYSiGNLP3M5X7stuD7N4r3uP2PZQUx) of the New Contributor workshop has been posted, 
and an outline of the video content can be found [here](/events/2018/05-contributor-summit). 

# Community

Kubernetes is a large, lively, friendly open-source community.
As many open source projects often do, it depends on new people becoming members and regular code contributors. 
The [Community Membership Document](/community-membership.md) covers membership processes and roles. 
Please consider joining Kubernetes, and making your way up the contributor ladder!

## Communication

- [General Information](/communication) relating to Kubernetes communication policies

## Events

Kubernetes participates in KubeCon + CloudNativeCon, held three times per year in China, Europe and in North America.
Information about these and other community events is available on the CNCF [events](https://www.cncf.io/events/) pages.

### Meetups

All Kubernetes meetups follow the general [Cloud Native Computing Foundation guidelines](https://github.com/cncf/communitygroups).
You may also contact CNCF Staff driving the Community Groups (previously known as Meetups) program by email (meetups@cncf.io)

## Mentorship

Learn more about the Kubernetes mentoring initiatives [here](http://git.k8s.io/community/mentoring/README.md).
Join past and present Kubernetes Contributors for a live question-and-answer session during 
[Meet Our Contributors](https://github.com/kubernetes/community/blob/master/mentoring/programs/meet-our-contributors.md). 

# Advanced Topics

This section includes things that need to be documented, but typical contributors do not need to interact with regularly.

- [OWNERS files](owners.md) - The Kubernetes organizations are managed with OWNERS files, 
which outline which parts of the code are owned by what groups.
