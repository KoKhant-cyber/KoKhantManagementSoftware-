# Ko Khant (Lin Htet Phyo) Management Software (Laptop Sales & Repair Services)

A standalone web application designed for laptop retail shops and repair centers with dual role-based security.

## 🚀 Key Features
- **Dual Role Access Control (Admin vs Staff)**:
  - **Admin Mode**: Full control to add new laptops, edit stock specifications, modify purchase costs, view profit margins, delete records, and configure settings.
  - **Staff Mode**: Staff can create repair tickets, update repair job status, sell laptops, and print invoices/receipts, but **purchase cost and profit margins are masked (`••••`)**, and stock cannot be added or edited without entering the Admin Password.
- **Laptop Inventory Tracking**: Specs, Serial/Service tags, purchase cost, retail price, and automated margin calculations.
- **Service & Repair Job Tickets**: Complete workbench tracking from diagnosis, waiting for spare parts, ready for pickup, to delivered.
- **Sales & Customer Invoices**: Generates clean, printable invoices and repair job sheets with your shop's custom branding.
- **Offline & Local Storage**: Automatically saves data in the browser's `localStorage`.
- **JSON Data Export/Import**: One-click backups to safeguard data or transfer records across devices.

## 🔑 Default Passwords
- **Admin Password**: `admin`
- **Staff PIN**: `1234`
*(You can change both anytime in the Settings & Security tab).*

## 📁 Repository Structure
```
├── index.html        # Main standalone single-page application
├── logo.png          # Shop branding logo
└── README.md         # Documentation & GitHub Pages setup guide
```

## 🌐 Deploy to GitHub Pages (Free)
1. Push `index.html`, `logo.png`, and `README.md` to your GitHub repository.
2. In your repo on GitHub, go to **Settings** > **Pages**.
3. Under **Build and deployment** > **Branch**, select `main` (or `master`) and folder `/ (root)`.
4. Click **Save**. Your software will be live at `https://<your-username>.github.io/<repo-name>/`.
