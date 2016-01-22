# elasticsearch-kubernetes-aws docker image

It expects aws credentials to be mounted at `/etc/secrets/aws/aws.env` in format:

```bash
export AWS_ACCESS_KEY_ID=<your access key id here>
export AWS_SECRET_ACCESS_KEY=<your access key secret here>
```

MIT license.
