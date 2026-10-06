# Awesome-Private-Public-Key-Infrastructure-Pki-Ca

## Top Private Public Key Infrastructure (PKI/CA) Ecosystem



**Curated List of SaaS Products & Open-Source GitHub Projects**  

*Focused on Private Certificate Authorities, Certificate Lifecycle & Self-Hosted PKI*  

**Last updated: October 2026**



This repository tracks notable **commercial private PKI platforms** and **open-source projects** that issue, manage, and revoke X.509 certificates for internal services, devices, and users — enabling mTLS, code signing, and secure machine-to-machine authentication without public CA dependencies.



**Examples** include AWS Private Certificate Authority, DigiCert ONE, Sectigo Certificate Manager, HashiCorp Vault PKI, Keyfactor Command, Venafi Trust Protection Platform, AppViewX CERT+, GlobalSign Atlas, Smallstep, and Entrust PKIaaS (the category leaders).



**Open-source emphasis**: Private PKI is one of the strongest open-source security domains. **Smallstep** leads as the modern open-source CA, **step-ca** delivers full ACME, **EJBCA** provides enterprise-grade PKI, and **CFSSL**, **Boulder**, **Dogtag**, and **OpenXPKI** offer CA foundations. **Cert-Manager** automates Kubernetes certificates, **Vault PKI** handles secrets-based issuance, and **SPIFFE/SPIRE** provides workload identity. **XCA** and **OpenSSL** complete the toolkit. This section is heavily expanded.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saas-hosted-platforms)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms



