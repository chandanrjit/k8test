# k8
Install Kubeclt
https://kubernetes.io/docs/tasks/tools/

kubectl version --client
kubectl cluster-info



Update the local kubeconfig with aws
-- aws eks update-kubeconfig --name developer2021 --region ap-southeast-2

Check file 
--  ls -l ~/.kube
-- check file content  cat ~/.kube/config
--  switch to context if mulitple :  kubectl config use-context  arn:aws:eks:ap-southeast-2:160342149700:cluster/developer2021
