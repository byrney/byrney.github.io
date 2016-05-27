---
layout: post
title: Anti-Patterns - The New Team
---

Our main derivatives trade booking system MCoS (Massively Complex Old System)
needs replacing. Draft in a new team of people from other businesses or
organisations to construct the replacement leaving the MCoS team to maintain
the current system



<table>
  <tbody>
    <tr>
      <td>Pattern Name</td>
      <td>The New Team</td>
    </tr>
    <tr>
      <td>Aliases</td>
      <td>Don't allow people who built the current system to taint the
              design of its replacement </td>
    </tr>
    <tr>
      <td>Type</td>
      <td>Organisational</td>
    </tr>
  </tbody>
</table>


## Risks ##

* The MCoS team will disinclined to help since:
  - If they succeed New Team are putting us out of a job
  - New Team won't succeed, it's all a waste of time...
  - We don't have time to help, just a long list of critical regulatory
    deliverables
  - New Team don't understand how our business works
* New Team genuinely won't understand how your business works (at least not
  the details)
* New Team will struggle to build a relationship with the users (until they
  try to roll it out and then they'll have more relationship than they can
  handle)
* While New Team play with Shiny Technolgy X Old Team are stuck writing
  scripts in Crazy Vendor Language McScript. They were depressed before, now
  they're leaving.

The result? Your estimate for how long the replacement will take is massively
optimistic. It always was but now you can double it. During the delay, MCoS
will have changed (new products have been added, those critical regulatory
changes have gone in). Your blitzkrieg upgrade plan, avoiding the pain of
keeping two systems in sync for a prolonged period, is marching towards Russia
-- winter is comming.

## Justifications ##

* New Team need to be focussed on delivering the new system (MCnS) rather than
  getting dragged into daily issues
* The MCoS team don't understand Shiny Technology X they're all McScripters
* The MCoS team have, thus far, failed to address the major archiectural
  issues, clearly they are not capable
* The MCoS team are stuck in a rut of doing things the MCoS way
* Besides, we need them to deliver all the critical reg fixes
* MCoS doesn't work, we need to change things up

## Proponents ##

New Team Team Lead: You sold New Guy a vision of greenfield development in
                    Shiny Technology X. Now you want him
                    to learn McScript?  Nah...

## Opposing Patterns ##

Keep adding resources to MCoS which just get diverted into doing BAU

Put the MCoS team lead in charge of the replacement because you don't want to
upset him and he's the only guy who can keep MCoS running.


## Related/Colluding Patterns ##

* Shiny Technology X
* It would be quicker to build it from scratch


## Comments ##

Obviously the MCoS team are not going to be able to do this by themselves.
They probably know many or the issues with the current system but may not have
experience of workable alternatives. You need new blood, not blue sky thinking
but people who who know one (or more) workable approaches for the issues.


The MCoS team still have crucial relationships and knowledge about the system
and it's users. You cannot afford to ignore or undervalue this. It's
impossible to migrate a trading business to a new system without some changes
in the old one.

One of the reasons you're moving to Shiny Technology X is because people who
know McScript are hard to find (or cost £900 a day as contractors). Do you
want to bet on migrating it all to Shiny Technology X before the last
McScripter has left?

## Antidotes ##





