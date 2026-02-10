FROM nginx:latest
#RUN apt-get update
#ENTRYPOINT ["/usr/share/nginx/html"]
COPY ./my-zepto-source-code /usr/share/nginx/html/
#COMMAND ["ls -l"]
EXPOSE 80
CMD ["nginx", "-g", "daemon off;"]
