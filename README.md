# Symptom Tracker for Veterans Support

Welcome to the official support repository for **Symptom Tracker for Veterans** - a secure, privacy-focused iOS app designed specifically for veterans to track daily health symptoms for VA (Veterans Affairs) medical documentation and disability claims.

## ⚠️ Important Disclaimer

**This application is NOT associated with, affiliated with, or endorsed by the U.S. Department of Veterans Affairs (VA) or any government agency.**

This app is an independent tool intended solely to help veterans:
- Log and track their health symptoms  
- Organize information for medical appointments
- Create personal health records
- Document symptom patterns over time

This app does NOT:
- Replace professional medical advice
- Guarantee VA disability ratings or approvals  
- Provide medical diagnoses or treatment
- Submit information directly to the VA
- Have any official connection to VA systems

*Always consult with qualified healthcare professionals and follow official VA procedures for medical care and disability claims.*

## 🏥 About the App

Symptom Tracker for Veterans is a comprehensive health logging application designed specifically to help veterans:
- Track daily symptoms with severity ratings (0-10 scale)
- **NEW**: Complete VA PTSD assessment questionnaire based on disability rating criteria
- **NEW**: Comprehensive documentation fields for triggers, coping strategies, therapy notes, and medication tracking
- **NEW**: CSV import/export functionality for data backup and migration
- Save drafts throughout the day
- Edit and update previous entries
- Generate professional PDF reports for medical appointments and C&P exams
- View symptom trends with interactive charts
- Secure data with biometric authentication

## 🧠 VA PTSD Assessment Feature

The app now includes a comprehensive PTSD questionnaire aligned with VA disability rating criteria (38 CFR 4.130):

### Core Symptoms Tracked:
- **Psychological**: Anxiety levels, depression severity, panic attack frequency
- **Sleep & Cognitive**: Sleep impairment, memory issues assessment
- **PTSD-Specific**: Hypervigilance, emotional numbing, flashbacks, nightmares, avoidance behaviors
- **Functional Impact**: Occupational and social impairment levels, medication requirements

### Documentation Fields:
- **Symptom Triggers**: Environmental, situational, or emotional trigger identification
- **Coping Strategies**: Document what helps manage symptoms effectively
- **Therapy Notes**: Track therapy sessions, progress, and techniques learned
- **Medication Notes**: Monitor medication effectiveness, side effects, and dosage changes
- **Daily Functioning**: Assess self-care abilities, routine maintenance, and independence levels
- **Work Impact**: Document effects on productivity, attendance, and workplace relationships
- **Relationship Impact**: Track impact on family, friendships, and social interactions

This structured assessment helps veterans provide comprehensive documentation for C&P exams and disability claims by aligning symptom tracking with VA evaluation criteria.

## 📊 CSV Import/Export Feature

### What is CSV Import/Export?
Symptom Tracker for Veterans now includes comprehensive CSV (Comma-Separated Values) import and export functionality, allowing you to:
- **Backup your complete symptom data** in a universal format
- **Transfer data between devices** when switching phones/tablets
- **Import previously exported data** to restore information
- **Analyze your data** in spreadsheet applications if needed

### Export Options
The app provides two export formats to meet different needs:

#### PDF Exports (Recommended for Sharing)
- **Professional formatting** suitable for healthcare providers and VA personnel
- **Secure and tamper-evident** - cannot be easily modified
- **Ideal for**: Medical appointments, C&P exams, disability claim documentation
- **Privacy**: More secure for sharing sensitive health information

#### CSV Exports (For Backup and Migration)  
- **Complete raw data** including all symptom entries and notes
- **Universal format** that can be imported back into the app
- **Ideal for**: Personal backups, data migration, analysis
- **⚠️ Privacy Note**: Contains unencrypted health data in plain text

### How to Export Data
1. Open the app and navigate to the **Export** tab
2. Choose your export format:
   - **Export as CSV**: For backup and data migration
   - **Export as PDF**: For sharing with healthcare providers
3. Select your export options and tap the export button
4. Save or share the exported file as needed

### How to Import CSV Data
1. Navigate to the **Export** tab in the app
2. Tap the **"Import from CSV"** button (green button)
3. Select your CSV file using the file picker
4. The app will:
   - Validate the CSV format and data
   - Create an automatic backup before import
   - Import valid entries and report any errors
   - Show a detailed import summary

### Import Safety Features
- **Automatic Backup**: Creates backup before any import to prevent data loss
- **Data Validation**: Ensures imported data matches expected format and types  
- **Error Reporting**: Detailed feedback about any issues during import
- **Partial Import Support**: Successfully imports valid entries even if some rows have errors
- **Format Verification**: Only accepts CSV files exported from Symptom Tracker for Veterans

