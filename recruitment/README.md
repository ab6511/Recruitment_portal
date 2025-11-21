# CareerHub - Recruitment Portal

A modern, fully-functional recruitment website connecting job seekers with employers efficiently.

## Project Overview

CareerHub is a comprehensive recruitment platform designed to simplify the job search and hiring process. The portal features a clean, intuitive interface with modern UI/UX design principles.

## Features Included

### 1. **Landing Page** (`index.html`)
- Hero section with compelling call-to-action
- Features overview highlighting platform benefits
- Statistics section showcasing platform growth
- Professional footer with links
- Responsive design for all devices

### 2. **Job Listings Page** (`jobs.html`)
- Advanced filtering system:
  - Filter by Location (New York, Los Angeles, Chicago, Remote)
  - Filter by Job Type (Full-time, Part-time, Contract, Freelance)
  - Filter by Experience Level (Entry, Mid, Senior, Executive)
  - Filter by Salary Range (interactive slider)
- 6 sample job cards with:
  - Job title, company, description
  - Location, job type, experience level, salary range
  - Required skills tags
  - Featured badge for premium listings
  - One-click apply button

### 3. **Candidate Authentication** 
- **Login Page** (`login.html`)
  - Email/Password authentication
  - Sign-up link for new users
  
- **Candidate Profile** (`profile.html`)
  - Profile information management
  - Resume upload with drag-and-drop
  - Application tracking dashboard
  - Saved jobs section
  - Application status indicators (New, Viewed, Interview, Rejected)

### 4. **Resume Management & Application Tracking**
- Resume upload section with file preview
- Application tracking with status updates:
  - New applications
  - Viewed by employer
  - Interview scheduled
  - Rejected
- Interview date display
- Application history with details

### 5. **Employer/Admin Panel**
- **Admin Login** (`admin-login.html`)
  - Secure employer authentication
  
- **Admin Dashboard** (`admin-dashboard.html`)
  - Overview statistics:
    - Active job postings
    - Total applications received
    - Scheduled interviews
    - Successful hires
  - Recent applications table
  - Quick action cards
  - Recent applications management

- **Job Management** (`admin-jobs.html`)
  - Post new job listings with modal form
  - Edit existing job postings
  - Close/archive job listings
  - View application count per job
  - Job status management

## File Structure

```
recruitment/
├── index.html              # Landing page
├── jobs.html               # Job listings page with filters
├── login.html              # Candidate login page
├── profile.html            # Candidate profile & dashboard
├── admin-login.html        # Employer login
├── admin-dashboard.html    # Admin main dashboard
├── admin-jobs.html         # Job posting management
└── style.css               # Unified stylesheet for all pages
```

## Key Features & Technologies

### Design Elements
- **Gradient Theme**: Purple to violet gradient for modern look
- **Responsive Layout**: Works seamlessly on desktop, tablet, and mobile
- **Interactive Elements**: Hover effects, animations, transitions
- **Clean UI**: Minimalist design with proper spacing and typography

### Technical Implementation
- **HTML5**: Semantic markup
- **CSS3**: Flexbox, Grid, Gradients, Animations
- **Vanilla JavaScript**: No framework dependencies
- **Interactive Features**:
  - Real-time salary slider updates
  - Tab navigation in profile section
  - Modal forms for job posting
  - Dynamic status badges

### Responsive Breakpoints
- Desktop: Full layout
- Tablet (768px): Adjusted grid layouts
- Mobile (480px): Single column layouts, optimized spacing

## How to Use

### For Job Seekers
1. Browse available jobs on the **Browse Jobs** page
2. Use filters to narrow down by location, type, experience, and salary
3. Click **Apply Now** on any job listing
4. Create an account or login with existing credentials
5. Upload resume in **My Profile**
6. Track all applications in the **Applications** section
7. Save favorite jobs for later

### For Employers
1. Login to the **Employer** portal
2. Navigate to **Manage Jobs** dashboard
3. Click **+ Post New Job** to create a listing
4. Fill in job details, description, skills required, and salary
5. View all applications in real-time
6. Schedule interviews and track candidates
7. Manage multiple job postings

## Color Scheme
- **Primary Gradient**: #667eea to #764ba2 (Purple to Violet)
- **Accent**: #ffd700 (Gold)
- **Text**: #333 (Dark Gray)
- **Background**: #f9f9f9 (Light Gray)
- **Borders**: #e0e0e0 (Light Border)

## Browser Compatibility
- Chrome (Latest)
- Firefox (Latest)
- Safari (Latest)
- Edge (Latest)

## Customization Tips

### Change Color Scheme
Edit the CSS variables in `style.css`:
```css
/* Change gradient colors */
background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
```

### Add More Job Listings
Duplicate a `.job-card` div in `jobs.html` and update:
- Job title, company name, description
- Location, job type, experience, salary
- Required skills tags

### Customize Filter Options
Edit the filter groups in `jobs.html`:
```html
<div class="filter-group">
    <label><strong>Location</strong></label>
    <input type="checkbox" value="your-city"> Your City
</div>
```

## Future Enhancements
- Backend integration with database
- User authentication system
- Email notifications
- Advanced analytics and reporting
- Video interview integration
- Skill assessment tools
- AI-powered job recommendations
- Payment gateway for featured listings

## Setup Instructions

1. Extract all files to a folder
2. Open `index.html` in your web browser
3. Navigate through different pages using the navigation menu
4. Explore different features and sections

No server or dependencies required - fully client-side application!

## License
© 2025 CareerHub. All rights reserved.

---

**Created**: November 2025
**Version**: 1.0
