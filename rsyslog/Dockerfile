FROM larocca/rsyslog:latest
LABEL org.freenas.interactive="false"		\
      org.freenas.version="3.2"			\
      org.freenas.upgradeable="false"		\
      org.freenas.expose-ports-at-host="true"	\
      org.freenas.autostart="true"		\
      org.freenas.port-mappings="514:514/tcp,514:514/udp"
      org.freenas.volumes="[                            \
          {                                             \
              \"name\": \"/var/log\",                   \
              \"descr\": \"log files\"                  \
          }                                             \
      ]"
