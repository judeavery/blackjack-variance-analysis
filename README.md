# Blackjack Variance Analysis (In Progress)

## Project Overview
This project explores **risk, variance, and expectation in blackjack** using large-scale simulation.  
Rather than asking whether blackjack can be “beaten,” the goal is to understand **why even optimal play can feel unfair** due to variance, long losing streaks, and bankroll constraints.

The project focuses on simulating realistic casino rules and player behavior to quantify:
- Expected value (EV)
- Volatility and downswings
- Risk of ruin
- The difference between *mathematical edge* and *lived experience*

This repository is **actively under development** and results will evolve as the simulation engine and experiments are completed.

---

## Motivation
Blackjack is a rare real-world system where:
- Probabilities are well-defined
- Optimal strategy is known
- Outcomes still feel unpredictable to humans

Even when players use perfect basic strategy or card counting, large downswings and long losing streaks are common. This project aims to **quantify that disconnect** and explain why intuition often fails in high-variance environments.

---

## Project Status
**Current State:** In progress  
- Core simulation engine is being built
- Strategy logic and betting policies are under development
- No final results or conclusions yet

This README will be updated as milestones are completed and results become available.

---

## Planned Features
The final project will include:

### Simulation Engine
- Multi-deck blackjack simulator (6-deck shoe)
- Realistic casino rules:
  - Dealer stands on soft 17 (S17)
  - Blackjack payout: 3:2
  - Double after split allowed (DAS)
  - No surrender
  - Insurance never taken
- Accurate handling of:
  - Splits
  - Doubles
  - Blackjacks
  - Shoe penetration and reshuffling

### Strategy & Betting
- Basic strategy implementation
- Hi-Lo card counting system
- Flat betting vs count-based bet spreads
- Bankroll tracking across long sessions

### Metrics & Analysis
- Expected value per hand
- Variance and standard deviation
- Longest losing streaks
- Maximum drawdown
- Risk of ruin under different bankroll sizes
- Performance conditional on true count

### Visualization & Reporting
- Bankroll trajectories
- Distribution of session outcomes
- Drawdown and streak length distributions
- Comparison of strategies and rule variations

## Repository Structure (Planned)
-TBD


