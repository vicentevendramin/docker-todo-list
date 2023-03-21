FROM node:14
EXPOSE 3001
ADD .node_modules.tar.gz .
COPY ./ /app
ENTRYPOINT [ "npm" ]
CMD ["start"]