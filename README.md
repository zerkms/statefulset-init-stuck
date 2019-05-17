How to use it
=============

1. Deploy `service.yaml` and `statefulset.yaml`
1. Wait while a pod is scheduled and backs off
1. Now try to deploy `statefulset-v2.yaml`

Expected: it should upgrade and start successfully

Actual: the version 1 of the statefulset is stuck forever