- **[AWS Private Certificate Authority](https://aws.amazon.com/private-ca/)**  

  **AWS's managed private CA** — issue and manage private certificates for internal services . **Integrated with ACM, IAM, and CloudWatch** . **Best for AWS-native private PKI** .



- **[DigiCert ONE](https://www.digicert.com/)**  

  **Enterprise PKI and certificate management** — private CA, certificate lifecycle, and IoT identity . **Best for large enterprises** .



- **[Sectigo Certificate Manager](https://sectigo.com/)**  

  **Certificate lifecycle management** — private and public certificates at scale . **Best for enterprise certificate management** .



- **[HashiCorp Vault PKI](https://www.hashicorp.com/products/vault)**  

  **Vault's PKI secrets engine** — dynamic certificate issuance and revocation . **Best for Vault users** .



- **[Keyfactor Command](https://www.keyfactor.com/)**  

  **Machine identity management** — PKI, certificate lifecycle, and code signing . **Best for enterprise and IoT** .



- **[Venafi Trust Protection Platform](https://venafi.com/)**  

  **Enterprise machine identity management** — certificate lifecycle automation at scale . **Best for large enterprises** .



- **[AppViewX CERT+](https://www.appviewx.com/)**  

  **Certificate lifecycle automation** — discovery, renewal, and compliance . **Best for enterprise certificate management** .



- **[GlobalSign Atlas](https://www.globalsign.com/)**  

  **Cloud PKI platform** — private CA and certificate management . **Best for managed PKI** .



- **[Smallstep](https://smallstep.com/)**  

  **Modern PKI platform** — see Open-Source section for the core project.



- **[Entrust PKIaaS](https://www.entrust.com/)**  

  **Managed PKI as a service** — private CA and certificate lifecycle . **Best for enterprise PKI** .



## Open-Source GitHub Projects



### Private Certificate Authorities



- **[Smallstep](https://github.com/smallstep/certificates)**  

  **The leading modern open-source certificate authority**, Apache-2.0 licensed with **6,000+ GitHub stars** . **ACME, OIDC, and X.509 certificate issuance** . **step-ca** is a full ACME CA with short-lived certificates . **Automated certificate rotation and renewal** . **The de facto open-source private CA** . **Best for modern private PKI** .



- **[step-ca](https://github.com/smallstep/certificates)** — Already listed. **ACME certificate authority** .



- **[EJBCA Community](https://github.com/Keyfactor/ejbca-ce)**  

  **Enterprise-grade open-source CA**, LGPL-2.1 licensed . **Full-featured with OCSP, SCEP, ACME, and EST** . **Certificate lifecycle management** . **Best for enterprise PKI** .



- **[CFSSL](https://github.com/cloudflare/cfssl)**  

  **Cloudflare's PKI and TLS toolkit**, BSD-2-Clause licensed with **8,000+ GitHub stars** . **Certificate signing, verification, and bundling** . **Best for custom PKI** .



- **[Boulder](https://github.com/letsencrypt/boulder)**  

  **Let's Encrypt's ACME CA implementation**, MPL-2.0 licensed . **The CA behind Let's Encrypt** . **Best for ACME CA implementation** .



- **[Dogtag PKI](https://github.com/dogtagpki/pki)**  

  **Red Hat's certificate system**, GPL-2.0 licensed . **Enterprise PKI with certificate lifecycle** . **Best for enterprise PKI** .



- **[OpenXPKI](https://github.com/openxpki/openxpki)**  

  **Open-source PKI with workflow engine**, Apache-2.0 licensed . **Best for complex PKI workflows** .



- **[XCA](https://github.com/chris2511/xca)**  

  **X Certificate and Key Management**, BSD-3-Clause licensed . **GUI for certificate management** . **Best for desktop PKI** .



### Certificate Automation & Kubernetes



- **[Cert-Manager](https://github.com/cert-manager/cert-manager)**  

  **Kubernetes certificate management**, Apache-2.0 licensed with **12,000+ GitHub stars** . **Automates TLS certificate issuance and renewal** . **Supports Let's Encrypt, Vault, Venafi, and private CAs** . **Best for Kubernetes certificates** .



- **[Vault PKI](https://github.com/hashicorp/vault)**  

  **Vault's PKI secrets engine**, BSL licensed . **Dynamic certificate issuance** . **Best for Vault users** .



- **[OpenBao PKI](https://github.com/openbao/openbao)**  

  **Linux Foundation fork of Vault**, MPL-2.0 licensed . **PKI secrets engine and secret management** . **Best for Vault without BSL** .



- **[SPIFFE/SPIRE](https://github.com/spiffe/spire)**  

  **Workload identity with automatic certificate rotation**, Apache-2.0 licensed with **1,700+ GitHub stars** . **SPIFFE ID framework** . **Best for zero-trust workload identity** .



- **[Teleport](https://github.com/gravitational/teleport)**  

  **Certificate-based infrastructure access**, Apache-2.0 licensed with **16,000+ GitHub stars** . **SSH, Kubernetes, and database access** . **Best for infrastructure access** .



### Certificate Libraries & Tools



- **[OpenSSL](https://github.com/openssl/openssl)**  

  **The foundational cryptography and TLS toolkit**, Apache-2.0 licensed . **Certificate generation and management** . **Best for cryptographic operations** .



- **[LibreSSL](https://github.com/libressl/portable)**  

  **OpenBSD's OpenSSL fork**, ISC licensed . **Security-focused cryptography** . **Best for security-conscious deployments** .



- **[BoringSSL](https://github.com/google/boringssl)**  

  **Google's OpenSSL fork**, ISC licensed . **Used by Chrome and Android** . **Best for Google ecosystem** .



- **[mkcert](https://github.com/FiloSottile/mkcert)**  

  **Simple local CA for development**, BSD-3-Clause licensed with **50,000+ GitHub stars** . **Zero-config TLS certificates for localhost** . **Best for local development** .



- **[certstrap](https://github.com/square/certstrap)**  

  **Simple CA and certificate management**, Apache-2.0 licensed . **Command-line CA** . **Best for simple PKI** .



- **[easy-rsa](https://github.com/OpenVPN/easy-rsa)**  

  **Simple CA for OpenVPN**, GPL-2.0 licensed . **Certificate management for VPN** . **Best for OpenVPN PKI** .



### Additional Strong Open-Source Options



- **cfssl** — Cloudflare's PKI toolkit .

- **Certbot** — Let's Encrypt client .

- **ACME.sh** — ACME protocol client .

- **Lego** — Let's Encrypt client in Go .

- **Cert-manager** — Kubernetes certificates .

- **Vault PKI** — Dynamic certificates .

- **OpenBao** — Vault fork .

- **Dogtag** — Red Hat certificate system .

- **EJBCA** — Enterprise CA .

- **OpenXPKI** — Workflow-based PKI .



**Frameworks for building custom private PKI solutions**: Combine **Smallstep** or **step-ca** for modern ACME private CA with short-lived certificates . Use **EJBCA Community** for enterprise-grade PKI with OCSP, SCEP, and EST . Deploy **Cert-Manager** for Kubernetes certificate automation . Choose **Vault PKI** or **OpenBao** for dynamic certificate issuance . Integrate **SPIFFE/SPIRE** for workload identity with automatic rotation . Use **CFSSL** for custom PKI tooling . Note that true enterprise PKI with managed certificate lifecycle, compliance validation, and vendor-supported SLAs (Venafi, Keyfactor, DigiCert) remains primarily commercial territory; open-source stacks provide strong certificate authority, automation, and workload identity foundations that require integration for complete private PKI management.



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- Private PKI platforms manage cryptographic keys and certificates that provide access to critical systems. Self-hosted solutions require proper security hardening, key management, and backup procedures.

- **Certificate authority private keys are extremely sensitive** — compromise allows impersonation of any service. HSM-backed key storage is recommended for production CAs .

- **License considerations**: Smallstep uses Apache-2.0, EJBCA uses LGPL-2.1, Cert-Manager uses Apache-2.0, and Vault uses BSL. Verify licensing against your use case before committing .

- **Certificate rotation is critical** — short-lived certificates reduce compromise impact but require automation. SPIRE, Cert-Manager, and Smallstep provide rotation capabilities .

- The open-source ecosystem provides strong certificate authority, automation, and workload identity foundations, but **managed certificate lifecycle, compliance validation, and vendor-supported SLAs** remain primarily commercial offerings.



---



**Made for security engineers, platform teams, and organizations seeking private PKI sovereignty.**  

Let's make private public key infrastructure more open, transparent, and secure.
