#FROM javastreets/mule:latest    # Commented Due to Rate limit of Docker Hub 

# Pushed the above image in Private repo and calling in FROM section
FROM 996941117170.dkr.ecr.us-east-1.amazonaws.com/mulesoft-base:latest 
COPY ./target/say-hello-mule4-docker*.jar /opt/mule/apps/

CMD [ "/opt/mule/bin/mule"]
