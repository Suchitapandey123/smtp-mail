=============================
Simple PHP Contact Form (SMTP)
=============================

Thank you for downloading this contact form package.

This script allows you to receive contact form messages directly to your email
using PHPMailer + SMTP. No installation or setup is required besides updating
your email and SMTP settings.

-----------------------------------
1. Folder / File Structure
-----------------------------------

contact-form/
│
├── index.html        (Contact form UI)
├── sendmail.php      (Handles email sending)
└── PHPMailer/        (Library folder - DO NOT DELETE)

Do NOT rename or move the PHPMailer folder.

-----------------------------------
2. How to Setup SMTP (IMPORTANT)
-----------------------------------

You must update your email and app password inside sendmail.php.

Open: sendmail.php

Find these lines:

    $mail->Username = 'yourgmail@gmail.com';
    $mail->Password = 'your-app-password';

Replace with your own:

    $mail->Username = 'YOUR_EMAIL@gmail.com';
    $mail->Password = 'YOUR_APP_PASSWORD';

-----------------------------------
3. How to Generate Gmail App Password
-----------------------------------

If you use Gmail, follow these steps:

1. Open: https://myaccount.google.com/
2. Go to "Security"
3. Turn ON "2-Step Verification"
4. After enabling, scroll down to "App Passwords"
5. Create a new App Password
6. Copy the 16-digit password and paste it in sendmail.php

-----------------------------------
4. How to Upload on Your Server
-----------------------------------

1. Upload all files + PHPMailer folder to your hosting server
2. Make sure index.html and sendmail.php are in the SAME directory
3. Open your website and test the form

-----------------------------------
5. Testing the Form
-----------------------------------

Open your contact form in the browser:

   https://yourwebsite.com/contact-form/

Fill the form and submit.

If everything is correct, you should see:

   "Message sent successfully!"

-----------------------------------
6. Trouble? Common Errors
-----------------------------------

1. Wrong email or wrong app password  
   → Fix the values inside sendmail.php

2. PHPMailer folder missing  
   → Ensure the PHPMailer folder is uploaded fully

3. Hosting blocks SMTP  
   → Switch to another SMTP like:
      - Gmail SMTP
      - Outlook SMTP
      - Zoho SMTP
      - Mailgun
      - SendGrid

-----------------------------------
7. Support
-----------------------------------

If you need help with installation, contact the seller.

Thank you!
