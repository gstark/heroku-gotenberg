FROM nginx

FROM gotenberg/gotenberg:7

COPY password /home/gotenberg/default.htpasswd
COPY nginx.subst.conf /home/gotenberg/nginx.subst.conf

COPY --from=nginx /usr/sbin/nginx /usr/sbin/nginx

ENTRYPOINT ["/bin/bash", "-c" ]
CMD []