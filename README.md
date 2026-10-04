# Website Builder Agent

An AI-powered website builder agent that coordinates planning, design, backend, frontend, and security to build complete websites automatically.

## Features

- **Orchestrator Pattern**: Coordinates multiple specialized agents
- **Full-Stack Generation**: Creates both backend and frontend
- **Security Auditing**: Built-in security checks
- **Design System**: Generates consistent UI with animations

## Architecture

```
WebsiteBuilderOrchestrator
├── WebsitePlanner      # Analyzes requirements
├── DesignAgent         # Creates design system
├── BackendBuilder      # Builds Flask backend
├── FrontendBuilder     # Builds animated frontend
├── IntegrationAgent    # Integrates components
└── SecurityAuditor     # Performs security audit
```

## Quick Start

```bash
# Install dependencies
pip install flask

# Run the builder
python -m agent.orchestrator
```

## Project Structure

```
deep_harness/
└── agent/
    ├── __init__.py       # Package init
    ├── orchestrator.py   # Main orchestrator
    ├── planner.py        # Planning agent
    └── designer.py       # Design agent
```

## How It Works

1. **Planning**: Analyzes requirements and creates site map
2. **Design**: Creates design system with Lucide icons
3. **Backend**: Builds Flask backend with security features
4. **Frontend**: Builds animated frontend with components
5. **Integration**: Integrates frontend and backend
6. **Security**: Performs security audit

## License

MIT
