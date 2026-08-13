JAGESH ELECTRONIC Customer Reminder — V12 OTP Recovery

Replace these files in the existing jagesh-customer-reminder repository:
index.html, sw.js, manifest.json, logo.jpg, icon-192.png, icon-512.png, icon-512-maskable.png

V12 fixes:
- Mobile-friendly PIN/OTP screen; no vertical overflow problem.
- After OTP is successfully sent, the 6-digit OTP input appears immediately.
- OTP verification uses Supabase Auth REST API.
- create_user:false prevents the recovery flow from creating a new account.
- Clear error messages are shown when Supabase SMS is not configured.
- 60-second resend timer.

IMPORTANT: Real SMS OTP requires Email Authentication enabled in Supabase and an SMS provider configured. Supabase currently supports providers including Twilio, Vonage and MessageBird. Do NOT put a service_role/secret key in this website.
