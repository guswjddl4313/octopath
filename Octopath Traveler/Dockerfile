FROM tomcat:8.5

RUN apt-get update && apt-get install -y wget unzip

COPY app2/struts2-blank.war /usr/local/tomcat/webapps/app2.war

COPY app1/index.html /usr/local/tomcat/webapps/app1/index.html

Run echo "FLAG{D0_you_7hink_it_i5_4_vuln3rabi1ity}" > ./flag.txt
RUN chmod 444 ./flag.txt