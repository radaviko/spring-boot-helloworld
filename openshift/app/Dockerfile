FROM image-registry.openshift-image-registry.svc:5000/openshift/ubi8-openjdk-8:1.3

COPY target/*.jar /deployments/

CMD ["/usr/local/s2i/run"]
