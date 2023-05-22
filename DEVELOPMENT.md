# Development

## Log4brains

ADRs are managed with [Log4brains](https://github.com/thomvaill/log4brains). 

Instead of installing it, you can run it with Docker:

```bash
docker run --platform linux/amd64 --rm -ti -v $(pwd):/workdir -p 4004:4004 thomvaill/log4brains help
```
