# demoapi

**Excercise:**

**Create configMap**
Create a ConfigMap named trauerweide with content tree=trauerweide
Create the ConfigMap stored in existing file /manifests/cm.yaml

**Access ConfigMaps in Pod**
Create a Pod named pod1 of image nginx:alpine
Make key tree of ConfigMap trauerweide available as environment variable TREE1
Mount all keys of ConfigMap birke as volume. The files should be available under /etc/birke/*
Test env+volume access in the running Pod

N/B - Use the branch: opilonelson-patch-1 and make a pull request
