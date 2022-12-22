# Kubedim

Kubedim is a drop-in solution for Kubernetes to orchestrate intelligent load shedding on optional components of a system in response to periods of high load. Kubedim was created as part of an integrated master's thesis at Imperial College London.

Useful links:

- Check out my office hours interview with Grafana/k6.io discussing this project [here](https://nicolevanderhoeven.com/blog/20210813-kubedim-microservices-testing/)
- Want to read the thesis? Click [here](https://iamkelv.in/assets/thesis.pdf)
- Want to see some code?
  - [kcz17/dimmer](https://github.com/kcz17/dimmer) contains base logic and control theory-based actuation
  - [kcz17/load-testing](https://github.com/kcz17/load-testing) contains k6 configuration code to orchestrate load testing against a service
  - [kcz17/profiler](https://github.com/kcz17/profiler) contains the service that profiles users' intent
- Want to find documentation? Click [here](https://kubedim.readthedocs.io/en/latest/)
