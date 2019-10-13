# curl-docker

## Contains

* CURL
* OpenSSL
* Brotli
* NgHTTP2

## How to use

### Example

The base command when starting the container is `curl`. An example of a curl command could be:

```
curl -svo /dev/null http://example.com
```

When using this container the command would be:

```
docker run --rm -it theh00k/curl -svo /dev/null http://example.com
```

Bash Integration

To replace the local curl command you can add the following to your `.bashrc`

```
alias curl="docker run --rm -it theh00k/curl"
```

This will allow you to use:

```
curl -svo /dev/null http://example.com
```
