# 🏔️ Aquarius Engineering Department - Manual Tasks Checklist

## 🎯 Nerve UI Configuration Tasks

### **Phase 1: Immediate (Today)**

#### **1. GitHub Organization Setup**
- [ ] **Visit GitHub:** https://github.com
- [ ] **Log in** with `scorpio@arcturiongroup.com` account
- [ ] **Click profile picture** (top right) → **"Settings"**
- [ ] **Left sidebar** → **"Organizations"**
- [ ] **Click "New organization"** button
- [ ] **Select "Free" plan**
- [ ] **Organization name:** `arcturion-technologies`
- [ ] **Contact email:** `scorpio@arcturiongroup.com`
- [ ] **Billing email:** [your billing email]
- [ ] **Click "Create organization"**
- [ ] **Verify organization URL:** https://github.com/arcturion-technologies

#### **2. Repository Transfer**
- [ ] **Go to repository:** https://github.com/scorpio-assistant/arcturion-technologies
- [ ] **Click "Settings" tab** (top of repo page, next to "Insights")
- [ ] **Scroll down** to **"Danger Zone"** section
- [ ] **Click "Transfer"** button
- [ ] **Destination owner:** Search for `arcturion-technologies`
- [ ] **Confirm transfer** (type repository name: `arcturion-technologies`)
- [ ] **Wait for transfer** (should be instant)
- [ ] **Verify new URL:** https://github.com/arcturion-technologies/arcturion-technologies

#### **3. GitHub Pages Setup**
- [ ] **Go to transferred repo:** https://github.com/arcturion-technologies/arcturion-technologies
- [ ] **Click "Settings" tab**
- [ ] **Left sidebar** → **"Pages"**
- [ ] **Source:** Select `main` branch
- [ ] **Folder:** `/ (root)`
- [ ] **Save**
- [ ] **Wait 1-2 minutes** for deployment
- [ ] **Verify website:** https://arcturion-technologies.github.io

### **Phase 2: Platform Connections (This Week)**

#### **4. YouTube Authentication Fix**
- [ ] **Visit Google Cloud Console:** https://console.cloud.google.com
- [ ] **Navigate to:** APIs & Services → OAuth consent screen
- [ ] **Verify YouTube Data API v3 is enabled**
- [ ] **Check YouTube scope:** `https://www.googleapis.com/auth/youtube.upload`
- [ ] **Reauthorize YouTube connection** in Composio
- [ ] **Test upload** with short video

#### **5. Instagram Business Connection**
- [ ] **Ensure Instagram account** is Business/Creator type
- [ ] **Visit Facebook for Developers:** https://developers.facebook.com
- [ ] **Create App** → **"Business"** type
- [ ] **Add Instagram Basic Display** product
- [ ] **Configure OAuth Redirect URIs**
- [ ] **Submit for review** (may take days)
- [ ] **Connect Instagram** via Composio once approved

#### **6. Reddit OAuth Setup**
- [ ] **Visit Reddit Apps:** https://www.reddit.com/prefs/apps
- [ ] **Click "create app"** or "create another app..."
- [ ] **App type:** "script"
- [ ] **Redirect URI:** `https://composio.dev/oauth/reddit/callback`
- [ ] **Get client ID & secret**
- [ ] **Connect Reddit** via Composio

#### **7. Slack/Discord Connections**
- [ ] **Slack:** Create app at https://api.slack.com/apps
- [ ] **Discord:** Create app at https://discord.com/developers/applications
- [ ] **Configure OAuth scopes** for posting
- [ ] **Connect via Composio**

### **Phase 3: Nerve UI Enhancements**

#### **8. API Cost Tracking Integration**
- [ ] **Review Composio usage dashboard**
- [ ] **Set up cost alerts** at $50, $100, $150 thresholds
- [ ] **Create monthly budget report** template
- [ ] **Integrate with Nerve UI** cost display

#### **9. Visual Task Mapping**
- [ ] **Design department visualization** (7 departments)
- [ ] **Create workflow diagrams** for each department
- [ ] **Implement real-time status indicators**
- [ ] **Add progress tracking** for manual tasks

#### **10. Plain-English Interface**
- [ ] **Audit current Nerve UI** for technical jargon
- [ ] **Replace with simple English** equivalents
- [ ] **Add tooltips/help text** for complex terms
- [ ] **Test with non-technical users**

### **Phase 4: Advanced Configuration**

