FROM nginx
RUN rm -rf /usr/share/nginx/html/index.html
RUN rm -rf /etc/nhinx/nginx.conf
RUN rm -rf /etc/nginx/conf.d/defauld.conf
COPY nginx.conf /etc/nhinx/nginx.conf
COPY static /usr/share/nginx/html/