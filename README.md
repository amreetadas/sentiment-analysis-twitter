# sentiment-analysis-twitter
You will need Python, Tensorflow and Keras installed on your computer in addition to R to run the code. The installation guide can be found here:

https://tensorflow.rstudio.com/install/

(It might take a little bit of googling in addition to the steps above to cater to the requirements of your system.)

<!-- DH general comments

- I appreciate the setup note in this README.  Project organization also looks good. 

- The data files are large, and including them in the repo makes it slow to download.  It's also not immediately obvious how the contents of the `Data` folder match up with the Kaggle repos.  So, rather than tracking the data files in your project, I would recommend (1) including download instructions in this README, with (2) expected locations and filenames for each download.  

- I have lots of comments about style.  But I think my most important comment is the recommendation to split this up into multiple scripts, for the different stages of your analysis pipeline: (1) cleaning the sentiment data, (2) fitting the model, (3) cleaning the election data, (4) applying the model to the election data, (5) EDA of the sentiment-tagged election data.  It took about an hour to get the cleaning step for the sentiment dataset to work correctly in R 4.3, and when I hit an error in fitting the sentiment model a few minutes later I gave up trying to reproduce your analysis.  Separating the script would mean that I could just skip (2) and continue reproducing your analysis from (3).  It would also mean that, as you continue your analysis, you don't need to spend 15 minutes or whatever running steps 1-4 fresh every time you restart R.  

 -->