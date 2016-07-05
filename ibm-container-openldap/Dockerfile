FROM dinkel/openldap:latest

COPY entrypoint-bluemix.sh /entrypoint-bluemix.sh

ENTRYPOINT ["/entrypoint-bluemix.sh"]

CMD ["slapd", "-d", "32768", "-u", "root", "-g", "root"]
