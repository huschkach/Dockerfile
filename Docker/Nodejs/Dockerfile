FROM ubuntu:18.04
RUN apt update; \
    apt install -y curl; \
    curl -fsSL https://deb.nodesource.com/setup_16.x | apt install -y nodejs;
WORKDIR /home
RUN  echo "console.log('Hello from JavaScript')" > hello.js;
CMD ["node", "hello.js"]
