## Top-level definitions
> [!info]+ Definition of **discrete organization**
> **Discrete organization** is a structure of information which describes **knowledge**.
>
> Concepts related to [[structures of information#More thoughts on information structures]]:
> - While there are many potential ways of describing knowledge, this structure seeks to do so by **organizing** it.
> - When organizing information, we are essentially making the conscious decision to factor out (mettre en évidence) certain common characteristics of KIs to illustrate their connexions. This means that we are deciding to only show a small part of the total knowledge base. This is just like making a guitar song with sheet music: by creating the sheet music we are describing only an infinitesimally small part of the potential music that can be described.

> [!info]+ Definition of **knowledge**
> **Knowledge** is the understanding of the nature of things. In this structure of information, "things" are *items*. (More often than not, items are KU.)

> [!info]+ Definition of **organization**
> **Organization** follows [[The principles of organization]].

## The rules of discrete organization

Discrete organization is built on the structure of knowledge graphs.

### Definitions
> [!info]+ Definition of **knowledge graphs**
> A **knowledge graph** is an [Arborescence (graph theory)](https://en.wikipedia.org/wiki/Arborescence_\(graph_theory\)). The root of the graph is the GP $U$.

> [!info]+ Definition of **graph points**
> A **graph point** is a point on the KG. Each GP contains a set KI.

> [!info]+ Definition of **graph edges**
> A **graph edge** is an edge on the KG, which connects two GPs together. Each edge represents a rule, which determines the subset of KIs of the child GP.

> [!info]+ Definition of **knowledge items**
> A **knowledge item** is a "piece" of information, which has any number of characteristics.

> [!info]+ Definition of **knowledge units**
> A **knowledge unit** is the smallest form of KI. A KU is defined by the following 2 characteristics:
> 1. They contain a CC.
> 2. They contain any multitude of KUs (often called the unit's "attributes").

> [!info]+ Definition of **knowledge connexions**
> A **knowledge connexion** is a connexion between 2 KU. KCs are always bidirectional, which means that `A child of B == B parent of A`. They are described by the following 2 characteristics:
> 1. They contain a CC, which pertains to both of its units.
> 2. They contain two KU, which are connected by the KC.

> [!info]+ Definition of **core concepts**
> A **core concept** is a piece of information which is self describing (it is described by its nature alone). (These exist, because, otherwise, there would be no way to describe anything, as everything would just point to something else, which points to something else.)

### Construction of the graph

The KG is constructed step by step according to the following steps:
1. The root $U$ is created and initially contains the set of all KIs.
2. A number $n$ of child GPs are created from $U$. Each child contains a subset of the KIs contained in $U$ based on the rule chosen in the GEs.
3. Depending on the **rigidity of organization** (explained in [[The principles of organization]]), the KIs present in the children will be hidden or removed from the parent.
4. Steps 2 and 3 are recursively repeated on the children $m$ number of times.

N.B. As mentioned in the *definition of discrete organization*, when we are choosing the rules for the GEs in step 2, we are making the conscious decision to show only some of the knowledge - more on this in [[The principles of organization]].

It might seem strange that I have been talking about *knowledge items* this whole time, instead of simply using *knowledge units*, but there is a very specific reason for this: [[multi-level organization]]. This method allows us to organize organization.

## Knowledge systems

This whole time, I have been developing a theory of moderate complexity, but for what? A theory with no application is a useless thing indeed. That is why we need [[knowledge system]]s.

## Légende

| Acronym | Term                      |
| ------: | :------------------------ |
|      KS | Knowledge System          |
|      KG | Knowledge Graph           |
|      OO | Operation of Organization |
|      GP | Graph Point               |
|      GE | Graph Edge                |
|      KI | Knowledge Item            |
|      KU | Knowledge Unit            |
|      KC | Knowledge Connexion       |
|      CC | Core Concept              |
