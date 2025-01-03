# PFF_FC_Assessment
An analysis of event and tracking data to predict pass completion percentage in the 2022 World Cup

Included in this repository is a .ipynb file with code for the data cleaning, exploratory analysis, visualizations, and modeling. In addition, there is a PDF with the blog post with two visuals included and a further description of the process to predict pass completion percentage in the World Cup Final for both France and Argentina. Finally, there is a folder called datafiles with the data used in this project. I could only upload the metadata.csv file since it was the only one that was under the file size requirement, but the other files I used were as follows: events.json, as well as the jsonl.bz2 files for the games 3816, 3819, 3834, 3835, 3849, 3850, 10511, 10503, 10504, 10513, 10514, 10515, and lastly 10517, which is the World Cup Game file that I saved until the last prediction stage for seeing actual pass completion percentage, but it is not included in the modeling process.

In terms of running the .ipynb file, I ran it in Jupyter notebook, where I created a project folder called PFF_FC_Project and had the aforementioned file structure. This way, I was able to use relative file paths to load data files. It did take some time to load certain data files, but as long as you configure the data files in a folder called data files, and that (as well as the .ipynb file) are contained within the PFF_FC_Project folder, then things should run smoothly. 

I also included a few prompts I used to prompt ChatGPT as screenshot in the GPT Screenshots folder.
