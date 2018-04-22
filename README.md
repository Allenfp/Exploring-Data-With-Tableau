# Data Exploration With Tableau

## NYC bike share data. 

The Purpose of this project was to become framiliar with Tableau as an analysis tool and to get comfortable with dealing in extremely large and messy datasets. [NYC bike share data](https://s3.amazonaws.com/tripdata/index.html) is available in a monthly downloadable CSV that, on more than one occation, has experienced subtle changes to its structure. 

The downloads were performed using python and jupyter notebooks, CSV files were combined using BASH, a 5% random sample was produced using Pandas, and the various issues with datetime datatype was resolved using Python and Pandas. Finally the data was loaded into, and analyzed with, Tableau.

The original dataset contained ~53 million rows. Due to the limits of my computer, a random sampling of 5% was used (~2.7 million rows). Due to GitHub's data storage policy, even the sample data could not be stored (It was over a gig, even compressed). To recapture the data, simply run the jupyter notebook script that is also included. 

### Please note:
Many of the details (such as numbers values and descriptions) are only visible upon the cursor hovering over the worksheet elements, and thus are not visible in the PDF format. Sorry!
