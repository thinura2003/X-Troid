FROM fusuf/whatsasena:latest

RUN git clone https://github.com/thinura2003/X-Troid /root/X-Troid
WORKDIR /root/X-Troid/
ENV TZ=Europe/Istanbul
RUN npm install supervisor -g
RUN yarn install --ignore-engines

CMD ["node", "bot.js"]
