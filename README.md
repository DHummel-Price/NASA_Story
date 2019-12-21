# How do NASA Contracts relate to the locations of NASA centers and Congressional Budget committee assignments? 

For over 60 years, the National Aeronautics and Space Administration ([NASA](https://www.nasa.gov/)) has lead humanity's efforts to explore the air and space around us. NASA's research has led to countless inventions and technologies, and the organization has inspired many thousands of children to grow up to become scientists. As self-evident as the worth and importance of NASA might be, it still must fight for proper funding and support from the Federal Government. You can help NASA in this fight for resources by contacting your elected officials. As this article will demonstrate, NASA has stakeholders across the country, so every voter should engage with their represenation to express support.

## Find your Congressional District 
The first step in contacting your congressional representitives is knowing who they are. At the following link, you can look up your district and rep by entering your zip code: 

* [Click Here](https://www.house.gov/htbin/findrep) to look up Your Congressional representitive.  
* [Click Here](https://www.senate.gov/senators/index.htm) to look up your senators.  

Take a moment to write down your district and the names of your rep and two senators. This information is your most basic responsibilty as an informed voter and faciliates the next step, determining whether they sit on any relevant budget committees  

## Congressional Budget Creation 
The process by which the Federal government creates and approves the budget each year is not simple, but it can be boiled down into three parts:

* Part I: Presidential Budget Proposal created by the Executive Branch (The President)
* Part II: House and Senate Authorization Committees and Subcommittees
* Part III: House and Senate Appropriations Committees and Sucbommittees

This article focuses on the impact that you can have on parts 2 and 3 of the process by contacting your Senators and Representitives to express your support for NASA. A more complete explanation of the full process can be found on the Federal Government's website [here](https://www.usa.gov/budget). A primer is also included in the Planetary Society's free online course [Space Advocacy 101](https://courses.planetary.org/p/space-advocacy-101). The course is easy, modular, and only takes a few hours to complete. I highly recommend it. 


**Committees relevant to NASA**
Members of the budgeting committees have an outsized influence on NASA's budget. If your Senators and Representitives are on any of these committees, it is especially important for you to engage with them about NASA and space exploration. The Committess involved in establishing NASA's budget are the following:

* [The House Science, Space, and Technology Authorization Committee](https://science.house.gov/)
* [The House Space and Aeornautics Subcommittee](https://science.house.gov/subcommittees/space-116th-congress)
* [The House Commerce, Justice, Science, and Related Agencies Approprations Subcommittee](https://appropriations.house.gov/subcommittees/commerce-justice-science-and-related-agencies-116th-congress)

* [The Senate Commerce, Science, and Transportation Authorization Committee](https://www.commerce.senate.gov/)
* [The Senate Aviation and Space Subcommittee](https://www.commerce.senate.gov/aviation-and-space)
* [The Senate Commerce, Justice, Science, and Related Agencies Approprations Subcommittee](https://www.appropriations.senate.gov/subcommittees/commerce-justice-science-and-related-agencies)

**Why Your Voice Matters**
As the following will demonstrate, many districts and states have natural incentive to support NASA based on already extant facilities and contracts. However, these places do not entirely overlap with districts and states with relevent committee appointments. Speaking up to your elected representation is vital! The following uses NASA procurment data [(NASA PDV)](https://prod.nais.nasa.gov/cgibin/npdv/map.cgi) and data from the above committee links. For more information about how these data were cleaned, please view the cleaning word document and three cleaning Jupyter Notebooks in the [repo](https://github.com/DHummel-Price/NASA_Story) for this page.   

### NASA Centers are Scattered Across the Country
NASA has 10 field centers:

* Ames Research Center (ARC): Mountain View, CA  
* Armstrong Flight Research Center (AFRC): Edwards Air Force Base, CA  
* Glenn Research Center (GRC): Cleveland, OH  
* Goddard Space Flight Center (GSFC): Greenbelt, MD  
* NASA Headquarters (HQ): Washington, D.C.  
* Johnson Space Center (JSC): Houston, TX  
* Kennedy Space Center (KSC): Merritt Island, FL  
* Langley Research Center (LaRC): Hampton, VA  
* Marshall Space Flight Center (MSFC): Huntsville, AL  
* Stennis Space Center (SSC): Hancock County, MS

For more infomation about the focus of each center as well as additional NASA facilities, see [NASA's website](https://www.nasa.gov/about/sites/index.html).

The following maps break down these locations by state and by Congressional District.

<center><iframe seamless frameborder="0" src="https://public.tableau.com/views/ByStates/StateCentersDash?:embed=yes&:display_count=yes&:showVizHome=no" width = '100%' height = '420'></iframe></center>

<center><iframe seamless frameborder="0" src="https://public.tableau.com/views/ByDistricts/Centers?:embed=yes&:display_count=yes&:showVizHome=no" width = '100%' height = '320'></iframe></center>
  

### Geographic Diversity in NASA Contract Awards 
Now let's look at the geographic distribution of NASA contracts. The maps below show this distribution first by state and then by district. Note: the values used to create the maps are contract awards that have been put on a scale of order of magnitude for better readability. Hover over the map to see the specific award amounts.  

<center><iframe seamless frameborder="0" src="https://public.tableau.com/views/ByStates/StateAwardDash?:embed=yes&:display_count=yes&:showVizHome=no" width = '100%' height = '420'></iframe></center>

<center><iframe seamless frameborder="0" src="https://public.tableau.com/views/ByDistricts/Awards?:embed=yes&:display_count=yes&:showVizHome=no" width = '100%' height = '420'></iframe></center>


  
### Committee Membership  
Now let's look at where committee members are from. Notice that these do not neatly overlap with the location of the centers discussed above. 

<center><iframe seamless frameborder="0" src="https://public.tableau.com/views/ByStates/StateCommitteeDash?:embed=yes&:display_count=yes&:showVizHome=no" width = '100%' height = '420'></iframe></center>
  
<center><iframe seamless frameborder="0" src="https://public.tableau.com/views/ByDistricts/Committees?:embed=yes&:display_count=yes&:showVizHome=no" width = '100%' height = '420'></iframe></center>

### Drill-down: California
California has three different NASA centers; the map below isolates California for a more detailed look. 

<center><iframe seamless frameborder="0" src="https://public.tableau.com/views/ByDistricts/CaliDash?:embed=yes&:display_count=yes&:showVizHome=no" width = '100%' height = '420'></iframe></center>

## Relationships between Variables
The parallel coordinate diagrams below contain the three variables discussed above. A parallel coordinate diagram facilites comparison of more than two variables. If the award amount strongly coorelated with committee membership and the location of field centers, we would expect most of the lines to be somewhat horizontal, with minimal crossing. We do not see that in the below diagrams. The takeaway is that many different districts and states have a stake in NASA, so don't assume your district is unimportant! Use the highlighter tool to enter your state and district to highlight it in the plot. Note: Due to limitations of Tableau, the three variables have min-max scaled to place them on the same scale. Hover your mouse over any given line to see the absolute values. 

<center><iframe seamless frameborder="0" src="https://public.tableau.com/views/ByStates/ParallelDash?:embed=yes&:display_count=yes&:showVizHome=no" width = '100%' height = '400'></iframe></center>

<center><iframe seamless frameborder="0" src="https://public.tableau.com/views/ByDistricts/Parallel?:embed=yes&:display_count=yes&:showVizHome=no" width = '100%' height = '400'></iframe></center>

## A Call to Action  
As the above demonstrates, NASA has a large and diverse set of Congresspeople with incentive to support NASA. I encourage you take a moment right now to send a note to your elected representitives urging them to support NASA. Congressional Offices rarely hear from constitutents regarding space policy and NASA, so they will take more note of your correspondence than they might for other issues. Don't stress too much about what to say. Simply state that you are a registered voter who is passionate about NASA and space, and that you urge your rep to support NASA however they can. Your voice matters. Call, write, or visit your rep today! 

### Project Origination and Acknowledgements 
This project originally was developed for the Data Vizualization course as part of the author's Master of Science in Data Science for Public Policy degree program at the McCourt School for Public Policy at Georgetown University. Special Thanks to the Planetary Society for providing the background domain knownledge that inspired this project. The project would not be possible without the guidance of Taylor Corbett (<link to Taylor's page here>) and the other students in the course: Jean Landry Binam Keyanfe, Lixue Chen, Chandler Dawson, Zachary Gozlan, Eric LaRose, Yining Li, Ziqi Niu, Madeline Pickens, Andrea Cristina Quevedo Acuna, George Schoeffel, Harsh Sharda, Neha Tiwari, and Lily Yue. (Links for anyone in the class who wants them?) 
