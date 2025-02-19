# Bitwarden Architectural Decision Records

An [Architectural Decision (AD)][AD] is a software design choice that addresses
a functional or non-functional requirement that is architecturally significant. 
This might, for instance, be a technology choice (e.g., Java vs. JavaScript), a
choice of the IDE (e.g., IntelliJ vs. Eclipse IDE), a choice between a library
(e.g., [SLF4J][SLF4J] vs [java.util.logging][java.util.logging]), or a decision
on features (e.g., infinite undo vs. limited undo).

## @Bitwarden

The goal of introducing AD in the engineering team at Bitwarden is to steer
development towards a maintainable and expandable code base. While at the same
time striving for uniformity across all pods.

It will also serve as a base for proposing and planning technical debt.

## Process

While the process was originally created primarily for leads to discuss
architectual decisions, it's important to us to keep the process open for
anyone.

To that end, anyone is free to open a PR suggesting an AD. The decision will
then be discussed to reach a general concensus between the leads before being
adopted.

[AD]: https://en.wikipedia.org/wiki/Architectural_decision
[SLF4J]: https://www.slf4j.org/
[java.util.logging]: https://docs.oracle.com/javase/8/docs/api/java/util/logging/package-summary.html
