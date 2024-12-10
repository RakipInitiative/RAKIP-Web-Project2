# Project overview

## Project name
FSKX-Microservice-Platform

## Project description
This Platform shall be a microservices-based resource that enables Model Creators to define and shareFSKX models, Model Curators to evaluate these FSKX files before they are made accessible through a cloud-based model repository (with model versioning via Zenodo), Unregistered Users to find, search and inspect the FSKX files and Registered User to run user-defined simulations with the FSKX models from the repository. Platform Administrators will have the ability to efficiently monitor and maintain the FSKX microservice platform along with all its APIs and applications.
The platform will support secure, cloud-based execution of FSKX models without requiring Registered Users to install software locally. Backend services will be implemented as dedicated microservices, ensuring scalability, modularity, and ease of maintenance. Dedicated UIs will be provided for Model Creators, Model Curators, Users, and Platform Administrators to interact with the platform..
### Goals
- Support Model Creation: Enable Model Creators to input metadata, paste their model code (supporting multiple programming languages executable without a license), and generate FSKX model files via the service.
- Facilitate Model Review: Provide tools for Model Curators to evaluate and validate models before they are accepted into the community repository.
- Enable execution of FSKX files for Registered Users: Allow Registered Users to execute registered FSKX models using custom input parameters without needing to install any software.
- Microservices Architecture: Implement a modular design where key functionalities are each handled by dedicated microservices, enhancing scalability and maintainability.
- Security and Efficiency: Ensure models are secure before registration in the model repository and before execution, implement security features across all microservices, and provide automated deployment environments via Docker.
- User Management and Support: Include a user management system for Platform Administrators, enforce user-specific and microservice-specific resource quotas, and provide UIs for user feedback and support.

## Client
*Insert client name and contact info*

## Project lead
Thomas Schüler

## Project team
Thomas Schüler
Matthias Filter
Tinatin Kasradze
Racem Ben-Romdhane
MSG (external contractor)

## Definition of done
**Minimum Viable Product:**
- Cloud Server based FSKX Platform 
  - online resource to create valid FSKX model files
  - online resource to execute curated FSKX models online
  - system architecture and microservices adhere to BSI requirements
  - centralized monitoring of microservices established
  - CI/CD for microservices include unit-tests, vulnurability-scanning, automatic deployment to Cloud (AWS)
- complete documentation of work done
  - management summary with links to each ticket
- runbooks to opereate AWS cloud-services and implemented microservices
 

## Input information
requirement analysis: [google-doc](https://docs.google.com/document/d/1I6cHCkQaCJaefLsXmQtdH74ExnBeQS_q-rwV_40FnoM/edit?tab=t.0#heading=h.vn6jbd619nez)

## Result document
*Insert link to document, once report was created*

## Expected resources required
*tbd*

## Timeline
Start: 06.09.2024 Kickoff Meeting
Milestone 1 (minimum viable product): 31.12.2024
Expected End: end of 2025
