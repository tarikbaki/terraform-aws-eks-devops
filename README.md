# terraform-aws-eks-devops

$ terraform init

$ terraform apply

### prepare kube config in the local machine to manage aws eks cluster
$ aws eks --region eu-central-1 --profile myAccount update-kubeconfig --name "Aws-Eks-DevOps-cluster"


$ kubectl apply -f deployment/deploy-marvel.yml

$ kubectl proxy

go to: http://127.0.0.1:8001/api/v1/namespaces/default/services/http:marvel:/proxy/search?character=thor

thanks to : https://github.com/Harshetjain666/terraform-aws-eks-fargate-cluster
