# 🌱 Hopeseed – Investment Platform for Students & Retirees

**Domain:** hopeseed.net  
**Tagline:** *Grow your future, seed by seed.*

Hopeseed is a secure, accessible investment platform designed for students and retired individuals in Asia. It offers flexible investment plans (£50–£10,000), goal‑based savings (for kids, future targets), and a built‑in support bot.

## ✨ Features
- 🔐 Secure user authentication with KYC‑ready verification
- 📈 Investment plans with competitive returns (demo data)
- 🎯 Goal‑based savings: “Save for Kids” & “Future Targets”
- 🤖 AI‑powered support bot & community support group
- ♿ Fully accessible (WCAG 2.1 AA)
- 📜 Compliant with GDPR, SSL/TLS, and international data protection norms

## 🚀 Quick Start

### Prerequisites
- Python 3.10+
- PostgreSQL (or SQLite for testing)
- Node.js (for building static assets, optional)

### Installation
1. Clone the repository  
   `git clone https://github.com/hopeseed/hopeseed.git`
2. Create a virtual environment & install dependencies  
   `pip install -r requirements.txt`
3. Copy `.env.example` to `.env` and fill in your secret keys
4. Run migrations  
   `python manage.py migrate`
5. Create a superuser  
   `python manage.py createsuperuser`
6. Run the development server  
   `python manage.py runserver`

### Deployment
- Use **Gunicorn** + **Nginx** with HTTPS.
- Set `DEBUG=False` and configure allowed hosts.
- Integrate a payment gateway (e.g., Stripe) for real deposits.

## 📚 Documentation
- [Accessibility Statement](docs/accessibility.md)
- [Privacy Policy](docs/privacy.md)
- [Terms of Service](docs/terms.md)

## 🛡️ Compliance
Hopeseed adheres to:
- **GDPR** – User data is stored securely, consent obtained.
- **PCI DSS** – Payment pages are iframed via certified gateways.
- **Age verification** – Only users aged 18+ can register.
- **KYC** – Optional verification for withdrawals above £2,000.

## 🤝 Support
- **Bot:** Click the chat bubble in the bottom‑right corner.
- **Community:** [Join our Telegram Support Group](https://t.me/hopeseed_support)
- **Email:** support@hopeseed.net

## 📝 License
MIT
