FROM jenkins/jenkins:lts
#WORKDIR /home/jenkins/key/
#COPY . .
#USER root
#RUN apt-get update && \
#apt-get -y install apt-transport-https \
#     ca-certificates \
#     curl \
#     gnupg2 \
#     software-properties-common
#RUN curl -fsSL https://download.docker.com/linux/$(. /etc/os-release; echo "$ID")/gpg > /tmp/dkey
#RUN apt-key add /home/jenkins/key/gpg
#RUN add-apt-repository \
#   "deb [arch=amd64] https://download.docker.com/linux/$(. /etc/os-release; echo "$ID") \
#   $(lsb_release -cs) \
#   stable"
#RUN apt-get update
#RUN apt-get -y install docker-ce
