##### Creating a Project
```bash
oc new-project order \
    --description="A project/namespace for order service" \
    --display-name="order"
```

##### List all Projects
```bash
oc get projects
```

##### Change Project

```bash
oc project order-dev
```

##### Checking current Project status

```bash
oc status
```

#### Deleting a Project
```bash
oc delete project order-dev
```