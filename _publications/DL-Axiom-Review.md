---
title: "Description Logic Axiom Construction: A Narrative Review of Symbolic, Triple-Based, Lexical, and Large Language Model Approaches"
collection: publications
category: preprints
permalink: /publication/DL-Axiom-Review
excerpt: 'A narrative review that places lexical, symbolic, triple-based, and large language model methods for constructing description logic axioms in a single taxonomy.'
date: 2026-10-09
venue: 'SSRN'
paperurl: 'https://doi.org/10.2139/ssrn.7578678'
bibtexurl: 'https://soheilabadifard.github.io/files/DL-Axiom-Review.bib'
citation: 'Dalal, A., Abadifard, S., Gelal, N., Niroula, P., Jagodnik, K., & McGinty, H. (2026). Description Logic Axiom Construction: A Narrative Review of Symbolic, Triple-Based, Lexical, and Large Language Model Approaches. SSRN preprint. https://doi.org/10.2139/ssrn.7578678'
---

**Abstract.** Constructing expressive axioms in the Web Ontology Language and description logics, such as subclass, disjointness, domain, range, and general concept inclusion axioms, remains a bottleneck in ontology learning, because manual authoring does not scale to large knowledge graphs. Recent surveys have covered parts of this field, but none that we identified places lexical methods, symbolic and neural-symbolic description logic learners, triple-based inductive and logical methods, and large language model methods side by side on shared dimensions. This narrative survey unifies these four families under a single taxonomy of axiom construction over Resource Description Framework data and related inputs, including triples, text, labeled examples, ontology signatures, and prompts. We compare the families by input requirements, axiom coverage, controllability, scalability, and dependence on triples. We identify a recurring architectural pattern in the language model literature, in which a generative model proposes candidate axioms and a verification layer based on retrieval, schema repair, entailment, methodology audit, or description logic reasoning constrains them. Because the studies use different benchmarks and metrics, we do not treat their results as directly comparable, and we discuss a hybrid pipeline argument in which lexical and language model proposers, triple-based scorers, and description logic learners and reasoners each carry the operational load they are best suited for. The principal open problem is evaluation, especially benchmark leakage in the language model era.
