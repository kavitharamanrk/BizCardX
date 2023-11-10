# BizCardX
Extracting Business Card Data with OCR

BizcardX application is for extracting text from the uploaded visiting card image file.

Workflow:

1. Upload

    Upload Business card which should be jpg/jpeg/png
    That uploaded card image is processed and texts are extracted using easyocr package
    Processed image and extracted texts are displayed
    Extracted information can be stored in sqllite table by clicking save to database button

2. Modify

    provision is given to select the card holder which are stored in db
    selected card holder's details are displayed in text boxes
    If we want to change to data we can change
    Modified data can restored to db by clicking update to db button
    when we click viewed modified data button modified data is displayed in the table

3. Delete

    By selecting the card holder we can delete that entire card holder's information
    For re confiming the delete operation delete button is clicked

4. About

    It shows the application related information
    And what are the technologies are used to deveop this application

Packages to install
easyocr,streamlit,streamlit_option_menu and sqllite

This app is executed through local tunnel
