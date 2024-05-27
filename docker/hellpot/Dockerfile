FROM ubuntu:20.04
#
COPY HellPot /opt/hellpot/
COPY dist/config.toml /opt/hellpot/config/
#

# Start hellpot
WORKDIR /opt/hellpot

CMD ["./HellPot", "-c","config/config.toml"]
# CMD ["tail", "-f"]

