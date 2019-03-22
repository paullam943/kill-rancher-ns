# kill-rancher-ns

Kill a Rancher Kubernetes namespace which is stuck in the state of "Terminating".

Also see: [kubernetes/kubernetes#60807](https://github.com/kubernetes/kubernetes/issues/60807)

This scripts automates the steps suggestes by some people on the comments of the issue.

**Note:** Use at your own risk! It works for me though.

## Usage

~~~sh
./kill-rancher-ns mycluster myproject
~~~

**Note:** You will need to be logged in to your Rancher cli, and have the necessary permissions.

## Pre-requisites

Your will need to have the following things installed:

* bash
* curl
* jq
* rancher

You can down Rancher CLI from https://rancher.com/docs/rancher/v2.x/en/cli/ and put it in the same folder of this script.
