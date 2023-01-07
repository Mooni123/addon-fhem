ARG BUILD_FROM
ARG BUILD_ARCH

FROM $BUILD_FROM
LABEL maintainer="kastbernd@gmx.de"

# Copy data for add-on
RUN rm -rf /opt/fhem

COPY run.sh /
RUN chmod a+x /run.sh

WORKDIR "/"
ENTRYPOINT [ ]
CMD [ "/run.sh" ]
