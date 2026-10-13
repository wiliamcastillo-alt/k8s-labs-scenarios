Step 2 - Create Deployment
Create an NGINX deployment.

kubectl create deployment webapp --image=nginx
Verify deployment:

kubectl get deployment
Verify pod creation:

kubectl get pods
Expected output:

webapp   1/1   Running
