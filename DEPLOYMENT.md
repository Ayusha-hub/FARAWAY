# SignalX AI - Deployment Guide

## 🚀 Vercel Production Deployment

### Prerequisites

1. **Vercel Account** - Create account at vercel.com
2. **GitHub Repository** - Push code to GitHub
3. **Firebase Project** - Set up Firebase project with:
   - Authentication (Email/Password)
   - Firestore Database
   - Storage
   - API Keys

### Environment Variables

Add these environment variables in Vercel:

```bash
NEXT_PUBLIC_FIREBASE_API_KEY=your_firebase_api_key
NEXT_PUBLIC_FIREBASE_AUTH_DOMAIN=your_project.firebaseapp.com
NEXT_PUBLIC_FIREBASE_PROJECT_ID=your_project_id
NEXT_PUBLIC_FIREBASE_STORAGE_BUCKET=your_project.appspot.com
NEXT_PUBLIC_FIREBASE_MESSAGING_SENDER_ID=your_sender_id
NEXT_PUBLIC_FIREBASE_APP_ID=your_app_id
NEXT_PUBLIC_GEMINI_API_KEY=your_gemini_api_key
NEXT_PUBLIC_MAPBOX_TOKEN=your_mapbox_token
```

### Deployment Steps

1. **Connect Vercel to GitHub**
   - Go to Vercel dashboard
   - Click "Add New Project"
   - Import your GitHub repository

2. **Configure Build Settings**
   - Framework Preset: Next.js
   - Root Directory: `./`
   - Build Command: `npm run build`
   - Output Directory: `.next`

3. **Add Environment Variables**
   - Add all Firebase and API keys
   - Mark sensitive variables as "Secret"

4. **Deploy**
   - Click "Deploy"
   - Wait for build to complete
   - Vercel will provide a production URL

### Firebase Setup

1. **Enable Authentication**
   - Go to Firebase Console → Authentication
   - Enable Email/Password provider
   - Add test users if needed

2. **Configure Firestore**
   - Create Firestore database
   - Set rules (use `firestore.rules` from project)
   - Deploy indexes (use `firestore.indexes.json`)

3. **Configure Storage**
   - Enable Storage for Firebase
   - Set security rules
   - Configure CORS if needed

### Post-Deployment Checklist

- [ ] Test authentication flow
- [ ] Verify Firestore connectivity
- [ ] Test incident reporting
- [ ] Verify AI analysis works
- [ ] Test live map rendering
- [ ] Check SOS functionality
- [ ] Verify notifications
- [ ] Test demo mode
- [ ] Check analytics page
- [ ] Verify global search
- [ ] Test on mobile devices
- [ ] Check performance metrics

### Performance Optimization

The project includes:
- **SWC Minification** - Enabled in next.config.mjs
- **Package Optimization** - Lucide React and Recharts optimized
- **Dynamic Imports** - Heavy components lazy-loaded
- **Image Optimization** - Next.js Image component
- **Console Removal** - Console logs removed in production

### Monitoring

- **Vercel Analytics** - Built-in performance monitoring
- **Firebase Console** - Monitor database and auth
- **Vercel Logs** - Check for errors and warnings
- **Lighthouse** - Run performance audits

### Rollback Strategy

If deployment fails:
1. Vercel automatically keeps previous deployments
2. Use "Redeploy" with previous commit
3. Check environment variables
4. Review build logs for errors

### Custom Domain (Optional)

1. Buy domain from registrar
2. Add domain in Vercel settings
3. Update DNS records (CNAME)
4. Enable SSL (automatic)

### Troubleshooting

**Build Errors:**
- Check Node.js version (should be 18+)
- Verify all dependencies installed
- Check for TypeScript errors

**Runtime Errors:**
- Verify environment variables
- Check Firebase configuration
- Review browser console for errors

**Performance Issues:**
- Check bundle size in Vercel
- Enable caching headers
- Review Firestore query performance

## 🔒 Security Checklist

- [ ] All API keys in environment variables
- [ ] Firebase rules deployed
- [ ] Rate limiting implemented
- [ ] Input validation on forms
- [ ] HTTPS enforced
- [ ] CORS configured
- [ ] Authentication required for sensitive routes
- [ ] No sensitive data in client-side code

## 📊 Scaling Considerations

### Current Architecture
- Serverless (Vercel)
- Firebase auto-scaling
- CDN for static assets
- Real-time via Firestore

### Future Scaling
- Add Redis for caching
- Implement rate limiting
- Add CDN for images
- Consider edge functions
- Database sharding if needed

## 🎯 Production Best Practices

1. **Always test in staging first**
2. **Use feature flags for new features**
3. **Monitor error rates**
4. **Set up alerts for critical errors**
5. **Regular security audits**
6. **Keep dependencies updated**
7. **Backup critical data**
8. **Document deployment process**

## 📝 Maintenance

### Regular Tasks
- Weekly: Check error logs
- Monthly: Update dependencies
- Quarterly: Security audit
- Annually: Architecture review

### Emergency Contacts
- Vercel Support
- Firebase Support
- Domain Registrar
- DNS Provider

## 🌐 URL Structure

- **Production**: `https://signalx-ai.vercel.app`
- **Custom Domain**: `https://signalx.ai` (if configured)
- **API Routes**: `/api/*`
- **Dashboard**: `/dashboard`
- **Auth**: `/login`, `/signup`

## ✅ Deployment Complete

Once deployed, SignalX AI will be:
- Accessible globally via CDN
- Auto-scaling with Vercel
- Real-time with Firebase
- Optimized for performance
- Secure with best practices
- Ready for hackathon judging
