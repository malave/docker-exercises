FROM nginx:1.19.3
HEALTHCHECK --interval=45s \
 --timeout=5s \
 --start-period=10s \
 --retries=2 \
 CMD curl -f http://localhost/ || exit 1
EXPOSE 80