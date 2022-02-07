# Sample configuration for tap-mongodb

## Prerequisites

- Python ^3.8
- poetry

## Setup

Create a .env file with the following variables (and fill in the values):

```
TAP_MONGODB_PASSWORD=
S3_RAW_BUCKET=
TARGET_S3_AWS_ACCESS_KEY_ID=
TARGET_S3_AWS_SECRET_ACCESS_KEY=
```

- Run `poetry install`
- Run `poetry run meltano install`

Now you can run any meltano commands with `poetry run meltano ...`
