# Tokio Proxy
This project demonstrates a basic HTTP proxy built with Rust and the Tokio framework.

**Self-Signed Certificate Generation**

Utilize the `keygen.sh` script to generate a self-signed SSL certificate for secure proxy operations. Execution of this script produces a new certificate.

**Verification**

When testing, use the `--insecure` flag with `curl`. Without this flag, connections may be rejected as the self-signed certificate isn't recognized by most clients.