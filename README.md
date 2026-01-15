# Aura AI Email Confirmation Page

This is the email confirmation landing page for Aura AI - Multi-Agent Intelligence Platform.

## 🚀 Live URL
[https://yourusername.github.io/aura-ai-confirm/](https://yourusername.github.io/aura-ai-confirm/)

## 📋 Usage
This page is automatically shown to users after they click the email confirmation link sent by Aura AI.

## 🔗 URL Parameters
The page accepts these URL parameters:
- `email` - User's email address (required)
- `name` - User's name (optional)
- `type` - Should be "signup" for email confirmation

Example:https://yourusername.github.io/aura-ai-confirm/?email=user@example.com&name=John&type=signup


## 🛠️ Integration
This URL is used in the Supabase `emailRedirectTo` parameter:

```javascript
emailRedirectTo: 'https://yourusername.github.io/aura-ai-confirm/?email=${encodeURIComponent(email)}&name=${encodeURIComponent(name)}&type=signup'
