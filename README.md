# FakeNewsProject
The goal of this project is to create a fake news prediction system. Fake news is a major problem that can have serious negative effects on how people understand the world around them. You will work with a dataset containing real and fake news in order to train a simple and a more advanced classifier to solve this problem. This project covers the full Data Science pipeline, from data processing, to modelling, to visualization and interpretation.

### Running the notebook
Make sure that you have the 995KFakeNewsCoruput_subset (995,000_rows.csv) in the directory. Sometimes there is an error
when trying the cleaned csv, when using a dataset that already is on the local machine. When trying to load the cleaned data tokens will be seperated chars instead of words. This issue is solved by downloading 995,000_rows.csv fresh from Absalon. 

**To recreate the conda env that is needed to run the notebook, open a terminal and run the command in the FakeNewsProject directory:** 
conda create --name fake_news --file requirements

To run our notebook **Beware:** the computer we use to run our notebook used a server grade CPU and had 64 GB of ECC ram and may therefore have a hard time to run on other computers since we don't split the 999,500rows dataset up when cleaning. **Run the notebook at your own risk, you may experience crashes**.