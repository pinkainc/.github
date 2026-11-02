## Pinka

Open-source core banking. Each project implements a public API that a closed platform
already defines, the way MinIO implements S3: existing clients work unchanged, and
everything behind the API is our own design. Compatibility is shown with recordings and
tests, not claimed.

| Repository | What it is |
| --- | --- |
| [open-ledger](https://github.com/pinkainc/open-ledger) | Minka-compatible ledger. The official Minka SDK and CLI run against it unchanged; all 146 API operations are confirmed against recordings of the Minka sandbox. Site: [open-ledger.mpt.hr](https://open-ledger.mpt.hr) |
| [open-banking](https://github.com/pinkainc/open-banking) | Bank server compatible with the LHV Connect API: mutual TLS, ISO 20022 payments and statements, VIBANs, SEPA direct debit, FX. Runs as a local emulator; it can book on open-ledger. |
| [docs.minka.io](https://github.com/pinkainc/docs.minka.io) | Reference mirror of the Minka documentation and OpenAPI spec that open-ledger is built against. |

All code is MIT. The projects are independent and not affiliated with Minka or LHV.
