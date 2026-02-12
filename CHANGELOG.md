Changelog
All notable changes and milestones for the MISO / SushiSwap integration project.

Unreleased
Ongoing maintenance, docs improvements, and tests.
2021
December 2021
Release: v1.3 — UX refinements for token sale flow, improved error handling for failed transactions.
Added monitoring scripts to detect failed auctions and notify maintainers.
Tests: expanded E2E tests for front-end purchase flows; smart contract interaction mocks added.
August 2021
Release: v1.2 — Improved wallet connection handling (meta‑mask + WalletConnect), gas fee estimation, and nonce management.
Security: added input validation and client-side sanitization for sale parameters.
CI: integrated test and lint steps into GitHub Actions.
May 2021
Release: v1.1 — Add support for multiple sale types (fixed-price, dutch auction) in the front-end UI.
Backend: introduced lightweight monitoring worker to track pending transactions and update UI state.
March 2021
Initial public release: v1.0 — Core MISO integration features:
Front-end components for token sale creation and participation (React, Web3.js).
Smart contract interaction helpers and utility scripts.
Deployment scripts and README with run instructions.
2020
December 2020
Prototype and POC completed — basic flow for token sale creation and front-end interaction with MISO contracts.
Implemented initial smart contract call wrappers (Web3.js) and sample UI pages.
Internal demo with stakeholders; collected feedback and defined product backlog for 2021.
October 2020
Project kickoff: specification, architecture, and tech stack selection.
Chosen stack: React, Web3.js, Hardhat (or project-specific tooling), Node.js for tooling scripts.
Set up initial repo, linters, and CI templates.
