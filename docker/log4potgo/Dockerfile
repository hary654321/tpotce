FROM ubuntu:20.04
#
# Setup log4pot
#
COPY log4pot /opt/log4pot/
COPY dist/responses/tomcat-default.html /opt/log4pot/responses/

# Start redishoneypot
WORKDIR /opt/log4pot

CMD ./log4pot --log /var/log/log4potgo/log/log4potgo.json

# CMD tail -f
