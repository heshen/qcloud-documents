Currently, the cloud database provides the following instance types:

- **Master instance**: This instance can be purchased directly. It has all the features of the cloud database.

- **Master instance (exclusive)**: In the mode of Database Dedicated Cluster, this instance can be applied for in the dedicated cluster. It has all the features of the cloud database.

- **Disaster recovery instance**: This instance is deployed remotely (different availability zones) to sync (async) data of the master instance in real time for database disaster recovery. It has only some features of the cloud database.

- **Temporary instance**: This instance is generated by rollback to verify the data after rollback operation. You can switch the verified temporary instance to the master instance by the feature of switching to master instance.
