FROM nginx:1.9

COPY nginx.conf /etc/nginx/nginx.conf
COPY registry.conf /etc/nginx/conf.d/registry.conf
COPY docker-registry-v2.conf /etc/nginx/docker-registry-v2.conf
COPY domain.crt /etc/nginx/domain.crt
COPY domain.key /etc/nginx/domain.key
