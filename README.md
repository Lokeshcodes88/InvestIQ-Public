# 📈 InvestIQ – Personalized Equity Portfolio Tracker

**InvestIQ** is a full-fledged web application designed to help retail investors intelligently manage and analyze their equity investments. The platform offers features such as real-time portfolio tracking, XIRR performance analysis, Risk metrics analysis, benchmark comparisons, and seamless transaction management, all with a clean and responsive interface.

> ⚠️ **Note:** This repository is a **demo** version of the ongoing InvestIQ project.  
> The project is under active development, and new features, improvements, and production-ready integrations are continuously being added. Stay tuned!

> 💡 Built with **React**, **FastAPI**, **PostgreSQL**, **Redis**, and **Tailwind CSS**  
> 🔒 Secure login with JWT-based authentication  
> ⏱️ Real-time auto-refresh and scheduled caching for performance  
> ☁️ Future-ready: Easily deployable to cloud platforms like AWS, GCP, or Azure  

---

## 🚀 Features

### ✅ Dashboard (Home)
- One-click summary of your entire portfolio
- Real-time market value and 1-day price change
- XIRR (Extended Internal Rate of Return) to evaluate investment performance
- Benchmark comparison with **Nifty 50** and top mutual funds

### 📥 Transactions
- Upload stock order history via Excel sheet
- Manually add, edit, or delete transactions
- View detailed transaction history with filters
- Smart duplicate detection and validation

### 🔐 Authentication
- User-friendly login/signup interface
- JWT-based secure authentication
- Each user has an isolated portfolio workspace

### 🔄 Auto Refresh and Caching
- Auto-refreshes every 15 seconds for live portfolio data
- Redis caching to prevent heavy recalculations during trading hours
- Smart cache expiration set at 3:30 PM IST (end of trading day)

### 📊 Analytics
- Sector-wise and stock-wise allocation charts
- Profit/Loss visualization over time
- Tax optimization suggestions

---
