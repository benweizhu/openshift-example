A deployment configuration, which describes the desired state of a particular component of the application as a pod template.

One or more replication controllers, which contain a point-in-time record of the state of a deployment configuration as a pod template.

One or more pods, which represent an instance of a particular version of an application.

Features provided by the deployment system:

A deployment configuration, which is a template for running applications.

Triggers that drive automated deployments in response to events.

User-customizable strategies to transition from the previous version to the new version. A strategy runs inside a pod commonly referred as the deployment process.

A set of hooks for executing custom behavior in different points during the lifecycle of a deployment.

Versioning of your application in order to support rollbacks either manually or automatically in case of deployment failure.

Manual replication scaling and autoscaling.