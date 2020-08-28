[![PyPI version](https://badge.fury.io/py/PyUpdater-S3-Plugin.svg)](https://badge.fury.io/py/PyUpdater-S3-Plugin)


Fork from [PyUpdater-S3-Plugin](https://github.com/Digital-Sapphire/PyUpdater-S3-Plugin)

Add `endpoint_url` config item to make it supports S3 compatible services, like [Qiniu](https://www.qiniu.com/) , [Aliyun OSS](https://www.aliyun.com/product/oss) , [Minio](https://min.io/) .


# PyUpdater S3 plugin

PyUpdater upload plugin for AWS S3

## Installing

    $ pip install git+https://github.com/bakyoo/PyUpdater-S3-Plugin.git


## Configuration

System environmental variables

Optional - If set will be used globally. Will be overwritten when you add S3 settings during pyupdater init

| Variable              | Meaning                                 |
| --------------------- |---------------------------------------- |
| PYU_AWS_ID            | Your amazon api id                      |
| PYU_AWS_SECRET        | You amazon api secret                   |
| PYU_AWS_SESSION_TOKEN | You amazon api session token (optional) |
| PYU_AWS_BUCKET        | Bucket name (optional)                  |
| PYU_AWS_BUCKET_REGION | AWS Bucket Region (optional)            |
| PYU_AWS_ENDPOINT_URL  | AWS endpoint url (optional)             |
| PYU_AWS_BUCKET_KEY    | AWS Bucket Key (optional)               |
