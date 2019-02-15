---
title: "Repository set up"
date: 2019-02-01T13:50:34Z
weight: 40
---

We want to set up our open source reops is a way that's consistent and that
encourages participation from the community. With that in mind every open source
reop should have at least the following set up:

# README #

Every repo should have a readme file that contains the following sections

## Introduction ##

A description of the project and its purpose

## Building ##

How to build the project and how it is tested. If possible we should embed the
status of CI as a button.

## Usage Examples ##

Library code should contain examples of use

# License #

The standard licence used across the `input-output-hk` GitHub organisation is
the apache 2.0 license. See [Licensing](../licence/) for more detail

# Contributing #

Guidlelines on how to contribute to the project. This section should point to
the documentation on how we use [GitHub](github-process.md) and instructions on
how to submit issues and pull requests. It should also point to the style guide
and coding standards for the main languages of the project.

There are a couple of ways to set this up. The suggestested method is to add a
file called `CONTRIBUTING` to the `/docs/` directory of each repo.

For more information see the
[<i class="fas fa-github"></i> GitHub Guide](https://help.github.com/articles/setting-guidelines-for-repository-contributors/)

# Issue templates #

These should be set up and be as similar as possible as other projects within
Cardano that use the same programming environment. A growing repository of examples
can be found in the [<i class="fas fa-code"></i>
 Templates](/templates) section.
