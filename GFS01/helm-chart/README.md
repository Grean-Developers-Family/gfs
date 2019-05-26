# Helm-Chart

Too many step things to deploy(deployment, statefulset, service) why  not just pack it and then just deploy all at once.

Working Directory: 
## Deploy chart
One command is enough.
```sh
$ helm --namespace <namespace> install --name <name of chart | grean-go-app > go-api  
```
That's it.


You still can use `kubectl` `to check our deployment. And try to access app from internet.






