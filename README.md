### last edited on 08-07-2022

# Hand-Written-Character-Recognition
Using Deep-Learning
Project Duration : April 2022-July 2022

I present a handwritten Hindi character recognition system based on different Deep learning technique. 
Handwritten character recognition plays an important role and possible applications in assisting technology for blind and visually impaired users, human–robot interaction, automatic data entry for business documents, etc. 
In this work, we propose a technique to recognize handwritten Hindi characters using deep learning approaches like Convolutional Neural Network (CNN). 
This is a Character Recognition System which I developed for Devanagari Script.

### What is Devanagari?
#### An alphabet usually employed for Sanskrit and used as a literary hand for various modern languages of India

### Project Requirements :

#### Install latest version of Anaconda & inside Anaconda Navigator we have to work upon Jupyter Notebook.

##### 1.Launch Anaconda Powershell Prompt & create a new Conda Environment to install all required packages.
##### conda create --name myenv     
   eg: conda create --name test
##### After creating the environment do activate that environment by the command:  conda activate myenv  
After doing so install the following packages inside the environment as listed below:

##### 2.Install the Python version:  conda install python=3.6.13
##### 3.Install numpy:  conda install numpy
##### 4.Install keras:  conda install keras
##### 5.Install tensorflow:  conda install tensorflow
##### 6.Install opencv:  conda install opencv-python==3.4.17.63

After you are done installing all these packages ,simply exit the anaconda powershell prompt.
### Note: Keep the following files inside the same folder:
1. data.csv- LINK::https://drive.google.com/file/d/1Qz-2JIiRM8UmZu2HtAgqq_wFNoqgGyw2/view?usp=sharing
data.csv file is large so provided the google drive link for that.
2. devnagari_model.h5
3. train.ipynb
4. app.ipynb

handWritingRecognition.py require data set data.csv for training and testing.<br>
application.py require devanagari_model.h5 model for classify the characters.
