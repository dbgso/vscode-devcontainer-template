FROM ubuntu:18.04

COPY certificate.pem /usr/share/ca-certificates/
ENV NODE_EXTRA_CA_CERTS=/usr/share/ca-certificates/certificate.pem
RUN echo certificate.pem >> /etc/ca-certificates.conf
RUN update-ca-certificates
