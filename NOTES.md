Tried on windows
- installed via "winget install stern.stern"
- logged on Openshift via "oc login ..."
- command line example

stern . --namespace 'ns-1,ns-2,ns-3' --init-containers false --exclude-pod micrometrics --tail 10
=> this will tail all log with standard template (namespace pod-name container-name message) excluding micrometrics pods

--prompt true
=> choose which pod to tail from a list

