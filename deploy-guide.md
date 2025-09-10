# Frontend Projects Deployment Guide

## Projects Identified for Vercel Deployment:

### 1. React Movie Explorer
- **Repository**: https://github.com/Kennethfeh/react-movie-explorer
- **Type**: React Frontend Application
- **Status**: Ready for deployment

### 2. Code Snippet Manager  
- **Repository**: https://github.com/Kennethfeh/code-snippet-manager
- **Type**: Full-Stack JavaScript Application
- **Status**: Ready for deployment

### 3. Astro Content Portfolio
- **Repository**: https://github.com/Kennethfeh/astro-content-portfolio  
- **Type**: Astro Frontend Framework
- **Status**: Ready for deployment

## Deployment Commands:

### Option 1: Deploy from GitHub (Recommended)
```bash
# Deploy React Movie Explorer
vercel --prod --name react-movie-explorer-kenneth

# Deploy Code Snippet Manager
vercel --prod --name code-snippet-manager-kenneth

# Deploy Astro Content Portfolio  
vercel --prod --name astro-portfolio-kenneth
```

### Option 2: Clone and Deploy Locally
```bash
# Clone and deploy React Movie Explorer
git clone https://github.com/Kennethfeh/react-movie-explorer.git
cd react-movie-explorer
vercel --prod

# Clone and deploy Code Snippet Manager
git clone https://github.com/Kennethfeh/code-snippet-manager.git
cd code-snippet-manager
vercel --prod

# Clone and deploy Astro Content Portfolio
git clone https://github.com/Kennethfeh/astro-content-portfolio.git
cd astro-content-portfolio
vercel --prod
```

## Expected Live URLs:
After deployment, you'll get URLs like:
- React Movie Explorer: https://react-movie-explorer-kenneth.vercel.app
- Code Snippet Manager: https://code-snippet-manager-kenneth.vercel.app  
- Astro Portfolio: https://astro-portfolio-kenneth.vercel.app

## Next Steps:
1. Deploy all three projects
2. Collect the live URLs
3. Update portfolio with "View Live" buttons
4. Test all live links