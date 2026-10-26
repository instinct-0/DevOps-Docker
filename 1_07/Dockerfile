FROM ubuntu:24.04
RUN apt update && apt install -y curl

WORKDIR /app
COPY script.sh .
CMD [ "./script.sh" ]
