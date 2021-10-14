FROM ISURU_TEAM/isuwa-dena:latest

RUN git clone https://github.com/isuwabrooo/isuru-dena /root/isuru-dena
WORKDIR /root/isuru-dena/U
ENV TZ=Europe/Istanbul
RUN npm install supervisor -g
RUN yarn install --no-audit

CMD ["node", "bot.js"]
