FROM node:19
WORKDIR /data
RUN wget https://dl.google.com/linux/direct/google-chrome-beta_current_amd64.deb
RUN apt update -y && apt install -y ./google-chrome-beta_current_amd64.deb
RUN rm -rf ./google-chrome-beta_current_amd64.deb
