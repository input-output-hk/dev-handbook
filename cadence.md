# Cadence

All processes in nature have a cadence or rhythm. A development team is no
different. What follows in this document is a suggested cadence for a
development team in a larger engineering department.

The aim of thinking about this is that we have a concrete starting point to
improve from. Rather than vague statements about trying things we can have
measurable goals in the form of "We will try changing this from X to Y".

# Daily tasks

Daily tasks are those things that ensure the team is working well together and
that bottlenecks are addressed. The daily cadence is mostly about ensuring that
everyone within the team has everything they need to do their work on an ongoing
basis.

## Check issues on the board

This should be an ongoing process of checking that completed tasks are ticked
off and anything that requires a review gets one in a timely manner.

## Daily check in

This can be as simple as a quick line in a shared slack channel or it could be a
more formal stand up. The intention is that everyone on the team should know
what's in flight and how what they are doing relates to everything else

# Weekly tasks

These are mostly tasks that take place at the team (or intra-team) level. They
are mostly aimed at ensuring alignment and shared understanding of the work to
be done from different points of view:

Inter team:

 * Do we have sufficient work defined and is that work understood well enough to
   complete?
 * Are we learning lessons and improving our practices?
 * Do we understand how what we are doing fits into the bigger picture
 
Intra team:

 * Do we know how what the work of teams is related (dependencies etc)
 * Does each team have a high level view of what the other teams are working on
 * Are we sharing lessons learned across teams
 
PM/management:

 * Do we have an understanding of the work in progress
 * Have we aligned the teams to the current focus and the most important tasks
   to achieve the highest priority items
 * Do we have effective reporting and tracking in place

## Task breakdown

When new items are added to the teams backlog there should be an initial task
breakdown. This is unlikely to be the full picture, unless the feature is going
to be worked on immediately, but it's useful to have a first pass and define
what is known now. The outcome of this exercise are high level epics and tasks,
defined to the best of our ability based on what we know right now.

The other thing that needs to happen on a regular basis is the definition of
milestones. Milestone group work that is intended to be completed together. When
this happens the issues that are added to the backlog are assessed for readiness
(i.e. is the issue sufficiently well defined to complete) and dependencies. If
the features and issues are sufficiently well understood by those who will do
the work they can be accepted and given an estimate in story points.

## Retrospective/reporting

Performing retrospectives regularly is of critical importance. It's a chance for
the team to reflect on the work they have just done and consider any lessons to
be learned or new things to try in the next period of execution. Without doing
this in a fairly rigorous way, it's very hard to consistently improve.

The benefit of a retrospective should be for the team to improve, but it can be
used for double duty with a little bit more structure. If we also record the
findings of a retrospective in a common format across teams, this fairly short
weekly meeting can also form the input of the team's progress report for the
week, meaning that we don't need a separate meeting for preparing an update.

### Debrief on issues completed and underway

Every issue that's worked on is an opportunity for learning how do perform our
craft better. During the retrospective we should assess the issue considering:

 * How well defined was the issue
   * Did we break it down completely upfront or were unforeseen tasks added after
     it was started?
   * Did we thoroughly assess the dependencies and possible risks beforehand?
 * How accurate was the estimate?
 * Is the issue complete or still underway?
 
When an issue is completed the `Consequences` section of the issue should be
filled in.

### Assessment of milestones and epics underway

We should also report on the progress of milestones and epics. This is more as
an external report of the team's progress but the
[dev-team-weekly-report.md](dev-team-weekly-report.md) also has a section for
any blockers, risks or other comments related to milestone and epic progress to
be recorded.

### Weekly team report produced

The output of the weekly retrospective is the team's weekly report. The weekly
report should contain information at a granularity which is useful for both
external reporting, but contains insight for the team to review reports over
time. This includes high level summaries of issues completed as well as
milestones and epics. There's also a section in the report for lessons learned
and new ideas to try in the next week. See
[dev-team-weekly-report.md](dev-team-weekly-report.md) for the template.

## Team leads' meeting

The aims of the weekly team lead's meeting are:

 * To ensure that the teams have a clear picture of what each other are doing
 * Sharing lessons learned
 * Reporting progress or blockers to PM and management
 
The intention here is essentially the same as the team retrospective, just "one
level up".
