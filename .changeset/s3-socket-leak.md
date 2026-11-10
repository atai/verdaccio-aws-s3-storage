---
'verdaccio-aws-s3-storage': patch
---

Release S3 GetObject sockets when a tarball read is aborted or destroyed, and add optional `connectionTimeout`, `requestTimeout`, `socketTimeout` and `maxSockets`.
