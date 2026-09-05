<div align="center">

# Tisankan Jeyakumar

### Chief Technical Officer · [Yarl Ventures (PVT) Ltd](https://yarlventures.com) · Jaffna, Sri Lanka

**I build production systems people depend on daily.**
Healthcare, education and commerce. Node.js and TypeScript on the backend,
React and Flutter on the front, AWS underneath.

<br/>

[![Website](https://img.shields.io/badge/tisankan.dev-0B0B0B?style=for-the-badge&logo=googlechrome&logoColor=white)](https://tisankan.dev)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/tisankan)
[![npm](https://img.shields.io/badge/npm-CB3837?style=for-the-badge&logo=npm&logoColor=white)](https://www.npmjs.com/~tisankan)
[![dev.to](https://img.shields.io/badge/dev.to-0A0A0A?style=for-the-badge&logo=devdotto&logoColor=white)](https://dev.to/tisankan)
[![Email](https://img.shields.io/badge/hello@tisankan.dev-EA4335?style=for-the-badge&logo=maildotru&logoColor=white)](mailto:hello@tisankan.dev)

![Profile views](https://komarev.com/ghpvc/?username=rascal-sl&label=Profile%20views&color=0e75b6&style=flat-square)
[![Followers](https://img.shields.io/github/followers/rascal-sl?style=flat-square&logo=github&label=Followers&color=1F6FEB)](https://github.com/rascal-sl)

</div>

---

## What I actually do

I lead engineering at a Sri Lankan technology company and still write most of the backend myself. The work is systems people depend on daily rather than side projects: appointment booking that must not double-book, payment flows that must not double-charge, and student records that must reconcile at the end of term.

Most of what I know came from the unglamorous half of that: idempotent payment webhooks, race-safe state transitions, timezone arithmetic that survives a daylight saving change, and audit trails that hold up when somebody disputes a charge six months later.

**Opinions I hold, having been wrong before.** Pick the boring option. Validate once at the edge and trust it downstream. Make state transitions atomic instead of hoping. Treat a modular monolith as the default until something genuinely forces a split. Measure before you believe a rule works.

---

## Organizations I build under

| Organization | What it is | |
| --- | --- | --- |
| [**Yarl Ventures (PVT) Ltd**](https://github.com/Yarl-Ventures-PVT-Ltd) | The company. Technology partner for SMEs and growth-stage businesses | [yarlventures.com](https://yarlventures.com) |
| [**Tisankan.dev**](https://github.com/Tisankan-dev) | Open-source packages and developer tooling | [tisankan.dev](https://tisankan.dev) |
| [**EDUS Tutor**](https://github.com/edustutor) | Education platform. Classes, attendance, exams, fee collection | [edustutor.com](https://edustutor.com) |
| [**MediMan**](https://github.com/mediman-ife) | Telehealth. Consultations, video and audio calls, e-prescriptions | [mediman.life](https://mediman.life) |
| [**Starly.me**](https://github.com/Starly-me) | Product work in progress | |

### In production

| Product | Scale |
| --- | --- |
| **MediMan** telehealth platform | 100+ verified doctors, 1,200+ users across Sri Lanka |
| **EDUS** education platform | Powers EDUS Online Institute and EDUS Lanka |
| **Yarl Ventures CRM** | Company-wide leads, customers, projects and invoicing |

---

## Open source

I publish tooling I actually use. Everything MIT, documented and maintained.

| Package | What it does | Version |
| --- | --- | --- |
| [**vetdeps**](https://www.npmjs.com/package/vetdeps) | Tells you whether an npm package you are about to install is the one you think it is. Catches typosquats, AI-hallucinated names and known malware. Zero dependencies, zero telemetry | [![npm](https://img.shields.io/npm/v/vetdeps?style=flat-square&color=cb3837&logo=npm&logoColor=white)](https://www.npmjs.com/package/vetdeps) |
| [**depshield**](https://www.npmjs.com/package/depshield) | Dependency analyzer. Finds unused packages and cuts bundle size with AST-based detection | [![npm](https://img.shields.io/npm/v/depshield?style=flat-square&color=cb3837&logo=npm&logoColor=white)](https://www.npmjs.com/package/depshield) |
| [**async-queue-manager-tsk**](https://www.npmjs.com/package/async-queue-manager-tsk) | Async task queues with DAG dependencies and adaptive concurrency | [![npm](https://img.shields.io/npm/v/async-queue-manager-tsk?style=flat-square&color=cb3837&logo=npm&logoColor=white)](https://www.npmjs.com/package/async-queue-manager-tsk) |
| [**express-auth-magic**](https://www.npmjs.com/package/express-auth-magic) | Express authentication middleware covering JWT, OAuth and sessions | [![npm](https://img.shields.io/npm/v/express-auth-magic?style=flat-square&color=cb3837&logo=npm&logoColor=white)](https://www.npmjs.com/package/express-auth-magic) |
| [**openrouter-ai-sdks**](https://www.npmjs.com/package/openrouter-ai-sdks) | OpenRouter AI SDK for Node.js | [![npm](https://img.shields.io/npm/v/openrouter-ai-sdks?style=flat-square&color=cb3837&logo=npm&logoColor=white)](https://www.npmjs.com/package/openrouter-ai-sdks) |
| [**s3-file-uploader**](https://www.npmjs.com/package/s3-file-uploader) | Small wrapper for uploading files to Amazon S3 | [![npm](https://img.shields.io/npm/v/s3-file-uploader?style=flat-square&color=cb3837&logo=npm&logoColor=white)](https://www.npmjs.com/package/s3-file-uploader) |
| [**social-share-links-generator**](https://www.npmjs.com/package/social-share-links-generator) | Share link generation for the major social platforms | [![npm](https://img.shields.io/npm/v/social-share-links-generator?style=flat-square&color=cb3837&logo=npm&logoColor=white)](https://www.npmjs.com/package/social-share-links-generator) |
| [**capdrift**](https://pub.dev/packages/capdrift) | Shows what a Dart package can do, what changed between versions, and whether that change violates your policy. Capability fingerprints, execution surfaces, behavioural diffing. Never executes the code it reads | [![pub](https://img.shields.io/pub/v/capdrift?style=flat-square&color=0175C2&logo=dart&logoColor=white)](https://pub.dev/packages/capdrift) |
| [**deo_emerges**](https://pub.dev/packages/deo_emerges) | Flutter networking on Dio. Request deduplication, typed responses, uploads and downloads with progress. Two dependencies, all six platforms, WebAssembly ready, 160/160 on pub.dev | [![pub](https://img.shields.io/pub/v/deo_emerges?style=flat-square&color=0175C2&logo=dart&logoColor=white)](https://pub.dev/packages/deo_emerges) |
| [**file_compression_plus**](https://pub.dev/packages/file_compression_plus) | Flutter. Image and PDF compression with quality and dimension control | [![pub](https://img.shields.io/pub/v/file_compression_plus?style=flat-square&color=0175C2&logo=dart&logoColor=white)](https://pub.dev/packages/file_compression_plus) |

### Upstream contributions

Merged into projects I do not maintain.

| Project | Contribution | PR |
| --- | --- | --- |
| [**nanocoder**](https://github.com/Nano-Collective/nanocoder) | Stream the daemon log tail instead of reading the whole file to return its last 64KB. Also corrects a byte offset applied to a decoded string, which shortened the window on any log holding multi-byte characters | [#1043](https://github.com/Nano-Collective/nanocoder/pull/1043) |
| [**nanocoder**](https://github.com/Nano-Collective/nanocoder) | Release the pending slot in the daemon IPC client when serializing or writing a request throws, instead of leaving one entry per failed request for the lifetime of the client | [#1045](https://github.com/Nano-Collective/nanocoder/pull/1045) |
| [**nanocoder**](https://github.com/Nano-Collective/nanocoder) | Stop an MCP disconnect rebuilding the whole tool registry, which discarded workspace custom tools with their approval metadata, skill and bundle tools, and the gate that hides `web_search` without an API key | [#1056](https://github.com/Nano-Collective/nanocoder/pull/1056) |
| [**nanocoder**](https://github.com/Nano-Collective/nanocoder) | Route sub-agent tool approvals to the ACP client rather than denying them silently, so a client that gates writes sees delegated work as well as top-level calls | [#1080](https://github.com/Nano-Collective/nanocoder/pull/1080) |
| [**nanocoder**](https://github.com/Nano-Collective/nanocoder) | Expand brace patterns such as `*.{ts,tsx}` in event-router subscription globs, so a skill subscribed with one actually fires. Unbalanced braces stay literal rather than building a regex that throws | [#1079](https://github.com/Nano-Collective/nanocoder/pull/1079) |
| [**plotly.js**](https://github.com/plotly/plotly.js) | Add `layout.legend.groupdoubleclick`, so a legend double-click can isolate a single trace while a single click still toggles its whole group. Follows the existing `groupclick` pattern | [#7997](https://github.com/plotly/plotly.js/pull/7997) |
| [**super-productivity**](https://github.com/super-productivity/super-productivity) | Anchor the schedule day panel's `now` to the day being shown, so the panel stops emptying between midnight and a custom start-of-next-day. Pulls the anchoring the month view already did inline into one helper both views share | [#9835](https://github.com/super-productivity/super-productivity/pull/9835) |

---

## Writing

**[Checking whether an npm package "exists" stopped working](https://dev.to/tisankan/checking-whether-an-npm-package-exists-stopped-working-2j0e)**

AI tools hallucinate package names about 19.7% of the time, and attackers pre-register the predictable ones. That quietly broke the existence check most install guards rely on. Includes the two detection rules I got wrong and had to measure my way out of.

More at [tisankan.dev/blog](https://tisankan.dev/blog/).

---

## Tech

<div align="center">

![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![NestJS](https://img.shields.io/badge/NestJS-E0234E?style=flat-square&logo=nestjs&logoColor=white)
![Express](https://img.shields.io/badge/Express-000000?style=flat-square&logo=express&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![Flutter](https://img.shields.io/badge/Flutter-02569B?style=flat-square&logo=flutter&logoColor=white)
![Dart](https://img.shields.io/badge/Dart-0175C2?style=flat-square&logo=dart&logoColor=white)

![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-FF4438?style=flat-square&logo=redis&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-FF9900?style=flat-square&logo=amazonwebservices&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Cloudflare](https://img.shields.io/badge/Cloudflare-F38020?style=flat-square&logo=cloudflare&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)

</div>

---

## Activity

<div align="center">

[![Streak](https://streak-stats.demolab.com/?user=rascal-sl&theme=github-dark-blue&hide_border=true&date_format=j%20M%5B%20Y%5D)](https://github.com/rascal-sl)

[![Activity graph](https://github-readme-activity-graph.vercel.app/graph?username=rascal-sl&theme=github-compact&hide_border=true&area=true)](https://github.com/rascal-sl)

</div>

Most of my work lives inside the organizations above rather than on this profile.

---

<div align="center">

### Elsewhere

[![X](https://img.shields.io/badge/@JTisankan-000000?style=flat-square&logo=x&logoColor=white)](https://x.com/JTisankan)
[![ORCID](https://img.shields.io/badge/ORCID-A6CE39?style=flat-square&logo=orcid&logoColor=white)](https://orcid.org/0009-0009-4600-7236)
[![pub.dev](https://img.shields.io/badge/pub.dev-0175C2?style=flat-square&logo=dart&logoColor=white)](https://pub.dev/publishers/tisankan.dev/packages)
[![Yarl Ventures](https://img.shields.io/badge/Yarl%20Ventures-1F6FEB?style=flat-square&logo=briefcase&logoColor=white)](https://yarlventures.com)

Open to talking about backend architecture, supply chain security,
and building engineering teams in Sri Lanka.

**[hello@tisankan.dev](mailto:hello@tisankan.dev)**

</div>
