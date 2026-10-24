# 🚀 DevOps-Commander

> **An intelligent DevOps incident response and GitOps management copilot for Kubernetes teams using Jira**

[![Jira Forge App](https://img.shields.io/badge/Jira-Forge%20App-blue?logo=jira)](https://developer.atlassian.com/)
[![Node.js](https://img.shields.io/badge/Node.js-20.x-green?logo=node.js)](https://nodejs.org/)
[![TypeScript](https://img.shields.io/badge/TypeScript-Latest-blue?logo=typescript)](https://www.typescriptlang.org/)
[![License](https://img.shields.io/badge/License-MIT-yellow)](LICENSE)

---

<img width="806" height="506" alt="image" src="https://github.com/user-attachments/assets/9c09382a-7d50-42fb-91b4-335bbbe07b94" />

**Applicaton Installation Link:**

> Note: The link is too long but it is the correct for the Application 

https://developer.atlassian.com/console/install/65c24f25-846c-423c-8092-518b8ea5e4f7?signature=AYABeBxc6399EUbbw7sz7Hbf4iUAAAADAAdhd3Mta21zAEthcm46YXdzOmttczp1cy13ZXN0LTI6NzA5NTg3ODM1MjQzOmtleS83MDVlZDY3MC1mNTdjLTQxYjUtOWY5Yi1lM2YyZGNjMTQ2ZTcAuAECAQB4IOp8r3eKNYw8z2v%2FEq3%2FfvrZguoGsXpNSaDveR%2FF%2Fo0BB9%2F6dVDoxCPbuGDJtzudcAAAAH4wfAYJKoZIhvcNAQcGoG8wbQIBADBoBgkqhkiG9w0BBwEwHgYJYIZIAWUDBAEuMBEEDJ8dhNlpM3ddYP7N7QIBEIA7ZAWQ267txeMSFfnxhVhgh%2FrzSwW2RhIrx2GAWX%2BnR0FY0s8ntlNFhqLu2yYbjuxQZ8J%2B4BakvASEQwQAB2F3cy1rbXMAS2Fybjphd3M6a21zOmV1LXdlc3QtMTo3MDk1ODc4MzUyNDM6a2V5LzQ2MzBjZTZiLTAwYzMtNGRlMi04NzdiLTYyN2UyMDYwZTVjYwC4AQICAHijmwVTMt6Oj3F%2B0%2B0cVrojrS8yZ9ktpdfDxqPMSIkvHAFhech9BVKidw0jOv0lb3ReAAAAfjB8BgkqhkiG9w0BBwagbzBtAgEAMGgGCSqGSIb3DQEHATAeBglghkgBZQMEAS4wEQQML%2BucdlfmyuZPhmS1AgEQgDvuDvSgjH3a9vz2GmDDjCmbPjMEqi0Fx37o5FTDUvm%2BfVkdHrIIZWMQYkiFC3lna4vbaHpHKKRXjAe%2FbQAHYXdzLWttcwBLYXJuOmF3czprbXM6dXMtZWFzdC0xOjcwOTU4NzgzNTI0MzprZXkvNmMxMjBiYTAtNGNkNS00OTg1LWI4MmUtNDBhMDQ5NTJjYzU3ALgBAgIAeLKa7Dfn9BgbXaQmJGrkKztjV4vrreTkqr7wGwhqIYs5AYsiR%2B4Fsyhd687wTIS4EcQAAAB%2BMHwGCSqGSIb3DQEHBqBvMG0CAQAwaAYJKoZIhvcNAQcBMB4GCWCGSAFlAwQBLjARBAws5ija47E%2FceR6qXgCARCAO6%2F9q2inyiTLpOpwXY%2BRLcYvKs05zbcTVMiaLlDZ1anr4Dkz6WeGAikTht3bCng9R%2Fju%2FvZFp4uE1izoAgAAAAAMAAAQAAAAAAAAAAAAAAAAACXEb%2B34OPRudnj8eiM5o8P%2F%2F%2F%2F%2FAAAAAQAAAAAAAAAAAAAAAQAAADLm%2Bpn%2FSvaj45qtR4OFh%2B%2FBqOAbz7V34ygF5wFHoezBN4kOaERJOgMkJU7GPP1kfvLiTfYH9FrdMM%2BqNrWiOz7bVPY%3D&product=jira

## 📋 Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Key Capabilities](#key-capabilities)
- [Architecture](#architecture)
- [Installation](#installation)
- [Getting Started](#getting-started)
- [Configuration](#configuration)
- [Usage Examples](#usage-examples)
- [Roadmap](#roadmap)
- [Contributing](#contributing)

---

## Overview

**DevOps-Commander** is a Jira Forge app that transforms how DevOps and SRE teams manage incidents, analyze Kubernetes cluster health, and coordinate incident response workflows. By combining intelligent analysis with GitOps principles, it enables teams to:

- 🔍 **Analyze cluster states, logs, and GitOps pipelines** in real-time
- 🎯 **Generate actionable remediation steps** with root cause analysis
- 📊 **Track incidents and responses** directly in Jira
- ⚡ **Automate on-call handoff summaries** for seamless team transitions
- 🤖 **Leverage AI-powered insights** for faster incident resolution

Perfect for teams running Kubernetes, managing GitOps deployments with ArgoCD, and coordinating multi-team incident response through Jira.

---

## ✨ Features

### 1. **Cluster Health Analysis**

Instantly assess your Kubernetes cluster's health by analyzing:
- Pod status and resource utilization
- Node health and capacity metrics
- Network connectivity and DNS resolution
- Storage and persistent volume status

### 2. **Incident Response Workflow**

Structured incident management with:
- **Context Gathering**: Automatically collect cluster logs and state
- **Root Cause Analysis**: AI-powered identification of failure points
- **Impact Assessment**: Understand blast radius and affected services
- **Remediation Steps**: Get concrete, executable action items
- **On-Call Handoff**: Generate comprehensive summaries for team handovers

### 3. **GitOps Integration**

- **ArgoCD Status Monitoring**: Track application deployment health
- **GitOps Pipeline Analysis**: Identify drift and deployment issues
- **Declarative Deployment Insights**: Analyze YAML configurations and state mismatches

### 4. **Kubernetes Expertise**

Built-in knowledge of:
- Kubernetes v1.33+ architecture and best practices
- RBAC and security policies
- Multi-cluster deployment patterns
- Container networking and service mesh principles

---

## 🎯 Key Capabilities

### Real-Time Intelligence

```
Incident Triggered → Cluster Analysis → Root Cause Identification → 
Remediation Generation → Jira Issue Creation → Team Notification
```

### Smart Action Modules

| Module | Function | Output |
|--------|----------|--------|
| **Analyze Cluster** | Deep dive into Kubernetes state | Cluster health report |
| **Summarize Incident** | Synthesize logs and metrics | Incident summary |
| **Analyze GitOps Status** | Track ArgoCD and deployment health | Pipeline status report |
| **Generate Payload** | Create structured incident data | Jira-ready payload |
| **Incident Response** | Full incident workflow automation | Action-ready runbook |
| **On-Call Handoff** | Team transition documentation | Handoff summary |

---

## 🏗️ Architecture

### Component Stack

```
┌─────────────────────────────────────────────────┐
│         Jira Forge UI (React Components)       │
├─────────────────────────────────────────────────┤
│      DevOps-Commander Resolver Handlers         │
├─────────────────────────────────────────────────┤
│   AI-Powered Analysis Engine (Claude 3 Sonnet) │
├─────────────────────────────────────────────────┤
│   Kubernetes API Client & GitOps Analyzer      │
├─────────────────────────────────────────────────┤
│    External Services Integration Layer          │
│  (Kubernetes, ArgoCD, Jira Cloud Platform)     │
└─────────────────────────────────────────────────┘
```

### Tech Stack

- **Runtime**: Node.js 20.x
- **Language**: TypeScript
- **UI Framework**: React (Jira Forge UI Kit)
- **AI Engine**: Anthropic Claude 3 Sonnet
- **Kubernetes Client**: Official Kubernetes JS client
- **Build Tool**: Webpack
- **Package Manager**: npm/yarn

---

## 📦 Installation

### Quick Install

> ✨ **Install DevOps-Commander directly into your Jira instance with a single click:**

[![Install DevOps-Commander](https://img.shields.io/badge/Install%20into%20Jira-Click%20Here-blue?style=for-the-badge&logo=jira)](https://developer.atlassian.com/console/install/65c24f25-846c-423c-8092-518b8ea5e4f7?signature=AYABeBxc6399EUbbw7sz7Hbf4iUAAAADAAdhd3Mta21zAEthcm46YXdzOmttczp1cy13ZXN0LTI6NzA5NTg3ODM1MjQzOmtleS83MDVlZDY3MC1mNTdjLTQxYjUtOWY5Yi1lM2YyZGNjMTQ2ZTcAuAECAQB4IOp8r3eKNYw8z2v%2FEq3%2FfvrZguoGsXpNSaDveR%2FF%2Fo0BB9%2F6dVDoxCPbuGDJtzudcAAAAH4wfAYJKoZIhvcNAQcGoG8wbQIBADBoBgkqhkiG9w0BBwEwHgYJYIZIAWUDBAEuMBEEDJ8dhNlpM3ddYP7N7QIBEIA7ZAWQ267txeMSFfnxhVhgh%2FrzSwW2RhIrx2GAWX%2BnR0FY0s8ntlNFhqLu2yYbjuxQZ8J%2B4BakvASEQwQAB2F3cy1rbXMAS2Fybjphd3M6a21zOmV1LXdlc3QtMTo3MDk1ODc4MzUyNDM6a2V5LzQ2MzBjZTZiLTAwYzMtNGRlMi04NzdiLTYyN2UyMDYwZTVjYwC4AQICAHijmwVTMt6Oj3F%2B0%2B0cVrojrS8yZ9ktpdfDxqPMSIkvHAFhech9BVKidw0jOv0lb3ReAAAAfjB8BgkqhkiG9w0BBwagbzBtAgEAMGgGCSqGSIb3DQEHATAeBglghkgBZQMEAS4wEQQML%2BucdlfmyuZPhmS1AgEQgDvuDvSgjH3a9vz2GmDDjCmbPjMEqi0Fx37o5FTDUvm%2BfVkdHrIIZWMQYkiFC3lna4vbaHpHKKRXjAe%2FbQAHYXdzLWttcwBLYXJuOmF3czprbXM6dXMtZWFzdC0xOjcwOTU4NzgzNTI0MzprZXkvNmMxMjBiYTAtNGNkNS00OTg1LWI4MmUtNDBhMDQ5NTJjYzU3ALgBAgIAeLKa7Dfn9BgbXaQmJGrkKztjV4vrreTkqr7wGwhqIYs5AYsiR%2B4Fsyhd687wTIS4EcQAAAB%2BMHwGCSqGSIb3DQEHBqBvMG0CAQAwaAYJKoZIhvcNAQcBMB4GCWCGSAFlAwQBLjARBAws5ija47E%2FceR6qXgCARCAO6%2F9q2inyiTLpOpwXY%2BRLcYvKs05zbcTVMiaLlDZ1anr4Dkz6WeGAikTht3bCng9R%2Fju%2FvZFp4uE1izoAgAAAAAMAAAQAAAAAAAAAAAAAAAAACXEb%2B34OPRudnj8eiM5o8P%2F%2F%2F%2F%2FAAAAAQAAAAAAAAAAAAAAAQAAADLm%2Bpn%2FSvaj45qtR4OFh%2B%2FBqOAbz7V34ygF5wFHoezBN4kOaERJOgMkJU7GPP1kfvLiTfYH9FrdMM%2BqNrWiOz7bVPY%3D&product=jira)


### Prerequisites

- ✅ Node.js 20.x or higher
- ✅ npm or yarn package manager
- ✅ Jira Cloud instance with admin access
- ✅ Forge CLI (`npm install -g @atlassian/forge-cli`)
- ✅ Kubernetes cluster access (kubeconfig configured)
- ✅ Anthropic API key for Claude integration

### Step 1: Clone the Repository

```bash
git clone https://github.com/pooja-bhavani/DevOps-Commander.git
cd DevOps-Commander
```

### Step 2: Install Dependencies

```bash
npm install
# or
yarn install
```

### Step 3: Configure Environment Variables

Create a `.env.local` file in the root directory:

```env
# Anthropic API Configuration
ANTHROPIC_API_KEY=your-api-key-here

# Kubernetes Configuration
KUBERNETES_API_URL=https://your-cluster-api:6443
KUBERNETES_NAMESPACE=default

# Jira Cloud Configuration
JIRA_SITE_URL=https://your-instance.atlassian.net
JIRA_API_TOKEN=your-api-token

# Application Settings
ENVIRONMENT=development
DEBUG=true
```

### Step 4: Deploy to Jira

```bash
forge deploy
```

Follow the prompts to authenticate with your Jira instance.

### Step 5: Install the App

Generate your installation link:

```bash
forge install
```

Select your Jira instance and follow the authorization flow.

---

## Deployment Timeline

```
┌─────────────────────────────────────────┐
│     Push to Git (commit/merge)          │
└──────────────┬──────────────────────────┘
               │
               ▼
┌─────────────────────────────────────────┐
│     Run Tests & Linting (CI)            │
└──────────────┬──────────────────────────┘
               │
               ▼
┌─────────────────────────────────────────┐
│   Forge Deploy to Dev/Staging           │
└──────────────┬──────────────────────────┘
               │
               ▼
┌─────────────────────────────────────────┐
│     Manual Testing & Verification       │
└──────────────┬──────────────────────────┘
               │
               ▼
┌─────────────────────────────────────────┐
│  Forge Deploy to Production             │
└──────────────┬──────────────────────────┘
               │
               ▼
┌─────────────────────────────────────────┐
│    Monitor & Validate in Production     │
└─────────────────────────────────────────┘
```

## 🚀 Getting Started

### First Run Setup

1. **Open a Jira issue** in your Jira Cloud instance
2. **Look for the DevOps-Commander panel** on the right sidebar
3. **Click "Analyze Cluster"** to test connectivity
4. **Grant permissions** when prompted for Kubernetes access

### Quick Test

```bash
# Development mode with hot reload
fm dev

# Run linting checks
npm run lint

# Build for production
npm run build
```

---

## ⚙️ Configuration

### Kubernetes Authentication

DevOps-Commander supports multiple auth methods:

- **In-Cluster Authentication** (ServiceAccount token)
- **Kubeconfig File** (local development)
- **AWS IAM** (EKS clusters)
- **OIDC** (GKE and other providers)

### Jira Integration

Enable automated issue creation:

```yaml
# manifest.yml
permissions:
  - key: read
    description: Read issues
  - key: write
    description: Create and update issues
```

### Claude API Setup

Get your API key from [Anthropic Console](https://console.anthropic.com/) and set it in environment variables.

---

## 💡 Usage Examples

### Example 1: Cluster Health Check

**Scenario**: Your application pods are failing

1. Open a Jira issue: "Pods in namespace-xyz failing to start"
2. Click **"Analyze Cluster Health"** in DevOps-Commander
3. Get:
   - Pod status breakdown
   - Resource constraint analysis
   - Node health metrics
   - Recommended fixes
   - 
   ![Cluster Health Analysis - Pod Status and Resource Metrics](./docs/screenshots/cluster-health-analysis.png)

### Example 2: Incident Response

**Scenario**: Services degraded after a deployment

1. Create issue: "Service degradation post-deployment"
2. Trigger **"Incident Response Workflow"**
3. DevOps-Commander automatically:
   - Analyzes cluster state
   - Identifies root cause (e.g., image pull failure, RBAC issue)
   - Generates remediation steps
   - Creates action items in Jira
  
   - ![Incident Response Workflow - Root Cause Analysis and Remediation Steps](./docs/screenshots/incident-response-workflow.png)

### Example 3: On-Call Handoff

**Scenario**: Shift change or escalation needed

1. Click **"Generate On-Call Handoff"**
2. Receive:
   - Current incident summary
   - Recent deployments
   - Cluster anomalies
   - Key contact points
  
   - ![On-Call Handoff Summary - Team Transition Documentation](./docs/screenshots/on-call-handoff.png)

---

## 📊 Dashboard & Monitoring

### Platform Health Status

Monitor your platform health across:
- ✅ Atlassian App APIs
- ✅ Bitbucket APIs
- ✅ Confluence APIs
- ✅ Jira APIs
- ✅ Identity APIs
- ✅ And 20+ more services

- ![Platform Health Dashboard - Monitoring Atlassian Services](./docs/screenshots/platform-health-dashboard.png)

---

## 🗺️ Roadmap

### Phase 1 (Current)
- [x] Kubernetes cluster health analysis
- [x] Incident response automation
- [x] GitOps (ArgoCD) integration
- [x] Jira issue creation and tracking
- [x] AI-powered root cause analysis

### Phase 2 (Planned)
- [ ] Multi-cluster management
- [ ] Custom alert rules engine
- [ ] Slack/Teams integration for notifications
- [ ] Cost optimization recommendations
- [ ] Advanced RBAC audit trails

### Phase 3 (Future)
- [ ] Machine learning for anomaly detection
- [ ] Predictive failure analysis
- [ ] Self-healing automation
- [ ] Cross-team incident correlation

---

## 📚 API Reference

### Core Resolver Functions

#### `analyzeClusterHealth`
Analyzes Kubernetes cluster health and returns status report.

```typescript
analyzeClusterHealth(context: any): Promise<ClusterAnalysis>
```

#### `incidentResponse`
Initiates full incident response workflow.

```typescript
incidentResponse(context: any): Promise<IncidentResponse>
```

#### `summarizeIncident`
Generates incident summary from logs and metrics.

```typescript
summarizeIncident(context: any): Promise<IncidentSummary>
```

---

## 🔐 Security

### Security Best Practices

1. **Never commit secrets** - Use environment variables
2. **Validate all inputs** - Prevent injection attacks
3. **Use RBAC** - Limit Kubernetes permissions
4. **Encrypt sensitive data** - Use secure storage
5. **Audit logging** - Track all incident responses

### Permissions Model

DevOps-Commander respects Jira and Kubernetes RBAC:
- Only reads data you have access to
- Creates issues in projects you have write access to
- Respects ServiceAccount permissions in Kubernetes

---

## 🤝 Contributing

We welcome contributions! Here's how to get started:

1. **Fork the repository**
   ```bash
   git clone https://github.com/yourusername/DevOps-Commander.git
   ```

2. **Create a feature branch**
   ```bash
   git checkout -b feature/amazing-feature
   ```

3. **Make your changes** and commit
   ```bash
   git commit -m 'Add amazing feature'
   ```

4. **Push to your fork**
   ```bash
   git push origin feature/amazing-feature
   ```

5. **Open a Pull Request**

### Development Guidelines

- Follow TypeScript strict mode
- Write unit tests for new features
- Update documentation as needed
- Run linter before committing: `npm run lint`

---

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

## 🙋 Support & Community

- 📖 **Documentation**: Check the [Wiki](../../wiki)
- 💬 **Issues**: Found a bug? [Open an issue](../../issues)
- 💡 **Discussions**: Have ideas? [Start a discussion](../../discussions)
- 📧 **Email**: For commercial support, contact devops-commander@example.com

---

## 🎓 Learning Resources

- [Kubernetes Official Documentation](https://kubernetes.io/docs/)
- [Jira Forge Developer Guide](https://developer.atlassian.com/platform/forge/)
- [ArgoCD Documentation](https://argo-cd.readthedocs.io/)
- [Claude API Guide](https://docs.anthropic.com/)

---

## 📈 Stats & Metrics

![DevOps-Commander Stats](https://img.shields.io/badge/Active%20Users-100%2B-green)
![Uptime](https://img.shields.io/badge/Uptime-99.75%25-blue)
![Response Time](https://img.shields.io/badge/Avg%20Response%20Time-%3C500ms-brightgreen)

---

**Made with ❤️ for DevOps teams by [Pooja Bhavani](https://github.com/pooja-bhavani)**

⭐ If you find this project helpful, please consider giving it a star!
