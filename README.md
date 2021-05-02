# EventStore-Kubernetes
Example of yaml manifest files to set up EventStore Cluster with persistent data on Kubernetes and AWS  
  
<strong>Note:</strong> there is now an official EventStore Kubernetes Chart available here https://github.com/EventStore/EventStore.Charts  
That chart has been initially based on this repo. It's now better to use the official chart.  
<strong>Updated Note:</strong> Unfortunately the EventStore team was not willing to support an official Helm Chart and they discontinued it with a bit of non-sense around the need of a data operator. Having a data operator for Kubernetes it’s a good idea as an addition in order to control a fleet of EventStore instances (single or cluster) but it doesn’t add anything you can’t get with normal StatefulSet, services and deployments. A port of the old official chart is here https://github.com/ameier38/charts maintained by the guy helped me in the first place while I was working in EventStore. Enjoy!
  
Eventstore  
https://eventstore.org/  
https://github.com/EventStore/EventStore  
  
Kubernetes  
https://kubernetes.io/  

Tutorial
http://www.dinuzzo.co.uk/2018/08/13/set-up-an-eventstore-cluster-on-kubernetes/

