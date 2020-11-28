# Welcome to **Travel Guide Application**
# made in collaboration of group-31
# of Cybertek's batch-21 students

This application was made in use of next software:
- Git
- Jira
- IntelliJ
- Sublime

Please look for markdown syntax [here](chrome-extension://oemmndcbldboiebfnladdacbdfmadadm/https://guides.github.com/pdfs/markdown-cheatsheet-online.pdf)

5 top countries traveled to per continent

1. Which country are you visiting?

  a. Valid =>  If country is within list (Maybe multiple country option)

  i. Requirements are presented according to the valid country. (They are not going to be the same for each one)

  - [ ] Do you have a covid-19 test from 48 hours
  - [ ] If no, return invalid (step b.)
  - [ ] If yes, continue to 1.a.ii

  ii. Are you a citizen/resident?

  - If Yes

    - continue to the next step iii.

  - If No

    - Are you flying for business/government?

        i. Yes

          - Do you have government papers to fly?

            * If yes continue to step iii

  iii. Return invalid

  b. Invalid => If country is not within list

    i. Would you like to select another destination?

      1. Yes => Program re-runs
      2. No => Program stops


2. Interface (UI)

  a. Creating a user account.

    - Full Name
    - Email
    - Where they are from: Country, City
    - Username
    - Password

  b. Get updates from the site.

	c. Saving the User info

	d. GRAPHIC FRONT END
