# fleet-manager-releases

## Fleet Manager – Demo v0.1.0-alpha

This release contains a **pre-built, ready-to-deploy version** of Fleet Manager, packaged as a **tar file** for direct server deployment.  
It is part of our **OpenScaler app deployment video series** and showcases the full app with a polished UI.

---

### Highlights
- **Deployment-ready:** start directly with PM2 or your preferred Node.js process manager  
- **Dispatcher & C-Suite dashboards:** explore core functionality  
- **Beautiful login page:** first impression matters  
- **Images included:** screenshots of the app UI

---

### Quick Start
```bash
tar -xvf fleet-manager-demo-v0.1.0-alpha.tar
cd fleet-manager
pm2 start npm --name fleet-manager -- run start
