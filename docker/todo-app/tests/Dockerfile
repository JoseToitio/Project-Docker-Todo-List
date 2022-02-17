FROM mjgargani/puppeteer:trybe1.0

WORKDIR /testsApp

ADD node_modules.tar.gz /testsApp

COPY ./ /testsApp

ENTRYPOINT [ "npm", "start" ]