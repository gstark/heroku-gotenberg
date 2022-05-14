FROM nginx

FROM gotenberg/gotenberg:7

COPY nginx.subst.conf /tmp/nginx.subst.conf
COPY password /tmp/default.htpasswd

COPY FROM /usr/sbin/nginx /usr/sbin/nginx

ENTRYPOINT [ "gotenberg", "--api-port", 

