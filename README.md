[![PyPI version](https://badge.fury.io/py/PyUpdater-S3-Plugin.svg)](https://badge.fury.io/py/PyUpdater-S3-Plugin)

# PyUpdater S3 plugin

PyUpdater upload plugin for S3 Generica

## Installing

    $ pip install PyUpdater-S3-plugin


## Configuration

System environmental variables

Optional - If set will be used globally. Will be overwritten when you add scp settings during pyupdater init

| Variable              | Meaning                                 |
| --------------------- |---------------------------------------- |
| PYU_AWS_ID           | Your amazon api id                      |
| PYU_AWS_SECRET       | You amazon api secret                   |
| PYU_AWS_SESSION_TOKEN | You amazon api session token (optional) |
| PYU_AWS_BUCKET       | Bucket name (optional)                  |
| PYU_REGION            | Region to use                           |
| PYU_URL               | URL for the s3 service
