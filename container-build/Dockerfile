# Use the httpd-parent image as base
FROM quay.io/openshift/origin-hello-openshift
LABEL io.k8s.description="Postal is an Go HTTP server" \
io.k8s.display-name="postal 1.0.1" \
io.openshift.expose-services="8081:http" \
io.openshift.tags="postal"
EXPOSE 8081
USER 1001
ENTRYPOINT ["app/postal"]
CMD [ "-p=8081" ]
