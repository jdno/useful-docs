# Useful Documentation for Software Projects

Good documentation is important in any software project. But for many different
reasons, most projects don't have documentation. It is hard to figure out what
to document, where to do it and how to keep it up-to-date. Making time to figure
these things out is often not possible within the scope of a project, which is
where _Useful Documentation_ comes in.

This project proposes a structure for documentation in modern software projects.
It is designed to capture the most important information in a process that is
transparent, collaborative and extensible.

## Document Types

Project documentation is split into two categories: **decisions** and
**requirements**. Decisions document the _why_, and **requirements** document
the _what_. The _how_ is documented by the code itself, or if that is
insufficient through documentation in the code.

### Decisions

The outline for decisions is based on [Architecture Decision Records][adr]. It
captures the context for a decision as well as its outcome in a brief format.
For decisions, the following rules apply:

- Decisions are numbered sequentially and monotonically
- Decisions are never deleted but _superseded_ by new ones

For more information on ADRs, check out the original blog post. For examples,
take a look at the [GOV.UK](https://github.com/alphagov) repositories, where
ADRs are widely used.

### Requirements

It is important to plan a little bit ahead when implementing new features, and
requirements documents are a standard way to do this. They capture the goal of a
new feature, the steps it takes to implement it as well as any questions or
concerns a new feature might introduce.

The structure of the requirements document is inspired by the [requirements document](https://confluence.atlassian.com/doc/blog/2015/08/how-to-document-product-requirements-in-confluence)
in [Confluence](https://www.atlassian.com/software/confluence).

## License

This project is licensed under the terms of the MIT license.

[adr]: http://thinkrelevance.com/blog/2011/11/15/documenting-architecture-decisions
