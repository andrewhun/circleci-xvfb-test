FROM cimg/openjdk:17.0.14

USER root

RUN apt-get update \
  && apt-get install -y xvfb

USER circleci

CMD ["/bin/sh"]