Expense Tracker Project - 3-Tier Application Deployment

Project Overview

The Expense Tracker is a 3-tier application that helps users manage their expenses by providing:
Frontend : Nginx web server hosting the user interface
Backend  : Node.js application server handling business logic
Database : MySQL for secure data storage

Key Features
- Add expenses with descriptions
- View expense history
- Secure data storage
- Scalable architecture

Manual Deployment Documentation

We strongly recommend reviewing the manual deployment process first to understand the underlying components:

1. Frontend Setup(frontend.MD) - Nginx configuration and deployment
2. Backend Setup(backend.MD)   - Node.js server installation and configuration
3. Database Setup(database.MD)- MySQL installation and schema creation

Automation Roadmap

We will progressively automate the deployment process using various technologies to demonstrate their value:

Phase 1: Basic Automation
- Shell Scripting: Initial deployment automation
- Ansible: Configuration management and orchestration

Phase 2: Infrastructure as Code
- Terraform : Cloud resource provisioning
- Docker    : Containerization of components

Phase 3: Advanced Orchestration
- Kubernetes: Container orchestration and scaling
- CI/CD Pipelines : Automated testing and deployment

 Technology Stack

| Tier        | Technology       | Purpose                          |
|-------------|------------------|----------------------------------|
| Frontend    | Nginx            | Web server and reverse proxy     |
| Backend     | Node.js          | Application logic and API        |
| Database    | MySQL            | Persistent data storage          |
| Automation  | Various tools    | Streamlined deployment processes |

Getting Started

Prerequisites
- Basic Linux server knowledge
- Understanding of web technologies
- Command line proficiency

Recommended Learning Path
1. Review the manual deployment guides
2. Experiment with each component separately
3. Follow along with the automation phases as they're implemented

Contribution Guidelines

We welcome contributions! Please:
1. Fork the repository
2. Create a feature branch
3. Submit a pull request with clear documentation


"The best way to learn is by doing. This project provides hands-on experience with modern deployment technologies through practical implementation.
