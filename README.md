# STR_26_29
## A1 Forensic BIM
### Design Issues
#### Identified issues
1. The columns in the north-east part of the building are significantly more loaded than the columns in the rest of the building - 26-02-A-ClientReport, page 10
2. The structural elements are generally overdimensioned in the existing building, and can carry more load than they are right now - 26-04-A-ClientReport, page 14
3. There isn't a borehole for B308 and boreholes for nearby buildings have been used instead for defining soil layer and ground water.
#### Identified solutions
1. The layout of the structural elements could have been done, so the loads are more evenly distributed between the columns. 
2. 
3. A borehole for B308 could have been done in the design fase
### Model Issues
#### Identified issues
1. Because the construction was built without a model, it is possible to make mistakes when modelling it for transformation. This makes it easy to overlook something important.
#### Identified solutions
1. A model from the beginning is important if there should be any changes later.
### Tool Issues
#### Identified issues
1. There are no tools that gives an overview and visualization of the loads.
2. Structural element numbering for load transferring can be a pain to manage.
#### Identified solutions
1. Making a python tool to visualize and present the loads
2. A tool that automatically names structural elements based on their placement (grid) and type
