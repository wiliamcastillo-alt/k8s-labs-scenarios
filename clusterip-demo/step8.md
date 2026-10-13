Step 8 - Cleanup
Remove all resources.

Delete Service:

kubectl delete svc webapp
Delete Deployment:

kubectl delete deployment webapp
Delete BusyBox test pod:

kubectl delete pod testpod
Verify cleanup:

kubectl get all
