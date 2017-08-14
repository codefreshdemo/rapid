:experimental:

Steps:
1. Authenticate with Google in integration page
2. Add your cluster
3. Go to Kubernetes view and click "Add new Service"
4. Switch to yaml based config and copy-paste the files from /kube
5. Deploy and enjoy

More advanced cased
1. Finish all steps from 1-5
2. Add this repository (fork if you wish)
3. Configure your pipeline
3.1 Configure push step, push the build image to your repository
3.2 Configure deploy step:
3.2.1 Select Codefresh beta Type
3.2.2 Fill the cluster, namespace and service 
3.2.3 Build you pipeline