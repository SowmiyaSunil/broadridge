•  Importing JSON Data: Importing JSON array where each object contains date and commits for that date. I have stored only few date as the file is too large
•  Initialize Variables: Initializing variables to check maximum and minimum number of commits. Listing max_dates and min_dates to store date corresponding to max and min commits.
•  Loop: 
	Iterate over the list of commits
	Update the max_Comits & max_date if the current number of commits exceeds the previous maximum commit and date.
	Update the min_Comits & min_date if the current number of commits is less than the previous min commit and date.
	If  multiple dates have the same number of commits: appending the date to the respective list.
•  Printing Results: print the dates with the maximum and minimum commits along with the total number of commits on those dates.
