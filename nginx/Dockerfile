FROM daocloud.io/library/nginx:1.7.9
RUN useradd nginx -s /sbin/nologin -M
COPY nginx.conf /etc/nginx/
EXPOSE 80
CMD ["nginx", "-g", "daemon off;"]
# CMD ["bash"]
