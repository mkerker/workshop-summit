# Workshop content for Summit 2017

To run locally:

```
docker run -ti --rm -p 8080:8080 -e CONTENT_URL_PREFIX="https://raw.githubusercontent.com/openshift-evangelists/workshop-summit/master" osevg/workshopper
```


To run on OpenShift
```
oc new-app osevg/workshopper -e CONTENT_URL_PREFIX="https://raw.githubusercontent.com/openshift-evangelists/workshop-summit/master"
```
