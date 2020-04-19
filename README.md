# How to Deploy
* `kubectl apply -f .`

# How to Access
* run `kubectl get svc`
* get the port number from Ports column

### Current `kubectl get svc -n ashutoshojha` output is

```                
NAME               TYPE        CLUSTER-IP      EXTERNAL-IP   PORT(S)        AGE
svc-ashutoshojha   NodePort    10.111.127.63   <none>        80:30347/TCP   94m
svc-mysql          ClusterIP   10.99.125.239   <none>        3306/TCP       5s
svc-nginx          NodePort    10.99.124.66    <none>        80:32723/TCP   75m
```

* *Task 2:* http://18.210.162.103:30347/cal_2020.txt
* *Task 3:* http://18.210.162.103:32723