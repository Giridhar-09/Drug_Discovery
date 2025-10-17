# Drug Discovery using ChEMBL API 💊

A simple Python project that helps you search for drug compounds and their information using the ChEMBL database. Just enter a disease name and the program will show you all the drugs that are used to treat it!

## What Does This Project Do? 🤔

This project connects to the ChEMBL database (a huge online database of drug information) and lets you:
- Search for drugs by disease name
- View drug details like drug name, ChEMBL ID, indication, and development phase
- See the chemical structure of the drugs
- Get visual representations of the molecular compounds

## Example Output 📊

When you run this notebook and enter a disease like "dengue", you'll get:
- A table showing all drugs related to dengue fever
- Drug names and their ChEMBL IDs
- The indication (what the drug is used for)
- Max phase (how far the drug has progressed in clinical trials)
- Chemical structure images of the compounds (SMILES format)

## Libraries Used 📚

This project uses the following Python libraries:

1. **chembl_webresource_client** - To connect to and fetch data from the ChEMBL database
2. **rdkit** - A cheminformatics toolkit to handle chemical structures and draw molecular compounds
3. **pandas** - For organizing the drug data into nice tables
4. **requests** - To make API requests to ChEMBL
5. **IPython.display** - To display images and data in Jupyter notebook

## How to Run 🚀

1. Open the notebook in Google Colab or Jupyter Notebook
2. Run the first few cells to install all required libraries
3. Import all the necessary modules
4. Run the search cell and enter a disease name when prompted (e.g., "dengue", "malaria", "covid", "cancer")
5. Optionally, you can describe symptoms (this is optional)
6. The program will display a table with all related drugs and their chemical structures

## Important Notes ⚠️

- **The search takes time** - The cell that searches for drugs can take a while to run because it's pulling data from the live ChEMBL API
- **Internet required** - This project needs an active internet connection to fetch data from ChEMBL
- **Try different diseases** - You can search for various diseases like malaria, covid, cancer, diabetes, etc.
- **Live data** - The data is pulled from the public ChEMBL API, so it stays updated automatically

## What I Learned 📖

Through this project, I learned:
- How to work with public APIs and databases
- How to handle chemical data using RDKit
- How to visualize molecular structures
- How to organize scientific data using pandas
- How to create an interactive drug discovery tool

## Sample Diseases to Try 🔍

- dengue
- malaria
- covid
- cancer
- diabetes
- alzheimer

## Credits 🙏

This project uses:
- **ChEMBL Database** - European Bioinformatics Institute (EMBL-EBI)
- **RDKit** - Open-source cheminformatics toolkit
- Data is fetched from the live public ChEMBL API

---

Feel free to explore and try different diseases! This is a great way to learn about drug discovery and bioinformatics! 🎓✨