# leemcq.github.io

GitHub Pages user site. Its only job is to serve `/.well-known/assetlinks.json` at the host root, which Android checks to let Trusted Web Activity apps (e.g. Fellowship Face-Off, `com.leemcq.fellowshipfaceoff`, start URL `https://leemcq.github.io/logosliving/`) open full-screen without a browser bar.

After the first Play upload, add the **Play App Signing** SHA-256 (Play Console > Setup > App signing) to `sha256_cert_fingerprints` alongside the upload key fingerprint.

Do not add a custom domain (CNAME) to this repo: that would redirect all project sites under leemcq.github.io.
