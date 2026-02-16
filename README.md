[Click](https://console-openshift-console.apps.rm1.0a51.p1.openshiftapps.com/k8s/ns/centricdiameter-dev/kubevirt.io~v1~VirtualMachine)

virtctl image-upload dv windows11-installer-dv \
  --image-path ./win11.iso \
  --size=8Gi \
  --insecure \
  --force-bind
