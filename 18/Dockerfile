FROM brgilsonsp/ubuntu_jammy_2204:v1.0

RUN apt update
RUN apt upgrade -y
RUN curl -sL https://deb.nodesource.com/setup_18.x -o nodesource_setup.sh
RUN bash nodesource_setup.sh
RUN apt install -y nodejs
RUN apt clean