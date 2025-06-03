README is AI generated.

# Mage Cursor Rules Public

A collection of sanitized Cursor IDE rules for data engineering workflows with Mage.ai, dbt, BigQuery, and related tools.

## Overview

This repository contains Cursor IDE rule files (`.mdc`) that provide context and guidance for AI-assisted development in data engineering projects. These rules have been sanitized to remove sensitive information and are safe for public sharing.

## Structure

```
.cursor/
├── data_platform/
│   ├── bigquery.mdc          # BigQuery configuration and patterns
│   ├── data_warehouse.mdc    # Data warehouse context and tools
│   └── dbt_misc.mdc          # dbt project setup and environments
├── development/
│   ├── development-workflow.mdc  # Git workflow and best practices
│   └── memory.mdc            # Development guidance and common issues
├── mage/
│   ├── mage_glossary.mdc     # Mage.ai terminology and concepts
│   ├── mage_io_config.mdc    # Mage.ai configuration templates
│   └── mage_misc.mdc         # Mage.ai best practices and tips
├── project/
│   └── current_dev_state.mdc # Development status tracking
└── archive/
    └── mage_deployment_pipeline.mdc # Archived pipeline configurations
```

## What's Included

### Data Platform Rules
- **BigQuery**: Authentication patterns, dataset organization, query best practices
- **Data Warehouse**: Tool stack overview, architecture patterns  
- **dbt**: Environment setup, modeling layers (Bronze/Silver/Gold), profile configuration

### Development Rules
- **Workflow**: Git branching strategies, pre-commit hooks, merge practices
- **Memory**: Common pitfalls, syntax guidelines, troubleshooting tips

### Mage.ai Rules
- **Glossary**: Platform terminology and concepts
- **Configuration**: io_config.yaml templates for various data sources
- **Best Practices**: Coding patterns, file organization, pipeline design

### Project Management
- **Development State**: Template for tracking active work and progress

## Usage

1. Copy the `.cursor/` directory to your project root
2. Customize the rules for your specific environment
3. Add your actual credentials and project-specific details
4. Update the `current_dev_state.mdc` file as your project evolves

## Environment Variables

These rules use environment variables for sensitive information:
- `GOOGLE_CLOUD_PROJECT`: Your GCP project ID
- `GOOGLE_APPLICATION_CREDENTIALS`: Path to service account key
- Various data source credentials as referenced in `mage_io_config.mdc`

## Features

- **Sanitized Content**: All sensitive information removed for public sharing
- **Best Practices**: Curated patterns for data engineering workflows
- **Multi-Environment**: Support for dev/staging/prod environments
- **Tool Integration**: Seamless integration between Mage.ai, dbt, and BigQuery

## Contributing

Feel free to submit issues or pull requests to improve these rules for the data engineering community!

## License

MIT License - feel free to use and modify for your projects.
