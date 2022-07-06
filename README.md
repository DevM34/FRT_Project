<h1> Image Analysis using Cognitive Services </h1>

<h2> Project Statement/Opportunity </h3>

<p> Image analysis is the extraction of meaningfull information from the image. Analysis of images can give meaningful information including face detection, object detection, color scheme, gender detection, detect brand and various category. Using cognitive services provided by Azure Image Analysing web services will be made. This image analysis service will help us knowing the face, object and various elements in image. It can give us answers for who, when and where was the image taken. </p>

<h2> Azure Technologies Used </h3>

<b> 1. Computer Vision </b> <br>
<b> 2. Azure App Services </b> 

<h2> Prerequisites </h3>

<b> 1. Azure Subscription </b><br>
<b> 2. Visual Studio using ASP.NET core 5.0

<h2> Project Description </h2>
 
<p> Project's vision is to build an web based service which on uploading a image gives the detailed description about the content of Image. Analysis of image includes multiple factors including face detection, color scheme, detect brand, object, category. Use of Cognitive services such as Computer Vision provided by AZURE helps in analysing the image more efficiently. ASP.NET Framework was used with multiple languages including C#, java, html, css in creating this web service. We will be using Azure portal to manage resources created and will be using accordingly, azure provides both paid and free services. We will be using COMPUTER VISION to analyse the images and AZURE WEB APP to deploy the project and keep running. </p>
 
<h2> Step-by-Step Implementation </h2>

<h3> Creating Computer Vision Service </h3>

<b> Firstly, login to Azure portal and search for cognitive services. In cognitive services, go for Computer Vision and click on create and fill details. After filling details the computer vision service will be created. </b>
![image](https://github.com/DevM34/FRT_Project/blob/master/computervision.aspcore/Screenshots/1.png?raw=true)

<b> After filling all the details we will get our computer vision resource and we will have our subscription key and endpoint key. </b>
![image2](https://github.com/DevM34/FRT_Project/blob/master/computervision.aspcore/Screenshots/2.png?raw=true)

<b> Below image shows the subscription keys and Endpoint which will be required when we have to access to this service. </b>
 
![image3](https://github.com/DevM34/FRT_Project/blob/master/computervision.aspcore/Screenshots/3.png?raw=true)

<h3> Creating new project </h3>

<b> We will get started with creating the solution for our project. For this will will use Visual Studio 2019 and will use ASP.NET CORE WEB APP for creating solution </b>
![image4](https://github.com/DevM34/FRT_Project/blob/master/computervision.aspcore/Screenshots/4.png?raw=true)

<b> Now we will add client library from NuGet packages called for accessing Computer Vision Resources. </b>
<b> Microsoft.Azure.CognitiveServices.Vision.ComputerVision </b>

![image5](https://github.com/DevM34/FRT_Project/blob/master/computervision.aspcore/Screenshots/5.png?raw=true)
 
 <b> Now, here is the snippet of code where we will authenticate the user access to the service. </b>
 ![image6](https://github.com/DevM34/FRT_Project/blob/master/computervision.aspcore/Screenshots/6.png?raw=true)
 
 <b> Below is the code snippet for retrieving the analysis information from computer vision </b>
 ![image11](https://user-images.githubusercontent.com/104422578/177650857-89a11ae3-c052-4647-a810-054c0d04aba1.png)
 
 <h3> Deployment details </h3>
 
 <b> Solution was deployed from Visual Studio itself using the publish on Azure cloud by Azure App Services which publishes the solution on azure cloud.</b>
 ![image7](https://github.com/DevM34/FRT_Project/blob/master/computervision.aspcore/Screenshots/7.png?raw=true)
 
 <b> This is the details of web service deployed on azure. This creates a global link for access the Image Analysis </b>
 ![image8](https://github.com/DevM34/FRT_Project/blob/master/computervision.aspcore/Screenshots/8.png?raw=true)
 
 <b> This is the web service plans details </b>
 ![image9](https://github.com/DevM34/FRT_Project/blob/master/computervision.aspcore/Screenshots/9.png?raw=true)
 
 <h3> Resource Group </h3>
 
 <b> Resource group is like the organization under which we apply for the resources and all the resources we applied for are shown under one banner </b>
 
 ![image10](https://github.com/DevM34/FRT_Project/blob/master/computervision.aspcore/Screenshots/10.png?raw=true)
 
 <b> This is the image which shows the details about the web service deployed and the link was created which i9s shown in the image below </b>
 ![image12](https://github.com/DevM34/FRT_Project/blob/master/computervision.aspcore/Screenshots/12.png?raw=true)
 
 <h5> To access the project here is the link https://imageanalysisaspcore20220706221413.azurewebsites.net </h5>
 
 
 



