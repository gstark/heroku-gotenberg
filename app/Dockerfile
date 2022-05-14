FROM nginx

FROM gotenberg/gotenberg:7

RUN mkdir -p /etc/nginx/
COPY nginx.subst.conf /etc/nginx/nginx.subst.conf
COPY password /etc/nginx/default.htpasswd

COPY FROM /usr/sbin/nginx /usr/sbin/nginx

ENTRYPOINT [ "gotenberg", "--api-port", 

