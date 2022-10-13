FROM mjgargani/puppeteer:trybe1.0

WORKDIR /app

add node_modules.tar.gz .
COPY . .

ENTRYPOINT ["npm", "test"]

