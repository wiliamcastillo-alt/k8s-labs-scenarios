Step 6 - Scale the Application
Increase replicas.

kubectl scale deployment webapp \
--replicas=3
Verify:

kubectl get pods
Verify deployment:

kubectl get deployment
Expected replicas:

3/3
