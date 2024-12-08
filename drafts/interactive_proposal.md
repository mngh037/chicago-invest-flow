**Name**: Minh Nghiem

# Proposal 1

**Project Description**

Interactive dashboard of large-scale data breaches

Data source: https://docs.google.com/spreadsheets/d/1i0oIJJMRG-7t1GT-mr4smaTTU7988yXVz8nPlwaJ8Xk/edit?gid=2#gid=2 

The data source is a compiled list of large-scale data breach incidents from 2004-2024. An additional dataset on relevant company size is what I was looking for and thought would be nice to add, but have been unable to find one or any potential proxy for one.

Because a visualization has been done using this dataset, I'm linking the main article here as implementation will likely be built upon what has been done here with modifications: https://informationisbeautiful.net/visualizations/worlds-biggest-data-breaches-hacks/ 

I plan on incorporating xy coordinates with sorting and various filtering toggles, similar to what's achieved in this visualization (instead of year animation, I'm thinking of doing just a drop down option for year): https://www.google.com/publicdata/directory 

I'd also like to do something with a scroll functionality to help guide the narrative before ending at the one big interactive component that viewers could interact with, a bit like this one: https://pudding.cool/2024/10/abortion-mazes/ 

=> Option A is probably what I'm aiming for.

**Some concerns**

1. I have a lot of uncertainty starting this one (already spending 4 hours looking around), as I'm not sure if Option A is something I could pull off (I have very low confidence on D3, HTML, JS, and CSS evem after all that we have seen in class). It's hard to be creative when you don't know what's within the range of possible (I may not have seen enough interactive viz to have an inspiration). That being said, the existing proposal is the "safe bet" ie something I'm settling for for now as I look more for a dataset that's more "original". Would this (getting processed data and basing the skeleton of the work on existing data viz to hopefully "improve" it with some modification and added narratives) be acceptable? Or does it have to come from an original dataset?

2. I'm having a hard time identifying dataset+topic I want to present as I can't yet figure out the narratives I want to put across (writer block equivalent?) I'll continue to try to come up with another option for your feedback asap if that's okay.

**Mockup**
![interactive_mockup](./scratch/interactive_mockup.jpg)

# Proposal 2

**Project Description**
Interactive Dashboard of Investment Flow in Chicago: Where does the money go?

Data Source: https://datacatalog.urban.org/dataset/exploring-capital-flows-chicago 

The data examines different type of investments among communities in Chicago, scaled in different units (e.g. households, employees, etc.) to enable cross comparison at the tract level. Two key components that it studies is the racial and poverty disparities shown through the flow of development money that goes into these communities.

The final deliverable I'm thinking would be a mix of graphs with some degree of interactivity (narrative on one side and graphs on the other side) for some lead-in introduction with the users moving along by scrolling up for backward and down for forward. I'm thinking it could be similar to what's done here: https://pudding.cool/2024/10/abortion-mazes/

The story-telling above would lead viewers to one final big interactive component that's a map of Chicago with boundaries drawn at the community/neighborhood level and each tract colored in accordance with the aggregate investment it receives (in percentile terms). I'm thinking the different source of investment flow could either be a filter option to apply to all of the map, or something that can be displayed upon clicking on the tract. Right now I'm thinking majority race and poverty level could be reflected with that box also, but wanted to include in the map somehow that it is spelled out as soon as you look at it--something like, "this community is majority Black but is receiving significant less investment than its neighboring tracts/community that is made up mostly of White". The map would look like something like this: https://experience.arcgis.com/experience/6165e79d28a44f059dc7c76e2a863492/page/Summary-Statistics-2/?views=Community-Areas

=> I think option B would be suitable given the above description of what I have in mind for this project.

**Questions**

1. The data is in percentile term at the tract level. Is there anyway (or does it even make sense to) I can aggregate them to present the information at the community/neighborhood level?

2. Regarding presenting majority race and poverty info of a given tract without any hovering or clicking so it could be viewed as a whole the instant you look at the map (as mentioned above), do you have an idea on how I could do that? Is it something that could/should be done or is there any other sensible approach I could consider?

3. What are your general thoughts on the two proposals? Which do you think would be more suitable to pursue, given the timeframe and my own lack of past experience with HTML, JS, CSS, and D3?

**Mockup**
![interactive_mockup_2](./scratch/interactive_mockup_2.jpg)