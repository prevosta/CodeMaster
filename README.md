# Large Language Models Toolkit

A comprehensive toolkit for working with Large Language Models (LLMs). It offers tools to interact with LLMs and run automation tasks directly. Ideal for researchers and developers looking to streamline their workflows with advanced language model capabilities.

## Getting Started

To set up and run the Docker containers, follow these steps:

1. Clone the repository:
   ```
   git clone git@bitbucket.org:bid-group/llm-toolkit.git
   ```
2. Navigate to the project directory:
   ```
   cd /home/comact/llm-toolkit
   ```
3. Run the setup script to install dependencies and start the services:
   ```
   ./scripts/setup
   ```

## Accessing the Services

- The `ollama` service will be accessible at `http://localhost:11434`.
- The `open-webui` service will be accessible at `http://localhost:3000`.
- The `n8n` service will be accessible at `http://localhost:5678`.

## Stopping the Services

To stop the running services, use:
```
./scripts/teardown
```
To remove volumes as well, use:
```
./scripts/teardown --hard
```

## Project Structure

```
llm-toolkit
├── docker-compose.yml
├── scripts
│   ├── setup
│   └── teardown
├── shared
│   ├── done
│   │   ├── Annex-A.md
│   │   ├── ADFContinuationBonusfactsheet.md
│   │   └── 2024DefenceWorkforcePlanfactsheet.md
├── .vscode
│   └── extensions.json
├── .gitignore
└── README.md
```

## Services

### ollama

The `ollama` service is responsible for [describe the purpose of the ollama service]. It uses GPU resources for enhanced performance.

### open-webui

The `open-webui` service provides a web interface for [describe the purpose of the open-webui service].

### n8n

The `n8n` service is a workflow automation tool that allows you to automate tasks and integrate various services.

## Recommended VS Code Extensions

To enhance your development experience, it is recommended to install the following VS Code extensions:
- GitHub Copilot
- Docker

## License

All rights reserved.
