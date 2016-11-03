# KubeDNS

Kubernetes offers a DNS cluster addon, which most of the supported environments
enable by default.  We use [SkyDNS](https://github.com/skynetservices/skydns)
as the DNS server, with some custom logic to slave it to the kubernetes API
server.
