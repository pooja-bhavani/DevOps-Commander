# DevOps-Commander Deployment Guide

## Overview

This guide covers the deployment process for the DevOps-Commander Jira Forge app across different environments (development, staging, production).

## Prerequisites

- Node.js 20.x or higher
- Forge CLI v12.12.0+
- Jira Cloud instance with admin access
- Atlassian Developer Account
- Git for version control

## Deployment Environments

DevOps-Commander is deployed to three environments:

| Environment | Type | Purpose | Status |
|-------------|------|---------|--------|
| Development | Development | Local testing and feature development | Active |
| Staging | Development | Pre-production testing and QA | Active |
| Production | Production | Live deployment for end users | Active |

## Deployment Process

### Step 1: Lint and Validate

Before deploying, always run linting checks:

```bash
cd devops-commander
forge lint
```

**Output**: `No issues found.`

This ensures code quality and catches any errors before deployment.

### Step 2: Deploy to Environment

Deploy to your target environment:

```bash
# Deploy to development
forge deploy

# Deploy to staging
forge deploy --environment staging

# Deploy to production
forge deploy --environment production --no-verify
```

**Deployment Steps**:
1. ✓ Packaging app files
2. ✓ Uploading app
3. ✓ Validating manifest
4. ✓ Snapshotting functions
5. ✓ Deploying to environment

### Step 3: Verify Deployment

Check deployment status in the Atlassian Developer Console:

```
Console → DevOps-Commander → Deployments
```

**Deployment Status Indicators**:
- ✅ **SUCCESS** - Deployment completed without errors
- ⏳ **IN PROGRESS** - Deployment is currently running
- ❌ **FAILED** - Deployment encountered errors (check logs)

### Step 4: Install in Jira

After successful deployment, install the app in your Jira instance:

```bash
forge install
```

You'll be prompted to:
1. Select your Jira Cloud instance
2. Confirm the installation
3. Grant necessary permissions

## Deployment History

### Production Deployments

| Date | Time (UTC) | Contributor | Version | Environment | Status |
|------|-----------|-------------|---------|-------------|--------|
| Dec 20, 2025 | 20:24:19.768 | Pooja Bhavani | 2 | Production | ✅ SUCCESS |
| Dec 20, 2025 | 20:23:37.105 | Pooja Bhavani | 2 | default | ✅ SUCCESS |
| Dec 20, 2025 | 15:13:25.734 | Pooja Bhavani | 2 | default | ✅ SUCCESS |
| Dec 20, 2025 | 15:00:49.650 | Pooja Bhavani | 2 | default | ✅ SUCCESS |
| Dec 20, 2025 | 14:12:40.753 | Pooja Bhavani | 2 | default | ✅ SUCCESS |

## Monitoring Deployments

View real-time deployment metrics and logs:

```
Developer Console → Deployments → View Logs
```

### Key Metrics

- **Deployment Time**: Typically 2-5 minutes
- **Package Size**: ~2-3 MB
- **Function Count**: 6 resolver functions
- **Environment Variables**: Configured per environment

## Troubleshooting

### Deployment Failures

**Issue**: `Failed to fetch or select Developer Space`

**Solution**:
1. Ensure you're logged in: `forge login`
2. Verify Developer Space exists
3. Check Atlassian API token permissions

**Issue**: `Manifest validation failed`

**Solution**:
1. Run `forge lint` to identify issues
2. Fix validation errors in `manifest.yml`
3. Redeploy: `forge deploy`

### Installation Issues

**Issue**: `App installation failed`

**Solution**:
1. Verify Jira admin privileges
2. Check app permissions in manifest
3. Clear browser cache and retry
4. Ensure Jira instance has available app slots

## Rollback Procedure

If issues occur in production:

```bash
# Rollback to previous version
forge deploy --environment production --no-verify

# Or manually select a previous deployment
# From Developer Console → Deployments → Select Version → Deploy
```

## Best Practices

1. **Always test in development first** before production deployment
2. **Run linting** before every deployment
3. **Tag releases** in Git for version tracking
4. **Monitor logs** for 15 minutes after deployment
5. **Have a rollback plan** ready before production deployments
6. **Document changes** in deployment notes
7. **Schedule deployments** during low-traffic periods

## Version Management

Current major version: **2**

### Version Increment Strategy

- **Major** (X.0.0): Breaking changes or significant features
- **Minor** (1.X.0): New features that are backwards compatible
- **Patch** (1.1.X): Bug fixes and minor improvements

## Deployment Timeline

```
┌─────────────────────────────────────────┐
│     Push to Git (commit/merge)          │
└──────────────┬──────────────────────────┘
               │
               ▼
┌─────────────────────────────────────────┐
│     Run Tests & Linting (CI)            │
└──────────────┬──────────────────────────┘
               │
               ▼
┌─────────────────────────────────────────┐
│   Forge Deploy to Dev/Staging           │
└──────────────┬──────────────────────────┘
               │
               ▼
┌─────────────────────────────────────────┐
│     Manual Testing & Verification       │
└──────────────┬──────────────────────────┘
               │
               ▼
┌─────────────────────────────────────────┐
│  Forge Deploy to Production             │
└──────────────┬──────────────────────────┘
               │
               ▼
┌─────────────────────────────────────────┐
│    Monitor & Validate in Production     │
└─────────────────────────────────────────┘
```

## Support

For deployment issues:

- Check [Forge CLI Documentation](https://developer.atlassian.com/platform/forge/)
- Review [Jira Forge API Docs](https://developer.atlassian.com/cloud/jira/platform/)
- Contact DevOps-Commander maintainers

## See Also

- [Installation Guide](./INSTALLATION.md)
- [Configuration Guide](./CONFIGURATION.md)
- [Troubleshooting Guide](./TROUBLESHOOTING.md)
