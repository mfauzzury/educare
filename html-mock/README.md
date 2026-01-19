# EduCentre HTML Mock

This is a standalone HTML version of the EduCentre application that can run directly in a web browser without any build process or runtime dependencies.

## Features

- **No Installation Required**: Simply open the HTML files in a web browser
- **All Pages Converted**: Login, Admin Dashboard, Parent Portal, Students, Institutes, Attendance, and Fees
- **Working Navigation**: All internal links between pages work correctly
- **Responsive Design**: Uses Tailwind CSS CDN for styling
- **Icons**: Font Awesome icons for UI elements

## How to Use

### Method 1: Direct File Opening
1. Navigate to the `html-mock` folder
2. Double-click `index.html` or `login.html` to open in your default browser
3. Navigate through the application using the links

### Method 2: Local Web Server (Recommended)
For the best experience, serve the files using a local web server:

```bash
# Using Python 3
cd html-mock
python3 -m http.server 8000

# Using Node.js (if you have npx)
cd html-mock
npx http-server -p 8000

# Then open: http://localhost:8000
```

### Method 3: Share via File Hosting
Upload the entire `html-mock` folder to any file hosting service or GitHub Pages to share with others.

## Pages Available

1. **login.html** - Login page with parent/admin selection
2. **admin.html** - Admin dashboard with statistics and charts
3. **parent.html** - Parent portal with tabs for invoices, payments, attendance, and notifications
4. **students.html** - Student list management
5. **institutes.html** - Institute/school management
6. **attendance.html** - Attendance tracking
7. **fees.html** - Fee monitoring and collection

## Default Login Behavior

- **Parent Login**: Redirects to `parent.html`
- **Admin Login**: Redirects to `admin.html`

No actual authentication is performed - this is a mockup for demonstration purposes.

## File Structure

```
html-mock/
├── index.html              # Auto-redirects to login
├── login.html              # Login page
├── admin.html              # Admin dashboard
├── parent.html             # Parent portal
├── students.html           # Student list
├── institutes.html         # Institutes list
├── attendance.html         # Attendance management
├── fees.html              # Fee monitoring
├── assets/
│   └── images/
│       └── logodsc.png    # Logo image
└── README.md              # This file
```

## Technologies Used

- **HTML5**: Page structure
- **Tailwind CSS**: Styling via CDN (https://cdn.tailwindcss.com)
- **Font Awesome**: Icons via CDN
- **Vanilla JavaScript**: Tab switching and modal interactions

## Browser Compatibility

Works on all modern browsers:
- Chrome/Edge (latest)
- Firefox (latest)
- Safari (latest)

## Notes

- This is a static mockup - no data persistence
- All student data, invoices, and statistics are hardcoded examples
- No backend or database required
- Perfect for presentations, demos, and sharing designs

## Sharing with Others

You can share this mockup by:

1. **ZIP File**: Compress the `html-mock` folder and send via email
2. **GitHub**: Upload to a GitHub repository and enable GitHub Pages
3. **Netlify/Vercel**: Drag and drop the folder for instant deployment
4. **Google Drive/Dropbox**: Share the folder link (recipients can download and open locally)

## Future Enhancements

To convert this to a working application, you would need to:
- Set up a backend server (Node.js, PHP, Python, etc.)
- Add a database (MySQL, PostgreSQL, MongoDB)
- Implement real authentication
- Add API endpoints for data operations
- Connect forms to backend handlers

---

**Version**: 1.0
**Created**: January 2024
**Purpose**: Demonstration and sharing of EduCentre design
