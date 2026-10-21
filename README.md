# AWS Individual Sandbox • End-to-End AI CI/CD Test Bench

A modular sandbox repository separating the AI GitHub ⟷ AWS end-to-end bridge test bench into individual standalone test applications, prefixed by **Module** and **Test Number**.

Live GitHub Pages Hub: [https://cosmosanalytics.github.io/AWS-individual-sandbox/](https://cosmosanalytics.github.io/AWS-individual-sandbox/)

---

## 🔒 Owner Unlock & Public Security Gate

Because this repository is public, **every individual test app and the index hub are protected by the Owner Unlock Gate**:
- **Locked / Non-Owner Mode**: Non-owners cannot execute actions or trigger cloud workloads. All test buttons and execution triggers are strictly disabled and blocked until the Owner Passcode is entered.
- **Unlocked / Owner Live Mode**: Enter your Owner Passcode in the top bar. Unlocking in one test or on the hub automatically unlocks all 14 test apps across the browser session (`sessionStorage`), authorizing live execution on **AWS us-east-2** (Project *For Each and Every*) and real commits on GitHub.

---

## 🟢 Run All 14 Tests Suite (1 Live AWS Ping + 14 Contract Checks)
- **Developer Guide**: [`run_all_test_suite_guide.html`](run_all_test_suite_guide.html)
- Combines **1 live AWS ping in `us-east-2`** (measuring roundtrip latency and returning AWS Lambda request ID) with **14 client-side architectural contract evaluations**.
- **100% Verifiable GitHub Artifacts**:
  - CI/CD Actions Run: [`Run #39422342144`](https://github.com/cosmosanalytics/AWS/actions/runs/39422342144) (HTTP 200 OK)
  - Production Main Head: [`Commit #5abc7f6`](https://github.com/cosmosanalytics/AWS/commit/5abc7f635ba77fe0d76b97aedac6cf2b79f6bbd7) (HTTP 200 OK)
  - Sandbox Head Commit: [Commit #588fbfa](https://github.com/cosmosanalytics/AWS-individual-sandbox/commit/588fbfa4408f9e305c76e4407fa996a257246c37) (HTTP 200 OK)
  - Isolated Feature Branch: [`feat/test-pr`](https://github.com/cosmosanalytics/AWS/tree/feat/test-pr) (HTTP 200 OK)
- **Cryptographic Bit-for-Bit Hashes (Test 12)**:
  - Clean Payload SHA-256: `2f5f50ae58809f059bfc20690bb8c9b33d7243a1dd739be2eca3c082dbb1a759`
  - Perturbed 1-Char SHA-256: `6a62d890782533c4df9d1a77cca1b246696cdfca1ef776ef5d3968fe1399aba9`
- **Semantic Polarity Challenge (Test 13)**: Pure vector scores 8/10 (fails negation & scalar polarity by mathematical design); hybrid filter achieves 10/10 (100%).

---

## 🪞 Document vs Vector & Graph Database Mismatch Auditor
- **Auditor App**: [`document_database_mismatch_auditor.html`](document_database_mismatch_auditor.html)
- Implements the **Knowledge Mirror Test**, **The Three Little Monsters (Missing, Extra, Unfindable)**, and the **Fact-by-Fact Invariant Heatmap**.
- Runs for project owner with **Client Hybrid Rule Engine ($0.00)** and **Amazon Bedrock (Claude Sonnet 4.6 in us-east-2)**.

---

## 📂 14 Individual Test Applications

### Module A: Git / PR Automation
- **Test 01**: [`mod_a_test_01_git_push.html`](mod_a_test_01_git_push.html) — `git push sandbox/main-sync` (Push File via Lambda to GitHub `sandbox/main-sync` branch)
- **Test 02**: [`mod_a_test_02_pull_request.html`](mod_a_test_02_pull_request.html) — Pull Request Gate (Initiate isolated branch `feat/test-pr` & open PR #2 while keeping `main` untouched at `#5abc7f6`)

### Module B: 4 GitHub CI/CD Action Jobs
- **Test 03**: [`mod_b_test_03_ast_review.html`](mod_b_test_03_ast_review.html) — Action Job 1 (AI AST Syntax Review & Claude Sonnet 4.6 Spec Audit)
- **Test 04**: [`mod_b_test_04_secret_shield.html`](mod_b_test_04_secret_shield.html) — Action Job 2 (DevSecOps Zero-Leak Secret Shield & 15-File Key Scanner)
- **Test 05**: [`mod_b_test_05_ci_matrix.html`](mod_b_test_05_ci_matrix.html) — Action Job 3 (Automated 48/48 CI Test Matrix & Policy Invariants, Run #39422342144)
- **Test 06**: [`mod_b_test_06_aws_401_preflight.html`](mod_b_test_06_aws_401_preflight.html) — Action Job 4 (AWS us-east-2 401 Gate Pre-Flight Security Probe: 3 Knocks)

### Module C: GitHub ⟷ AWS 3-Way Bridge
- **Test 07**: [`mod_c_test_07_github_to_aws_push.html`](mod_c_test_07_github_to_aws_push.html) — Connection ① (GitHub ➔ AWS Forward Push Trigger Channel, exec-sfn-78a2f4c9)
- **Test 08**: [`mod_c_test_08_github_to_aws_pull.html`](mod_c_test_08_github_to_aws_pull.html) — Connection ② (GitHub ➔ AWS Reverse Telemetry Pull Channel, SHA #5abc7f6 & Run #39422342144)
- **Test 09**: [`mod_c_test_09_aws_to_github_return.html`](mod_c_test_09_aws_to_github_return.html) — Connection ③ (AWS ➔ GitHub Step Functions & Bedrock Claude Sonnet 4.6 Return Channel)

### Module D: Shield & Bedrock AI Dispatch
- **Test 10**: [`mod_d_test_10_cost_shield.html`](mod_d_test_10_cost_shield.html) — Owner Cost Gate (AWS us-east-2 Authorization Gate: Dual Path Knock)
- **Test 11**: [`mod_d_test_11_multi_engine_ai.html`](mod_d_test_11_multi_engine_ai.html) — Amazon Bedrock Multi-Model Dispatch (Benchmark Claude Sonnet 4.6, Claude 3.5 Haiku, and Amazon Nova Pro in `us-east-2`)

### Module E: Cloud State, Storage & Graph
- **Test 12**: [`mod_e_test_12_amazon_s3.html`](mod_e_test_12_amazon_s3.html) — Amazon S3 (PutObject & GetObject 74B SHA-256 Checksum Match in `us-east-2`)
- **Test 13**: [`mod_e_test_13_vector_db.html`](mod_e_test_13_vector_db.html) — Vector Database & Semantic Similarity Search (10-Question Scorecard: 80% Pure Vector vs 100% Hybrid)
- **Test 14**: [`mod_e_test_14_knowledge_graph.html`](mod_e_test_14_knowledge_graph.html) — Knowledge Graph Database & 3-Hop Cypher Traversal (20/20 Facts, 100% Precision)

---

## ☁️ Production AWS Endpoints (Region: us-east-2)
- **Lambda Function URL**: `https://rzif6dkmsvpk7xczl3ekzksepe0uyejl.lambda-url.us-east-2.on.aws/`
- **Step Functions State Machine**: `cosmos-cicd-ai-pipeline-sfn`
- **Amazon Bedrock**: Live Claude Sonnet 4.6 (`us.anthropic.claude-sonnet-4-6`)
- **Amazon S3 Store**: `s3://cosmos-ai-factory-cicd-artifacts/deployments/`
- **Project**: For Each and Every (Region: us-east-2)
