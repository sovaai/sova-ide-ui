- docker build --tag sova-ide-ui:test .
- docker run --rm -p 3000:5000 --name sova-ide-test-ui sova-ide-ui:test