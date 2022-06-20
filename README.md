# Object_Detection
Object detection is used to locate and identify objects in images. Azure´s "custom vision service" was used to train a model to recognize specific classes of objects in images.

## Get scripts running:
- set up a python 3.8 environment
- pip install azure-cognitiveservices-vision-customvision==3.1.0
## Image Tagging and Model Training using the Custom Vision Tool
Images of three types of objects were uploaded to the custom vision ai tool for tagging and subsequent training. 

![custom vision ai](images\custom_vision_ai.jpg)


Despite a small set of tagged images, the ai performs already very well with a recall of 93% and a precision of 100%.

![model performance](images\custom_vision_ai_performance.jpg)

## Testing the model on unseen Image
The image shown below was uploaded for inference to test the ai model. 
![test image](test-detector\produce.jpg)
As can be seen, the ai model detectes all three items with scores clearly above 90%. Also the objects locations seem very accurate.

![test image](test-detector\output.jpg)


