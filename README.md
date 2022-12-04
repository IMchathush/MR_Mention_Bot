# MR_Mention_Bot
MR Bot Zone Project ⚡️🇱🇰

# https://docs.github.com/en/code-security/supply-chain-security/configuring-dependabot-security-updates
# Basic set up

version: 2
updates:
  # Maintain dependencies for GitHub Actions
  - package-ecosystem: 'github-actions'
    directory: '/'
    schedule:
      interval: 'daily'
