# A note Image

A note application that has been dockerized.

Download the application with the below command
git clone --branch EdnahM https://github.com/EdnahM/Note_Image.git

Docker installation.
- Install Docker if not installed on your machine.
- One can test the docker installation using docker -v
- Docker version will be indicated

Go to your working Directory into Note_Image
- cd Note_Image


Build the image:
- docker build --t note_image .
#### This will download the base image which is node:12 alpine and hence you will see it in the images. 
Check the build images if successfull
- docker images

You will see your note_image image

Run the image 
- docker run -dp 3000:3000 note_image

Check for the running images
- docker ps -a

So to access your application on the browser
- http://127.0.0.1:3000



### In case you want the image download directly, 
Download the image using:
- docker pull ednahm/note_image
 
Then run the image as:
- docker run -dp 3000:3000 ednahm/note_image

Access your brower  to access the application.
- http://127.0.0.1:3000

Yeah,, you have your notemaking application.

## Happy coding 
#### Docker
