# 🎓 ESIL University Foundation Year Program Website

A comprehensive trilingual education platform featuring both public-facing content and administrative capabilities. Built for GitHub Pages hosting with static HTML, CSS, and JavaScript.

## 🌟 Features

### Public Website
- **Trilingual Education Focus**: English, Russian, and Kazakh language integration
- **Interactive Landing Page**: Modern, responsive design with animations
- **Application System**: Students can submit applications directly through the website
- **Scholarship Applications**: Integrated scholarship request system
- **Consultation Booking**: Schedule meetings with admissions team
- **Program Information**: Detailed curriculum, faculty, and program features

### Admin Panel
- **Secure Login**: Username: `admin`, Password: `1234`
- **Dashboard Analytics**: Real-time statistics and metrics
- **Application Management**: Review and update student applications
- **Student Progress Tracking**: Monitor enrolled students' progress
- **Scholarship Administration**: Manage scholarship applications and approvals
- **Consultation Management**: Handle consultation requests and scheduling
- **Content Management**: Upload and manage educational content
- **Data Export/Import**: Full data management capabilities

## 🚀 Quick Start

### GitHub Pages Deployment

1. **Fork or Clone Repository**
   ```bash
   git clone https://github.com/yourusername/esil-foundation-program.git
   cd esil-foundation-program
   ```

2. **File Structure**
   ```
   esil-foundation-program/
   ├── index.html          # Main landing page
   ├── admin.html          # Admin panel
   ├── README.md           # This file
   └── .github/
       └── workflows/
           └── pages.yml   # GitHub Pages deployment
   ```

3. **Enable GitHub Pages**
   - Go to repository Settings
   - Navigate to "Pages" section
   - Select "Deploy from a branch"
   - Choose "main" branch and "/ (root)"
   - Save settings

4. **Access Your Site**
   - Public site: `https://yourusername.github.io/esil-foundation-program/`
   - Admin panel: `https://yourusername.github.io/esil-foundation-program/admin.html`

## 🔐 Admin Access

### Method 1: Direct URL
Navigate to: `https://yourusername.github.io/esil-foundation-program/admin.html`

### Method 2: Secret Key (from main page)
Type `admin123` anywhere on the main page to open admin panel

### Login Credentials
- **Username**: `admin`
- **Password**: `1234`

## 💾 Data Storage

This system uses **localStorage** for data persistence since GitHub Pages only supports static hosting:

- **Applications**: Stored in `localStorage.applications`
- **Scholarships**: Stored in `localStorage.scholarshipApplications`
- **Consultations**: Stored in `localStorage.consultations`
- **Settings**: Stored in `localStorage.programSettings`

⚠️ **Important**: Data is stored locally in the browser. For production use, consider integrating with a backend service or database.

## 🎨 Customization

### Branding
Update colors, logos, and content in:
- `index.html`: Main website content and styling
- `admin.html`: Admin panel appearance and functionality

### Content
- **Program Information**: Edit sections in `index.html`
- **Faculty Details**: Update instructor information
- **Statistics**: Modify dashboard metrics
- **Course Details**: Change curriculum information

### Functionality
- **Add new application fields**: Modify the application form functions
- **Custom admin features**: Extend the admin panel capabilities
- **Additional data types**: Add new localStorage categories

## 📊 Admin Panel Features

### Dashboard
- Total applications count
- Pending reviews
- Accepted students
- Scholarship requests

### Applications Management
- View all student applications
- Filter by status (pending, accepted, rejected)
- Update application status
- View detailed application information

### Student Tracking
- Monitor student progress (1-30 weeks)
- Track language proficiency
- View current course week

### Scholarship Administration
- Review scholarship applications
- Approve/deny requests
- Track scholarship types
- Monitor distribution

### Content Management
- Upload curriculum materials
- Manage assessments
- Handle multilingual content
- File organization system

### Analytics
- Program completion rates
- Language learning progress
- Geographic distribution
- Performance metrics

## 🌐 Trilingual Support

The platform is designed for three languages:
- **🇬🇧 English**: International communication
- **🇷🇺 Russian**: Regional academic language
- **🇰🇿 Kazakh**: National language and culture

### Language Features
- Vocabulary convergence analysis
- Cultural framework integration
- AI-powered language learning
- Cross-cultural communication training

## 🤖 AI Integration

Built with Kazakhstan's ISSAI technology integration:
- **KAZ-LLM**: 8-70 billion parameter models
- **Soyle Platform**: Multilingual speech recognition
- **NLP Toolkit**: Morphological analysis
- **Personalized Learning**: Adaptive educational paths

## 📱 Responsive Design

- **Desktop**: Full featured admin panel and website
- **Tablet**: Optimized touch interface
- **Mobile**: Streamlined mobile experience
- **Cross-browser**: Compatible with modern browsers

## 🔧 Development

### Local Development
1. Clone repository
2. Open `index.html` in browser for main site
3. Open `admin.html` in browser for admin panel
4. No build process required - pure HTML/CSS/JS

### Making Changes
1. Edit HTML/CSS/JS files directly
2. Test locally in browser
3. Commit and push to GitHub
4. Changes automatically deploy via GitHub Pages

## 📋 Data Structure

### Application Object
```javascript
{
  id: number,
  name: string,
  email: string,
  language: string,
  motivation: string,
  status: 'pending' | 'accepted' | 'rejected',
  dateApplied: string,
  grades: string
}
```

### Scholarship Object
```javascript
{
  id: number,
  name: string,
  email: string,
  type: string,
  familyIncome: string,
  achievements: string,
  status: 'under_review' | 'approved' | 'denied',
  applicationDate: string
}
```

### Consultation Object
```javascript
{
  id: number,
  name: string,
  email: string,
  preferredDate: string,
  notes: string,
  status: 'scheduled' | 'completed' | 'cancelled',
  requestDate: string
}
```

## 🔒 Security Considerations

### Current Implementation
- Simple password authentication for demo purposes
- Client-side data storage
- No encryption of stored data

### Production Recommendations
- Implement proper user authentication
- Use HTTPS for all communications
- Add server-side data validation
- Implement data backup systems
- Add audit logging
- Use environment variables for sensitive data

## 🚀 Future Enhancements

### Technical Improvements
- Backend database integration
- Real-time notifications
- File upload capabilities
- Email automation
- Payment processing
- Video conferencing integration

### Educational Features
- Online classroom integration
- Assignment submission system
- Grade book functionality
- Student portfolios
- Parent/guardian portals
- Certificate generation

### Analytics Enhancements
- Advanced reporting
- Predictive analytics
- Learning path optimization
- Performance benchmarking
- A/B testing capabilities

## 📞 Support

### Technical Issues
- Check browser console for errors
- Verify localStorage availability
- Ensure JavaScript is enabled
- Clear browser cache if needed

### Content Updates
- Modify HTML files directly
- Update text content and images
- Adjust styling in CSS sections
- Test changes before deployment

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Test thoroughly
5. Submit a pull request

## 📧 Contact

For questions about the ESIL Foundation Year Program:
- **Email**: foundation@esil.edu.kz
- **Phone**: +7 (717) 212-34-56
- **Address**: Astana, Kazakhstan, Kabanbay Batyr Ave, 43A

---

**Built with ❤️ for trilingual education excellence**