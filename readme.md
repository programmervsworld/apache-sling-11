# Apache Sling 11 On CentOS

This docker definition builds a base apache sling 11 server running on port 8080. It's primarily used for tutorials and explanations on the programmervsworld youtube channel, however its bare bones and ready for local development.

# Running
In order to get a running server just use:

```docker run -it -p 8080:8080 programmervsworld/apache-sling-11```

The server can then be accessed at:

```http://localhost:8080/starter/index.html```