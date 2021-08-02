---
published: false
---
---
layout: post
title: You're up and running!
---

## Why do we need it?
	
When you develop any solution in a team of more two developers you most probably face with different code styles that your teammates follow. That leads to code reading issues - when you are checking let's say pull request your eye catches differences in code styles(for instance diffrent spacing) and distructs you from your original goal - checking correctness of business rules.

## How can we achieve this?

The most straightforward way is to distribute IDE code style configuration between your teammates. But what if one of your teammates uses diffrent IDE or if we would like to force code style rules in CI? And what about code design analysis like complexity or maintability? Here IDE configuration won't help us but **code analysers** will.

### .NET Analyzers
Porpouse of .NET analyzers is to inspect code for
- style
- complexity
- maintability
- design

Code analysis is already included in .NET 5 SDK and enabled by default if you use .NET 5 as a target platform. 