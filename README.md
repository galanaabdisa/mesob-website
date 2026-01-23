# MESOB Agaro - One Stop Service Center

A bilingual (English, Amharic, Oromo) web application for Agaro City's One Stop Service Center (MESOB).

## Features

### For Users:
- View all 28 organizations at MESOB
- Browse services in three languages
- Search functionality
- Mobile responsive design

### For Admin:
- Add/edit/delete organizations
- Manage services in three languages
- Update site content (titles, contact info)
- Change background design
- Export/import data
- Simple password protection

## How to Deploy on Netlify

### Step 1: Create GitHub Repository
1. Go to https://github.com and sign in
2. Click **New repository**
3. Name it `mesob-agaro`
4. Click **Create repository**

### Step 2: Upload Files
1. Download the provided `index.html` file
2. In your GitHub repository:
   - Click **Add file** → **Upload files**
   - Drag and drop `index.html`
   - Add a commit message: "Initial commit"
   - Click **Commit changes**

### Step 3: Deploy to Netlify
1. Go to https://netlify.com
2. Sign up with GitHub
3. Click **Add new site** → **Import an existing project**
4. Select your GitHub repository
5. Click **Deploy site**

### Step 4: Set Admin Password (Optional but Recommended)
1. In Netlify dashboard, go to **Site settings**
2. Click **Environment variables**
3. Add a new variable:
   - Key: `MESOB_ADMIN_PASSWORD`
   - Value: `your-secure-password`
4. In the HTML file, change the default password in the JavaScript section

## Access Instructions

### For Regular Users:
- Visit your Netlify URL (e.g., `mesob-agaro.netlify.app`)
- Select language and browse organizations

### For Admin (ICT Department):
1. Visit the site
2. Press **Ctrl + Shift + A** to reveal admin button
3. Click **Admin Access** button
4. Enter password (default: `admin123`)

## Default Organizations
The system comes pre-loaded with 28 government organizations including:
- Water Utility
- Land Office
- Civil Registration
- Trade Office
- Health Department
- Education Office
- And more...

## Technical Details
- Built with HTML, CSS, and JavaScript
- Uses localStorage for data persistence
- No database required
- Mobile responsive
- Works offline
- Easy to customize

## Customization
The ICT admin can:
1. Change organization names and services
2. Update contact information
3. Modify site appearance
4. Add new organizations
5. Export data for backup

## Support
For technical support, contact:
Computer Science Department, Jimma University