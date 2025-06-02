# OnChain-FedLearn MVP Tasks

This document outlines the essential tasks required to build a minimum viable product (MVP) of the OnChain-FedLearn system, focusing on integrating existing federated learning code and creating a modular anomaly detection pipeline.

## Phase 1: Federated Learning Integration
**Setup and Configuration**
   - [ ] Task 1: Clone and set up existing federated learning repository
   - [ ] Task 2: Set up and test 2-node network configuration
   - [ ] Task 3: Test basic federated learning functionality
   - [ ] Task 4: Document integration points for anomaly detection

## Phase 2: Anomaly Detection Pipeline
**Framework Setup**
   - [ ] Task 5: Set up class structures and interfaces for modular algorithm framework
   - [ ] Task 6: Implement algorithm configuration system
   - [ ] Task 7: Create pipeline orchestration layer

**Data Ingestion**
   - [ ] Task 8: Create data ingestion interface for single blockchain
   - [ ] Task 9: Implement basic data preprocessing (as needed)
   - [ ] Task 10: Set up data validation

**Metrics**
   - [ ] Task 11: Implement single anomaly detection algorithm
   - [ ] Task 12: Set up metrics storage

**Data Fusion**
   - [ ] Task 13: Implement basic fusion algorithm
   - [ ] Task 14: Set up confidence scoring

**Pipeline Integration**
   - [ ] Task 15: Roll the marble: end-to-end testing

## Phase 3: NEAR Integration
**Integration with Federated Learning**
   - [ ] Task 16: Set up NEAR account and permissions
   - [ ] Task 17: Connect anomaly detection pipeline to federated learning nodes
   - [ ] Task 18: Test integrated system

## Phase 4: Testing & Deployment
**Local Testing**
   - [ ] Task 19: Implement unit tests for anomaly detection
   - [ ] Task 20: Set up integration tests
   - [ ] Task 21: Create end-to-end testing environment

**Deployment**
   - [ ] Task 22: Deploy to NEAR testnet
   - [ ] Task 23: Set up test nodes
   - [ ] Task 24: Create deployment scripts
   - [ ] Task 25: Document deployment process

## Technical Requirements
- Existing federated learning codebase
- NEAR Protocol SDK
- Python/Rust for anomaly detection
- Basic encryption libraries
- Web3 libraries for NEAR interaction

## Success Criteria
- Existing federated learning code runs successfully
- Single anomaly detection algorithm processes data end-to-end
- Basic training rounds can be completed
- System can run on NEAR testnet
- Modular components can be tested independently

## Next Steps After MVP
- Add more anomaly detection algorithms
- Implement more sophisticated privacy measures
- Add support for more nodes
- Enhance model architecture
- Improve UI/UX
- Add more advanced analytics

## Notes
- Focus on getting existing federated learning code working first
- Keep anomaly detection components modular and independent
- Document all components thoroughly
- Create clear testing procedures
- Maintain clean interfaces between components 