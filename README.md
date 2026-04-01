# [Uncover Status](https://Uncover-Fitness.github.io/status)

Automated uptime monitoring and status page for [Uncover](https://uncover.fit), powered by [Upptime](https://github.com/upptime/upptime).

## Monitored Services

| Service | URL |
|---------|-----|
| Web App | https://uncover.fit |
| API | https://uncover-production-2743.up.railway.app/api/v1/health |

## How It Works

- GitHub Actions checks endpoints every **5 minutes**
- When a service goes down, a **GitHub Issue** is automatically created
- Response time graphs are generated **daily**
- Status page is published to **GitHub Pages**

## Setup

This repo requires a `GH_PAT` secret (Personal Access Token with `repo` scope) to allow Upptime workflows to commit status data.

[![Uptime CI](https://github.com/Uncover-Fitness/status/actions/workflows/uptime.yml/badge.svg)](https://github.com/Uncover-Fitness/status/actions/workflows/uptime.yml)
