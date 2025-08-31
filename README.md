# demoapi

Excercise: 
Create a ConfigMap named trauerweide with content tree=trauerweide
Create the ConfigMap stored in existing file /root/cm.yaml

apiVersion: v1
data:
  tree: birke
  level: "3"
  department: park
kind: ConfigMap
metadata:
  name: birke
