---
title: Start
type: start
---

# Welcome to The State Ontology Project!

This is a project made by Zon, which aims to create an ontology to compare various definitions of "[[mention:The State]]", make a few arguments on interesting topics, and explore the feasability of ontology-creation.

But first, what is an Ontology, and why should you care about it?

[Ontology](https://en.wikipedia.org/wiki/Ontology) is the philosophical study of being, investigating what [[mention:Entity|Entities]] exist, how they are grouped into categories, and what [[mention:Relation]]s exist between them. More recently, the philosophical subfield of Ontology has been flirting with the field of Information Science, creating the a new subfield of [applied ontology](https://en.wikipedia.org/wiki/Ontology_(information_science)) which aims to not only figure out what entities exist, but to represent them all inside computer systems and be able leverage that knowledge within computer programs.

For the purposes of this project though, the goal is to try to create an (informal) ontology, visualizing it with a interactive graph, and experimenting with different structures to represent ideas pertaining to The State (and The Internet). 

## The Structure of the Project

This project is likely a bit daunting to jump right in to—there are 75 nodes to click on and 178 links! So here is a general overview of the main features:

#### The Arguments

There are a few argument nodes (shown in gray), giving some unstructued commentary on a few topics, which are a good place to start if you just want to read some argumentation. (See the [[mention:Category - Arguments]] node for more info)

#### The Terms

There are two terms (The State and The Internet) which have multiple definitions that "define" them. A major goal of the project is to compare and contrast these definitions in various ways, and to point out that while there may be no one "right" definition, there are certain ones more useful in certain contexts than others!

### The Ontology

Finally, the rest of the ontology is made up of an actual ontology: A network of relations between definitions (ideas?, concepts?) as an effort to capture some small meaningful part of the structure of our world, for self-reflection, computer interpretability, ease of communication, learning, automation, or whatever else ontologies are useful for. This ontology contains domain-specific concepts as well as highly abstract definitions, combining both the qualities of a [Domain Ontology](https://en.wikipedia.org/wiki/Ontology_(information_science)#Domain_ontology) and an [Upper Ontology](https://en.wikipedia.org/wiki/Upper_ontology) (which is required to ground the domain ontology) into a Hybrid Ontology.

## User Guide
 - Click on nodes to see what they say.
 - Use `Node Types` and `Link Types` drop-down on left-side panel to filter by node or link type (Alt-clicking one type will show just that one type, alt-clicking again will reset). Use Alt-R to reset all filters
 - Use Index drop-down to see all nodes in a list
 - Use Graph Parameters to hide node labels or link labels.

## Node and Link Key

There are 6 node types (see the left-panel for the color key):
 - Category (contains a list of similar / relevant nodes)
 - Definition (either defines a term, or is an assumed term/definition pair on its own)
 - Argument (contains text arguing / commentating for a position, `using` or `mentioning` other nodes)
 - Source (contains an APA 7 citation, link to resource in applicable, and commentary on the use of the source)
 - Quote (one or more direct quotations cited from a source)
 - Term (A term that is to be defined by other Definition nodes)

There are 6 link types
 - contains (used primarily to link from categories)
 - uses (if a node is used as a reference by another node, usually for definitions or arguments)
 - mention (if a node mentions another node in passing, i.e. for arguments)
 - cites (if a node cites a source, i.e. for arguments or quotes)
 - defines (if a definition node defines a term)
 - quotes (if a node uses a quote from a quote node)
 - is_a (if a definition is a subtype of another definition)
 - prop (if a definition uses another definition as a property)

## Node Categories

If you are looking for a particular category of thing to start on, here's some to get you started:

 - [[mention:Category - State Definitions]]

 - [[mention:Category - Arguments]]

 - [[mention:Category - Assumed Definitions]]

 - [[mention:Bibliography]]


## Built with Cosma

Thanks to the developers over at the [Cosma](https://github.com/graphlab-fr/cosma) project for the graph visualization site generator!
