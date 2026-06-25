Enterprise AI Agent Platform
Reference Architecture
for OpenShift AI

Version 1.0

------------------------------------------------------------

An enterprise reference architecture for building
cloud-native AI Agent Platforms on OpenShift AI.

This architecture standardizes how AI Agents,
Tool Calling, Business Services, Metadata,
and Enterprise Systems collaborate.

The goal is to provide a reusable,
vendor-neutral architecture that enables
organizations to build production-grade AI
applications while keeping business logic,
metadata, and AI reasoning clearly separated.

Core Principles

• AI performs reasoning
• Business APIs execute business logic
• Metadata is managed by OpenMetadata
• Every external capability is exposed as a Tool
• Agents remain stateless
• Workflows are orchestrated by LangGraph
• Deployments follow GitOps
• Everything runs natively on OpenShift



Chapter 1

Vision

--------------------------------------------------

Chapter 2

Architecture Principles

・Cloud Native
・AI Native
・Agent First
・Tool First
・API First
・Metadata First
・Open Standards
・GitOps
・Security by Design

--------------------------------------------------

Chapter 3

Reference Architecture

Logical Architecture

Physical Architecture

Deployment Architecture

Reference Implementation

Chapter 4

Technology Stack

・OpenShift AI
・LangGraph
・Quarkus
・OpenMetadata
・vLLM
・Granite
・PostgreSQL
・Kafka
・Keycloak

Chapter 5

Platform Architecture

Presentation Layer

AI Orchestrator

Agent Layer

Tool Layer

Business Layer

Infrastructure Layer

Chapter 6

AI Agent Framework

Schema Agent

Registration Agent

Validation Agent

Search Agent

Planning Agent

Workflow Agent

Coding Agent

Operations Agent

Governance Agent

Chapter 7

Tool Framework

OpenMetadata Tool

Business Tool

Filesystem Tool

Git Tool

OpenShift Tool

Kubernetes Tool

Search Tool

Kafka Tool

Chapter 8

Prompt Framework

System Prompt

Task Prompt

Workflow Prompt

Validation Prompt

Tool Prompt

Chapter 9

Memory Framework

Conversation Memory

Session Memory

Workflow Memory

Knowledge Memory

Context Window Strategy

Chapter 10

OpenMetadata Integration

Schema

Glossary

Lineage

Domain

Ownership

Data Quality

Chapter 11

Business Services

Quarkus

REST

Validation

Persistence

Audit

Transaction

Chapter 12

Security

Keycloak

OIDC

RBAC

Secrets

TLS

Audit

Chapter 13

Deployment

Helm

Kustomize

GitOps

Tekton

ArgoCD

Chapter 14

Observability

OpenTelemetry

Prometheus

Grafana

Jaeger

Structured Logging

Chapter 15

Scalability

Stateless Agents

Horizontal Scaling

Model Serving

GPU Pool

High Availability

Chapter 16

Developer Guide

Local Development

Testing

Debugging

Developer Hub

Chapter 17

Claude Code Guide

Project Context

Implementation Order

Workflow

Coding Strategy

Testing Strategy



Appendix A

Coding Rules

--------------------------------

Appendix B

Directory Structure

--------------------------------

Appendix C

Naming Convention

--------------------------------

Appendix D

Technology Selection

--------------------------------

Appendix E

Reference Repository Layout

--------------------------------

Appendix F

Future Roadmap
