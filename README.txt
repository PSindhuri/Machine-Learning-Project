



***************************************************************************************

			STEPS TO RUN THE CODE (PYTHON JUPYTER NOTEBOOK )

***************************************************************************************

Step 1 : Please download Python and Anaconda 3.
	 Python's Sci-kit,matplotlib will be used here.

Step 2 : The main project python notebook file is Sindhuri_ML_Project_Code.ipynb.We can run this
	  directly to see the results.
	 The input data set for this file is ./ML_ANNOTATOR/HistScore.csv for 10 bins
	 and ./ML_ANNOTATOR/hist16bin.csv for 16bins.




NOTE  : THE ABOVE TWO STEPS ARE ENOUGH AS THE INPUT FILES (HISTOGRAM OF IMAGE FILES) ARE ALREADY 
	EXTRACTED INTO TWO SEPARATE CSV FILES (10 AND 16 BINS).




*******************************************************************************************

				ANOTHER METHOD

  			     Starting from scratch

******************************************************************************************

Step 1 : Download the dataset from the following link
 
	 https://goo.gl/4YZ1Ur

	 This link contains cropped images of photos.
	 Save all images into a folder named cropped.
	 Store the folder as follows  in ./ML_ANNOTATOR/Annotator/cropped
	 i.e at the top level where Sindhuri_ML_Project_Code.ipynb is present.

Step 2 : ./ML_ANNOTATOR/RoadInput.csv contains the list of images and their scores.

Step 3 : Run the CreateHist(10bins).ipynb and CreateHist(16bins).ipynb.
	 This creates ./ML_ANNOTATOR/HistScore.csv for 10 bins
	 and ./ML_ANNOTATOR/hist16bin.csv for 16 bins.

Step 4 : The main project python notebook file is Sindhuri_ML_Project_Code.ipynb
	 The input data set for this file is ./ML_ANNOTATOR/HistScore.csv for 10 bins
	 and ./ML_ANNOTATOR/hist16bin.csv for 16bins.

Now we can run this file Sindhuri_ML_Project_Code.ipynb and the Project_Report.pdf contains a summary of the results.

In the folder ML_ANNOTATOR there is file named annotator.jar 
This jar file was provided by Prof Shawn Healey,SDSU.
It was used to create RoadInput.csv


	 


