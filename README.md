# I don't have SR-IOV

But I still want to test KubeVirt's SR-IOV integration on my laptop. Let's try
to do it with netdevsim. Again.

``` sh
./cluster/up.sh
./cluster/kubectl.sh get nodes
./cluster/cli.sh ssh node01
./cluster/down.sh
```

