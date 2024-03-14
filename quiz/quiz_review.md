CS3120 - Quiz Review Guides
===============================

[Back to main page](../index.html)

<a name="links"></a>Links to past quizzes
---------------------------------------

[Spring 24 Quiz 1](./sp24-quiz1.pdf)

[Spring 24 Quiz 2](./sp24-quiz2.pdf)

[Fall 23 Quiz Day 1](./QuizDay1.pdf)

[Fall 23Quiz Day 2](./QuizDay2.pdf)


<a name="introduction"></a>Module 1 Review Topics and Example Questions
---------------------------------------

Module 1 involved a high-level discussion of what computing really means, as well as a review of proof techniques, cardinality, and other related topics. This list is **NOT EXHAUSTIVE** and there may be questions on the quiz that do not cleanly fall into any of the categories below. Students should be able to do the following on an assessment:

- Any problem from any of the homework assignments on this module, including new problems that are similar but have slight variations.

- Discuss Input/Output of computers as Strings using formal notation and interpretation simple descriptions of alpabets and sets of strings. Example questions:
	- If $\Sigma=\{0,1\}$, then what do the following languages represent: $\Sigma^+$, $\Sigma^2 \ U \ \Sigma^3$. 
	- Write out a formal description of the following set (you may use set operators union, concatenation, and star if you want to e.g., $\{0,1\}^* \ U \ \{1\}^3$): The set of binary strings in which number of 0's is exactly three times the number of 1's

- Understand and describe the properties of functions:
	- Injective, Surjective, and Bijective
	- Give examples of functions with these properties
	- Given a function, explain which properties it has:
		- E.g., Consider the function $\mathbb{N}->\mathbb{N} \ \ f(x)=x^2$. Is this function injective? surjective?
	- Cardinality: Be able to count the number of elements in a set
		- E.g., How many elements are in the set of rational numbers in which the denominator and numerator can only be 1, 2, or 3?

- Create bijections between two sets to show they have equal cardinality.
	- Finite sets
	- Infinite sets
	- Argue that a provided bijection is injective and surjective
		- E.g., In class we saw a bijection from NxN to N. Argue, in words, why this function is injective.

- Understand and perform a proof by diagonalization to show that a set is uncountably infinite.
	- See example from class AND homework problem.


<a name="introduction"></a>Module 2 Review Topics and Example Questions
---------------------------------------

Module 2 involved the introduction of the DFA and NFA machines, including the class of languages they recognize (regular languages). We always introduced the regular expressions, a different way of describing the same class of languages. This list is **NOT EXHAUSTIVE** and there may be questions on the quiz that do not cleanly fall into any of the categories below. Students should be able to do the following on an assessment:

- Any problem from any of the homework assignments on this module, including new problems that are similar but have slight variations.

- Understand and describe the difference between a function and a language. Describe how these are effectively the same but are presented in a different manner. Convert function descriptions into equivalent languages descriptions:
	- Describe the language equivalent of this function: This function takes in strings containing 0, 1, and 2 and returns true if the sum of the bits is odd, otherwise it returns false.

- Show an understanding of Deterministic Finite Automata, how they work / operate. Be able to:
	- Draw a DFA that recognizes a given language
	- Describe the language (as a regular expression) that is recognized by a given DFA.
	- Step through the computation of a DFA on a given input.
	- Answer questions about the limitations of DFAs

- Show an understanding of the formal description / notation for a DFA. Write out the description of a DFA using formal notation instead of a picture (graph notation).

- Show an understanding of the formal definition of a valid computation on a DFA.

- Do all of the above, but for an NFA
	- Understand and describe non-determinism, its benefits and limits
	- Design a simple NFA
	- Convert and NFA into an equivalent DFA
	- Explain / prove that NFA and DFAs are equivalent in computational power.

- Show a proof of closure for regular languages under union, concatenation, and star.
	- Prove closure under a new operation (complement, intersection, etc.)

- Read and write regular expressions as defined in this module. Answer any of the previous types of questions using regular expressions.

- Explain the proof that regular expressions are equivalent to DFA/NFA.
	- Prove a language is regular by providing a regular expression for it.

- Answer questions about the validity of the pumping lemma
	- Use the pumping lemma to prove a language is not regular.


<a name="introduction"></a>Module 3 Review Topics and Example Questions
---------------------------------------

Module 3 was a shorter module that discussed context-free grammars, push-down automata, and the pumping lemma for CFGs. This list is **NOT EXHAUSTIVE** and there may be questions on the quiz that do not cleanly fall into any of the categories below. Students should be able to do the following on an assessment:

- Draw a simple pushdown automata for a simple CFG
	- Draw a pushdown automata for this language: $0^n10^n$

- Write out production rules for a simple grammar
	- Write out the Context-Free Grammar for the language $0^n10^n$

- Do the following for PDAs / CFGs:
	- Look at an example PDA and list the language it recognizes
	- Look at an example CFG and list the language it generates
	- Look at a PDA with a bug/issue and fix it
	- Look at a PDA and an example string and describe whether the PDA accepts the string or not
	- Detect whether a given string is generated by a given context-free grammar.

- Discuss the proof of equivalence between context-free grammars and pushdown automata
	- How do we simulate a context-free grammar with a PDA?
	- How do we simulate a PDA with a context-free grammar?

- Use the pumping lemma to prove a non-CFG is indeed not context-free
	- Use the pumping lemma to show that $a^nb^nc^nd^ne^n$ is not context-free



<a name="introduction"></a>Module 4 Review Topics and Example Questions
---------------------------------------

Module 4 introduced the Turing Machine and the notion of decidability. We also discussed reductions, and some computational classes (TM non-recognizable, etc.) This list is **NOT EXHAUSTIVE** and there may be questions on the quiz that do not cleanly fall into any of the categories below. Students should be able to do the following on an assessment:

- Interpret a Turing Machine that is described or drawn in detail. What strings does it accept? What strings does it not accept, etc.

- Write a TM (in high level prose) that recognizes a given language

- Describe non-deterministic turing machines accurately that solve problems using non-determinism.

- Discuss the difference between decidability and recognizability.

- Discuss the definition of complement, and why the complement language can sometimes be harder to recognize than the language itself.

- Prove problems are undecidable through reduction.




