FROM nginx

FROM gotenberg/gotenberg:7

COPY password /home/gotenberg/default.htpasswd
COPY nginx.subst.conf /home/gotenberg/nginx.subst.conf

COPY --from=nginx /usr/sbin/nginx /usr/sbin/nginx
COPY --from=nginx /usr/bin/envsubst /usr/bin/envsubst

ENTRYPOINT ["/bin/bash", "-c" ]
CMD []