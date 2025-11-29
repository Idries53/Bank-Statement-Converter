# 🏦 Universal Bank Statement Converter

**Free web app to convert any bank statement PDF to Excel with automatic currency detection**

[![Streamlit App](https://static.streamlit.io/badges/streamlit_badge_black_white.svg)](https://share.streamlit.io)

## 🌟 Features

- ✅ **50+ Currency Support** - Automatic detection of USD, EUR, GBP, INR, AED, JPY, CNY, and 40+ more
- ✅ **Universal Bank Compatibility** - Works with any bank statement format
- ✅ **Smart Transaction Parsing** - Automatically identifies incoming/outgoing transactions
- ✅ **Professional Excel Export** - Clean, formatted spreadsheets with summary statistics
- ✅ **Visual Analytics** - Charts and graphs for transaction analysis
- ✅ **Mobile Friendly** - Works on desktop, tablet, and mobile
- ✅ **100% Free** - No registration, no limits, completely free to use

## 🚀 Quick Start

### For End Users:
1. Visit the deployed app (URL provided after deployment)
2. Upload your bank statement PDF
3. Click "Convert to Excel"
4. Download your formatted Excel file

### For Developers:
```bash
# Clone this repository
git clone https://github.com/your-username/universal-bank-converter.git

# Install dependencies
pip install -r requirements.txt

# Run locally
streamlit run app.py

# Open http://localhost:8501
```

## 📊 Supported Currencies

| Currency | Symbol | Examples |
|----------|--------|----------|
| USD | $ | US Dollar, American banks |
| EUR | € | Euro, European banks |
| GBP | £ | British Pound, UK banks |
| INR | ₹ | Indian Rupee, HDFC, ICICI, SBI |
| AED | د.إ | UAE Dirham, Emirates NBD, FAB |
| JPY | ¥ | Japanese Yen |
| CNY | ¥ | Chinese Yuan |
| CAD | C$ | Canadian Dollar |
| AUD | A$ | Australian Dollar |
| CHF | Fr | Swiss Franc |
| +40 more | | |

## 🔧 Technology Stack

- **Frontend**: Streamlit
- **Data Processing**: Pandas, NumPy
- **PDF Processing**: PyPDF2, pdfplumber
- **Visualization**: Plotly
- **Export**: OpenPyXL

## 🎯 Use Cases

- **Personal Finance**: Convert bank statements for budgeting
- **Business Accounting**: Process customer transactions
- **Expense Tracking**: Analyze spending patterns
- **Tax Preparation**: Organize financial records
- **Financial Analysis**: Create reports and charts

## 🌍 Supported Bank Types

- Personal bank statements
- Business/corporate accounts
- Credit card statements
- Investment account statements
- Multi-currency accounts

## 🔒 Privacy & Security

- **No Data Storage**: Files processed and immediately discarded
- **Local Processing**: All work done in browser/server
- **No Registration**: Zero personal data collection
- **Encrypted**: HTTPS by default

## 📈 Sample Output

The converter creates Excel files with:
- **Transactions Sheet**: All extracted transactions
- **Summary Sheet**: Statistics and totals
- **Charts**: Visual analytics
- **Multiple Currencies**: Automatic detection and separation

## 🚀 Deployment

This app can be deployed for free on:
- **Streamlit Cloud** (recommended)
- **Heroku**
- **AWS**
- **Google Cloud**
- **Azure**

See [DEPLOYMENT_GUIDE.md](DEPLOYMENT_GUIDE.md) for detailed instructions.

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Test thoroughly
5. Submit a pull request

## 📄 License

MIT License - Feel free to use for personal and commercial purposes.

## 🎉 Credits

Built with ❤️ by MiniMax Agent
- Universal currency detection
- Smart transaction parsing
- Professional Excel export
- Visual analytics

---

**Convert any bank statement to Excel in seconds! No registration required. 100% Free!**