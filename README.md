# kong-custom-plugin-py-tcp
Python Custom Plugins for Kong - TCP Stream

A simple custom plugin for Kong using te python PDK - used with kong in the tcp-stream mode

1. Build the Kong image from the dockerfile

```code
docker build -t <tag-name> .
```

2. Update the docker-compose file with the image built

```code
image: <tag-name>
```

3. The declarative config file included creates a single service and route pointing to tcpbin. To test, run

```code
nc localhost 5555
<enter a character and it will be echoed back>
```

You should see hello messages on the Kong logs emiited by the custom plugin
