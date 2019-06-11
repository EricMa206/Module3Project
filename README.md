# Mod_3_Project

## Background ##

For this project we chose to study the roll call (yay or nay voting) in the U.S. House and U.S Senate for the 2018 First Step Act.

The First Step Act or The Formerly Incarcerated Reenter Society Transformed Safely Transitioning Every Person Act "reforms the federal prison system of the United States of America, and seeks to reduce recidivism. An initial version of the bill passed the House of Representatives (360–59) on May 22, 2018;[1] a revised bill passed the U.S. Senate (on a bipartisan 87–12 vote) on December 18, 2018.[2] The House approved the bill with Senate revisions on December 20, 2018 (358–36). The act was signed by President Donald Trump on December 21, 2018, before the end of the 115th Congress.[3] The act, among many provisions, retroactively applies the Fair Sentencing Act, allows for employees to store their firearms securely at federal prisons, restricts the use of restraints on pregnant women, expands compassionate release for terminally ill patients, places prisoners closer to family in some cases, authorizes new markets for Federal Prison Industries, mandates de-escalation training for correctional officers and employees, and improves feminine hygiene in prison."[4]

Our goal was to determine if factors such as the number of legislators home state private prisons, acceptance of PAC donations from private prison PACs or crime rates in their state influenced whether a legislator voted yay or nay.

## Hypotheses ##

We set up our hypotheses as:

H1 - The First Step Act is significantly different bill from the norm for the 115th congress in terms of receiving more votes than the mean - didn’t test

H2 - The difference in how legislators voted is significantly affected by whether they took PAC donations from the private prison PAC.

H3 - The difference in how legislators voted is significantly affected by whether there are more private prisons in their state.

H4 - The difference in how legislators voted is significantly affected by whether the crime rates are high or low in their home state.


## Data Sets ##

- Senate roll call data for the 2nd Session of the 115th Congress
- House roll call data for the 2nd Session of the 115th Congress
- PAC donations to Senators from Core Civic (private prison)
- PAC donations to Representatives from Core Civic (private prison)
- PAC donations to Senators from GEO Group (private prison)
- PAC donations to Representatives from GEO Group (private prison)
- U.S. Federal Prisons
- U.S. Crime Rates


We began by using the Propublica API to request the roll call for the First Step Act for both the House and the Senate. We downloaded the json file and created data frames for each set of data.

Using data from opensecrets.org, we created csv files of all the 2016 and 2018 GEO Group and Core Civic PAC donations to members of Congress. This data also included donations to those running for Congress which we did not end up using.


We used the Bureau of Prisons API to request the locations of all the U.S. Federal prisons. This dataset also included Federal private prisons. Again, we created a dataframe with the data in the json file.






1. Collins, Doug (23 May 2018). "First Step Act". Actions – H.R.5682 – 115th Congress (2017–2018). Congress. Retrieved 21 December 2018.
2. Sullivan, Dan (21 December 2018). "First Step Act of 2018". S.756 – 115th Congress (2017–2018). Congress. Retrieved 21 December 2018.
3. "Trump signs bipartisan criminal justice overhaul First Step Act into law", The Guardian, December 21, 2018.
4. Wikipedia
