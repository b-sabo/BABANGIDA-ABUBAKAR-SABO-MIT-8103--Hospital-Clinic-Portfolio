# Activity 5: Distributed and Cloud Databases

## Aim
This activity explores cloud-hosted databases and important concepts in distributed database systems.

## PostgreSQL Deployment
The Hospital/Clinic relational database was deployed using Neon. The project uses the Free plan in the London region (Europe West 2).

## NoSQL Deployment
MongoDB Atlas was used to host the `hospital_nosql` database and its patient document collection.

## Distributed Database Concepts
- **Replication:** Keeping copies of data on multiple database nodes to improve availability and resilience.
- **Sharding:** Splitting data across multiple nodes to support larger workloads.
- **Availability:** Designing systems to remain accessible when components fail.
- **Consistency:** Ensuring that users see data according to the database's consistency rules.

## Important Limitation
Neon and MongoDB Atlas were configured as separate database deployments. Their data was not automatically synchronised. Replication and sharding concepts are discussed here; specific configurations or failover tests should only be reported if they were actually performed.

## Evidence
Screenshots of the cloud database dashboards will be added to the `screenshots` folder.

## Conclusion
Cloud database services simplify database deployment and management. The choice of service and distributed architecture depends on data requirements, availability goals, scalability, and cost.
