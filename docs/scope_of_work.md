# Scope of work - Requirements

`
Scope of work:

Web API URL’s for the below API’s
 
1.	Roster Details
a.	Parameter: Start Date, End Date
b.	Returns:   Power Force ID, Site Code, Employee Code, Start Time, End Time, Shift Confirmation, Actual Sign-In and Sign-Out, Job Date

2.	Create Roster
a.	Parameter: Site Code, Employee Code, Start Time, End Time, Job Date
b.	Returns: Power Force ID

3.	Edit Roster
a.	Parameter: Power Force ID, Site Code, Employee Code, Start Time, End Time, Job Date
b.	Returns: Power Force ID

4.	Confirmed Roster
a.	Parameter: Power Force ID, Status
b.	Status    
i.	1: Accepted
ii.	2:  Rejected

5.	Actual sign in - sign out roster
a.	Parameter: Power Force ID, Sign In, Sign in Comments,  Sign Out, Sign Out Comments
b.	Status    
i.	1: Accepted
ii.	2:  Rejected

6.	Delete Roster
a.	Parameter: Power Force ID

7.	Replacement Roster
a.	Parameter: Old Power Force ID, Site Code, Employee Code, Start Time, End Time, Job Date
b.	Returns: Power Force ID

`