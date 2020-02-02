#FROM openjdk:11.0.6-jdk as openjdk
FROM jboss/keycloak:8.0.0

#COPY --from=openjdk /usr/local/openjdk-11/conf/security/java.security /usr/share/crypto-policies/DEFAULT/java.txt
RUN rm -f /usr/share/crypto-policies/DEFAULT/java.txt