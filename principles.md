# Principles

The following high level principles should guide development of Cardano SL
and other IOHK projects.

## Correctness
"Correctness over all else. Code that doesn't work shouldn't exist." -- Mark
Hibberd

## Robustness

This code base needs to be robust against everything from malicious attackers
trying to steal ADA or interfere with the correct working of the
network/blockchain to accidental misconfiguration by the user.

## Compositional Correctness

Large, complex, robust and correct programs are built out of layers of smaller
components that are robust and correct. At the lowest level correctness is
ensured by thorough testing and most tests should be property-based tests. Upper
layers, which do little more than compose the operations of lower levels should
need less testing, but tests should still be property-based where ever possible.

## Operational Simplicity

Building and running the software, including tests, example programs, benchmarks
etc should be as simple and foolproof as possible. Avoid complicated command
line requirements, special magic setup or requiring Nix.

## Conceptual clarity

Code should be as simple as possible without compromising correctness or
performance. The reason for and behavior of each individual component, from
functions up should be relatively easy to explain without reference to the code.
This means it is often desirable to split large functions into smaller easier to
understand components. This also allows these smaller components to be tested in
isolation if that is appropriate.

## Code for the Future

Code should not be written for the computer or the compiler but for the person
who has to read/understand/debug/modify it later. For a project like Cardano
which aims to be around for a long time, "later" may mean a decade or more in
the future.

## Tools over process

Humans are fallible. It is unreasonable to require a human to remember to
complete an optional, error prone process correctly. These optional and/or error
prone processes should be replaced with tools that are part of the normal
development process and check that all required process steps have been
completed.

## Openness

None of our existing techniques, tools or practices should be immutably locked
in stone. When better techniques, tools or practices become available, they
should be considered. However, this should be balanced with avoiding chasing the
latest development fad. In line with this we should have a good reason for using
all of our existing techniques, tools and practices. Finally, everybody on the
team should be free to suggest improvements or question the status quo.

## Be awesome to each other

Everybody working on Cardano SL and at IOHK are on the same team. Aim to treat
everyone with the kindness and respect. Be kind when giving feedback, don't take
it personally when receiving it.

## Work/life balance

IOHK is a distributed company with people located in a huge range of different
time zones. That means we need to accept the fact that we cannot always have the
required people in the same online meeting at the same time. It means we should
not put pressure on people to be online at times wildly outside what would be
considered normal working hours in their local time zone. To work around
timezone issues we need to leverage other tools at our disposal including Slack,
Github, Google Docs or whatever.
