# OxNet Science 2022 - Ecology Notebook

This is the README file for the OxNet Science Programme seminar,
delivered by PhD Student Maisie Vollans, about using linear mixed models
to analyse ecological data. If you are on the OxNet programme and
have any questions about the data or code, please post your question on
the OxNet forum or get in touch with Holly Roach <holly.roach@path.ox.ac.uk>.

# Downloading the Notebook

The python notebook and related resources for used for this homework are stored
in this Git repository: https://github.com/HollyRoach/OxNet-Ecology

To use this code in SageMaker, you will need to do the following:
  1. Log on to SageMaker Studio Lab, start the runtime, and open your project.
  2. Open the “Git” mention and select “Clone Git Repository”
  3. This will pop up a dialogue box. In the empty field (”Git repository URL (.git):”) paste the following: https://github.com/HollyRoach/OxNet-Ecology
  4. Make sure to **check** the box after “Search for environment.yml and build Conda environment.” 
  This is because we have already specified the libaries and other tools required for completing this notebook, this step will install the libraries required
  for the homework and is **necessary**.
![image](https://user-images.githubusercontent.com/84270235/162771797-47564dea-3bf2-4aa8-a352-9d7bf3fb2dc2.png)

  6. Click the blue Clone button

This will cause the terminal to open and install the conda environment we have made specifically for this notebook. 
In doing this, you will need to Confirm you want to build Conda environment, by pressing ok in the pop up window:
![image](https://user-images.githubusercontent.com/84270235/162765910-ced06ee2-ea31-485f-8e64-c6b5af88e9a6.png)

After the terminal has finished installing your new conda environment, your SageMarker should look similar to this screenshot 
(though colours may vary as this is in dark mode):
![image](https://user-images.githubusercontent.com/84270235/162771982-49a21ff6-8bb6-422c-9070-5863dcd8bbb0.png)

Next open the the Ecol_Data_Worksheet.ipynb notebook in SageMaker Studio Lab. When you have opened the notebook,
you will need to change the conda environment from default to ecol. You can do this in the following steps:
  1. Click on the default:Python icon in the top right corner of the screen
  2. From the drop down menu, select ecol:Python

![image](https://user-images.githubusercontent.com/84270235/162767960-cae17866-fab0-4cbc-9f65-ca82a2cdf028.png)

Only once you have changed the enviroment, will you be able to then start working through the notebook.
