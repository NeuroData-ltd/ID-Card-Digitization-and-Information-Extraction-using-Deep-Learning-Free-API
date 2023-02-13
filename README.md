<div align="center">
  <a href="https://www.neurodata.tech/">
    <img src="https://avatars.githubusercontent.com/u/67514861?v=4" alt="NEURODATA ID Card Digitization Sample" width="100"/>
    </a>
</div>

<h1 align="center">NEURODATA ID Card Digitization Sample</h1>

** **

## ID Card Digitization and Information Extraction using Deep Learning Free API


Annotations include bounding boxes for each image and have the same name as the image name. You can find the example to train a model in python, by updating the api-key and model id in corresponding file.


** **

# Build an ID Card Info Extraction Model


<div align="center">
    <img src="https://neurodata.tech/storage/blogs/carte%20neurodata_1676143595.png" alt="id-card-digitization-gif" width = "500"/>
</div>

## Step 1: Get your free API Key
Get your free API Key from https://neurodata.tech/products

## Step 2: Sign up and verify your email
you will get a token for 100 requests for ID card extraction informations.


## Step 3: Upload Images For parsing
Get the results 

<div align="center">
    <img src="sample.png" alt="id-card-parsing-neurodata-results" width = "500"/>
</div>
** **

#Pipeline
###Corner Detection and Alignment
<div align="center">
    <img src="https://user-images.githubusercontent.com/48142689/92223664-fd60b780-eeca-11ea-8e7e-76f93f4ed888.png" alt="id-card-neurodata-pipeline" width = "800"/>
</div>
###Recto/Verso Document detection
<div align="center">
    <img src="https://user-images.githubusercontent.com/48142689/92224160-a0193600-eecb-11ea-9243-82d02d86812a.png" alt="id-card-neurodata-process" width = "800"/>
</div>
###Text Detection
<div align="center">
    <img src="https://user-images.githubusercontent.com/48142689/92224160-a0193600-eecb-11ea-9243-82d02d86812a.png" alt="id-card-neurodata-process" width = "800"/>
</div>
###Recognize image text and final results with OCR and informations translation
####Final Result
```sh
{
   "birthDate": "06 / 04 / 20",
   "birthPlace": "بنزرت - binzart",
   "firstName": "حبيب   Habib",
   "id": "11427713",
   "lastName": "الجلاجلة   Jalajla",
   "otherName": "بذ منصور بن الحبيب   bourgeon Mansour Ben alhabib",
   "recto_verso": "face"
}
     
```




