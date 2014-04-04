#Formal methods
Formal methods = formal specification + formal verification
  
Formal specification (FS)
- As part of defect prevention
- Formal => prevent/reduce defect injection due to imprecision, ambiguity, etc
- Briefly covered as related to FV

Formal verification (FV)
- As part of QA, but focus on positive
  "Prove absence of fault"
- People intensive
- Several commonly used approaches


#Formal Specification: Ideas
Formal specification
- Correctness focus
- Different levels of details
- 3Cs: complete, clear, consistent
- Two types: descriptive & behavioral

Descriptive formal specifications
- Logic: pre-/post-conditions
- Math functions
- Notations and language support: Z, VDM, etc

Behavioral formal specifications: FSM, Petri-Net, etc

#Formal Verification: Ideas
"Testing shows the presence of errors, not their absence." -- Dijkstra

Formal verification: proof of correctness
- Formal specs: as pre/post-conditions
- Axioms for components or functional units
- Composition (bottom-up, chaining)
- Development and verification together

Other related approaches
- Semi-formal verification
- Model checking
- Inspection for correctness

#Formal Verification Basics
Basic approaches
- Floyd/Hoare axiomatic
- Dijkstra/Gries weakest precond (WP)
- Mills’ prog calculus/functional approach

Basis for verification
- logic (axiomatic and WP)
- mathematical function (Mills)
- other formalisms

Procedures/steps used
- bottom-up (axiomatic)
- backward chaining (WP)
- forward composition (Mills), etc

#Model checking
- Behavioral specification via FSMs
- Proposition: property of interest expressed as a suitable formula
- Model checker: algorithm/program to check proposition validity
- Proof: positive result
- Counterexample: negative result

