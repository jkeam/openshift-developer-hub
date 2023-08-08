1. Create postgresql ephemeral and
set `POSTGRESQL_ADMIN_PASSWORD` and set password to `root`

2. Expose [ocp repo](https://docs.openshift.com/container-platform/4.13/registry/securing-exposing-registry.html)

3. Pull down quay image and push into OCP.

4. oc create -f ./app.yaml
