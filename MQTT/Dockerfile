FROM arm32v6/eclipse-mosquitto

COPY ./mosquitto/mosquitto.conf /mosquitto/config/mosquitto.conf
#COPY ./mosquitto/entrypoint.sh /entrypoint.sh
COPY ./mosquitto/passwd /mosquitto/config/passwd

#ENTRYPOINT ["sh", "/entrypoint.sh"]
#CMD ["mosquitto_passwd",  "-U",  "mosquitto/config/passwd"]
