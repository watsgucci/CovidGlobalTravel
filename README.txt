Software: 
Git
Jira
IntelliJ
Sublime

5 top countries traveled to per continent 

1.Which country are you visiting? 
	a. Valid   ⇒ If country is within list (Maybe multiple country option)
		i. Requirements are presented according to the valid country. (They are not going to be the same for each one)
			1. Do you have a covid test from 48 hours
			2. If no, return invalid (step b.) 
			3. If yes, continue to 1.a.ii
		ii. Are you a citizen/resident?
			1. If Yes 
				a. continue to the next step iii. 
			2. No
				a. Are you flying for business/government?
					i. Yes
						1. Do you have government papers to fly?
							a.If yes continue to step iii
					ii. Return invalid


	b. Invalid => If country is not within list
		i. Would you like to select another destination? 
			1. Yes => Program re-runs
			2. No => Program stops


2. Interface (UI)
	a. Creating a user account.
		i. Full Name
		ii. Email
		iii. Where they are from: Country, City
		iv. Username
		v. Password
	b. Get updates from the site.
	c. Saving the User info
	d. GRAPHIC FRONT END
