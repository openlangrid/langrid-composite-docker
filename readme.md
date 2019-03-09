# docker files for servicegrid core node

## Getting started

1. Modify ./volumes/tomcat/conf/Catalina/localhost/langrid-composite-service-2.0.xml to fit your settings.
2. Place war file to ./volumes/tomcat/webapps
3. Modify ./docker-compose.yml to make settings consistent.
4. Run docker-compose
```
# launch services (tomcat)
docker-compose up -d
```

