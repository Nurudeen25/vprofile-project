FROM nginx
LABEL "Project"="Vprofile"
LABEL "Author"="Deen"
#this will move default conf file and copy to our own build config file
RUN rm -rf /etc/nginx/conf.d/default.conf
COPY nginvproapp.conf /etc/nginx/conf.d/vproapp.conf
#make sure we create this nginvproapp.conf in same location