# Automate_filling_of_web_forms

This project is designed to automate the process of filling web forms by extracting data from an Excel sheet. By eliminating manual data entry, this automation helps increase efficiency and reduce the potential for errors.

## Prerequisites
- UiPath Studio

## Overview
This project demonstrates how to automate the process of filling data into a web form using UiPath and data extracted from an Excel file. The key steps covered in this project are as follows:

1. **Reading Data from an Excel File**: The project utilizes the "Read Range" activity in UiPath to extract data from an Excel file. This step is essential for reading data from the Excel table.

2. **Opening a Web Browser**: To interact with the web form, the "Use Application/Browser" activity is used to open a web browser. This action sets the stage for data input.

3. **Creating a Loop for Iteration**: A loop is created to iterate through each row of the data table obtained from the Excel file. This loop is crucial for systematically handling each row's data.

4. **Data Input with "Type Into" Activity**: The "Type Into" activity is employed to enter data into specific fields on the web form. This step demonstrates how to dynamically populate fields with data from the Excel file.

5. **Submitting Data**: After data entry, the automation clicks the "Submit" button on the web form. This action triggers the submission of the entered data.

6. **Preparing for the Next Row**: In preparation for the next row of data, the automation clicks on the "Submit Another Response" link. This ensures a seamless transition to the next set of data to be entered.

Through these steps, this project showcases how the automation successfully reads data from the Excel file and efficiently populates the web form, streamlining the data entry process. The  activities plays a pivotal role in this process by facilitating the whole process.

By following the instructions outlined in this project, you can automate the process of filling web forms, saving time and reducing the risk of errors associated with manual data entry.
