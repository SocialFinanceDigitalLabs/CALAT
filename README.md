# CALAT Geographic Analysis
Create heatmaps of IMD data and population density with identifiers of adult learning facilities.

## Download

If you don't have git installed, you can just download this code as a zip file:
- In the top right corner of this repository there's a button that reads `<> Code` - click on it
- Choose the option that reads `Download ZIP`
- Extract its contents
  
## Setup

1. Install python in your machine. Use the latest version available for your OS: https://www.python.org/downloads/;
2. Open the command prompt (cmd.exe);
3. Navigate to the folder where you cloned this repository. (e.g. `cd C:\Users\username\Documents\GitHub\calat-geographic-analysis`);
4. Create a virtual environment by running `python -m venv venv` - it will make your life easier in the future.
5. Activate the virtual environment by running `venv\Scripts\activate`;
6. Run `pip install -r requirements.txt` to install the required python packages;
7. Run `jupyter notebook` to start the notebook server;
8. Click on `calat-geographic-analysis.ipynb` to open the notebook.
9. Run the notebook by clicking on the `Run` button on the top menu - you can run cell by cell or all at once.
10. The image outputs are saved in the `output` folder.

If in the future you come across this repository again and want to run the notebook, you can skip steps 1, 4 and 6.

## Edit the postcodes

The postcodes are stored in the "adult_learning_facilities_postcodes.xlsx" file. In order to edit/add/remove postcodes, you just need to edit this excel file, save it and then rerun all the cells in the notebook again. This will create new images in the `output` folder and replace the old ones.
