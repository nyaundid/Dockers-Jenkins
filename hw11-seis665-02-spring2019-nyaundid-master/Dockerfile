FROM nginx
        
        RUN apt-get update -y
        RUN apt-get install figlet -y
        
        ENTRYPOINT ["figlet", "-f", "script"] 
        LABEL maintainer="DARIUS NYAUNDI <darius.nyaundi@yahoo.com>"
       
        EXPOSE 80
        
        COPY dist /usr/share/nginx/html
