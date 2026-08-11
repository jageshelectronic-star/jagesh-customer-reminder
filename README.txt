JAGESH ELECTRONIC — Secure Customer Reminder
Upload all files to the ROOT of the jagesh-customer-reminder GitHub Pages repository.
Keep GitHub Pages on main / root.
This version uses Supabase Auth + customers table + RLS.
Login with the Owner email created in Supabase.
IMPORTANT: after confirming owner login works, disable public sign-ups in Supabase Authentication settings.
Never use a Supabase secret/service_role key in this website.
Customer records are stored in Supabase and protected by user_id RLS.
GPS requires HTTPS and device location permission.
Backup can be exported/shared to Gmail manually.
