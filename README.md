s3deploy
=========

[![Latest Version](https://pypip.in/v/s3deploy/badge.png)](https://pypi.python.org/pypi/s3deploy/)
[![Build Status](https://travis-ci.org/petermelias/s3deploy.svg?branch=master)](https://travis-ci.org/petermelias/s3deploy)
[![Montly Downloads](https://pypip.in/d/s3deploy/badge.png?month)](https://pypi.python.org/pypi/s3deploy)
[![Download format](https://pypip.in/format/s3deploy/badge.png)](https://pypi.python.org/pypi/s3deploy/)
[![Coverage Status](https://coveralls.io/repos/petermelias/s3deploy/badge.png?branch=master)](https://coveralls.io/r/petermelias/s3deploy?branch=master)
[![License](https://pypip.in/license/s3deploy/badge.png)](https://pypi.python.org/pypi/s3deploy/)


Deploy static sites to S3 with a single command. Efficient, fast, simple.


### Usage

#### CLI Interface

```bash
$> s3deploy --overwrite --config ~/s3deploy.config.yaml ~/my-static-site
```

That's it.

#### Installation:

```bash
$> pip install s3deploy
```

Notes:

- Omit the ```--overwrite``` option if you don't want to erase the bucket.
- If you name the config file ```s3deploy.config.yaml``` and run the binary from the CWD where that file is present, s3deploy will find it automatically.
- You must have a config file to run s3deploy: ```aws_key```, ```aws_secret```, ```bucket_name``` must all be set.
