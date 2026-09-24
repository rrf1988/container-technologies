FROM nginx:stable-alpine

LABEL org.opencontainers.image.title="FIAP Lab-01"
LABEL org.opencontainers.image.description="Página de exemplo servida pelo NGINX"

COPY index.html /usr/share/nginx/html/index.html

EXPOSE 80

CMD ["nginx", "-g", "daemon off;"]
