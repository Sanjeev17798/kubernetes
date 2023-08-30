# kubernetes
#Learning of kubernetes
#Creating a Pods with Yaml 

apiVersion:V1
Kind:Pod
metadata:
  name:myfirstpod       #name is child of metadata it is recommended to 2 space aligmnet   
  labels:
    app:nginux           
spec:
  containers:
  - name:nginux
    image:nginux
    
    
  
