# NDSRtoNOVA
This code calculates the percentage of calories or grams from each NOVA classification of food consumed by a participant. 

Use file 1 from NDSR.  
Assign a NOVA score each food consumed.  I deduped the tab-delimited output file and created a list of each food that we needed to classify.  

Note:  After you create the NOVA scores for all the foods, you will then reshape a subset of the dataframe from long to wide so that each participant (or observation) has its own line.  You will then need to merge this with an NDSR output file that has each participant's (or observation's) total kcal and total gram as a column/variable.  Because I separately used NDSR files 4 and 9 to calculate other diet pattern scores, I merged into that dataframe for this part.  
Before merging, make sure that your file 1 data and merge-to file have the exact same participant/observations.  
