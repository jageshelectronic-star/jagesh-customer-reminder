JAGESH ELECTRONIC Customer Reminder — V11 OTP Recovery

Replace ONLY these files in the existing jagesh-customer-reminder repository root:
1. index.html
2. sw.js
3. manifest.json
4. logo.jpg
5. icon-192.png
6. icon-512.png
7. icon-512-maskable.png

V11 adds:
- Existing 6-digit PIN remains the normal login.
- “PIN भूल गए? Mobile OTP से बदलें” recovery option.
- Supabase Phone OTP is used for recovery.
- After successful OTP verification, user can set a new 6-digit PIN.
- Existing customer data/history/recycle-bin/local settings remain in the browser.
- Service-worker cache bumped to v11-otp to force the new code to load.

IMPORTANT:
- Supabase project must have Authentication > Providers > Phone enabled.
- An SMS provider must be configured in Supabase for real OTP delivery.
- The website contains only the Supabase publishable key. Never put a Supabase secret/service-role key in the HTML.
- Recovery phone is prefilled as +917007373771; change it in the UI if the registered number is different.
