cat <<EOF > docker-compose.yml
version: '3'
services:
  web-app:
    build: .
    ports:
      - "8085:80"
    volumes:
      - ./index.html:/usr/share/nginx/html/index.html
EOF
