# microservices-kubernetes-blog
Step 1: add following line in /etc/hosts file 

127:0.0.1 posts.com

Step 2: install helm 
Step 3: deploy the ingress controller with the following command:


  `helm upgrade --install ingress-nginx ingress-nginx \
  --repo https://kubernetes.github.io/ingress-nginx \
  --namespace ingress-nginx --create-namespace`

Step 4: install skaffold from
  https://skaffold.dev/docs/install/

Step 5: Run `skaffold dev` command on root folder to run the project

Step 6: open browser with url posts.com to run the client project
