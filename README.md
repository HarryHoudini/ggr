# ggr

1. docker-compose up
2. docker run --name selenoid_new3 -p 4440:4444 -v /var/run/docker.sock:/var/run/docker.sock -v '~/Documents/ggr/etc/e/:/etc/selenoid/:ro' aerokube/selenoid:latest-release
3. docker kill -s HUP <container_id>

http://localhost:8888/status
http://localhost:8080

http://test:test-password@localhost:4444/wd/hub
