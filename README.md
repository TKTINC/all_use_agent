# ALL-USE Agent

## Overview

ALL-USE (Automated Lumpsum Leveraged US Equities) Agent is an autonomous agent designed to manage a triple-account trading system that generates consistent income and builds long-term wealth through options trading in US equity markets.

## Agent Capabilities

- **Perception**: Monitor market conditions, account states, and external signals
- **Cognition**: Analyze market conditions, select strategies, and make trading decisions
- **Action**: Execute trades, manage positions, and perform account lifecycle operations
- **Memory**: Maintain knowledge of trading history, market patterns, and strategy performance
- **Learning**: Improve strategies based on performance and adapt to changing market conditions

## Triple-Account Structure

The ALL-USE Agent manages three specialized accounts:

1. **Gen-Acc (Generator)**: Weekly ATM wheel strategy (40-50 delta) on high-volatility stocks
2. **Rev-Acc (Revenue)**: Income-stable wheel (30-40 delta OTM) on blue-chip stocks
3. **Com-Acc (Compounding)**: Long-hold compounding engine using shares and LEAPS

## Key Features

- Week-type classification and prediction (Green, Red, or Chop)
- ATR Protocol for risk management and position adjustment
- Account forking, reinvestment, and merging logic
- Integration with STAR-LAB for external trading signals
- Continuous learning and strategy optimization

## Repository Structure

- `/docs`: Documentation including implementation prompts and responses
- `/src`: Source code for the agent implementation
  - `/agent_core`: Core agent architecture components
  - `/learning_systems`: Learning and optimization capabilities
  - `/trading_systems`: Trading strategies and execution logic
- `/tests`: Comprehensive test suite

## Development Status

Currently in initial development phase, focusing on agent architecture design and core capabilities.

## Getting Started

See the [Team Onboarding Guide](/docs/team_onboarding_guide.md) for setup instructions.
