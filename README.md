[README.txt](https://github.com/user-attachments/files/25795746/README.txt)
Read-me file to accompany 'Gut microbiome diversity correlates with reversal learning in hybridizing songbirds' 
Authors: Austin C. Russell*, Joan C. Spinelli, Noel Martinez, Robert L. Curry, Robin D. Johnsson, Timothy C. Roth II, Georgy A. Semenov, Scott A. Taylor, Amber M. Rice
*corresponding author: Austin's email address?

This read-me file describes the variables contained in each of the data files submitted to accompany this manuscript.

File: Cognition_Script_forMS.Rmd
Description: R code for analyzing microbiome sequence data, subsequent statistical analyses, and production of figures for the manuscript. Comments about code are made using hashmarks (#). 


File: cognition_metadata.csv
Description: Contains chickadee ancestry assignment, sex, nest location, collection year, behavioral results, and sequencing file names containing 16S rRNA sequences.

sampleID: identifier for each chickadee host individual

seq_file: name of fastq file containing 16S rRNA sequences from this chickadee host fecal collection

wgs.class: ancestry category assigned to each chickadee host based on hybrid index and interspecific heterozygosity values as calculated from chickadee whole genome sequences. The four categories include BCCH (black-capped chickadees), HYCH (recent generation hybrids), ADV.CA (advanced-generation Carolina backcrossed individuals), and CACH (Carolina chickadees).

Sex: Sex of the chickadee host. The two categories include M (male) and F (female).

Nest: Nesting snag ID, indicating from which  nest the chickadee nestling was collected.

Nest_Site: Collection site containing the source nest of each nestling. The sites span across the hybrid zone. From north to south, they include: GameLands129 (State Game Lands 129), HickoryRun (Hickory Run State Park), TwinLakes (Twin Lakes County Park), Tuscarora (Tuscarora State Park), Jacobsburg (Jacobsburg State Park), SouthMtn (South Mountain on Lehigh University campus), Desales (DeSales University), Nockamixon (Nockamixon State Park), PeaceValley (Peace Valley Park), and Nolde (Nolde Forest State Park).

PS_Test1_solve: elapsed time (in seconds) for bird to obtain the worm by pushing the transparent covering from the side. If the bird failed to solve on the first testing day, then this value is the sum of 3600 seconds (from the first day) plus the number of elapsed seconds from the second day. If bird failed both days, this value equals the max time of 7200 seconds (2 hours)

meanAL_day2to7_score: Mean number of inspections required to find worm across test days 2-7 for each bird. Maximum of 15 inspections per day; minimum of 1 inspection per day. If bird did not find worm within maximum time allowed, a score of 15 was given for that day. NA given if video malfunction, etc. Average was taken across all 6 test days (unless NA present).

meanRL_day2to7_score: Mean number of inspections required to find worm across test days 2-7 for each bird. Maximum of 15 inspections per day; minimum of 1 inspection per day. This test was run immediately after the associative learning test, so "day 1" is the first day that the bird had the opportunity to find the worm in its new location. If bird did not find worm within maximum time allowed, a score of 15 was given for that day. NA given if video malfunction, etc. Average was taken across all 6 test days (unless NA present).

Collection_year: Year nestling was collected and behavioral tests were conducted. Years include 2021 and 2022.  

