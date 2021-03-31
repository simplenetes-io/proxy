# Proxy

If changing proxy.conf for a cluster, reupload the configs for the proxy pod then rerun the proxy pod.

As for now the proxy pod uses a prototype JavaScript natively compiled version of the proxy executable.
This is intended to be replaced with the Golang version.
