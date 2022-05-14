FROM nginx

FROM gotenberg/gotenberg:7

COPY password /tmp/default.htpasswd
COPY nginx.subst.conf /tmp/nginx.subst.conf

COPY --from=nginx /usr/sbin/nginx /usr/sbin/nginx

ENTRYPOINT [ "/bin/bash" ]
CMD []