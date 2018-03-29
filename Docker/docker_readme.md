
#Install requirements.txt
pip install -r requirements.txt

#Test the application
python app.py

#Build the Docker Image
docker build -t repositoryname:tag .
(example: docker build -t aashishch65/demo:latest .)

#Run the container
docker run -d -it -p 5000:5000 containerid
(example: docker run -d -it -p 5000:5000 75ed1e4830b3)

#Tag the image according to the repo
docker tag "imageid" repositoryname:tag
(example: docker tag 75ed1e4830b3 aashishch65/demo:v1)
