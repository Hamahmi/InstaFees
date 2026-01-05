# 💸 InstaFee – Instapay Fee Calculator

Simple web app to calculate how much you need to send via **Instapay Egypt**
so that the **exact desired amount** reaches the receiver.

## ✨ Features
- Arabic / English 🌐
- Dark Mode 🌙
- Exact fee calculation
- Smart splitting based on Instapay limits
- Daily & monthly limit warnings
- No backend – works offline

## 💰 Fee Rules
| Amount Sent | Fee |
|------------|-----|
| ≤ 500 EGP | 0.5 EGP |
| 500 – 20,000 | 0.1% |
| > 20,000 | 20 EGP |

## 🚧 Limits
- Single transfer: **70,000 EGP**
- Daily limit: **120,000 EGP**
- Monthly limit: **400,000 EGP**

The app automatically:
- Calculates required sent amount
- Splits transfers if needed
- Warns when multiple accounts are required

## 🚀 Usage
1. Enter the amount you want to **be deducted**
2. Instantly see:
   - Amount to send
   - Fees
   - Number of transfers
   - Warnings if any

## 🛠 Tech
- HTML
- CSS
- Vanilla JavaScript

## 📄 License
MIT
