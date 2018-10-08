# Development github process #

## Motivation ##

We have a pretty large development team spread across several teams. These teams
have somewhat different focuses, from formal methods engineers developing proofs
and executable specs, to more implementation focused teams. We also use several
different programming languages now.

The aim of this document is to lay out a lightweight, developer focused set of
best practices for managing work and tracking progress using github. These
processes are owned by the developers themselves and everyone should feel
empowered to suggest improvements on an ongoing basis as we figure out what
works and what could be improved. The aim of this document is the set out the
basics and ensure that there's a common understanding of all the moving parts.
Teams that require should overlay this document with any tweaks or changes that
they wish to make for their own day to day work flows. We will also establish a
regular feedback loop so that where appropriate we can incorporate these changes
to the main process.


Github has in built tooling for developer centric project management. We can
leverage these tools to track work in a way that makes sense to developers.
There's extensive documentation on how to use these tools in the [GitHub
Guides](https://guides.github.com/) website. In particular the [Mastering
Issues](https://guides.github.com/features/issues/) documentation is worth
reviewing.

## GitHub benefits ##

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

Projects can be internal to a GitHub repository, or a GitHub organisation.

## <a id="milestone"></a>Milestones ##

A github milestone is a unit of delivery. A grouping of individual [prs](#pr) or
[issues](#issue) that are the break down of a deliverable chunk of work. A
milestone is internal to a GitHub repository.

## <a id="pull request"></a>Pull Requests ##

## <a id="issue"></a>Issues ##

An issue is a breakdown of work from a [milestone](#milestone). The general rule
of thumb for these is as granular as possible, but 
