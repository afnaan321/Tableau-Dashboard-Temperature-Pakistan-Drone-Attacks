Documentation:
Data Sets chosen over the region of Pakistan.
Data Sets information and Background information:
Relation between terrorism and counter terrorism with temperature and over all affect of these 
actions on the people.
The data sets used were:
  a. GlobalLandTempraturesByCountry
  b. PakistanSuicideAttacks Ver 11 (30-November-2017) 
  c. PakistanDroneAttacksWithTemp Ver 11 (November 30 2017) 
The data set other than Berkely were taken from Kaggle, posted by Mr. Zeeshan Usmani a renowned
Pakistani Data scientist. Many versions of the data sets were available, however the latest versions 
were selected. 
  Since the Berkely data set only has date values from only the first of each month, the other two data 
sets were split to a granularity of Months and years. Then all three of them were joined, Null values, 
and un-formed data was cleaned in tableau prep. The final data set is also attached, namely TEMP_ 
DRONE_SUICIDE_PAK_DATA. Available as both a tableau extract and a csv.
The general relation that can be drawn with temperature and suicide bombings is that in winters 
when the temperatures are low. People wear heavy jackets and clothes that are hefty, making it 
easier for the culprits to hide themselves among crowds. Resulting in an increased numbers of blasts 
in winter. 
Story 1:
  Dashboard 1:
    Question Addressed: What Level of sensitivity and category of people are targeted in different 
    months?
      Monthly Total average temperature tells us the number of blasts. Greater the Total average 
      temperature, greater would be the number of entries meaning that in that month the number of 
      blasts occurred is greater. Following these trends and keeping the sensitivity level of location in mind, 
      High sensitivity areas are attacked in months with a rather harsh climate. i.e., extreme cold or 
      extreme summers. Targets in these conditions are usually military areas.
  Dashboard 2:
    Question Addressed: Which province & city has had more of what, terrorism or counter terrorism
    and what can be drawn from that relation?
      Very rarely Suicide Bombs have been more in number than Drone strikes against them, why is that?
      Drone strikes have been in great number in regions which are closer to the Afghan border, are not 
      necessarily more populus and don’t have a surplus of revenue generated for the nation. 
Story 2:
  Dashboard 3:
    Question Addressed: When are people more injured, in Drone attacks or Suicide Bombings? And can 
    it be related to temperature uncertainty?
      Overall relation depicts that more civilians are injured in suicide bombings. And interestingly the 
      more stable the temperature has been for a few months, the injured number of people rise. 
      An inverse proportionality can be drawn of injured people and temperature uncertainty.
  Dashboard 4:
    Question Addressed: Is there a Pattern of Suicide Bombs in provinces and Type of Day Pattern of 
    Blasts recognition and comparison?
      We can compare multiple provinces and see in which types of days are likely to be experience a 
      suicide bombing. 
      We can also see that in which province, there is a prejudice among sects and can compare death 
      tolls.
Conclusion:
Through keen observing of the visualization, we can conclude that:
    a. The months in which the temperature is pleasant, i.e., autumn and spring season. The 
    number of blasts increase, and the sensitivity of locality is not high. These are the months in 
    which civilians are most outside the confinements of their homes. The majority target places 
    include Parks and grounds. This is also pointing to the fact that the number of casualties also 
    increase among low sensitivity areas.
    b. It is rarely observed that the Counter terrorism (Drone Strikes) acts are fewer in number than 
    Terrorist attacks(Suicide Bombs). However the casualties and affecties are more affiliated to 
    Suicide bombs. Ergo Drone strikes although having more explosive weight manage to keep 
    the civilian loss at a minimum
