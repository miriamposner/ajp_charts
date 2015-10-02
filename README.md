# ajp_charts
This is data about the kinds of images published in *The American Journal of Psychiatry*, gathered for a research project.

To gather this data, I obtained PDFs of every issue of *The American Journal of Psychiatry* from 1910 to 1960 and then used OpenCV to extract all of the images. I then hand-tagged the images according to the following categories:

* anatomical diagram
* apparatus
* brain section
* building
* chart
* hands
* histology
* historical
* other
* other diagram
* patient
* patient-produced artifact
* physician
* specimen
* x-ray

Because charts were the most common images published in the *AJP*, I wanted to see what the data would look like if I excluded them. So ajp_categorized_nochart.csv is that data.