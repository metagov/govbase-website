---
layout: default
title: "Projects"
permalink: /docs/projects/
---

# Projects Table

Platforms, software, and research in online governance.

To add a new project, fill out the [Airtable form](https://airtable.com/shr1BcXojViDgTOdX).

## Available views
- **All records**
- **Linked to: Cases**: projects involved in an [online governance case](./cases)
- **Linked to: Cryptogov Survey**: projects that have completed the [Cryptogov survey](./cryptogov):
- **Linked to: Entity-Decision Model**: projects with a defined [Entity-Decision Model](./ed-model)
- **By development status**: grouped by whether the project is a work in progress, active, inactive, or dead
- **Open-source software**: projects labeled open-core or open-source
- **DAO ecosystem projects**: projects that create or facilitate Decentralized Autonomous Organizations (DAOs)
- **Policy Templates**: plain-text or code documents that describe a governance policy
- **Metagov projects**: projects owned by Metagov
- **Metagov Gateway support**: projects for which [Metagov Gateway](https://gateway.metagov.org/) has implemented a plugin

## Fields of interest
- **Year founded**: Year that the project was first released, or if that not lear, year of first code commit.
- **Status**: A project is inactive if it has been at least 2 years since the last commit. It's dead if the code and/or service is no longer accessible.
- **Online/offline**: is the project specifically intended for online communities or offline communities? If not clear, say "not specific". If it is not intended for either (e.g. Linux), say "Not community-related". Intended to distinguish online governance tools like SourceCred from primarily offline tools like Consul (this later category of tools often gets classified under the heading of "civic tech", e.g. https://civictech.guide/).
- **Implements structures**: a This is meant as, "this project implements or helps implement a community or organization with these observed structures." Alternately: "after using this project, an organization will likely demonstrate these observed structures." E..g Aragon implements DAOs, CIVS implements voting, and so on.
- **Category**: 
  1. *product*: libraries, tools, applications, and even services
  2. *platform*: hosted applications that communities interact on
  3. *standard*: includes protocols and text standards. Communities can interact via protocols, but protocols aren't hosted like platforms are.
  4. *mashup*: mashup of several platforms or products.
  5. *research*: includes data sets (like Govbase!) and algorithms. It does NOT include papers.
- **Project ownership type**: 
  1. *Public domain*: the project's code or content is not held under copyright
  2. *Open-source*: the project's code or content is available for use under an open-source or open-content license
  3. *Open-core*: a significant part of the project's code or content is available for use under an open-source or open-content license
  4. *Privately-owned*: the project's code or content is privately-owned
- **Used by project**: a staging column for more precise ways in which two projects interact, i.e. *Requires project (hard dependency)*, *Suggests project (soft dependency)*, *Forked from project*, and *Built interop with project*