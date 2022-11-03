# CWRUBootcamp_M12_11022022_Plotly_Hoynacke
# Project Background 
Roza has a partially completed dashboard that she needs to finish. She has a completed panel for demographic information and now needs to visualize the bacterial data for each volunteer. Specifically, her volunteers should be able to identify the top 10 bacterial species in their belly buttons. That way, if Improbable Beef identifies a species as a candidate to manufacture synthetic beef, Roza's volunteers will be able to identify whether that species is found in their navel.
This new assignment consists of four technical analysis deliverables:
  - Deliverable 1: Create a Horizontal Bar Chart
  - Deliverable 2: Create a Bubble Chart
  - Deliverable 3: Create a Gauge Chart
  - Deliverable 4: Customize the Dashboard
  
# Deliverable 1: : Create a Horizontal Bar Chart
### Code is written to create the arrays when a sample is selected from the dropdown menu
### Code is written to create the trace object in the buildCharts() function
### Code is written to create the layout array in the buildCharts() function that creates a title for the chart

<img width="416" alt="Screen Shot 2022-11-02 at 6 27 16 PM" src="https://user-images.githubusercontent.com/111096384/199632229-334dc81c-9c6c-49b5-bf47-674a30a4ca73.png">

<img width="471" alt="Screen Shot 2022-11-02 at 6 27 19 PM" src="https://user-images.githubusercontent.com/111096384/199632237-ed85cd6c-79d4-4931-8219-c977e3bb158e.png">

### When the dashboard is first opened in a browser, ID 940’s data should be displayed in the dashboard, and the bar chart has the following:
  - The top 10 sample_values are sorted in descending order
  - The top 10 sample_values as values
  - The otu_ids as the labels
 
 <img width="718" alt="Screen Shot 2022-11-02 at 6 31 17 PM" src="https://user-images.githubusercontent.com/111096384/199632507-f770aec4-b27b-4443-aebd-f6734b4257d7.png">

# Deliverable 2: Create a Bubble Chart
### The code for the trace object in the buildCharts(); function does the following
  - Sets the otu_ids as the x-axis values
  - Sets the sample_values as the y-axis values
  - Sets the otu_labels as the hover-text values
  - Sets the sample_values as the marker size
  - Sets the otu_ids as the marker colors
### The code for the layout in the buildCharts(); function does the following:
  - Creates a title
  - Creates a label for the x-axis
  - The text for a bubble is shown when hovered over

<img width="388" alt="Screen Shot 2022-11-02 at 6 32 39 PM" src="https://user-images.githubusercontent.com/111096384/199632563-bc64e6c4-65cc-4cd1-921a-02312c911e1e.png">
  
### When the dashboard is first opened in a browser, ID 940’s data should be displayed in the dashboard. All three charts should also be working according to their requirements when a sample is selected from the dropdown menu

<img width="1107" alt="Screen Shot 2022-11-02 at 6 33 26 PM" src="https://user-images.githubusercontent.com/111096384/199632618-c0ad874d-4030-4d71-a386-baf2c0693257.png">
  
# Deliverable 3 Create Gauge Chart
### The code to build the gauge chart does the following:
  - Creates a title for the chart.
  - Creates the ranges for the gauge in increments of two, with a different color for     each increment.
  - Adds the washing frequency value on the gauge chart.
  - The indicator shows the level for the washing frequency on the gauge.
  - The gauge is added to the dashboard.
  - The gauge fits in the margin of the <div> element.

  <img width="1170" alt="Screen Shot 2022-11-02 at 6 34 33 PM" src="https://user-images.githubusercontent.com/111096384/199632700-55db6a62-5017-4b90-ad99-08d4580c051f.png">
  
  <img width="439" alt="Screen Shot 2022-11-02 at 6 37 41 PM" src="https://user-images.githubusercontent.com/111096384/199632987-f929085b-2f51-42de-ac8c-2843c2cadb87.png">
  
# Deliverable 4 Requirements
### The webpage has three customizations.
 
<img width="360" alt="Screen Shot 2022-11-02 at 6 35 06 PM" src="https://user-images.githubusercontent.com/111096384/199632746-75f40303-5094-49a0-8964-cef305804693.png">

### When the dashboard is first opened in a browser, ID 940’s data should be displayed in the dashboard, and all three charts should be working according to the requirements when a sample is selected from the dropdown menu 

<img width="729" alt="Screen Shot 2022-11-02 at 6 35 45 PM" src="https://user-images.githubusercontent.com/111096384/199632807-971f4f18-8829-4701-9b50-8bcdd5dcf28d.png">
  
Please visit the site by accessing it throuhg the terminal using python -m http.server and navivgating to http://127.0.0.1:8000


