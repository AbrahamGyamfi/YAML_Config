# YAML_Config

A demonstration repository showcasing configuration file management using YAML and JSON formats, with validation and best practices for application configuration.

## 📋 Overview

This repository contains example configuration files for a web application, demonstrating the equivalence between YAML and JSON formats.  It includes validation screenshots proving the correctness of both configuration formats.

## 🚀 Features

- **Dual Format Support**: Configuration files available in both YAML and JSON formats
- **Validated Configurations**: All configuration files have been validated using industry-standard linters
- **Production-Ready Structure**: Demonstrates proper organization of application, server, and database configurations

## 📁 Repository Contents

```
YAML_Config/
├── app-config.yaml                    # YAML format configuration
├── app-config.json                    # JSON format configuration
├── Screenshot_YAML_lint.png           # YAML validation proof
└── Screenshot_jsonlint.com. jpeg       # JSON validation proof
```

## 🔧 Configuration Structure

The configuration files contain the following sections: 

### Application Settings
- Application name and version
- Environment configuration (production/development)

### Server Configuration
- Host binding address
- Port number

### Database Settings
- Database engine specification
- Connection parameters (host, port)
- Authentication credentials

## 📝 Example Usage

### YAML Format (`app-config.yaml`)
```yaml
application:
  name:  my-web-app
  version: 1.0.0
  environment: production

server: 
  host: 0.0.0.0
  port: 8080

database:
  engine: mysql
  host: db. example.com
  port: 3306
  username: admin
  password: mysecurepassword
```

### JSON Format (`app-config.json`)
```json
{
    "application": {
        "name": "my-web-app",
        "version": "1.0.0",
        "environment": "production"
    },
    "server":  {
        "host": "0.0.0.0",
        "port": 8080
    },
    "database": {
        "engine": "mysql",
        "host": "db. example.com",
        "port": 3306,
        "username": "admin",
        "password": "mysecurepassword"
    }
}
```

## ✅ Validation

All configuration files in this repository have been validated using industry-standard linters to ensure proper syntax and structure. 

### YAML Validation

The YAML configuration file has been validated using [YAML Lint](http://www.yamllint.com/), confirming proper YAML syntax and structure.

![YAML Validation Result](https://github.com/AbrahamGyamfi/YAML_Config/blob/main/Screenshot_YAML_lint.png)

*YAML validation screenshot showing successful parsing and validation*

### JSON Validation

The JSON configuration file has been validated using [JSONLint](https://jsonlint.com/), ensuring JSON formatting compliance and correctness.

![JSON Validation Result](https://github.com/AbrahamGyamfi/YAML_Config/blob/main/Screenshot_jsonlint.com.jpeg)

*JSON validation screenshot showing successful parsing and validation*

Both validation results confirm that the configuration files are syntactically correct and ready for use in production environments.

