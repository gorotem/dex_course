Task number 1:
TWO Namespace definition.

apiVersion: v1
kind: Namespace
metadata:
  name: rotem1-namespace

**********************************

apiVersion: v1
kind: Namespace
metadata:
  name: rotem2-namespace

**********************************

Task number 2:
Deployment definition.

apiVersion: apps/v1
kind: Deployment
metadata:
  name: rotem-deployment
  namespace: rotem1-namespace
spec:
  replicas: 1
  selector:
    matchLabels:
      app: rotem-app
  template:
    metadata:
      labels:
        app: rotem-app
  spec:
    containers:
      - name: nginx
        image: nginx
        ports:
          - containerPort: 80


