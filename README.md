# Background
This project is made to help me finish my research as civil engineering bachelor student.
Here, I did spatial analysis to look for suitable location for the development of offshore wind turbine in South Sulawesi, Indonesia.

# Whom is this code for
- this project is intended for indonesian researcher who are interested to do similar research (some part of the code are written in Bahasa).
- this code uses pandas and matplotlib frequently, so I assumed that the reader are comfortable with both library.

# Code
This project is done using python language, with the help of jupyter notebook.
There are four notebooks, each is for: 
- understanding data spatially using GDAL
- wind data analysis, distribution fitting, using SciPy
- cost benefit analysis using Pandas, Numpy and SciPy
- data visualization, especially using Seaborn and Matplotlib

# Files
the source data that is required to be able to run the code are:
- wind data from: http://indonesia.windprospecting.com. the download link is available in csv folder as txt file. total size of the data is about 5 GB. once you download it, you need to unzip move all files into a folder named "wind_data".
- elevation raster data from: http://tides.big.go.id/DEMNAS/. you have to sign up first. go to BATNAS section and download the raster file for latitude:-5 to -10 and longitude: 115 to 120.
- other necessary files are available in csv folder

You can run the code without problem (I hope so). However, it may be difficult to understand what the code pieces do without understanding the context first. The context is my thesis scrip (in bahasa Indonesia), which is available to download here: (Not available yet) 
