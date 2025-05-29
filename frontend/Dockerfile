FROM nginx:1.28-alpine-slim
COPY  code  /usr/share/nginx/html
RUN rm -rf /etc/nginx/nginx.conf
COPY nginx.conf  /etc/nginx/nginx.conf
CMD [ "nginx","-g","daemon off;" ]
COPY expense.conf /etc/nginx/default.d/expense.conf