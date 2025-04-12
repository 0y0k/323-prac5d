# 323-prac5d
 
### 1.logged in to Google Cloud SDK:

<code>gcloud auth login</code>

### 2.Set my project 

<code>gcloud config set project sit323-25t1-yang-ecf2a39</code>

### 3.Build Docker image

<code>docker build -t microservice:latest .</code>

### 4.Tag the image

<code>docker tag microservice:latest us-central1-docker.pkg.dev/sit323-25t1-yang-ecf2a39/microservice-repo/microservice:latest</code>

### 5.Push the image

<code>docker push us-central1-docker.pkg.dev/sit323-25t1-yang-ecf2a39/microservice-repo/microservice:latest</code>

### 6.Pull the image(test)

<code>docker pull us-central1-docker.pkg.dev/sit323-25t1-yang-ecf2a39/microservice-repo/microservice:latest</code>

