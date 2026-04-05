# k8s-practical
install miniqube in AWS ec2 (ubuntu -> instance type small)

create nginx pod & expose the service outside using NodePort


kubectl create/apply -f pod.yml  
kubectl create/apply -f service.yml

issues:
as I'm using miniqube in AWS ec2 and faced some issues while accessing the nginx.
