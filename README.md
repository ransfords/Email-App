SmartMailBot – Personalized Email Automation with Gmail SMTP

SmartMailBot is a powerful and flexible Python-based email bot that allows users to send personalized, branded, and trackable emails using Gmail's SMTP. It's tailored for bulk sending with dynamic customization per recipient, perfect for educational use, UI/UX testing, or marketing simulations.

 Features

 Gmail SMTP Integration – Uses App Passwords for secure, unlimited delivery

 Fully Customizable Emails – Insert recipient name, email, card number, and more

 Brand Styling Options – Barclays, Barclays View, PayPal, Netflix and more

 Live Delivery Tracker – Monitor successful deliveries and failures in real-time

 Flexible Frontend for Input – Input recipient list, select message type, and brand style

 Auto Footer & Branding – Automatically adds footer with legal, privacy, and disclaimers

 Setup

Clone the repo

git clone https://github.com/your-username/smartmailbot.git
cd smartmailbot

Install Dependencies

pip install -r requirements.txt

Set Environment Variables

export GMAIL_EMAIL="youremail@gmail.com"
export GMAIL_PASSWORD="your_app_password"

Run the Bot

python main.py

 How to Get a Gmail App Password

Go to Google Account Security

Enable 2-Step Verification

Scroll to "App Passwords"

Select app as Mail, device as Other, name it SmartMailBot

Copy and paste the generated 16-character password into your .env or terminal

 Example Messages

Barclays Promo: "Check out the new benefits of your Barclays View™ Mastercard."

Netflix Reminder: "Your July payment is successful. Enjoy new shows this weekend."

PayPal Alert: "Your account activity summary is now available."

 Disclaimer

This tool is strictly for educational purposes only. Do not use for unsolicited emails or impersonation. Always comply with relevant data privacy and anti-spam laws.

 Future Features

Google Sheets integration for dynamic recipient loading

Email open-tracking pixel

Admin dashboard with logs and analytics

 License

MIT License – Free to use for ethical projects.

