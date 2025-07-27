FROM cimg/openjdk:17.0.14

USER root

RUN apt-get update && \
    apt-get install xorg && \
    apt-get install -y xvfb libx11-6 libx11-xcb1 libxext6 libxrender1 libxtst6 libxi6 libfreetype6 libgtk-3-0 libgtk-3-dev

USER circleci

CMD ["/bin/sh"]