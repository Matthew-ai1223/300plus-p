# 300plus - Educational Platform

Version 1.0.2

## Overview
300plus is a comprehensive educational platform designed for secondary school UTME students, offering structured courses in various subjects. The platform provides an interactive learning environment with course materials, practice problems, quizzes, and examinations.

**Live URL(Version 1.0.1):** [https://300plus.great-site.net/](https://300plus.great-site.net/)

![300plus Platform Screenshot](https://i.ibb.co/8nNng9VP/Screenshot-2025-04-08-032246.png)

## Project Structure

### Core Components
- **AI Module** (`/AI`)
  - Admin dashboard integration
  - AI-powered learning assistance

- **Backend System** (`/backend`)
  - Admin management
  - User management
  - CBT (Computer-Based Testing) system
  - Core functionality includes
  - Database operations
  - Session management
  - Security features

- **Blog System** (`/blog`)
  - Content management
  - Post creation and management
  - Category organization
  - Search functionality
  - Sitemap generation
  - Subscription management
  - Error handling (403, 404, 500)

- **Customer Service** (`/customer service`)
  - Support ticket system
  - User assistance interface

- **Free Account System** (`/free account`)
  - User registration
  - Login system
  - Dashboard interface
  - Student data management
  - Premium upgrade options
  - CBT integration

- **JAMB Past Questions** (`/jamb_past_question`)
  - Subject-wise question banks
  - Practice tests
  - Performance tracking
  - Contact management

- **Course Management** (`/new_coures`)
  - Secondary School curriculum
  - WASC/NECO preparation
  - Math mastery classes
  - Post-UTME preparation
  - Science practicals
  - Feedback system

- **Referral System** (`/referral_system`)
  - User registration
  - Referral tracking
  - Earnings management
  - Withdrawal processing
  - Admin controls
  - Payment processing

## Features

### Course Structure
- Organized into 6-month modules
- Progressive learning path
- Comprehensive subject coverage
- Interactive learning resources
- Dark/Light mode support
- Responsive design

### Learning Resources
- Course Materials
  - Structured topic organization
  - Detailed explanations
  - Progress tracking
  - Interactive interface
- Practice Problems
  - Topic-specific exercises
  - Step-by-step solutions
  - Hints and explanations
  - Progress monitoring
- Quizzes
  - Multiple-choice questions
  - Immediate feedback
  - Score tracking
  - Detailed explanations
- Monthly Examinations
  - Comprehensive testing
  - Time-bound assessments
  - Score calculation
  - Progress unlocking
- Video Lectures
  - Topic-specific videos
  - Duration tracking
  - Progress monitoring
  - Playlist organization

### Subjects Available
- Sciences
  - Physics
    - Mechanics Fundamentals
    - Thermodynamics
    - Electromagnetism
    - Waves and Optics
    - Modern Physics
    - Exam Preparation
  - Chemistry
  - Biology
- Languages
  - English
    - Pronouns and Prepositions
    - Idioms and Expressions
    - Synonyms and Antonyms
    - Question Tags and Concord
    - Phrases, Clauses, and Grammatical Structure
    - Stress and Orals

### Additional Features
- Blog System
  - Content management
  - SEO optimization
  - Newsletter subscriptions
  - Search functionality
- Referral Program
  - User tracking
  - Earnings management
  - Withdrawal system
  - Admin controls
- JAMB Preparation
  - Past question banks
  - Practice tests
  - Performance analytics
- Customer Support
  - Ticket system
  - User assistance
  - FAQ management

## Technical Requirements
- PHP 7.4 or higher
- MySQL Database
- Web Server (Apache/Nginx)
- Modern Web Browser
- JavaScript enabled

## Installation
1. Clone the repository
2. Set up your web server to point to the project directory
3. Import the database schema
4. Configure database connection in `config.php`
5. Set appropriate file permissions
6. Ensure all required PHP extensions are enabled

## Directory Structure
```
300plus/
├── AI/
│   └── admin_dashboard.php
├── backend/
│   ├── admin/
│   ├── m_c/
│   ├── CBT_System/
│   ├── includes/
│   ├── user/
│   └── logout.php
├── blog/
│   ├── admin/
│   ├── classes/
│   ├── config/
│   ├── tools/
│   ├── uploads/
│   ├── cache/
│   └── *.php
├── css/
│   ├── style.css
│   └── bootstrap.min.css
├── customer service/
│   └── indext.php
├── free account/
│   ├── cbt/
│   ├── *.php
│   └── create_users_table.sql
├── jamb_past_question/
│   └── *.php
├── new_coures/
│   ├── feedback/
│   ├── WASC_neco/
│   ├── math_mastrey_class/
│   ├── post_utme_prep/
│   ├── Secondary_School/
│   ├── Science_Practicals/
│   ├── config.php
│   └── p_n.php
└── referral_system/
    └── *.php
```

## Features in Detail

### Course Materials
- Structured learning modules
- Topic-wise content organization
- Interactive learning interface
- Progress tracking
- Dark/Light mode support
- Responsive design

### Practice Problems
- Topic-specific exercises
- Step-by-step solutions
- Hints and explanations
- Progress monitoring
- Difficulty levels
- Interactive feedback

### Quizzes
- Multiple-choice questions
- Immediate feedback
- Score tracking
- Topic-wise assessment
- Detailed explanations
- Progress saving

### Monthly Examinations
- Comprehensive testing
- Time-bound assessments
- Score calculation
- Progress unlocking
- Section-wise marking
- Automatic grading

### Video Lectures
- Topic-specific videos
- Duration tracking
- Progress monitoring
- Playlist organization
- Video completion tracking
- Responsive player

## User Interface
- Responsive design
- Dark/Light mode support
- Intuitive navigation
- Progress indicators
- Notification system
- Mobile-friendly layout

## Security Features
- User authentication
- Session management
- Input validation
- Secure database operations
- XSS protection
- CSRF protection
- File upload security
- Access control

## Contributing
1. Fork the repository
2. Create a feature branch
3. Commit your changes
4. Push to the branch
5. Create a Pull Request

## License
This project is licensed under the MIT License - see the LICENSE file for details.

## Support
For support, please contact the development team or create an issue in the repository.

## Version History
- 1.0.2 - Current version
  - Added dark/light mode support
  - Improved responsive design
  - Enhanced progress tracking
  - Added video lecture features
  - Integrated blog system
  - Added referral program
  - Enhanced JAMB preparation
- 1.0.1 - Initial release
  - Basic course structure
  - Core learning features
  - User authentication
  - Progress tracking

## Ongoing Updates
The 300plus platform is continuously being improved and updated. Current development focus includes:

### Active Development Areas
- **AI Integration**
  - Enhancing AI-powered learning assistance
  - Implementing smart content recommendations
  - Developing automated assessment tools

- **Course Content Expansion**
  - Adding new subject modules
  - Updating existing course materials
  - Creating additional practice problems
  - Expanding video lecture library

- **User Experience Improvements**
  - Optimizing mobile responsiveness
  - Enhancing navigation systems
  - Implementing new interactive features
  - Improving performance and load times

- **Assessment System**
  - Developing advanced CBT features
  - Implementing real-time progress tracking
  - Adding detailed performance analytics
  - Creating personalized learning paths

- **Community Features**
  - Building discussion forums
  - Implementing peer-to-peer learning
  - Adding collaborative study tools
  - Creating study group functionality

### Planned Features
- Live tutoring sessions
- Mobile application development
- Advanced analytics dashboard
- Gamification elements
- Social learning integration
- Offline content access
- Multi-language support

### Development Status
- Regular updates and bug fixes
- Continuous content expansion
- Performance optimization
- Security enhancements
- Feature testing and implementation
- User feedback integration

Note: The platform is under active development, and new features are being added regularly. Users are encouraged to provide feedback and report any issues they encounter.
