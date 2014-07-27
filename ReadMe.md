* Introduction

Fine particulate matter (PM_{2.5}) is an ambient air pollutant for which there
is strong evidence that it is harmful to human health. In the United States, the
Environmental Protection Agency (EPA) is tasked with setting national ambient
air quality standards for fine PM and for tracking the emissions of this
pollutant into the atmosphere. Approximatly every 3 years, the EPA releases its
database on emissions of PM_{2.5}. This database is known as the National
Emissions Inventory (NEI). You can read more information about the NEI at the
[[http://www.epa.gov/ttn/chief/eiinformation.html][EPA National Emissions Inventory web site]].

For each year and for each type of PM source, the NEI records how many tons of
PM_{2.5} were emitted from that source over the course of the entire year. The
data that we use for this assignment are for 1999, 2002, 2005, and
2008. The data is available [[https://d396qusza40orc.cloudfront.net/exdata%252Fdata%252FNEI_data.zip][here]].

* Goal
The overall goal is to explore the National Emissions Inventory database and see
what it say about fine particulate matter pollution in the United states over
the 10-year period 1999-2008.

* Questions

- Have total emissions from PM_{2.5} decreased in the United States from 1999 to
  2008?

  [[./plot1.png]]

- Have total emissions from PM_{2.5} decreased in the Baltimore City, Maryland
  from 1999 to 2008?

  [[./plot2.png]]

- Of the four types of sources indicated by the =type= (point, nonpoint, onroad,
  nonroad) variable, which of these four sources have seen decreases in
  emissions from 1999-2008 for Baltimore City? Which have seen increases in
  emissions from 1999-2008? 

  [[./plot3.png]]

- Across the United States, how have emissions from coal combustion-related
  sources changed from 1999-2008?

  [[./plot4.png]]

- How have emissions from motor vehicle sources changed from 1999-2008 in
  Baltimore City?

  [[./plot5.png]]

- Compare emissions from motor vehicle sources in Baltimore City with emissions
  from motor vehicle sources in Los Angeles County, California. Which city has
  seen greater changes over time in motor vehicle emissions?

  [[./plot6.png]]

