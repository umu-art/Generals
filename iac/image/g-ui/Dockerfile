FROM nginx:stable-alpine3.17
LABEL authors="vikazeni"
COPY /g-ui/dist/gui/browser /usr/share/nginx/html
COPY /iac/image/g-ui/nginx.conf /etc/nginx/conf.d/default.conf
