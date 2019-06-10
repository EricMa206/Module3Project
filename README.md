# Mod_3_Project

For this project we chose to study the roll call (yea or nay voting) in the U.S. House and U.S Senate for the 2018 First Step Act.

We set up our hypotheses as:

H1 - The First Step Act is significantly different bill from the norm for the 115th congress in terms of receiving more votes than the mean - didn’t test

H2 - The difference in how legislators voted is significantly affected by whether they took PAC donations from the private prison PAC.

H3 - The difference in how legislators voted is significantly affected by whether there are more private prisons in their state.

H4 - The difference in how legislators voted is significantly affected by whether the crime rates are high or low in their home state.




We needed the voting data for the 2nd Session of the 115th Congress - the Senate and the House, the total number of private federal prisons in the U.S., the 2016 PAC donations to Senators and Representatives that were roll call participants from the two largest private prison corporations (GEO Group and Core Civic) and crime data.

We began by using the Propublica API to request the roll call for the First Step Act for both the House and the Senate. We downloaded the json file and created data frames for each set of data.

We then used the Bureau of Prisons API to request the locations of all the U.S. Federal prisons, including Federal private prisons. Again, we created a dataframe with the data in the json file.

Using data from opensecrets.org, we created csv files of all the 2016 and 2018 GEO Group and Core Civic PAC donations to members of Congress (also included donations to those running for Congress.)

We needed to add 