### 🔒 CSV Data Safety Guidelines

**Important**: CSV files contain your complete health data in **unencrypted plain text**. Follow these security practices:

#### ✅ Safe Practices
- **Only share CSV files with trusted healthcare providers**
- **Delete CSV files from shared devices after use**  
- **Use secure transfer methods** (encrypted email, secure cloud storage)
- **Store CSV files in password-protected folders**
- **Use PDF exports when sharing** with healthcare providers for better security

#### ❌ Avoid These Risks
- **Never save CSV files to public or unsecured locations**
- **Don't email CSV files through unsecured channels**
- **Don't leave CSV files on shared computers**
- **Don't store CSV files in easily accessible folders**

#### 💡 Best Practice
**Use CSV exports primarily for personal backup purposes**. When sharing data with healthcare providers or VA personnel, use PDF exports for maximum security and professional presentation.

## 🔐 Privacy & Security

- **100% Local Storage** - All data stays on your device
- **No Cloud Services** - No data transmission to external servers
- **Biometric Protection** - PIN and Face ID/Touch ID authentication
- **No Analytics** - Zero tracking or data collection
- **Medical Grade Privacy** - Built specifically for health information

## 📱 Download

*App Store link coming soon*

## 🆘 Support Options

### GitHub Issues
For bug reports, feature requests, or technical questions:
- **[Open an Issue](https://github.com/stovalldav/SymptomTrackerSupport/issues/new)**
- **[View All Issues](https://github.com/stovalldav/SymptomTrackerSupport/issues)**

### Email Support
For direct support and general inquiries:
- **Email**: [symptomtrackerinfo@gmail.com](mailto:symptomtrackerinfo@gmail.com)

### Support Website
- **[Online Support Portal](https://stovalldav.github.io/SymptomTrackerSupport/)**

## 📋 Issue Templates

When reporting issues, please use our templates:
- **[Bug Report](https://github.com/stovalldav/SymptomTrackerSupport/issues/new?template=bug_report.md)** - For app crashes, data issues, or functionality problems
- **[Feature Request](https://github.com/stovalldav/SymptomTrackerSupport/issues/new?template=feature_request.md)** - For new feature suggestions or improvements

## 🔧 Common Issues

### Authentication Problems
- Make sure Face ID/Touch ID is enabled in your device settings
- Try using the PIN option if biometric authentication fails
- Contact support if you can't remember your PIN

### Data Export Issues
- Ensure you have sufficient storage space for PDF generation
- Try exporting smaller date ranges if large exports fail
- Check that you have apps capable of opening PDF files

### Performance Issues
- Restart the app if it becomes slow or unresponsive
- Clear old entries if you have excessive historical data (though this will delete your records)

## 💻 GitHub Pages Setup

This repository also hosts our support website using GitHub Pages. The site files are:
- `index.html` - Main support page
- `support.js` - Interactive functionality
- Assets and resources

To set up GitHub Pages for this repository:
1. Go to repository Settings
2. Navigate to Pages section
3. Set source to "Deploy from a branch"
4. Select "main" branch and "/ (root)" folder
5. Save settings

## 🏗️ Repository Structure

```
├── index.html          # Support website
├── support.js          # Website functionality  
├── README.md           # This file
├── .github/
│   └── ISSUE_TEMPLATE/
│       ├── bug_report.md
│       └── feature_request.md
└── assets/
    └── images/         # Website assets
```

## 🤝 Contributing

While this is primarily a support repository, we welcome:
- Bug reports and feature suggestions
- Documentation improvements
- Support website enhancements
- Translation contributions (future)

## 📞 Contact Information

- **Support Email**: symptomtrackerinfo@gmail.com
- **Support Website**: https://stovalldav.github.io/SymptomTrackerSupport/
- **GitHub Repository**: https://github.com/stovalldav/SymptomTrackerSupport

## 📄 License

This support repository and website are provided as-is for user assistance. The Symptom Tracker app itself is proprietary software.

---

**Note**: This repository is for support and documentation only. The actual app source code is not included here for security and privacy reasons.

## 🎯 Mission Statement

Symptom Tracker for Veterans is an independent application designed specifically for veterans who need reliable, secure, and professional symptom tracking for personal health documentation and medical appointments. Our commitment to privacy and local data storage ensures your health information remains completely under your control while helping veterans organize their health information.

**Important:** This app is not affiliated with the VA and does not guarantee any VA benefits or medical outcomes.

*Built with privacy, security, and healthcare professionals in mind.* 🏥⚕️