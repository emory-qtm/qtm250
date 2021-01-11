# Experiments in ML
Recall the cloudy versus clear sky [tank detector folklore](https://www.gwern.net/Tanks). Your task in this homework is to evaluate one of the [Machine Learning APIs from Google Cloud](https://cloud.google.com/apis#section-6) and attempt to uncover similar, surprising hidden variables backed up by statistical evidence that these variables may be impacting the output. 

For example, one group had explored the accuracy of ML transcription at increasing levels of speech speed by reading out reference texts at varying speed (words per minute). Their motivation stemmed from the experience of members of their group in competitive debate, an activity where competitors speak extremely rapidly and with less natural inflection. They suspected that this would affect the quality of transcriptions.

Finding such features will not be easy. These are state of the art models that have been thoroughly tested on a massive range of data. You will introduce your own data to the model to test on, collect the observations, and analyze your findings using spreadsheets.

Your grade is not based on how whether or not you find such evidence. Indeed, you may find in your analysis that all of the evidence points in another direction entirely from the hypotheses you made in your proposal. The grading rubric is based upon how complete and well-reasoned your analysis is, how original and practical your testing data is, how interesting your narrative is, and how professional your code and use of Google Cloud services is.

## Project deliverables

* A narrative, created using a Jupyter notebook, hosted on Google Cloud, and served to readers as a link to a webpage. For instance, similar in formatting (but not content) to [posts like this](https://aws.amazon.com/blogs/machine-learning/automatically-detecting-personal-protective-equipment-on-persons-in-images-using-amazon-rekognition/). 

* Collect data that you have created (pictures, text, etc. as appropriate to the model you are working with) in Google Cloud, test one of the ML APIs on it, create spreadsheets to record the results of your tests, and create statistical and visual analysis of the results.

* A Github repo containing all of the data and documentation needed for anyone interested in reproducing or modifying your project to do so. For instance, similar in the Readme (but not repo content) to [repos like this](https://github.com/aws-samples/amazon-rekognition-custom-ppe-detection-with-custom-labels).

* An architecture diagram, drawn using a tool like draw.io, and explained in your blog post. Here is [an example](https://gcp.solutions/diagram/ai-ml-recommendation-engines).
