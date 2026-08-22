# pushinbr/pam-api

This name is retained only for migration compatibility. The product is now
[`pushinbr/pam-http`](https://packagist.org/packages/pushinbr/pam-http).

## Start here

```bash
curl -fsSL https://push-in.github.io/pam/install.sh | sh
pam doctor
pam composer remove pushinbr/pam-api
pam composer require pushinbr/pam-http
```

Existing projects may keep resolving this package temporarily because it
depends on the replacement. New code must require `pushinbr/pam-http` directly.
