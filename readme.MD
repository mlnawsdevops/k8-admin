## Steps
1. create IAM policy for eksdescribe
2. create user ramesh and suresh and attach eksdescribe policy
3. create role 
4. create rolebinding == role and user
5. map user ramesh in kubectl get configmap aws-auth -n kube-system -o yaml
6. kubectl get role
7. kubectl get rolebinding
8. kubectl get clusterrole
9. kubectl get clusterrolebinding
10. create expense instance 
11. aws configure and give suresh secret key and access key
12. check the resources access