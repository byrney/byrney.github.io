---
layout: post
title: Financial Technology Anti-Patterns Intro
---

If you've worked in financial services for a while, and especially if you've
moved around a bit, you will have seen the same approaches applied to
delivering technology over and over. Nothing wrong with that, there are common
practices and problems across different business lines and across different
organisations. Some of these approaches consistently produce poor results.
These are the Ant-Patterns. Things we repeat but which never turn out as well
as we planned.

I collected examples of these for a while with an idea of building a Gang of
Four type
encyclopedia[^gamma] of all the anti-patterns. It turns out building such a
taxonomy is at least as hard as it appears so I have managed my expectations
(downwards, obviously) and decided just to try and capture the thoughts in a
set of posts. Maybe by the end of it a structure will emerge.

[^gamma]: https://en.wikipedia.org/wiki/Design_Patterns

## What is an Anti-Pattern ##

Wikipedia defines patterns:

> a design pattern is a general reusable solution to a commonly occurring
> problem within a given context in software design. [...]
> Patterns are formalized best practices that the
> programmer can use to solve common problems when designing an application or
> system.

> Reusing design patterns helps to prevent subtle issues that can cause major
> problems, and it also improves code readability for coders
> and architects who are familiar with the patterns.

Patterns applied appropriately should help us build better software and
processes. They also give us a vocabulary for talking about different
approaches without spelling out all the details. 'Oh, I see, it's an Abstract
Factory. Gotchya'.

An Anti-pattern is:

> a common response to a recurring problem that is usually ineffective and
> risks being highly counterproductive.

Something we that is "common" but ineffective. These are the approaches we see
applied over and over but always have the same problems.

## Types of Anti-Pattern ##

It turns out there are fewer technical anti-patterns then there are patterns.
But anti-patterns cover organisational and project management which are a rich
vein. There are more way to cock up a project or an organisation
than there are to get it right. The Financial Industry is no different and
most the patterns I'm going to talk about are organisational. Mixing up your
Abstract Factories with your Object Builders is pretty horrific but doesn't
have quite the same impact as off-shoring your technology to Azerbaijan.

Anti-patterns differ from patterns in that they can usually be paired up:  Too
much X is an anti-pattern. Not enough X is an anti-pattern. Consider the
following:

> Analysis paralysis: A project stalled in the analysis phase, unable to
> achieve support for any of the potential plans of approach<Paste>

> Escalation of commitment: Failing to revoke a decision when it proves wrong

Damned if you do, and damned if you don't, as they say...

## Pattern Structure ##

For each pattern I will try to provide at least the following.

- Pattern Name: Title of the pattern
- Pattern Type: Organisational, Programming, Architectural
- Pattern Description: Brief description
- Aliases: Alternate names
- Risks: Things to watch out for if you're in this situation
- Arguments used to justify this pattern: How to spot it before you start
- Proponents of this pattern: Who is most likely to drive you towards  it
- Balancing Patterns: The opposite pattern where applicable
- Related/Colluding Patterns: A project of any reasonable size will usually
  include clusters of anti-patterns.

In some cases there may be better ways of approaching the problem, ways to
mitigate the risks. No promises though.



