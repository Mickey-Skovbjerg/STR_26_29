# STR_26_29
## A1 Forensic BIM
### Design Issues
#### Identified issues
1. The columns in the north-east part of the building are significantly more loaded than the columns in the rest of the building - 26-02-A-ClientReport, page 10
2. The structural elements are generally overdimensioned in the existing building, and can carry more load than they are right now - 26-04-A-ClientReport, page 14
3. There isn't a borehole for B308 and boreholes for nearby buildings have been used instead for defining soil layer and ground water.
#### Identified solutions
1. The layout of the structural elements could have been done, so the loads are more evenly distributed between the columns. 
2. Making calculations that would support dimensions more suited for the loads they are given.
3. A borehole for B308 could have been done in the design fase
### Model Issues
#### Identified issues
1. Because the construction was built without a model, it is possible to make mistakes when modelling it for transformation. This makes it easy to overlook something important.
2. There might be places where different elements overlaps, or places where things should be connected, but there is a gap.
#### Identified solutions
1. A model from the beginning is important if there should be any changes later.
2. Inspecting the model at important places, by hiding elements to see if there are clashes anywhere.
### Tool Issues
#### Identified issues
1. Overview and visualization of loads are not automated.
2. Structural element numbering for load transferring can be a pain to manage.
3. Tracing the load in the IFC model is currently not automized.
4. IFC models are imperfect, and sometimes structural elements overlap or clash in the model.
5. There are a lot of current tools for element analysis, but there is not a good visualization of all results.
#### Identified solutions
1. Making a python tool to visualize and present the loads
2. A tool that automatically names structural elements based on their placement (grid) and type.
3. Making a tool, that automatically trace how loads travel in the building. It checks the whole system instead of just the individual elements.
4. A clash detection tool, that checks if there are somewhere in the model, where elements overlap or if there are free elements, that should be connected.
5. A dashboard showing the results of the current element analysis tools.
