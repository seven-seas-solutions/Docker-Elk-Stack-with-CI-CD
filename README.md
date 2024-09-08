# ELK Stack with Docker Compose

This project sets up an ELK (Elasticsearch, Logstash, Kibana) stack using Docker Compose. It allows for centralized logging and data analysis.

## Project Overview

The project demonstrates the setup of an ELK stack using Docker containers. The services are defined using `docker-compose` for easy deployment.

### Components
1. **Elasticsearch** - Stores the logs and provides full-text search and analytics.
2. **Logstash** - Collects and processes logs before forwarding them to Elasticsearch.
3. **Kibana** - A visualization tool for Elasticsearch.

### Features
- Centralized logging
- Real-time data analysis
- Fully containerized solution
- Basic CI/CD pipeline using GitHub Actions

## Requirements

- Docker 20.10+ installed
- Docker Compose v2.20.2+ installed

## Usage

1. Clone the repository:

   ```bash
   git clone https://github.com/seven-seas-solutions/elk-stack.git
   cd elk-stack

Start the ELK Stack:

   ```bash
docker-compose up -d
```
Access Kibana via http://localhost:5601.

Stop the services:

   ```bash
docker-compose down
```

## CI/CD Pipeline

A GitHub Actions pipeline is included to automatically build and test the Docker images whenever changes are pushed to the repository.

## License Information

The following open-source licenses apply to the project:

- Elasticsearch - Licensed under the Elastic License.
- Logstash - Licensed under the Apache License 2.0.
- Kibana - Licensed under the Elastic License.
- Docker Compose configuration - You are free to use and modify this configuration under the MIT License.

## Project Structure

   ```bash
.
├── docker-compose.yml
├── logstash
│   ├── Dockerfile
│   └── pipeline
│       └── logstash.conf
└── README.md
```

## Legal Disclaimer

Please ensure you comply with the licenses of all included software when using this project commercially. The Elastic License has specific limitations on use and distribution.

## Additional Resources
For more information on how to use elk, visit their official website: https://www.elastic.co/ 
and YouTube channel: https://www.youtube.com/@Elastic/videos

## Contributing

Feel free to submit pull requests to improve this project.

## Contact

For professional services related to the setup, deployment, or maintenance of ELK stacks, please contact Seven Seas Solutions.

www.sevenseassolutions.co.uk
cotact@sevenseassolutions.co.uk
