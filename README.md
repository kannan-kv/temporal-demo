Demonstrates the usage of temporal with self-hosted temporal.


#### Setting up

1. Go to temporal-client => docker compose up.
2. Driver-service, notification-service, and user-service need to be up individually as they are individual microservices. Up them individually
3. The workflow service contains the workflow definition as code and needs to be brought up as well. 
4. Uber service is the service that initiates the workflow mentioned in the above point
5. Go to http://localhost:8080 for the temporal UI dashboard to view the workflows.


Use case diagram

![1756351683396](images/README/1756351683396.png)
