FROM quay.io/sampandey001/secktor
RUN git clone https://github.com/dayanisuru/Dark-Nero-Bot-MD /root/dayanisuru
WORKDIR /root/dayanisuru/
RUN npm install npm@latest
RUN yarn install --network-concurrency 1
EXPOSE 8000
CMD ["npm", "start"]

