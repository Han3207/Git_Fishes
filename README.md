# Git_Fishes
## How to reproduce the project: 
Uploading it to the GitHub Desktop and then after collaborating the data can be cloned and thus, be reproduced neatly with the R running nicely. 

## Description of the workflow: 
The important filesa are the Git_Fishes file as it contains the R markdown, data, output, gitignore and README.file etc.
The major importants is the OA_activitydat_20190302_BIOL3207.csv data file and the git_fishes_student.Rmd file.
The output file contains the figure where we do not want this to be commited to the GitHub due to too much storage space taking. So, we need 'gitignore' file as well to help the GitHub ignore to not stage and commit the figure. 

## Meta-data description of the data columns and what they mean: 
----------------------------------------------------------------------
### This is found in the main data file 'OA_activitydat_20190302_BIOL3207.csv' data.
(Column Name - Description)
+ loc - Location, and year, where the data were collected. AIMS = Australian Institute of Marine Science; LIRS = Lizard Island Research Station
+ species	- Species name: acantho = Acanthochromis; Ambon = Pomacentrus amboinensis; Chromis = Chromis atripectoralis; Humbug = Dascyllus aruanus; Lemon = Pomacentrus moluccensis
+ treatment	- Elevated CO2 [CO2] (850-1,050 µatm) or control [Control] (400 - 450 µatm) groups
+ animal_id	- Fish identity
+ sl - Standard length of the fish in mm
+ size -	Size grouping of the fish, separated at 15 mm standard length into ‘big’ or ‘small’
+ activity - Number of seconds the fish was active per minute, averaged across the duration of the trial
+ comment -	Comment with notes on the origin of the data
