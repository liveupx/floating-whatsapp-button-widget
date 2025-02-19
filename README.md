# Floating WhatsApp Button Widget

Easily add a floating WhatsApp chat button to your website with a simple script. Just paste the code into your website's footer and customize it as needed.

## 🚀 Features
- Simple integration – just copy and paste the script.
- Fully customizable appearance and text.
- Works seamlessly on any website.
- Supports both desktop and mobile.

## 📌 Installation Guide

### 1️⃣ Include the Script in Your Website
Add the following script before the closing `</body>` tag in your website's footer:

```html
<script>
var url = 'https://github.com/liveupx/floating-whatsapp-button-widget/blob/main/widget.js';
var s = document.createElement('script');
s.type = 'text/javascript';
s.async = true;
s.src = url;
var options = {
    "enabled": true,
    "chatButtonSetting": {
        "backgroundColor": "#4dc247",
        "ctaText": "Hi",
        "borderRadius": "25",
        "marginLeft": "0",
        "marginBottom": "50",
        "marginRight": "50",
        "position": "right"
    },
    "brandSetting": {
        "brandName": "Liveupx",
        "brandSubTitle": "How can I help you?",
        "brandImg": "https://work.liveupx.com/media/public/LiveupX.jpg",
        "welcomeText": "Hi there!\nHow can I help you?",
        "messageText": "Hello, I have a question about {{page_link}}",
        "backgroundColor": "#0a5f54",
        "ctaText": "Start Chat",
        "borderRadius": "25",
        "autoShow": false,
        "phoneNumber": "917060371701"
    }
};
s.onload = function() {
    CreateWhatsappChatWidget(options);
};
var x = document.getElementsByTagName('script')[0];
x.parentNode.insertBefore(s, x);
</script>
```

### 2️⃣ Customize the Widget
You can modify the `options` object to change the button’s appearance, text, and behavior.

| Parameter | Description | Default Value |
|-----------|-------------|--------------|
| `backgroundColor` | Button background color | `#4dc247` |
| `ctaText` | Button text | `Hi` |
| `borderRadius` | Button border radius | `25` |
| `position` | Button position (`left` or `right`) | `right` |
| `phoneNumber` | Your WhatsApp number (with country code) | `917060371701` |
| `welcomeText` | Greeting message in chat window | `Hi there!\nHow can I help you?` |
| `messageText` | Default message text | `Hello, I have a question about {{page_link}}` |
| `brandName` | Displayed brand name | `Liveupx` |
| `brandImg` | Logo URL | *Liveupx Logo* |

### 3️⃣ Save and Refresh
Once you've added the script to your website, refresh the page to see the WhatsApp button in action!

## 📂 Repository
Find the latest updates and source code on GitHub:
🔗 **[Floating WhatsApp Button Widget](https://github.com/liveupx/floating-whatsapp-button-widget)**

## 🛠️ Contributing
Want to improve this project? Feel free to fork the repo, make changes, and submit a pull request!

## 📞 Support
For any issues or customizations, contact us at [Liveupx](https://liveupx.com).

---
📢 **Developed by [Liveupx](https://liveupx.com)**
