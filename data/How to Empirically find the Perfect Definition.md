---
title: How to Empirically find the Perfect Definition
type: argument
---

What makes a definition good? What even *are* definitions?<sup>\[‍[[mention:Definition]]‍\]</sup> Where do they come from?<sup>\[‍[[mention:Human|Humans]]‍\]</sup> How do they change over time?<sup>\[‍[[mention:Society]]‍\]</sup>. Those other questions are interesting<sup>\[[citation needed](https://knowyourmeme.com/memes/citation-needed)\]</sup>, but this argument is about the first one. Particularly, how to *quantify* properties of definitions, so we can battle them against each other until the best definition wins!

For a practical answer of what makes a definition (particularly a sociological definition) good, I turn to a 1999 paper by John Gerring<sup>[1]</sup>. This paper takes a pragmatic approach, understanding that no definition is "perfect", but that there are certain qualities that good definitions try to satisfy:

1. Familiarity - How familiar is the definition to a user or listener? (How much does it reuse existing commonly-used concepts?)
2. Resonance - How catchy or rememberable is the term or definition?
3. Parsimony - "How short is the term and its list of defining attributes?" (Possibly a type of Resonance)
4. Coherence - This property refers to whether the definition(s) of the concept under analysis satisfy the following properties:
   - Consistency - Whether properties contradict each other (i.e. if you have two commonly used definitions of a term that are logically inconsistent with each other and the writer doesn't specify between them, the concept they are using is not Coherent)
   - "Property Relatedness" - Whether properties of a concept are logically or functionally *related*. This is primarily here to measure how "essential" definitions are, and whether or not they are focused on a particular topic or phenomenon, or are just a list of unrelated properties.
5. Differentiation - How well the definition is allows one to differentiate between actual instances of things you want to talk about.
   - i.e. if you have a definition of The State, you might want to be able distinguish between things that are state-like, but not actual states. So, if you extended Weber's definition of the state to contain a descriptor like "has a military force", since that is true of most (or all) Weber States, it doesn't increase the differentiation power of the definition. 
6. Depth - How many accompanying properties are shared by the instances under definition?
   - A definition with more "depth" is more useful because it conveys (or implies) more associated information. While a given definition of a term may identify certain properties, (such as a State having a Monopoly on Violence), there are many other properties that are associated, but not directly defined (such as a police force or military). This property of Depth is a measure of how many of these other associated properties there are.
7. Theoretical Utility - How useful is a term in the context of a theory?
8. Field Utility - How much changing a given definition perturbes definitions that are built on or relate to it. (How much effort does it take to "renormalize" the "semantic field").

These desirable properties are all well and good, but if we want to do science with these, or perhaps use computers to figure out the "best possible definitions" for certain terms (if thats even possible, or useful), these criteria must be quantified! Thus, the following part of this argument note is proposing how these qualities might be measured empirically:

1. Familiarity - This could be simply measured, collectively at least, by counting frequency of the words that make up the definition and adding them up. Although, out of all the metrics on this list this seems like the least important, as it could theoretically be overcome by having people re-learn definitions and associations.
2. Resonance - This relates to the term moreso than the definition, and it is a language-specific property that changes depending on person and context. It could also theoretically be overcome by people just dealing with "non-resonant" definitions or terms (as we often have to do anyway).
3. Parsimony - This could just be measured approximately as a word (or perhaps character count) of the term or definition in question.
4. Coherence - Now this is an aspect that a computer-interpretable ontology might be helpful in measuring.
   - The consistency part of coherence could be measured by recording all the logical deductions one can make from all possible properties one might be interested in, and then do a search on all the properties contained within a definition to see if any of their deduction chains lead to a contradiction. If so, that violates consistency!
     - An example of this in action could be as follows: Now usually a single standalone definition is not inherently obviously inconsistent (us humans are good at recognizing obvious inconsistencies), however, different definitions for the same concept are often inconsistent with each other, such as (taken from Gerring) the term "Ideology" being defined simultaneously as "a system of ideas that promote social change" and by others as a "system of ideas the prevent \[social\] change". In an ontology "promote" might be defined in terms of the opposite of "prevent" (or vice-versa) which then creates an obviously contradictory situation that a computer could recognize.
   - "Property Relatedness" could similarly utilize an ontology, but in a different manner. If the Ontology in question tracks relations between the properties that compose to create a concept, this can be measured directly! (There may be some extenuating circumstances around what types of relations are preferred)
5. Differentiation - For this quality, it could be possible to quantify how much different concepts overlap in terms of either shared properties or shared instances of the entity. Overall "differentiation power" of a given concept could be measured by measuring how often a concept overlaps with other concepts, creating an overall measure of how well the concept differentiates itself.
   - For example, the term "fruit" has more differeniation power than "food" because food overlaps with many more concepts (meat, veggies, bread, etc.) than fruit does.
6. Depth - For this quality, it might be possible to quantify it by going through all known instances of a concept, going through all properties of those instances, and counting the frequency of common properties. Computationally intensive, but doable!
7. Theoretical Utility - For this one, its unclear at the moment how its possible to measure this. The ontology would need to be able to encode theories and then be able to see how well a given definition is used by a theory, perhaps averaging over all theories known? This may need more thought :)
8. Field Utility - This one however, is easy! Just count the number of times a definition is used by another definition in an ontology.

### Citations

[1]: [[cites:Gerring - 1999 - What Makes a Concept Good? A Criterial Framework for Understanding Concept Formation in the Social Sciences]]