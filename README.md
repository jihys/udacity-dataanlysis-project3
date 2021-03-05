# udacity-dataanlysis-project3


In this project, I will wrangle WeRateDogs Twitter data to create interesting and trustworthy analyses and visualizations. Since the Twitter archive only contains very basic tweet information, I will additionaly gather data using Tweeter API and combine with the WeRateDogs Twitter data. The combined data will be also assessed and cleaned to get insightful analyses and visualizations.

Data
WeRateDog Twitter Archive
The WeRateDogs Twitter archive contains basic tweet data for all 5000+ of their tweets, but not everything. One column the archive does contain though: each tweet's text, which I used to extract rating, dog name, and dog "stage" (i.e. doggo, floofer, pupper, and puppo) to make this Twitter archive "enhanced." Of the 5000+ tweets, I have filtered for tweets with ratings only (there are 2356).

Additional Data via the Twitter API
Retweet count and favorite count are very important information but these values are omitted. So I will gather these information through Twitter's API for all 5000+ tweet IDs within the enhanced tweetter archive file.

Twitter Image Predictions File
This file contains the dog breed classification results from a Nuerual Network model for every images in the WeRateDogs Twitter archive. This file has a table full of image predictions (the top three only) alongside each tweet ID, image URL, and the image number that corresponded to the most confident prediction (numbered 1 to 4 since tweets can have up to four images)


Please follow guide in `wrangle_act.ipynb`
Reporting for this Project
For summary of wrangling jobs I have done, pleae check out `wrangle_report.html` 
And for Analysis and Visual report, read this report. `act_report.html`



