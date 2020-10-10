FROM weaveworks/ignite-ubuntu

COPY --from=valeriansaliou/sonic:v1.3.0 /usr/local/bin/sonic /usr/local/bin/sonic

CMD [ "sonic", "-c", "/etc/sonic.cfg" ]

EXPOSE 1491