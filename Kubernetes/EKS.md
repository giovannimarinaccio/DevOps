# EKS

## create kubeconfig
https://docs.aws.amazon.com/eks/latest/userguide/create-kubeconfig.html  

    aws eks list-clusters  # to list avaiable clusters
    aws eks --region <region-code> update-kubeconfig --name <cluster_name>   # creates .kube/config file

