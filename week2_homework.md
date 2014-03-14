#Summary

##Defect Measurement and Analysis
	###Defect measurement:
		parallel to defect handling
		where injected/found?
		type/severity/impact?
		more detailed classification possible?
		consistent interpretation
		timely defect reporting

	###Defect analyses/quality models
		as followup to defect handling.
		data and historical baselines
		goal: assessment/prediction/improvement
		causal/risk/reliability/etc. analyses

##Mega-process:
	initiation, development, maintenance, termination.
	Development process components:
	requirement, specification, design, coding, testing, release.
##Process variations:
	waterfall development process
	iterative development process
	spiral development process
	lightweight/agile development processes and XP (extreme programming)
	maintenance process too
	mixed/synthesized/customized processes
	QA important in all processes

##Process variations (not waterfall) and QA:
	iterative: QA in iterations/increments
	spiral: QA and risk management
	XP: test-driven development
	mixed/synthesized: case specific

##SQE and QIP
###QIP (quality improvement paradigm):
	Step 1: understand baseline
	Step 2: change then assess impact
	Step 3: package for improvement
###QIP support:
	overall support: experience factory
	measurement/analysis: GQM (goal-question-metric paradigm)
	SQE as expanding QA to include QIP ideas.

##Pre-QA planning:
	###Quality goal
	Overall QA strategy:
	QA activities to perform?
	measurement/feedback planning
	Setting quality goal(s):
	Identify quality views/attributes
	Select direct quality measurements
	Assess quality expectations vs. cost
##Setting Quality Goals
	Identify quality views/attributes
	customer/user expectations,
	market condition,
	product type, etc.
	Select direct quality measurements
	direct: reliability
	defect-based measurement
	other measurements
	Assess quality expectations vs. cost
	cost-of-quality/defect studies
	economic models: COCOMO etc
##Forming QA Strategy
	QA activity planning
	evaluate individual QA alternatives
	strength/weakness/cost/applicability/etc.
	match against goals
	integration/cost considerations
	Measurement/feedback planning:
	define measurements (defect & others)
	planning to collect data
	preliminary choices of models/analyses
	feedback & followup mechanisms, etc.
##Analysis and Feedback
	###Measurement:
		defect measurement as part of defect handling process
		other data and historical baselines
	###Analyses: quality/other models
		input: above data
		output/goal: feedback and followup
		focus on defect/risk/reliability analyses
	###Feedback and followup:
		frequent feedback: assessments/predictions
		possible improvement areas
		project management and improvement
		
##Testing: Key questions:
Why: quality demonstration vs. defect detection and removal
How: techniques/activities/process/etc.
View: functional/external/black-box

##When to Stop Testing
	###Resource-based criteria:
		Stop when you run out of time.
		Stop when you run out of money.
		Irresponsible ) quality/other problems.
	###Quality-based criteria:
		Stop when quality goals reached.
		Direct quality measure: reliability
			resemble actual customer usages
	Indirect quality measure: coverage.
	Other surrogate: activity completion.
	Above in decreasing desirability.

##Usage-Based Testing and OP
	###Usage-based statistical testing:
		actual usage and scenarios/information
		captured in operational profiles (OPs)
		simulated in testing environment
		(too numerous => random sampling)
	###Applicability
		final stages of testing.
		particularly system/acceptance testing.
		use with s/w reliability engineering.
	Termination criteria: reliability goals

##Coverage-Based Testing
	###Coverage-based testing:
		systematic testing based on formal (BBT/WBT) models and techniques
		coverage measures defined for models
		testing managed by coverage goals
	###Applicability
		all stages of testing.
		particularly unit and component testing.
		later phases at high abstraction levels.
	###Termination criteria: coverage goals

##Steps in Systematic Testing
	###Instantiation of Fig 6.1 (p.69)
		with a formalized strategies/goals,
		based on formal models and techniques,
		managed by termination criteria.
	###Steps in model construction and usage:
		Define the model, usually represented as graphs and relations.
		"Check" individual elements:
		"Test": derive (sensitize) test cases and then execute them.

#Rate For Students
张亚华 (13126173) A

张亚宾 (13126172) A

臧凯源 (13126167) A

于铠瑞 (13126164) A

孙百仪 (13126128) A
