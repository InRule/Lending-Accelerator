# Mortgage Lending Kit
This rule application demonstrates all of the basic strategies and patterns for supporting LOS integrations.  I contains the following capabilities.

* Entity model based on the latest URLA from Fannie Mae and Freddy Mac (to be live by November, 2020).
* Totals calculate across primary collections such as assets, liabilities, etc.
* Flow control based on the standard "Controller Pattern" that uses top-level rule sets to route execution to lower-level rule set.
* A monthly payment calculation.
* Monthly payment amortization.
* Loan limit enforcement for single unit properties based on Fannie Mae's guidelines.
* APR calculation implementing the Newton Raphson (see the file APR_Formula.png).
* DTI enforcement for conforming loans.



