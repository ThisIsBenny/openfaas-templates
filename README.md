# Openfaas Templates

```bash
 faas-cli template pull https://github.com/ThisIsBenny/openfaas-templates
```

## Node 12 Template with Chromium

This template is based on the official Node12 template from OpenFaaS.
The Dockerfile was extended with Chromium, so that you can use libraries like puppeteer on ARM systems.

```bash
faas-cli new <Function-Name> --lang node12withChromium
```
