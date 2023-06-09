# intel-oneAPI

#### Team Name - Team Titans
#### Problem Statement - Object Detection For Autonomous Vehicles
#### Team Leader Email - amitjoshi2052003@gmail.com

## A Brief of the Prototype:
  This section must include UML Daigrms and prototype description
  
## Tech Stack: 
   List Down all technologies used to Build the prototype **Clearly mentioning Intel® AI Analytics Toolkits, it's libraries and the SYCL/DCP++ Libraries used**
   
## Step-by-Step Code Execution Instructions:
  1. We take two datasets from cityscape website. One containing images and another containing json file which contain the bounding boxes for the objects in the    image.
2. We relate the files in both dataset and extract the boudning boxes from the json along with path for the image containing the objects.
3. We store this data in a csv to be loaded again.
4. We load the store csv file into a dataframe.
5. We used yolo5 for this dataset.
6. We processed the data for yolo by extracting the stored information, normalizaing the bounding boxes associated values between 0-1 and then storing them in respective directory structures required for yolo.
7. We then pass the hyperparameters and config required to train our custom data.
8. We ran the model for 100 epochs.
9. We then can run the model of separate data inputs.

  
## What I Learned:
   Write about the biggest learning you had while developing the prototype
