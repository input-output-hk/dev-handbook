# Development github process #


We have a pretty large development organisation spread across several teams.
These teams have somewhat different focuses, from formal methods engineers
developing proofs and executable specs, to more implementation focused teams. We
also use several different programming languages now. All of these separate
streams of work need to integrate with the larger mission of IOHK and the
management processes that keep track of large, interconnected projects.

## Motivation ##

The aim of this document is to lay out a lightweight, developer focused set of
best practices for managing work and tracking progress using github. These
processes are owned by the developers themselves and everyone should feel
empowered to suggest improvements on an ongoing basis as we figure out what
works and what could be improved.

Teams that require amendments to this process should overlay this document with
any tweaks or changes that they wish to make for their own day to day work
flows. We will also establish a regular feedback loop so that where appropriate
we can incorporate these changes to the main process. The aim here is that
everyone should be doing roughly the same thing, and any differences should be
outlined. This is so that we can easily implement exchange or liaison programs
between teams and developers can slot into other teams easily when required.

## Principles ##

The software development process should set out the basic day to day workflow
that developers can follow. This workflow should strive for the optimal balance
between allowing the developer to focus on the most high value work and granting
the business an overview of what's in flight and when to expect delivery. To
achieve these competing aims and decide on the trade offs, we should be guided
by some principles. These are:

### Clarity ###

Things that should be clear from applying the process laid out in this document
are:

 * What each team is working on and the importance of that delivery to the "big
   picture".
 * What dependencies pieces of work have from other teams (and vice versa).
 * As accurate as possible view of when the pieces of work in flight can be
   expected to be delivered.
   
   
### Lightweight ###

The process should be easy to understand and implement and should impose the
minimum overhead on developers over and above general development tasks. The
ideal here is something that's integrated with developer tooling and automatic.

### Changeable ###

The process should be changeable as requirements shift or improvements are
identified.

### Integration ###

These processes should offer easy integration points to other managements
systems and processes. For example, it should be straightforward for a project
manager to get an overview of progress without having to pull developers into a
meeting or otherwise interrupt their flow.


## GitHub benefits ##


Github has in built tooling for developer centric project management. We can
leverage these tools to track work in a way that makes sense to developers.
There's extensive documentation on how to use these tools in the [GitHub
Guides](https://guides.github.com/) website. In particular the [Mastering
Issues](https://guides.github.com/features/issues/) documentation is worth
reviewing.

### Separation of managing work and reporting on work ###

Using github gives us a clear separation between things that developers care
about for their day to day work and the things that parties external from the
dev team care about for reporting and monitoring purposes. The basic unit of
sepration is the github [milestone](#milestone)

### Lightweight automation of reporting ###

GitHub is also smart about updating dashboards and providing an overview. Using
the standard tools in PRs (for example commenting that a PR "Closes
#<issue-number>") moves issues and PRs to the right status and updates related milestones.

[Automation](https://help.github.com/articles/configuring-automation-for-project-boards/)

## <a id="project"></a>Projects ##

Projects can be internal to a GitHub repository, or a GitHub organisation. They
have a kanban like board where all the issues and pull requests that are tagged
to that project appear. As issues are closed and PRs merged the cards on the
board are moved to done, but moving them to in progress is a manual process.

## <a id="milestone"></a>Milestones ##

A github milestone is a unit of delivery. A grouping of individual [prs](#pr) or
[issues](#issue) that are the break down of a deliverable chunk of work. A
milestone is internal to a GitHub repository.

## <a id="pull request"></a>Pull Requests ##

Pull requests are an intention to merge code into the main line of development
(or another branch). PRs are opened when a feature or other chunk of work is
development complete for review and possible further tweaks by other developers.

## <a id="issue"></a>Issues ##

An issue is a breakdown of work from a [milestone](#milestone). The general rule
of thumb for these is as granular as possible, but ideally less than a couple of
days work. The more granular the issue, the more precise the estimate can be.
