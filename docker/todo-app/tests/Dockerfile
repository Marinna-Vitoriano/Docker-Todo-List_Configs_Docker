FROM mjgargani/puppeteer:trybe1.0

EXPOSE 3000

WORKDIR /todotests

ADD node_modules.tar.gz .

COPY . .

ENTRYPOINT [ "npm", "test"]
