first build docker image with image name as "cats-app"

then start kubernetes pods as mentioned below - 
    - kubectl apply -f cats-app.yml 

to check deployments - 
    - kubectl get deployments

to check services 
    -  kubectl get services

to check pods log
    - kubectl logs pod-name

to delete kubectl deployment
    - kubectl delete -f bb.yaml