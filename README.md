# 🔍 LEI Relationship Lookup Tool

A professional web-based tool for looking up Legal Entity Identifier (LEI) relationship data using the GLEIF API.

## 🚀 Live Demo

**[Access the Tool Here](https://your-username.github.io/lei-relationship-lookup/)**

## ✨ Features

- **🔍 LEI Relationship Lookup**: Extract fund manager, umbrella fund, and parent/child relationships
- **📊 Bulk Processing**: Process multiple LEI codes simultaneously
- **📈 Export Options**: Download results in CSV format
- **🎯 Real-time Progress**: Track processing with visual progress indicators
- **🔒 Secure Access**: Password-protected interface
- **📱 Responsive Design**: Works on desktop, tablet, and mobile devices

## 🎯 Supported Relationship Types

- **Fund Manager**: Entity managing the fund
- **Umbrella Fund**: Parent fund structure
- **Direct Parent**: Immediate parent entity
- **Ultimate Parent**: Top-level parent entity

## 🛠️ How to Use

1. **Access the Tool**: Open the live demo link above
2. **Enter Password**: Use the provided password to access the tool
3. **Input LEI Codes**: Paste LEI codes (one per line) in the textarea
4. **Lookup Relationships**: Click "Lookup Relationships" to process
5. **View Results**: See comprehensive relationship data in the results table
6. **Export Data**: Download results as CSV for further analysis

## 📋 Demo LEI Codes

Try these LEI codes to see real relationship data:

- `549300NH6JD9BB4DEY40` - AQR Long-Short Equity Fund
- `5493000IBP32UQZ0KL24` - AQR Capital Management LLC  
- `549300E9PC51EN656011` - AQR Funds
- `213800OCCHX84PC3BV35` - VT Dromore Investment Fund

## 🔧 Technical Details

- **Frontend**: HTML5, CSS3, JavaScript (ES6+)
- **API**: GLEIF API v1 integration
- **Export**: XLSX.js library for Excel export functionality
- **Styling**: Modern gradient design with responsive layout
- **Browser Support**: Chrome, Firefox, Safari, Edge

## 📊 Data Source

This tool uses the official [GLEIF (Global Legal Entity Identifier Foundation)](https://www.gleif.org/) API to retrieve:

- Entity legal names and addresses
- Registration status and jurisdiction
- Fund management relationships
- Corporate hierarchy information

## 🔒 Security

- Password-protected access
- Session-based authentication
- No data stored on servers
- Client-side processing only

## 🎨 Design Features

- **Modern UI**: Gradient backgrounds and professional styling
- **Progress Tracking**: Real-time processing indicators
- **Error Handling**: Comprehensive validation and error messages
- **Export Options**: Multiple download formats
- **Mobile-First**: Responsive design for all devices

## 📝 Version History

- **v3.0** - Universal LEI relationship extraction
- **v2.5** - Enhanced API integration and export features
- **v2.0** - Added relationship data support
- **v1.0** - Initial release with basic LEI lookup

## 🚀 Quick Start for Developers

1. Clone this repository
2. Open `index.html` in a web browser
3. No build process required - pure HTML/CSS/JS
4. Customize the known relationships database as needed

## 📧 Support

For questions or support, please open an issue in this repository.

## 📄 License

This project is open source and available under the MIT License.

---

**Built with ❤️ for the financial data community**