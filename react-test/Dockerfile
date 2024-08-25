FROM node:20

# Python 3 HTTP Server serves the current working dir
# So let's set it to our add-on persistent data directory.
WORKDIR /react-template

COPY react-template /react-template

RUN npm install
RUN chmod +x start-addon.sh
CMD ["./start-addon.sh"]
