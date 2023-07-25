# Namsor-API-Integration-and-Data-Extraction
The objective of this task is to use the Namsor API to extract ethnic information from the provided list of names. By performing API requests to the Namsor API with each person's first and last name, we may collect information on their ethnicity.

## Calling Namsor API and Saving Response:
The script makes API calls to the Namsor API using the 'requests' library for each first and last name in the Excel file. The response from the API is saved as separate text files for each name in the 'output' directory.

<img width="754" alt="image" src="https://github.com/parth-7283/Namsor-API-Integration-and-Data-Extraction/assets/78414082/c1a7d12f-6da3-492a-8b1c-cb5d8b86d22a">
<img width="756" alt="image" src="https://github.com/parth-7283/Namsor-API-Integration-and-Data-Extraction/assets/78414082/71bd3f8e-bc35-4a4b-8a8a-e9e187579f41">

## Extracting Ethnicity Data and Saving the data in Excel:
The script then extracts the 'ethnicity' and 'ethnicityAlt' fields from each API response text file. It compiles this data into a new DataFrame and saves it to an Excel file named 'List.xlsx', which contains the columns - 'First Name', 'Last Name', 'Ethnicity', and 'Alternate Ethnicity'.

<img width="752" alt="image" src="https://github.com/parth-7283/Namsor-API-Integration-and-Data-Extraction/assets/78414082/5da3b55b-53f1-41b0-9a63-67bcdd2c5c43">
<img width="752" alt="image" src="https://github.com/parth-7283/Namsor-API-Integration-and-Data-Extraction/assets/78414082/0e25c305-cc6c-41f7-b4f9-e63f294a003f">
<img width="752" alt="image" src="https://github.com/parth-7283/Namsor-API-Integration-and-Data-Extraction/assets/78414082/923aa7af-b4e0-4434-98b6-c767b6942b8f">



## Output:
The script will generate an output in Excel with each mentioned first and last name's ethnicity and alternate ethnicity. The output file can be downloaded from [here](https://github.com/parth-7283/Namsor-API-Integration-and-Data-Extraction/blob/main/List.xlsx)

<img width="337" alt="image" src="https://github.com/parth-7283/Namsor-API-Integration-and-Data-Extraction/assets/78414082/12ea2660-09f8-47ea-a590-c3a5337d46fd">


