#Input Domain partitioning

##Basic concepts:
Divide into sets of sub-domains.
"domain", "sub-domain", and "region" often used interchangeably


##definitions:
A sub-domain is typically defined by a set of conditions in the form of:
f (x1; x2; ... ; xn) < K
where "<" can also be substituted by ">","=", "<>", "<=", or ">=".

##terminology:
Domain (sub-domain) boundaries:
	Distinguishes/defines different sub-domains.
	Each defined by it boundary condition,
	e.g., f (x1; x2; ...; xn) = K
	Adjacent domains:
	those share common boundary(ies)
Closed boundary: inclusive (<=, >=)
Open boundary: exclusive (<, >)
Closed domain: all boundaries closed
Open domain: all boundaries open
Interior point: in domain and not on boundary.
Exterior point: not in domain and not on boundary.


#Input Domain partitioning Testing

##General steps:
Identify input variable/vector/domain.
Partition the input domain into sub-domains.
Perform domain/sub-domain analysis.
Define test points based on the analysis.
Perform test and followup activities.

##definitions:
Boundary testing: Above with focus on boundaries.
Domain analysis:
Domain limits in each dimension.
Domain boundaries (more meaningful).
Closure consistency?
Plotting for 1D/2D, algebraic for 3D+.

##terminology:
Extreme point combinations (EPC):
	Combine above to derive test points.
	Combine variables ((cid:2), cross-product).
	# testcases: 4^n + 1.


