FROM node:16-alpine
EXPOSE 5000
COPY . .
RUN node -v
RUN npm -v
RUN npm install
ENV REACT_APP_BACKEND_URL http://127.0.0.1:8080
RUN npm run build
RUN npm install -g serve
CMD serve -s -l 5000 build
