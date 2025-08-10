# Release Notes

## Version 2.1.0 (2025-08-10)

### New Features
- ✨ New user dashboard with enhanced analytics
- 🔐 Two-factor authentication support
- 📊 Real-time usage metrics
- 🌙 Dark mode theme

### Improvements
- ⚡ 40% faster API response times
- 💾 Reduced memory usage by 25%
- 🔧 Better error handling and logging
- 📱 Mobile responsive improvements

### Bug Fixes
- 🐛 Fixed user profile image upload issue
- 🔨 Resolved pagination edge case
- 🎯 Fixed notification timing issues

### Breaking Changes
- ⚠️ API endpoint `/api/v1/user` changed to `/api/v1/users`
- ⚠️ Configuration format updated (see migration guide)

### Migration Guide
```javascript
// Old format
{ user: { settings: {...} } }

// New format  
{ users: { settings: {...} } }
```
