Step 5 - Test Connectivity
Create a temporary BusyBox pod.

kubectl run testpod \
--image=busybox \
--restart=Never \
-it -- sh
Once inside the container execute:

wget -qO- http://webapp
Exit the pod:

exit