#### **11. Twitter/X API Evaluation**
- [ ] **Research Twitter API v2 pricing**
- [ ] **Calculate ROI** for paid access
- [ ] **Evaluate alternatives** (GitHub-first strategy)
- [ ] **Decision:** Keep on back burner or invest

#### **12. Mobile Access Optimization**
- [ ] **Test Nerve UI** on iPhone (100.104.22.17)
- [ ] **Fix any mobile display issues**
- [ ] **Optimize touch targets** for mobile
- [ ] **Test CORS access** from mobile

#### **13. Automated Health Monitoring**
- [ ] **Set up heartbeat monitoring** for all departments
- [ ] **Create alert system** for failures
- [ ] **Implement auto-recovery** for common issues
- [ ] **Dashboard visualization** of system health

### **🎯 Priority Order**

1. **GitHub Organization** (15 minutes)
2. **Repository Transfer** (5 minutes)
3. **GitHub Pages** (5 minutes)
4. **YouTube Fix** (30 minutes)
5. **Instagram Setup** (1-2 days for review)
6. **Reddit OAuth** (30 minutes)
7. **Slack/Discord** (30 minutes each)
8. **Nerve UI Enhancements** (ongoing)

### **⏰ Time Estimates**

**Today (Sunday):**
- GitHub setup: 25 minutes
- YouTube investigation: 30 minutes

**Monday:**
- Instagram app creation: 30 minutes
- Reddit app creation: 30 minutes
- Slack/Discord: 1 hour

**Tuesday-Thursday:**
- Instagram review waiting period
- Nerve UI enhancements: 2-3 hours

### **🔧 Verification Steps**

After each task:
- **GitHub Organization:** Verify https://github.com/arcturion-technologies exists
- **Repository Transfer:** Verify https://github.com/arcturion-technologies/arcturion-technologies
- **GitHub Pages:** Verify https://arcturion-technologies.github.io loads
- **YouTube:** Test upload with 30-second test video
- **Instagram:** Verify post creation via API
- **Reddit:** Verify post to test subreddit
- **Slack/Discord:** Verify message sending to test channel

### **📊 Success Metrics**

- **GitHub Organization:** Created ✅
- **Repository Transfer:** Completed ✅
- **GitHub Pages:** Live ✅
- **YouTube Upload:** Working ✅
- **Instagram Post:** Working ✅
- **Reddit Post:** Working ✅
- **Slack/Discord:** Connected ✅
- **Nerve UI Enhanced:** Improved UX ✅

### **⚠️ Common Pitfalls**

1. **GitHub Pages** may take up to 10 minutes to deploy
2. **Instagram review** can take several days
3. **YouTube OAuth** may require additional scopes
4. **Reddit app** needs proper redirect URI configuration
5. **Slack/Discord** bots need proper permissions

### **🆘 Support Resources**

- **Composio Documentation:** https://docs.composio.dev
- **GitHub Pages Guide:** https://docs.github.com/en/pages
- **YouTube API Docs:** https://developers.google.com/youtube/v3
- **Instagram API Docs:** https://developers.facebook.com/docs/instagram-api
- **Reddit API Docs:** https://www.reddit.com/dev/api
- **Slack API Docs:** https://api.slack.com
- **Discord API Docs:** https://discord.com/developers/docs

---

**🏔️ Aquarius Engineering Department**
*Task checklist created: March 29, 2026 @ 5:22 PM EDT*
*Next update: Morning briefing March 30, 2026 @ 8:00 AM EDT*

**📊 Progress Tracking:**
- [ ] Phase 1: GitHub Setup (0/3)
- [ ] Phase 2: Platform Connections (0/4)
- [ ] Phase 3: Nerve UI Enhancements (0/3)
- [ ] Phase 4: Advanced Configuration (0/3)

**🔗 Related Resources:**
- **Repository:** https://github.com/scorpio-assistant/arcturion-technologies
- **Nerve UI:** http://127.0.0.1:3080/
- **Composio Dashboard:** https://app.composio.dev
- **This Checklist:** https://github.com/scorpio-assistant/arcturion-technologies/blob/main/aquarius/todo-manual-tasks.md

**💡 Pro Tips:**
1. Complete tasks in order for dependencies
2. Take screenshots of each step for documentation
3. Test after each configuration change
4. Update this checklist with progress
5. Ask for help if stuck for >15 minutes