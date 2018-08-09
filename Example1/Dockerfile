FROM scratch
EXPOSE 8081
COPY hello /
COPY templates templates
ENV WEB_SERVER_PORT :8081
EXPOSE $WEB_SERVER_PORT
CMD ["/hello"]

