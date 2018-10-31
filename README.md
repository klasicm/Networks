# Networks
This repo contains code and details on working with networks

FormattingNestedCellsIntoEdgeListwithAttributes: If you had someone going through a text document looking for governance actors and governance relationships to create network data and you didn't want to use a text coding software program (or R) you might have them filling out an excel sheet where:
Each row is an excerpt of text from the document
Each row contains data on the text excerpt, the document name, the date of the document, then a cell with a comma-separated list of actors, followed by a column with the relationship shared by all of those actors.

This particular script takes data of this format (test.csv, dummy data) and provides code that will take each of those rows and:
1. Separate out the comma-delimited actors list onto separate rows
2. Find all the possible combinations of those actors
3. Group the data by Excerpt/Document/Date/Relationship 

In the end you have a dataframe with the descriptive data (excerpt, doc name, date, relationship) as well as two columns formatted as an edge list for use in R to create networks.



