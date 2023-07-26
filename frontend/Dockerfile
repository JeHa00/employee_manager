FROM node:alpine

ENV HOME "/root"
ENV APP_HOME "$HOME/app"

RUN mkdir $APP_HOME
WORKDIR $APP_HOME

# Copy dependency definitions
COPY . $APP_HOME

EXPOSE 3000

CMD ["npm", "start"]