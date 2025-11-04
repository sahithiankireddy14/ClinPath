## ClinPath: Knowledge Graph with LLM Reasoning For Understanding Clinical Interactions
We present ClinPath, a holistic multimodal
framework that combines knowledge graph
modeling with large language model (LLM)
reasoning to represent and evaluate the en-
tire clinical journey. Built on the MIMIC-IV
database, we first introduce Clin-KG, a com-
prehensive knowledge graph that integrates di-
agnoses, symptoms, medications, procedures,
demographics, and provider interactions into
a unified view of patient care. Unlike prior
approaches that construct narrow, diagnosis-
focused graphs, Clin-KG captures the full spec-
trum of interactions spanning a patient’s care.
The LLM reasoning layer built on top of Clin-
KG demonstrates the utility of this framework
through both an established application of pa-
tient similarity analysis evaluated on our cus-
tom benchmark ClinPath-SimBench as well as a
novel application of provider behavior analysis.
These use cases highlight how graph-structured
information, enriched with LLM reasoning, can
yield clinically meaningful insights across mul-
tiple aspects of the care journey. While our
evaluation was conducted on MIMIC-IV, the
framework is designed to be adaptable to other
healthcare institutions through their respective
EHR systems, providing a reusable foundation
for understanding diverse clinical interactions.

This work was recently accepted to Machine Learning for Health (ML4H) Proceddings Track 2025. 
