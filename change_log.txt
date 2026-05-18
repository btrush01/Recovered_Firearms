Data Cleaning to-do List:


Firearm Manufacturer:
-Observed Smith & Wesson is represented with both the "&" and the word "and". Check unique entries, and combine values with similar discrepancies.

Firearm Model:
-Check unique values to ensure like entries are counted together.

Firearm Caliber:
-Weapons with no specified caliber represent 1492 entries. Rename them to "Unknown".

Recovery Address:
-Describes where recovered weapons were taken by the Police.
-Drop this column entirely. I can think of no useful analysis involving it.

City, State
-Drop these columns entirely, since almost all firearms were recovered in Louisville and/or Kentucky.

Person Recovered From Sex
-Drop the U and NaN slices, and present the pie chart with just Male and Female

Year:
-2008 and 2009 account for only 6 of the 14851 total recovered firearms. Consider dropping them.
-Alternatively, merge 2008 and 2009 with 2017, which is also underrepresented with just 531 recovered firearms recorded.




Stretch Goals:

Recovery Date:
-Zoom out from individual days to view recovery by month for each year.
