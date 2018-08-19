FROM openjdk:10-jre
MAINTAINER dave@minnigerode.org


# Our startup script
COPY startup .

# logback configured to talk to splunk http event collector (flagged in startup)
COPY logback-splunk-hec.xml .

ENTRYPOINT ["./startup"]
