# AWS Individual Sandbox • End-to-End AI CI/CD Test Bench

A modular sandbox repository separating the AI GitHub ⟷ AWS end-to-end bridge test bench into individual standalone test applications, prefixed by **Module** and **Test Number**.

Live GitHub Pages Hub: [https://cosmosanalytics.github.io/AWS-individual-sandbox/](https://cosmosanalytics.github.io/AWS-individual-sandbox/)

---

## 🔒 Owner Unlock & Public Security Gate

Because this repository is public, **every individual test app and the index hub are protected by the Owner Unlock Gate**:
- **Locked / Non-Owner Mode**: Non-owners cannot execute actions or trigger cloud workloads. All test buttons and execution triggers are strictly disabled and blocked until the Owner Passcode is entered.
- **Unlocked / Owner Live Mode**: Enter your Owner Passcode in the top bar. Unlocking in one test or on the hub automatically unlocks all 14 test apps across the browser session (`sessionStorage`), authorizing live execution on **AWS us-east-2** (Project *For Each and Every*, `966273137102`) and real commits on GitHub.

---

## 📂 14 Individual Test Applications

### Module A: Git / PR Automation
- **Test 01**: [`mod_a_test_01_git_push.html`](mod_a_test_01_git_push.html) — `git push origin main` (Push File via Lambda to GitHub `main` & `gh-pages`)
- **Test 02**: [`mod_a_test_02_pull_request.html`](mod_a_test_02_pull_request.html) — Pull Request Gate (Initiate isolated sandbox branch & review diff)

### Module B: 4 GitHub CI/CD Action Jobs
- **Test 03**: [`mod_b_test_03_ast_review.html`](mod_b_test_03_ast_review.html) — Action Job 1 (AI AST Syntax Review & Cognitive Tier Audit)
- **Test 04**: [`mod_b_test_04_secret_shield.html`](mod_b_test_04_secret_shield.html) — Action Job 2 (DevSecOps Zero-Leak Secret Shield & Key Scanner)
- **Test 05**: [`mod_b_test_05_ci_matrix.html`](mod_b_test_05_ci_matrix.html) — Action Job 3 (Automated 48/48 CI Test Matrix & Policy Invariants)
- **Test 06**: [`mod_b_test_06_aws_401_preflight.html`](mod_b_test_06_aws_401_preflight.html) — Action Job 4 (AWS us-east-2 401 Gate Pre-Flight Security Probe)

### Module C: GitHub ⟷ AWS 3-Way Bridge
- **Test 07**: [`mod_c_test_07_github_to_aws_push.html`](mod_c_test_07_github_to_aws_push.html) — Connection ① (GitHub ➔ AWS Forward Push Trigger Channel)
- **Test 08**: [`mod_c_test_08_github_to_aws_pull.html`](mod_c_test_08_github_to_aws_pull.html) — Connection ② (GitHub ➔ AWS Reverse Telemetry Pull Channel)
- **Test 09**: [`mod_c_test_09_aws_to_github_return.html`](mod_c_test_09_aws_to_github_return.html) — Connection ③ (AWS ➔ GitHub Step Functions & Bedrock Return Channel)

### Module D: Shield & Multi-Engine AI Dispatch
- **Test 10**: [`mod_d_test_10_cost_shield.html`](mod_d_test_10_cost_shield.html) — Dual-Mode Cost Shield ($0 Demo vs Live AWS Execution Gate)
- **Test 11**: [`mod_d_test_11_multi_engine_ai.html`](mod_d_test_11_multi_engine_ai.html) — Multi-Engine AI Dispatch (WebGPU / Groq LPU / Bedrock Claude Sonnet 4.6)

### Module E: Cloud State, Storage & Graph
- **Test 12**: [`mod_e_test_12_amazon_s3.html`](mod_e_test_12_amazon_s3.html) — Amazon S3 (Upload / PutObject & Download / GetObject in `us-east-2`)
- **Test 13**: [`mod_e_test_13_vector_db.html`](mod_e_test_13_vector_db.html) — Vector Database & Semantic Similarity Search (Cosine, Dot, Euclidean)
- **Test 14**: [`mod_e_test_14_knowledge_graph.html`](mod_e_test_14_knowledge_graph.html) — Knowledge Graph Database & Multi-Hop Cypher Traversal

---

## ☁️ Production AWS Endpoints (Region: us-east-2)
- **Lambda Function URL**: `https://rzif6dkmsvpk7xczl3ekzksepe0uyejl.lambda-url.us-east-2.on.aws/`
- **Step Functions State Machine**: `cosmos-cicd-ai-pipeline-sfn`
- **Amazon Bedrock**: Live Claude Sonnet 4.6 (`us.anthropic.claude-sonnet-4-6`)
- **Amazon S3 Store**: `s3://cosmos-ai-factory-cicd-966273137102/deployments/`
- **Project**: For Each and Every (`966273137102`)
