FROM mjgargani/puppeteer:trybe1.0
WORKDIR /app
ADD node_modules.tar.gz /
COPY e2e ./e2e
ENTRYPOINT [ "npm test" ]