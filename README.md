# Theory of Computation Notes

This repository contains my notes on various topics of Theory of Computation. The notes are written in LaTeX and are available in both `.tex` source and compiled `.pdf` formats.

## Topics Covered

### Myhill-Nerode Theorem
The Myhill-Nerode theorem provides a necessary and sufficient condition for a language to be regular. It states that a language is regular if and only if it has a finite number of equivalence classes under the Myhill-Nerode equivalence relation. This theorem is a powerful tool for proving that a language is not regular.
- [PDF](Myhill%20Nerode%20Theorem.pdf)
- [LaTeX Source](Myhill%20Nerode%20Theorem.tex)

### Pumping Lemma for Regular Languages
The pumping lemma for regular languages is a property that all regular languages must satisfy. It is often used to prove that a language is not regular by showing that it violates this property. The lemma states that for any regular language, any sufficiently long string in the language can be "pumped" – that is, a middle section of the string can be repeated any number of times to produce a new string that is also in the language.
- [PDF](Pumping%20Lemma.pdf)
- [LaTeX Source](Pumping%20Lemma.tex)

### Pumping Lemma for Context-Free Languages
Similar to the pumping lemma for regular languages, the pumping lemma for context-free languages is a property that all context-free languages must satisfy. It is used to prove that a language is not context-free. The lemma states that for any context-free language, any sufficiently long string can be divided into five parts, where the second and fourth parts can be pumped simultaneously to create new strings that are also in the language.
- [PDF](Pumping%20Lemma%20CFL.pdf)
- [LaTeX Source](Pumping%20Lemma%20CFL.tex)

### Church's Thesis
Church's Thesis (also known as the Church-Turing thesis) is a hypothesis about the nature of computable functions. It states that any function that can be computed by an algorithm can be computed by a Turing machine. This thesis provides a formal definition for the intuitive notion of "computability" and is a fundamental principle of the theory of computation.
- [PDF](Church’s%20Thesis.pdf)
- [LaTeX Source](Church’s%20Thesis.tex)

