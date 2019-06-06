# k8sreplication w/o using k8s repplication controller.
This is an simple '.yaml' file used to deploy two containerized applications that cannot be replicated by 'kubernetes repplication controller'. 
This configuration can be applied for applications that use HTTP 1.1 protocol, which uses the keep alive feature (to have persistent connections) and pipelining (to receive multiple requests through the same connection, in parallel)

It is a simple configuration as a code that you can use to build an artifact and deploy via CD pipeline if your application meet the conditions above. 

In case of doubt, you know what to do! ;)
