FROM scratch
MAINTAINER Kelsey Hightower <kelsey.hightower@gmail.com>
COPY kube-proxy /kube-proxy
VOLUME ["/etc/kubernetes", "/etc/ssl/certs", "/usr", "/lib64"]
ENTRYPOINT ["/kube-proxy"]
