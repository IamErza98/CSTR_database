# CSTR_database
This repository hosts the database of a Continuously Stirred Tank Reactor (CSTR) used in "An Optimization Approach To Select Koopman Observables For Data-based Modeling Using DMDc".

Description:
	The CSTR problem involves a chemical process where two reactants are mixed and react to generate compound A within a mixture at temperature T. The reaction is exothermic, meaning it releases heat, which slows the reaction rate as the process progresses. To regulate the temperature and, consequently, the reaction rate, a coolant flow is introduced, allowing for control of both the temperature and concentration.
Sampling:
	0.1 min
Number of samples:
	7500
Inputs:
	q: Coolant Flow l/min
Outputs:
	Ca: Concentration mol/l
	T: Temperature Kelvin degrees
Columns:
	Column 1: time-steps
	Column 2: q
	Column 3: Ca
	Column 4: T
