FROM nextcloud:apache
RUN apt-get update && apt-get install -y procps smbclient && rm -rf /var/lib/apt/lists/*
# ENV NEXTCLOUD_UPDATE=1
ENTRYPOINT ["/entrypoint.sh"]
CMD ["apache2-foreground"]
