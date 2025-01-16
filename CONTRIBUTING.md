# Contributing to SmartRent

Thank you for your interest in contributing to SmartRent! We aim to make the house rental management system more secure and convenient through blockchain technology and smart contracts. This document provides guidelines for contributing to our project.

## Table of Contents
- [Development Workflow](#development-workflow)
- [Code Standards](#code-standards)
- [Submitting Changes](#submitting-changes)
- [Testing Guidelines](#testing-guidelines)

## Development Workflow

1. Create a new branch for your feature/fix:
```bash
git checkout -b feature/your-feature-name
```

2. Make your changes and commit using conventional commit messages:
```bash
git commit -m "feat: add new feature"
git commit -m "fix: resolve issue with..."
```

3. Push your changes and create a pull request:
```bash
git push origin feature/your-feature-name
```

## Code Standards

### General Guidelines
- Follow clean code principles
- Write meaningful commit messages following conventional commits
- Include comments for complex logic
- Write unit tests for new features

### JavaScript/TypeScript
- Use ES6+ features
- Follow Airbnb JavaScript Style Guide
- Use TypeScript for type safety
- Use async/await for asynchronous operations

### Smart Contracts
- Follow Solidity style guide
- Document all functions and state variables
- Include proper error handling
- Optimize for gas efficiency
- Always include security considerations

## Submitting Changes

1. Ensure all tests pass
2. Update documentation if needed
3. Create a pull request with:
   - Clear description of changes
   - Link to related issues
   - Screenshots for UI changes
   - Test results

## Testing Guidelines

### Unit Tests
- Write unit tests for all new features
- Maintain at least 80% code coverage
- Use Jest for JavaScript/TypeScript testing
- Use Hardhat for smart contract testing

### Integration Tests
- Test API endpoints using Postman/Jest
- Test smart contract interactions
- Verify database operations
- Check message queue functionality

### End-to-End Tests
- Test complete user workflows
- Verify mobile and web interfaces
- Test blockchain transactions
- Validate smart contract operations

## Questions or Need Help?

Feel free to:
- Open an issue for bugs or feature requests
- Join our developer community (link to community)
- Contact the core team at [development email]

## License

By contributing to SmartRent, you agree that your contributions will be licensed under its MIT license.
