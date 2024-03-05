# Exploring Azure Visual Studio

## Steps to reproduce the Lab:

### Requirements:
- Access the MS Azure Portal and create an Azure AI Service Resource.

    - Access https://portal.azure.com
    - Click on Create a resource
    - Select Azure AI Services
    - Follow these details:
        - Subscription: Your Azure subscription.
        - Resource group: Select or create a resource group with a unique name.
        - Region: East US.
        - Name: Enter a unique name.
        - Pricing tier: Standard S0.
    - Create the Resource.

For all tests, use the https://portal.vision.cognitive.azure.com portal.

Access the Portal Vision and make the created resource as your default resource:

![LAB900_02](./images/Screenshot%202024-03-05%20at%2007.43.20.png)

### Detect Faces 
Select the Get Started with Detect faces in an image:

![LAB900_02](./images/Screenshot%202024-03-05%20at%2009.55.28.png)

You can test any image. The IA will detect any face, and will also tell you if the person is using mask or not.

![LAB900_02](./images/Screenshot%202024-03-05%20at%2009.29.44.png)

![LAB900_02](./images/Screenshot%202024-03-05%20at%2009.29.53.png)

You can see also the JSON response returned:

![LAB900_02](./images/Screenshot%202024-03-05%20at%2009.54.09.png)

### OCR 
Select the Get Started with Extract text from images:

![LAB900_02](./images/Screenshot%202024-03-05%20at%2009.59.50.png)

You can test the images, and see the text extract from them:

![LAB900_02](./images/Screenshot%202024-03-05%20at%2010.00.13.png)

![LAB900_02](./images/Screenshot%202024-03-05%20at%2010.00.23.png)

You can also see the JSON file returned:

![LAB900_02](./images/Screenshot%202024-03-05%20at%2010.00.53.png)

### Image analysis 
Here we can test different tools, from removing the background of images to add captions to images.

![LAB900_02](./images/Screenshot%202024-03-05%20at%2010.06.17.png)

Here are some examples:

![LAB900_02](./images/Screenshot%202024-03-05%20at%2010.07.02.png)

![LAB900_02](./images/Screenshot%202024-03-05%20at%2010.07.43.png)

![LAB900_02](./images/Screenshot%202024-03-05%20at%2010.08.21.png)

![LAB900_02](./images/Screenshot%202024-03-05%20at%2010.09.02.png)