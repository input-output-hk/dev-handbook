# Development github process #


Github has in built tooling for lightweight, developer focused project
management. We can leverage these tools to track work in a way that makes sense
to developers. There's extensive documentation on how to use these tools in the
[GitHub Guides](https://guides.github.com/) website. In particular the
[Mastering Issues](https://guides.github.com/features/issues/) documentation is
worth reviewing.

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

## <a id="milestone"></a>Milestones ##

A github milestone is a unit of delivery. A grouping of individual [prs](#pr) or
[issues](#issue) that are the break down of a deliverable chunk of work.

## <a id="pull request"></a>Pull Requests ##

## <a id="issue"></a>Issues ##

An issue is a breakdown of work from a [milestone](#milestone). The general rule
of thumb for these is as granular as possible, but 
