# 💰 Finance Tracker - Personal Finance Manager

A beautiful, privacy-focused Progressive Web App for managing your personal finances. Track income and expenses with an elegant, editorial-style interface.

## ✨ Features

- 📊 **Real-time Dashboard** - See your income, expenses, and balance at a glance
- 📝 **Transaction Management** - Add, edit, and delete transactions easily
- 📁 **Category Breakdown** - Visual breakdown of your spending by category
- 🔍 **Filtering** - View all transactions or filter by income/expense
- 💾 **Persistent Storage** - All data saved locally on your device
- 🎨 **Beautiful Design** - Editorial aesthetic with Playfair Display typography
- 📱 **Mobile Optimized** - Works perfectly on phones and tablets
- 🔒 **Privacy First** - All data stays on your device, never sent to servers
- ⚡ **Fast & Responsive** - Smooth animations and instant interactions
- 🌐 **Works Offline** - Access your data even without internet

## 📲 Installation

### For iPhone/iPad Users:

1. Open **Safari** browser (must use Safari on iOS)
2. Navigate to your hosted Finance Tracker URL
3. Tap the **Share button** (□↑) at the bottom
4. Scroll and tap **"Add to Home Screen"**
5. Tap **"Add"** to confirm

📖 [Detailed iOS Installation Guide](INSTALL_IOS.md)

### For Android Users:

1. Open **Chrome** browser
2. Navigate to your hosted Finance Tracker URL
3. Tap the **menu** (⋮) in the top right
4. Select **"Add to Home screen"** or **"Install app"**
5. Tap **"Install"** to confirm

📖 [Detailed Android Installation Guide](INSTALL_ANDROID.md)

## 🚀 Deployment

You can host these files on any static hosting service:

### Option 1: GitHub Pages (Free)
1. Create a new GitHub repository
2. Upload all files (index.html, manifest.json, service-worker.js)
3. Go to Settings → Pages → Enable GitHub Pages
4. Your app will be live at `https://yourusername.github.io/repo-name`

### Option 2: Netlify (Free)
1. Sign up at [netlify.com](https://netlify.com)
2. Drag and drop the files or connect your GitHub repo
3. Your app will be deployed instantly with a URL

### Option 3: Vercel (Free)
1. Sign up at [vercel.com](https://vercel.com)
2. Import your GitHub repo or upload files
3. Deploy with one click

### Option 4: Local Testing
1. Install a local server: `npm install -g http-server`
2. Run: `http-server -p 8080`
3. Open: `http://localhost:8080`

## 📁 File Structure

```
finance-tracker/
├── index.html           # Main app file
├── manifest.json        # PWA configuration
├── service-worker.js    # Offline functionality
├── INSTALL_IOS.md      # iOS installation guide
├── INSTALL_ANDROID.md  # Android installation guide
└── README.md           # This file
```

## 🎯 Usage

### Adding a Transaction
1. Click/tap the **"New Entry"** button
2. Select **Income** or **Expense**
3. Enter the amount, category, description, and date
4. Click **"Add Transaction"**

### Editing a Transaction
1. Hover over (or tap) a transaction
2. Click the **edit icon** (✏️)
3. Make your changes
4. Click **"Update Transaction"**

### Deleting a Transaction
1. Hover over (or tap) a transaction
2. Click the **delete icon** (🗑️)
3. Transaction is immediately removed

### Filtering Transactions
- Click **"All"** to see everything
- Click **"Income"** to see only income
- Click **"Expense"** to see only expenses

## 🔐 Privacy & Security

- ✅ **100% Local Storage** - All data stored on your device using localStorage
- ✅ **No Server Communication** - App never sends data anywhere
- ✅ **No Tracking** - Zero analytics or tracking code
- ✅ **No Login Required** - No accounts, passwords, or personal info needed
- ✅ **Complete Privacy** - Your financial data is yours alone

## 💡 Default Categories

- Food
- Transport
- Entertainment
- Bills
- Salary
- Investment
- Other

You can customize these by modifying the code in `index.html`.

## 🎨 Design Philosophy

The app features an editorial aesthetic inspired by financial publications:
- **Typography**: Playfair Display serif for elegance, Courier New monospace for data
- **Colors**: Stone/neutral palette with emerald for income, rose for expenses
- **Layout**: Generous spacing, soft shadows, subtle animations
- **Mobile-First**: Touch-optimized with responsive design

## 🌐 Browser Compatibility

### Fully Supported:
- ✅ Safari (iOS 11.3+)
- ✅ Chrome (Android 5.0+)
- ✅ Chrome (Desktop)
- ✅ Edge (Desktop)
- ✅ Firefox (Desktop)

### Limited Support:
- ⚠️ Chrome/Firefox on iOS (use Safari for installation)
- ⚠️ Internet Explorer (not supported)

## 📱 Device Compatibility

- ✅ iPhone (all models with iOS 11.3+)
- ✅ iPad (all models with iPadOS 11.3+)
- ✅ Android phones (5.0+)
- ✅ Android tablets (5.0+)
- ✅ Desktop computers (all modern browsers)

## 🛠️ Technical Stack

- **Framework**: React 18 (via CDN)
- **Styling**: Tailwind CSS (via CDN)
- **Icons**: Lucide React
- **Storage**: localStorage API
- **PWA**: Service Worker + Web App Manifest
- **Fonts**: Google Fonts (Playfair Display)

## 🔄 Updates

To update the app:
1. Replace the files on your hosting service
2. Update the `CACHE_NAME` in `service-worker.js` (e.g., `'finance-tracker-v2'`)
3. Users will get the update on their next visit

## 📊 Data Management

### Exporting Data (Future Enhancement)
Currently, data is stored in localStorage. To access it:
1. Open browser DevTools (F12)
2. Go to Application → Local Storage
3. Find `finance-transactions` key
4. Copy the JSON data

### Backing Up Data
Since data is stored locally:
- Consider taking screenshots of important data
- Copy localStorage data periodically
- Use multiple devices for redundancy

## 🤝 Contributing

This is a standalone PWA. To customize:
1. Edit `index.html` for functionality and design changes
2. Edit `manifest.json` for app metadata and icons
3. Edit `service-worker.js` for caching behavior

## 📄 License

This project is provided as-is for personal use. Feel free to modify and customize for your needs.

## 🆘 Support

### Common Issues:

**App not installing?**
- Use Safari on iOS, Chrome on Android
- Ensure HTTPS connection (required for PWAs)
- Check browser version compatibility

**Data disappeared?**
- Check if browser cache was cleared
- Ensure you're using the same browser
- localStorage persists until manually cleared

**Offline not working?**
- Service workers may take time to activate
- Try closing and reopening the app
- iOS has limited service worker support

---

Made with ❤️ for privacy-conscious individuals who want to track their finances without sharing data with third parties.

**Enjoy your financial privacy!** 💰🔒