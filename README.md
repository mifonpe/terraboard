# Terraboard🌍⚙️

Simple script to test [Terraboard](https://github.com/camptocamp/terraboard) locally.

## Installing it

```bash
curl -fsSL -o terraboard https://raw.githubusercontent.com/mifonpe/terraboard/main/terraboard
chmod 700 terraboard
mv terraboard /usr/local/bin
```

## Running it

```bash
export AWS_ACCESS_KEY_ID=<your-key>
export AWS_SECRET_ACCESS_KEY=<your-secret-key>
export AWS_REGION=<your-region>
export TFSTATE_BUCKET=<your-bucket>
terraboard up
```

## Cleaning up
```bash
terraboard down
```
