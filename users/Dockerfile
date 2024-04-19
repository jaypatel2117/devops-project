FROM public.ecr.aws/docker/library/node:lts-alpine3.19

WORKDIR /srv
ADD . .
RUN npm install

EXPOSE 3000
CMD ["node", "server.js"]
