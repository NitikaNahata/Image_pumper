# Image_pumper
The MLOps-driven application is created to enhance images by a factor of 4 using ESRGAN, a deep learning technique for image super-resolution. 
It is hosted on Render's web services and implemented as a Flask-based API. Users have the ability to upload low-resolution images to the API, 
and the application employs ESRGAN to increase their resolution fourfold. 

# Steps to Deploy the Application
Local Deployment
1) Clone the repostory
https://github.com/NitikaNahata/Image_Pumper.git

2) Create a conda Environment
conda create -n {Environment name} python==3.7 

3) Start the Environment
conda activate {Environment name} 

4) Install requirements
pip install requirements.txt

5) Run the Application
python app.py

6) Access the local Web Application
copy the url eg. 127.0.0.1/5000 from the out put and paste the URL in your browser


