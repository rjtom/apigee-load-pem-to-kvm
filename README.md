# apigee-load-pem-to-kvm
Examples for using the Apigee Edge nodeJS library to import .pem certificates into KVM
# Example Tools for Apigee Edge

These are example tools implemented in nodejs/Javascript, that use the apigee-edge-js library.

## Disclaimer

These tools are not an official Google product, nor are they part of an official Google product, nor are they included under any Google support contract.
Support is available on a best-effort basis via github or community.apigee.com .


## Installation
npm install

# Load a PEM as a value into a KVM (maybe encrypted)

```
./loadPemIntoKvm.js -n -v -o ORGNAME -e ENVNAME -m KVM_MAP_NAME -F ./certs/<Filename>.pem -N NAME_OF_VALUE
```
