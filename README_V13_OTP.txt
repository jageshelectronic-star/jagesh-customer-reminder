JAGESH ELECTRONIC Customer Reminder — V13 OTP FIX

This version changes the PIN recovery screen to a compact mobile-only OTP view so the numeric keypad does not push the OTP form off-screen.

OTP flow:
1. PIN भूल गए? दबाएँ.
2. केवल OTP recovery screen दिखेगी.
3. OTP भेजें दबाएँ.
4. सफल API response के बाद 6-digit OTP box दिखाई देगा.
5. OTP verify करके नया PIN सेट करें.

IMPORTANT: Supabase hosted Phone OTP requires Phone Auth enabled and an SMS provider configured. The website cannot deliver SMS by itself. If OTP is not received, configure the project's SMS provider (e.g. Twilio/Vonage/MessageBird/TextLocal) in Supabase.
