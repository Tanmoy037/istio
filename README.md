# istio
# This repo contains istio learning and using guide

### Istiod is a cerficate authority also for sevices to communicate securely
### For using istio, istio ingress gateway is the entry point for the cluster which is alternative to nginx Ingress Controller


**VirtualService:** How you route your traffic to a given destination(possible canary deployment using this)

**DestinationRule:** Configure what happens to traffic for that destination(how traffic is handled once it reaches a particular version)

**Inject data-plane(envoy) in pods:** ```kubectl label namespace default istio-injection=enabled```

*Resource* to leand istio - 
- https://www.youtube.com/watch?v=16fgzklcF7Y
- https://www.youtube.com/watch?v=voAyroDb6xk
- https://www.youtube.com/watch?v=eSNetKBe7Z8

