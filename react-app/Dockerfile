FROM nginx:alpine
RUN apk add --no-cache curl
COPY dist/ /usr/share/nginx/html

HEALTHCHECK CMD curl --fail http://localhost:5000 || exit 1 
