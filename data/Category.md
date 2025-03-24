---
title: Category
type: definition
---

A Category is a [[is_a:Structure]] where the [[uses:Relation]] in question must follow two rules:
 - Identity: For any [[uses:Structural Element]] A, there must be a unique "identity" relation from A to itself.
 - Composition: For any relation from ([[uses:Structural Element]]s) A to B and B to C, there must also be a corresponding relation from A to C. ($f : A -> B$, $g: B -> C$, $g \circ f : A -> C$)
 - Unit Laws: Composing the relations A -> A and A -> B mut result in the same A -> B relation. Same if it was A -> B and B -> B => A -> B.
 - Associative Law: The Composition operation must be associative.

See https://en.wikipedia.org/wiki/Category_(mathematics)#Definition for more info :)