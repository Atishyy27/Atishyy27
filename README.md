**AI engineer intern at NeoSapien, final-year at SGSITS Indore.** I fix bugs in other people's infrastructure and build the tools I use myself.

<samp>
<a href="https://atishay.tech">atishay.tech</a> ·
<a href="https://atishay.tech/journal/">writing</a> ·
<a href="https://atishay.tech/oss/">open source list</a> ·
<a href="https://linkedin.com/in/atishyy27">linkedin</a> ·
<a href="https://x.com/atishyy27">x</a>
</samp>

### Open source

57 merged pull requests in 29 upstream projects, cited in 12 release notes across 11 projects.

| Project | What I fixed | Shipped in |
|---|---|---|
| [Open Policy Agent](https://github.com/open-policy-agent/opa/pull/8887) | Integers above 64 bits lost precision in Rego arithmetic and aggregates, so policies decided on wrong numbers. Also restored error locations for rewritten head variables ([#8885](https://github.com/open-policy-agent/opa/pull/8885)). | [v1.19.0](https://github.com/open-policy-agent/opa/releases/tag/v1.19.0) |
| [fedimint](https://atishay.tech/oss/fedimint-fedimint/) | 8 merged: panics on untrusted durations and timestamps, Lightning fee limits checked on both fee parts ([#8921](https://github.com/fedimint/fedimint/pull/8921)), deposit retries the Bitcoin backend cannot prove ([#9202](https://github.com/fedimint/fedimint/pull/9202)). | [v0.12.0](https://github.com/fedimint/fedimint/releases/tag/v0.12.0), [v0.13.0](https://github.com/fedimint/fedimint/releases/tag/v0.13.0) |
| [Cilium](https://github.com/cilium/cilium/pull/47516) | Envoy xDS node-IP validation with `netip.ParseAddr`. | [v1.21.0-pre.0](https://github.com/cilium/cilium/releases/tag/v1.21.0-pre.0) |
| [OpenTelemetry Python](https://atishay.tech/oss/open-telemetry-opentelemetry-python-contrib/) | `IndexError` on comment-only SQL statements in the psycopg, psycopg2 and SQLAlchemy instrumentations. | [v0.66b0](https://github.com/open-telemetry/opentelemetry-python-contrib/releases/tag/v0.66b0) |
| [SHAP](https://github.com/shap/shap/pull/5164) | KernelExplainer now matches DataFrame columns to the background data by name. | [v0.53.0](https://github.com/shap/shap/releases/tag/v0.53.0) |
| [Meshery](https://github.com/meshery/meshery/pull/20733), [OpenEverest](https://github.com/openeverest/openeverest/pull/2851) | Nil-pointer crashes in MeshSync auto-registration and in JWT key loading. | [v1.0.60](https://github.com/meshery/meshery/releases/tag/v1.0.60), [v2.0.0-dev.2](https://github.com/openeverest/openeverest/releases/tag/v2.0.0-dev.2) |
| [Hyperledger Fabric](https://github.com/hyperledger/fabric/pull/5529) | Database errors silently swallowed in multi-key ledger queries. | merged |

Also merged in Braidpool (6), Podman (4), openswap (4), pyannote-metrics (3), rust-lightning, pixi, Kmesh, pypdf, Opik, MaxText and others. [Full list](https://atishay.tech/oss/).

### Things I built

- [**Maple**](https://github.com/Atishyy27/maple): fills Greenhouse, Lever, Ashby and Workday applications from one profile by matching field labels. No LLM: anything it is not sure of stays blank and gets logged.
- [**SENTINEL**](https://github.com/Atishyy27/xai-aml): explainable anti-money-laundering on transaction graphs, with a SHAP reason behind every flag. National top 5 of 500+ teams at the CIIS CyberShield Hackathon 2025. [Demo](https://ciis-demo.vercel.app/).
- [**Ek Awaaz**](https://gnani-entry.vercel.app): record a Hinglish script once, get voiceovers in other Indian languages in your own cloned voice. Built as a two-person team for Gnani's AI internship challenge.
- [**LeetCode Analytics**](https://github.com/Atishyy27/leetcode-analytics): rating-based analytics inside your LeetCode profile; one of 3 Chrome extensions with 385 users.
- [**e-SAHAYAK**](https://play.google.com/store/apps/details?id=in.gov.mp.shree.sram): labour app for the Govt. of MP, live in 12 factories with 500+ daily active workers.
- Claude Code tooling: [claude-code-identity](https://github.com/Atishyy27/claude-code-identity) (several accounts on one machine) and [usage-cost-plugin](https://github.com/Atishyy27/usage-cost-plugin) (daily token spend in the status line).

### Now and before

- **Now:** evaluation for speech and agent features at NeoSapien.
- **Before:** federated learning research at ABV-IIITM Gwalior (two papers submitted), and government apps for Madhya Pradesh.
- **Competitive programming:** ACM ICPC regionalist 2025, LeetCode Knight, Codeforces Specialist.
