# ============================================================
# ROS Vietnam - CODEOWNERS
# ============================================================
# This file defines code ownership and review responsibility.
# Code owners are automatically requested for reviews on PRs.
#
# Ownership implies:
# - Technical review responsibility
# - Architectural consistency
# - Long-term maintenance commitment
#
# ============================================================

# -------------------------
# Global Owners
# -------------------------
# Fallback owners for all files
* @ros-vietnam/core-maintainers

# -------------------------
# Documentation
# -------------------------
/README.md                @ros-vietnam/docs
/docs/                    @ros-vietnam/docs

# -------------------------
# Core ROS Packages
# -------------------------
/ros2/                    @ros-vietnam/core
/src/core/                @ros-vietnam/core

# -------------------------
# Simulation
# -------------------------
/simulation/              @ros-vietnam/simulation
/gazebo/                  @ros-vietnam/simulation

# -------------------------
# Perception
# -------------------------
/perception/              @ros-vietnam/perception

# -------------------------
# Motion Control
# -------------------------
/control/                 @ros-vietnam/control

# -------------------------
# Planning & Navigation
# -------------------------
/planning/                @ros-vietnam/planning
/navigation/              @ros-vietnam/planning

# -------------------------
# Swarm & Multi-Agent
# -------------------------
/swarm/                   @ros-vietnam/swarm

# -------------------------
# Fleet Management & Distributed Systems
# -------------------------
/fleet/                   @ros-vietnam/fleet
/distributed/             @ros-vietnam/fleet

# -------------------------
# Benchmarking & Evaluation
# -------------------------
/benchmarks/              @ros-vietnam/benchmark

# -------------------------
# CI / Infrastructure
# -------------------------
/.github/workflows/       @ros-vietnam/infra
/scripts/ci/              @ros-vietnam/infra
