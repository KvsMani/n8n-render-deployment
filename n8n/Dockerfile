FROM n8nio/n8n

ENV N8N_DEFAULT_BINARY_DATA_MODE=filesystem
ENV WEBHOOK_URL=https://n8n-service.onrender.com/
ENV N8N_BASIC_AUTH_ACTIVE=true
ENV N8N_BASIC_AUTH_USER=admin
ENV N8N_BASIC_AUTH_PASSWORD=securepassword

VOLUME /home/node/.n8n
EXPOSE 5678

CMD ["n8n"]