FROM node:14
EXPOSE 3000
ADD node_modules.tar.gz .
COPY ./ /app
ENTRYPOINT [ "npm" ]
CMD ["start"]