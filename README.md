# ORLIAn Source Code
Broken into 4 sections: 
1) Data Preperation
2) Model Construction
3) Visualizer using GradCam
4) Wiki (see tabs)

## How to use 
Models were run and implemented on Google Colab using a GPU (CUDA)
Untested on other hardware

1. Run the Data_Preperation notebook. Make sure your filepaths are correct
2. Once data preperation is done, run the MODEL_PATH notebook. Remember to set your models paths right
3. Outputted model should appear wherever you set MODEL_PATH in the Run_Model notebook
4. Run Generate_Visualizations_Using_GradCam to get your visualizations if you are debugging

## Running this code
Please use Google Colab with a GPU accelerator to ensure best performance. 
Untested on everything else, especially M1 Macs

## Documentation
Our documentation can be found on the Wiki tab. For whatever reason you can't find it, it's here: https://github.com/BurgundyIsAPublicEnemy/EPIDEMIUM-Season-3/wiki

We have released a lot of our visualizations and work such as mirrors of the data (used by other teams so we know it works): https://drive.google.com/drive/folders/1NlIszuJ3uWtWK-OJsQjevB1okv6AFV5E?usp=sharing

Here you can find our thoughts, deep dive sessions and paper reviews etc. but all the structured stuff is in the wiki.

# Contribution Guide 

Orlian is an open source project and is for everyone. Even beginners. 

Please avoid using excessive jargon and try explain terms. Remember: anyone with any experience should be able to understand.  This isn’t an academic paper as much as it’s a group effort to help solve a difficult problem. A group where people with no ML experience but with plenty of medical exprience work with those who do! 

Remember to explain your terms and ELI5 (Explain It Like I Am Five)

What does it feel like to have jargon thrown at you with no understanding? Look no further: https://www.youtube.com/watch?v=aW2LvQUcwqc

## PRs

PRs are openly accepted and contributions are welcome. Just remember to tell us what scores you are getting, and what you've done / fixed.

### Why do you have a best submission and current one? 
This is explained in the wiki (Model Results Part 1) but during development of the model, we discovered that some feature engineering we had done to make the data easier to use accidentally allowed us to short cut to the OS. Even though this is probably a Kaggler's dream, we eliminated the features to ensure the model wasn't going to short cut and was going to look at the images.

