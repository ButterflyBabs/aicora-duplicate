# Deployment Instructions

## GitHub Repository Setup

1. Create a new repository on GitHub (e.g., `aicora-duplicate`)
2. Run the following commands to push:

```bash
cd /root/.openclaw/workspace/aicora-duplicate
git remote add origin https://github.com/YOUR_USERNAME/aicora-duplicate.git
git branch -M main
git push -u origin main
```

## Vercel Deployment

### Option 1: Via Vercel CLI

```bash
npm i -g vercel
vercel
```

### Option 2: Via GitHub Integration

1. Go to https://vercel.com/new
2. Import your GitHub repository
3. Deploy!

### Option 3: Manual Upload

1. Go to https://vercel.com/new
2. Select "Import Git Repository"
3. Enter your GitHub repo URL
4. Deploy

## Configuration

The `vercel.json` file is already configured for SPA routing with the following routes:
- `/assets/*` - Serves static assets
- `/*` - Falls back to index.html for client-side routing

## Site Details

- **Original URL**: https://aicora.aisuites.io/dashboard
- **Type**: React Single Page Application (SPA)
- **Total Size**: ~14MB
- **Files**: 102 files

## Routes Identified

The application includes the following routes:
- `/dashboard` - Main dashboard
- `/login` - Login page
- `/agents` - Agents management
- `/clients` - Client management
- `/chats` - Chat interface
- `/content` - Content management
- `/editor` - Content editor
- `/image-editor` - Image editing tool
- `/ideation-generator` - AI ideation tool
- `/integrations` - Third-party integrations
- `/my-account` - User account
- `/schedule` - Scheduling
- `/help-support` - Support center
- And more...
