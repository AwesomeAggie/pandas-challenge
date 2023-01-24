# pandas-challenge

For this challenge I was given excel data for schools and required to make many different ways to compare the data. This can be seen by looking at the panda file PyCitySchools_starter.ipynb.  The first thing that was done was merge the data into one dataframs instead of two excel sheets. Once the data was merged it was more easily accessible to access. The next process was to convert the data away from individuals and into sums so that we could analyze the data not by students but by schools. Once everything was combined we had a district summary.

Seeing data in a district is great but to make anlysis of the data we needed to break it back down into individual schools to see how they were doing compared to district averages. The way we did this is seen in the school summary file as we broke up all the schools into individual rows as seen in the final table of the area. 

Now that we had data we could compare we wanted to see who has the highest overall passing. 
Highest PerformingPNG.PNG
Grabbing the top five what we notice is that the type of schools for highest passing were all Charter Schools. 

Noticing this we want to see what the five lowest are. When we grab this we notice that all of the five lowest are District Schools. 
Lowest Performing.PNG
This would lead us to believce that Charter Schools in the School District are preforming better that District Schools. 

To make sure this is the case at the bottom we have a Scores by School Type section. 
Scores by School.PNG
When comparing Charter Schools to District Schools wew can clearly see that Charter schools overall passing rate of 90% is far better that District Schools overall passing rate of 54%. This is the first conclusion we can draw from the data.

Now that we know Charter Schools are performing better than Distrcit Schools we would want to check if the data can help us see why. My first assumptioon would be to follow the money. However, when looking at the 5 best and worst again we can notice that only Thomas High School in the Charter has over $625.00 per student where as all the five lowest performing schools have over that much per student. We look at the budget column and see all the district schools also have far greater budgets. Something about this does not add up money wise.

Looking further we can see the reason is Total Students. On average the Charter Schools have far lower student counts that the District Schools. This is what we can gleam as to why Charter Schools perform better than District Schools as a whole. The highest student count for a Charter School is Wilson High School at 2283 while the lowest student count for a District School is 2739 at Ford High School. Coincendently Ford High has the second highest overall passing out of the District Schools though this data seems negligible because all the District Schools passing rates are less than 2% points apart.

Going further in we can see that all Distrcit Schools overall passing is under 55% while all Charter Schools overall passing is above 89%. While we can see that the Charter Schools are better and that it would seem to be because of a lower student count we cannot see if that is the only reason. There could be other reasons that the data cannot tell us as currently constructed. For instance what is the teacher to student ratio. If the Charter Schools students get more individual attention is that why they are performing well. We can guess that by student count but we do not know for sure. Could there be better teachers at Charter Schools because they pay the teachers more? Again we do not have access to salary data so this is just speculation. One last thing is how they are run which is somethin no amount of data can really show us. We just know in general that Charter Schools and District Schools have different rules.

There could be many other factors playing into this data but from what we have we can conclude that first Charter Schools perform better than District Schools and second a reason behind this is total student volume is lower in Charter Schools.