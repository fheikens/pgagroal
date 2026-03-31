# Changelog

## 2.1.0

- Initial public Docker Hub release
- Validated against PostgreSQL 14, 15, 16, 17, and 18
- Verified: startup, query path, pooling, authentication, metrics
- Security scans: clean (Trivy, gitleaks)
- Known issues:
  - Alpine build currently fails (musl / libpthread)
  - io_uring not supported in Docker Desktop (use `ev_backend = epoll`)
