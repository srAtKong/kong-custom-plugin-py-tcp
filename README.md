# kong-custom-plugin-py-tcp
Python Custom Plugins for Kong - TCP Stream

A simple custom plugin for Kong using te python PDK - used with kong in the tcp-stream mode

1. Build the Kong image from the dockerfile

```code
docker build -t <tag-name> .
```

3. Update the docker-compose file with the image built

```code
image: <tag-name>
```

5. Go!
