# Hiring Plan: AI Agent Services Team

## Company Context
- **Mission**: AI agent services for solopreneurs/SMBs using OpenClaw + Hermes + Paperclip
- **Revenue Goal**: $10K+/month recurring
- **Budget**: $500/month total
- **Owner**: Aslam (human cofounder), CEO Agent (autonomous decisions)

## Team Structure

### 1. Orchestrator Agent (FIRST HIRE - PRIORITY)
**Role**: Main OpenClaw agent, coordinates all operations
**Reports to**: CEO
**Key Responsibilities**:
- Coordinate between all specialist agents
- Manage OpenClaw workflows
- Ensure inter-agent communication via GitHub repos
- Execute complex multi-step projects
- Report progress to CEO

**Required Capabilities**:
- OpenClaw orchestration
- GitHub repo management for agent communication
- Task delegation and tracking
- Error handling and recovery

**Workspace**: F:\MyOpenclaw

---

### 2. Content Agent
**Role**: Creates all outbound content
**Reports to**: Orchestrator
**Key Responsibilities**:
- Tweets and social media posts
- Blog posts and articles
- Email sequences and proposals
- Client deliverables

**Required Capabilities**:
- Content generation (multi-format)
- Brand voice consistency
- SEO optimization
- Platform-specific formatting

---

### 3. Research Agent
**Role**: Lead research and prospecting
**Reports to**: Orchestrator
**Key Responsibilities**:
- Reddit scraping for leads
- Market research via Hermes
- Competitive analysis
- Customer persona development

**Required Capabilities**:
- Reddit API integration
- Hermes outreach automation
- Data analysis and synthesis
- Lead qualification

---

### 4. Verification Agent
**Role**: Quality assurance
**Reports to**: Orchestrator
**Key Responsibilities**:
- Quality check all client deliverables
- Test generated code/software
- Verify content accuracy
- Final approval before delivery

**Required Capabilities**:
- Code review
- Content validation
- Testing frameworks
- Standards enforcement

---

### 5. Website Agent
**Role**: AI-built websites ($5K/site offering)
**Reports to**: Orchestrator
**Key Responsibilities**:
- Build websites from requirements
- Deploy to hosting
- Client handoff
- Maintenance and updates

**Required Capabilities**:
- Full-stack development
- Modern frameworks (React, Next.js, etc.)
- Database design
- Deployment automation

---

## Hiring Sequence

### Phase 1: Foundation (NOW)
1. Hire Orchestrator Agent
2. Establish GitHub repos for inter-agent communication
3. Set up OpenClaw workspace in F:\MyOpenclaw

### Phase 2: Core Functions (AFTER Orchestrator)
4. Hire Content Agent
5. Hire Research Agent
6. Connect Hermes agent in F:\MyHermesagent

### Phase 3: Quality & Delivery (AFTER Phase 2)
7. Hire Verification Agent
8. Hire Website Agent

---

## Communication Architecture

```
GitHub Repos (for inter-agent communication):
├── company-orchestration/     # CEO -> Orchestrator directives
├── content-pipeline/          # Content Agent outputs
├── research-feed/             # Research Agent findings
├── quality-gate/              # Verification Agent checks
└── deployments/               # Website Agent builds
```

**GitHub Config**:
- Account: itsaslamopenclawdata
- PAT: Stored securely (provided by Aslam)
- Access: Full access for all agents via repo permissions

---

## Immediate Actions (CEO)
1. Create Orchestrator agent via Paperclip
2. Create initial GitHub repos
3. Assign first task to Orchestrator
4. Monitor initial runs
