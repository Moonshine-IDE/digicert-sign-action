# digicert-sign-action
Sign Windows installer using DigiCert One Signing Manager

| Input | Description |
| --- | --- |
| bin-path | Path to binary you want to sign |
| sm-host | A host from this list: https://docs.digicert.com/en/software-trust-manager/general/requirements.html |
| sm-api-key | DigiCert One API Key |
| sm-client-cert-file-b64 | Client Authentification Certificate in base64 |
| sm-client-cert-password | A password for Client Authentification Certificate |
| sm-thumbprint | Public thumbprint of the Code Signing Certificate |
| sm-keypair-alias | Keypair Alias
