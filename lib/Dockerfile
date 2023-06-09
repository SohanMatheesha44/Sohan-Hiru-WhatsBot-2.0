FROM quay.io/SohanMatheesha44/Sohan-Hiru-WhatsBot
RUN git clone https://github.com/SohanMatheesha44/Sohan-Hiru-WhatsBot /root/SohanMatheesha44
WORKDIR /root/SohanMatheesha44/
RUN npm install npm@latest
RUN yarn install --network-concurrency 1
EXPOSE 8000
CMD ["npm", "start"]
