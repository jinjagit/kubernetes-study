FROM docker.pkg.github.com/liquidvotingio/api/api:latest
#ENV SECRET_KEY_BASE=$(mix phx.gen.secret)
ENV DB_USERNAME=postgres
ENV DB_PASSWORD=postgres
ENV DB_NAME=liquid_voting_dev
ENV DB_HOST=host.docker.internal
EXPOSE 4000
ENV PORT=4000

ENTRYPOINT ["./bin/liquid_voting"]

# docker run -e SECRET_KEY_BASE=$(mix phx.gen.secret) -e liquid_voting:latest
CMD ["start"]