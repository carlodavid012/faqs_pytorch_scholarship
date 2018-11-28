
# Using GOOGLE COLAB

**Q: How to clone repo in my drive?**

Mount the drive using:

`from google.colab import drive
drive.mount('/content/drive/')`

Then:

`%cd /content/drive/`

To clone the repo in your drive

!`git clone <github repo url>`

**Q: How to use Colab**

Resource:
- https://medium.com/deep-learning-turkey/google-colab-free-gpu-tutorial-e113627b9f5d


**Q: I am trying to run the codes on Colab but got `AttributeError: module 'PIL.Image' has no attribute 'register_decoder'`.**

Execute `!pip install Pillow==4.1.1` and restart your notebook.

**Q: In colab is it necessary to write the lines related to cuda?**

Yes.

**Q: How to download and unzup the cats and dog dataset?**

!wget https://s3.amazonaws.com/content.udacity-data.com/nd089/Cat_Dog_data.zip 

!unzip Cat_Dog_data.zip



