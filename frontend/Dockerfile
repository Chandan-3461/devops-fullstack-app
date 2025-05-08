FROM node:14.17.0

WORKDIR /app
COPY . .

RUN npm install
RUN npm run build

# Serve with a static file server, e.g., serve
RUN npm install -g serve
CMD ["serve", "-s", "build"]
