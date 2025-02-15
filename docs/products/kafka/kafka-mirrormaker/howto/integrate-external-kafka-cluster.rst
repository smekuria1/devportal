Integrate an external Apache Kafka® cluster in Aiven
====================================================

Aiven for Apache Kafka® MirrorMaker 2 enables the cross-cluster topic replication between any two Apache Kafka® clusters, which can be deployed as Aiven or external services. To enable :doc:`replication flows <setup-replication-flow>` with an external Apache Kafka cluster you need to define a service integration endpoint.

Define an external Apache Kafka® service integration endpoint via Aiven console
-------------------------------------------------------------------------------

An external Apache Kafka® service integration endpoint can be defined in the `Aiven console <https://console.aiven.io/>`_.

1. Navigate to the Aiven project where you want to integrate the external Apache Kafka cluster.

2. Select **Integration endpoints**, and then **External Kafka** from the list of available services.

3. Click on **Add a new endpoint**.

4. Fill the **Endpoint name**, **Bootstrap servers** and the security settings and click **Create**.

5. The external Apache Kafka cluster is now available under the alias defined in the **Endpoint name** parameter
