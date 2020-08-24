# Python_WebAPI7
create a hello world web application API that listens on port 8080 and greets a user with Hello!

# 3) What other information would you add to health endpoint json object in step 2? Explain what would be the use case for that extra information?

Normally, for helath check endpoints, we expose service health or functional endpoints, so that these checks if they fail would alert devops engineers through notifications via monitoring tools


# Docker Build Command for creating docker image

docker build -t -name hello-world-flask:0.1 .

# Docker Run Command for running the API

docker run -d -p8080:8080 hello-world-flask:0.1