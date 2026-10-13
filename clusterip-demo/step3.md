Step 3 - Create ClusterIP Service
Expose the deployment using a ClusterIP service.

kubectl expose deployment webapp \
--port=80 \
--target-port=80
Verify:

kubectl get svc
Expected output:

NAME      TYPE        CLUSTER-IP
webapp    ClusterIP   10.x.x.x
