# Converts comma separated (CSV) files 
# To Attribute-Relation File Format (ARFF)
#WHERE 'converts' means taht an arr file is created and populated with 
#the csv data. The csv data is not deleted or modified.
#
#@Author Sampurna Chowdhury - github.com/Schowdhury1770
#@Date March, 2025 -  
#
#Python 3.6
#
#@Description
#Simple python program that reads a csv file , selects all its attributes 
#and assigns its data typee ('numeric' or 'nominal').
#Selects unique data values for each nominal attribute, and
#inserts a '0' on each empty cell
#This Program was made to facilitate some csv data cleaning when I was 
#trying to open a csv file in weka 
#This progran file helps to clean the csv file by converting it to arff file 
#Nominal values for the same attribute values , when it has empty cells 
#
#Note : you can open the arff file via  a text editor as well 
#for more information you can go into the Waikato website: https://www.cs.waikato.ac.nz/ml/weka/arff.html 
