# Lingfield United Trust site

[Charity website](https://www.lingfieldunitedtrust.org/)

```
AWS_ACCESS_KEY_ID=XXXX AWS_SECRET_ACCESS_KEY=XXXX \
  aws s3 cp ./public_html s3://www.lingfieldunitedtrust.org \
  --recursive --exclude '.DS_Store' \
  --acl public-read
```
