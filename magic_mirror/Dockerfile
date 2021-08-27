ARG BUILD_FROM
FROM ${BUILD_FROM}

# Add env
ENV LANG C.UTF-8

# Build arguments
ARG BUILD_ARCH
ARG BUILD_DATE
ARG BUILD_REF
ARG BUILD_VERSION

# Setup base
RUN apk add --no-cache git nodejs nodejs-npm curl wget unzip \
    && npm set unsafe-perm true \
    && npm i npm@latest -g 

WORKDIR /opt/magic_mirror

RUN git clone --depth 1 -b master https://github.com/MichMich/MagicMirror.git . \
  && npm install --unsafe-perm

# Copy data
COPY run.sh /
COPY config.js /
RUN chmod a+x /run.sh

CMD [ "/run.sh" ]



