# Claude Code Specialized Agents Collection

<div align="center">

[![Agents](https://img.shields.io/badge/Agents-153-blue.svg)](#agent-statistics)
[![Categories](https://img.shields.io/badge/Categories-12-green.svg)](#category-overview)
[![License](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

*A comprehensive collection of 153 specialized AI agents for [Claude Code](https://docs.anthropic.com/en/docs/claude-code), organized into 12 strategic categories for enhanced development workflows and domain-specific expertise.*

</div>

## 🚀 Overview

This repository contains **153 specialized agents** that extend Claude Code's capabilities across every aspect of software development, business operations, and digital strategy. Each agent is a domain expert, automatically invoked based on context or explicitly called when needed.

All agents are optimized with specific Claude models based on task complexity for optimal performance and cost-effectiveness, enabling sophisticated multi-agent workflows that handle complex, real-world scenarios.

## 📋 Category Overview

### 🏗️ 01. Core Development (12 Agents)
**Foundation of software engineering and architecture**
- API design and architecture
- Backend system development  
- Frontend interfaces and UX
- Full-stack application development
- GraphQL schema design
- Microservices architecture
- Mobile app development
- WebSocket real-time communications
- Electron desktop applications
- Architecture review and validation

### 💻 02. Language Specialists (30 Agents)  
**Expert developers for every major programming language**
- **Systems Languages**: Rust, C, C++, Go, Assembly
- **Enterprise Languages**: Java, C#, Scala, Kotlin
- **Web Technologies**: JavaScript, TypeScript, PHP, WebAssembly
- **Scripting & Data**: Python, Ruby, Perl, Shell, PowerShell
- **Functional Languages**: Haskell, Elixir, F#, Clojure
- **Mobile & Game Development**: Swift, Dart/Flutter, Unity C#
- **Database**: SQL optimization and design
- **Specialized**: MATLAB, R, Solidity, COBOL modernization

### ⚙️ 03. Infrastructure (18 Agents)
**DevOps, cloud, and system reliability engineering**
- DevOps troubleshooting and automation
- Cloud architecture (AWS, Azure, GCP, multi-cloud)
- Kubernetes and container orchestration  
- Database administration and optimization
- Security engineering and compliance
- Site reliability and incident response
- Network engineering and debugging
- Infrastructure as Code (Terraform, Ansible)
- Monitoring and observability
- CI/CD pipeline optimization

### 🛡️ 04. Quality & Security (13 Agents)
**Code quality, testing, and security assurance**
- Comprehensive code review and analysis
- Security auditing and vulnerability assessment
- Test automation and strategy
- Performance engineering and optimization
- Debugging and error investigation
- Quality assurance processes
- Code analysis and metrics
- Penetration testing
- Compliance verification
- Risk assessment

### 🤖 05. Data & AI (13 Agents)
**Data science, machine learning, and AI development**
- AI engineering and LLM applications
- Machine learning model development
- MLOps and model deployment
- Data science and analytics
- Data engineering and pipelines
- Natural language processing
- Computer vision applications
- Prompt engineering and optimization
- Big data processing
- Business intelligence
- Neural network design
- AI ethics and governance

### 🛠️ 06. Developer Experience (14 Agents)
**Tools, workflows, and productivity enhancement**
- Build system optimization
- Git workflow management  
- Documentation engineering
- Legacy system modernization
- Development environment setup
- Package management
- Code generation and scaffolding
- API documentation automation
- Developer onboarding
- Tool integration
- Workflow automation
- Knowledge management

### 🎯 07. Specialized Domains (15 Agents)
**Industry-specific and niche technology experts**
- Blockchain and cryptocurrency development
- IoT and embedded systems
- Game development and optimization
- FinTech and payment processing
- E-commerce and retail technology
- Healthcare and medical systems
- Educational technology platforms
- Real estate and property management
- Manufacturing and supply chain
- Media and content management
- Geographic information systems (GIS)
- Telecommunications
- Energy and utilities
- Transportation and logistics

### 📊 08. Business & Product (14 Agents)
**Business strategy, product management, and operations**
- Product management and strategy
- Business analysis and metrics
- Sales automation and CRM
- Marketing campaign development
- Customer support optimization
- Human resources and HR policies
- Legal compliance and documentation
- Financial planning and analysis
- Project management
- Vendor management
- Market research and competitive analysis
- User experience research
- Brand strategy and positioning

### 🎭 09. Meta & Orchestration (9 Agents)
**Agent coordination and workflow management**
- Multi-agent system coordination
- Context management across conversations
- Workflow orchestration and automation  
- Agent performance monitoring
- Task delegation and routing
- Communication protocol management
- System integration coordination
- Process optimization
- Resource allocation

### 🔍 10. Research & Analysis (7 Agents)
**Deep research, analysis, and strategic insights**
- Market research and competitive analysis
- Technology trend analysis and forecasting
- Strategic business intelligence
- Patent and intellectual property research
- Academic and scientific research
- Industry report analysis
- Consumer behavior research

### 📈 11. Marketing & SEO (10 Agents)
**Search engine optimization and content marketing**
- SEO content auditing and optimization
- Keyword research and strategy
- Meta tag and snippet optimization  
- Content structure and schema markup
- Featured snippet formatting
- Content freshness and updates
- Keyword cannibalization detection
- Authority building and E-E-A-T signals
- SEO-optimized content creation
- Content planning and strategy

### 🔧 12. Personal Productivity (2 Agents)
**Personal knowledge management and workflow optimization**
- Personal knowledge management (PKM) coordination
- Drafts action development and automation

## 📊 Agent Statistics

| Category | Agent Count | Primary Use Cases |
|----------|-------------|-------------------|
| **Core Development** | 12 | Software architecture, API design, full-stack development |
| **Language Specialists** | 30 | Programming in specific languages, syntax optimization |
| **Infrastructure** | 18 | DevOps, cloud architecture, system reliability |
| **Quality & Security** | 13 | Code review, testing, security auditing |
| **Data & AI** | 13 | Machine learning, data science, AI development |
| **Developer Experience** | 14 | Tools, documentation, workflow optimization |
| **Specialized Domains** | 15 | Industry-specific solutions, niche technologies |
| **Business & Product** | 14 | Product management, business strategy, operations |
| **Meta & Orchestration** | 9 | Agent coordination, workflow management |
| **Research & Analysis** | 7 | Market research, competitive analysis |
| **Marketing & SEO** | 10 | Search optimization, content marketing |
| **Personal Productivity** | 2 | Knowledge management, personal automation |
| **Total** | **153** | **Complete development ecosystem coverage** |

## ⚡ Installation

### Prerequisites
- [Claude Code](https://docs.anthropic.com/en/docs/claude-code) installed and configured
- Git for cloning the repository

### Quick Setup
```bash
# Clone the agents collection to your Claude Code directory
cd ~/.claude
git clone https://github.com/yourusername/agents.git

# Verify installation
ls ~/.claude/agents/
```

The agents are automatically available once placed in the `~/.claude/agents/` directory.

## 🎯 Usage Examples

### Automatic Agent Invocation
Claude Code intelligently selects the appropriate agent based on context:

```bash
# Automatically invokes api-designer
"Design a REST API for user authentication with OAuth2"

# Automatically invokes python-pro  
"Optimize this Python data processing pipeline"

# Automatically invokes devops-troubleshooter
"Production database is experiencing high connection timeouts"
```

### Explicit Agent Invocation
Request specific agents for targeted expertise:

```bash
# Code quality and security
"Use security-auditor to scan for OWASP vulnerabilities"
"Have code-reviewer analyze this component for best practices"

# Development tasks
"Get backend-architect to design microservice boundaries"
"Use frontend-developer to create responsive dashboard layouts"

# Infrastructure operations
"Have devops-troubleshooter analyze these production logs"
"Get kubernetes-architect to optimize cluster resource usage"

# Business and marketing
"Use business-analyst to create quarterly performance metrics"
"Have seo-content-writer optimize this blog post for search"
```

### Multi-Agent Workflows
Agents collaborate seamlessly on complex tasks:

```bash
# Feature development pipeline
"Implement user authentication with social login"
# Coordinates: api-designer → backend-architect → frontend-developer → security-auditor → test-automator

# Performance optimization workflow
"Optimize the e-commerce checkout process"  
# Coordinates: performance-engineer → database-optimizer → frontend-developer → business-analyst

# Production incident response
"Debug intermittent API timeouts in production"
# Coordinates: incident-responder → devops-troubleshooter → network-engineer → performance-engineer

# Content marketing campaign
"Launch SEO content strategy for new product"
# Coordinates: seo-keyword-strategist → seo-content-writer → content-marketer → business-analyst
```

## 🏆 Best Practices

### 🎯 Effective Agent Usage
1. **Trust automatic delegation** - Let Claude Code select optimal agents based on context
2. **Be specific with requirements** - Include tech stack, constraints, and quality criteria
3. **Leverage agent expertise** - Each agent is optimized for their specific domain

### 🔄 Multi-Agent Orchestration  
4. **Start with high-level requests** - Allow agents to coordinate complex multi-step workflows
5. **Provide rich context** - Ensure agents have necessary background information
6. **Review integration points** - Verify how different agents' outputs work together

### 🎛️ Advanced Control
7. **Use explicit invocation strategically** - When you need specific expert perspectives
8. **Combine complementary agents** - Different specialists can validate each other's work
9. **Request cross-functional reviews** - "Have security-auditor review backend-architect's design"

### 📈 Optimization
10. **Monitor workflow patterns** - Learn which agent combinations work best for your use cases
11. **Iterate on complex tasks** - Use agent feedback to refine requirements
12. **Match complexity to capability** - Leverage appropriate agent sophistication levels

## 🤝 Agent Orchestration Patterns

### Sequential Workflows
```
User Request → Agent A → Agent B → Agent C → Integrated Result

Example: "Build secure payment processing"
payment-integration → security-auditor → test-automator → deployment-engineer
```

### Parallel Execution  
```
User Request → Agent A + Agent B (simultaneously) → Merged Results

Example: "Optimize full-stack application performance"
performance-engineer + database-optimizer + frontend-developer → Combined optimizations
```

### Conditional Routing
```
User Request → Analysis Agent → Route to Appropriate Specialists

Example: "Fix production bug"
debugger → Routes to: backend-architect OR frontend-developer OR devops-troubleshooter
```

### Review & Validation
```
Primary Agent → Review Agent → Quality Assurance → Final Delivery

Example: "Implement new API feature"
api-designer → code-reviewer → security-auditor → Validated implementation
```

## 🛠️ Agent Selection Guide

### When to Use Which Agent Category

**🏗️ Planning & Architecture**
- Use `api-designer` for REST/GraphQL API design
- Use `backend-architect` for system architecture and database design  
- Use `frontend-developer` for UI/UX planning and component architecture
- Use `microservices-architect` for distributed system design

**💻 Language-Specific Development**
- Use language specialists (`python-pro`, `typescript-pro`, etc.) for idiomatic code
- Use `sql-pro` for database query optimization
- Use `mobile-developer` for cross-platform mobile applications

**⚙️ Operations & Infrastructure**
- Use `devops-troubleshooter` for production issues and deployments
- Use `kubernetes-architect` for container orchestration
- Use `cloud-architect` for infrastructure design and cost optimization
- Use `incident-responder` for critical outages requiring immediate action

**🛡️ Quality & Security**
- Use `code-reviewer` for code quality and best practices
- Use `security-auditor` for vulnerability scanning and compliance
- Use `test-automator` for comprehensive testing strategies
- Use `performance-engineer` for optimization and bottleneck resolution

**🤖 Data & Intelligence**
- Use `data-scientist` for analytics, insights, and reporting
- Use `ai-engineer` for LLM applications and RAG systems
- Use `ml-engineer` for machine learning model development
- Use `mlops-engineer` for ML infrastructure and experiment tracking

## 🚀 Advanced Features

### Model Optimization
Agents are assigned optimal Claude models based on task complexity:
- **Haiku**: Fast, cost-effective for routine tasks
- **Sonnet**: Balanced performance for most development work  
- **Opus**: Maximum capability for complex analysis and critical decisions

### Intelligent Context Management
- Agents share context across workflows
- Long-term memory for project continuity
- Automatic context switching for multi-domain tasks

### Workflow Automation
- Predefined workflow templates
- Custom agent sequences
- Conditional logic and branching
- Error handling and recovery

## 🤝 Contributing

We welcome contributions to expand and improve the agent collection!

### Adding New Agents
1. **Choose appropriate category** - Place agents in the correct numbered directory
2. **Follow naming conventions** - Use lowercase, hyphen-separated names (e.g., `new-agent.md`)
3. **Use standard format**:
   ```markdown
   ---
   name: agent-name
   description: Clear description of when this agent should be invoked
   model: haiku  # Optional: haiku/sonnet/opus based on complexity
   tools: tool1, tool2  # Optional: specify required tools
   ---
   
   System prompt defining the agent's expertise and capabilities...
   ```

### Contribution Guidelines
1. **Quality First** - Ensure agents provide real value and expertise
2. **Clear Documentation** - Write comprehensive descriptions and use cases
3. **Test Thoroughly** - Verify agents work correctly in various scenarios
4. **Follow Conventions** - Maintain consistency with existing agents

### Pull Request Process
1. Fork the repository
2. Create a feature branch (`git checkout -b new-agent-feature`)
3. Add your agent with proper documentation
4. Test the agent in various scenarios
5. Submit a pull request with detailed description

## 🔧 Troubleshooting

### Common Issues

**Agent Not Automatically Selected**
- Ensure your request clearly indicates the domain or task type
- Add more specific context about your technology stack
- Use explicit invocation if automatic selection isn't working

**Unexpected Agent Selection**
- Provide more detailed requirements and constraints
- Specify the type of solution you're looking for
- Use explicit agent names for precise control

**Conflicting Agent Recommendations**
- This is normal - different specialists may have different priorities
- Ask for reconciliation: "Resolve the differences between security-auditor and performance-engineer recommendations"
- Request a unified approach that balances all concerns

**Missing Context Between Agents**
- Provide comprehensive background information in your initial request
- Reference previous conversations and established patterns
- Use context-manager for complex multi-session workflows

### Performance Optimization
- Use appropriate model assignments for task complexity
- Leverage parallel agent execution for independent tasks
- Optimize agent selection for cost-effectiveness
- Monitor agent performance and adjust usage patterns

## 📚 Resources

- [Claude Code Documentation](https://docs.anthropic.com/en/docs/claude-code)
- [Agent Development Guide](https://docs.anthropic.com/en/docs/claude-code/sub-agents)
- [Claude Code Commands Collection](https://github.com/wshobson/commands) - 52 pre-built workflows
- [Claude Code GitHub Repository](https://github.com/anthropics/claude-code)

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- Anthropic team for Claude Code platform
- Open source community for inspiration and best practices
- Contributors who have helped expand and improve the agent collection

---

<div align="center">

**🎯 Ready to supercharge your development workflow?**

*Clone this repository and start leveraging 153 specialized agents across 12 strategic categories for unprecedented development productivity and expertise.*

[![Get Started](https://img.shields.io/badge/Get%20Started-Clone%20Now-brightgreen.svg)](#installation)

</div>