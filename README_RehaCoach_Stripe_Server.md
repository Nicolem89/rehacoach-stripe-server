
# RehaCoach Stripe Server

🔐 Automatischer Zahlungs- & Abo-Server für RehaCoach mit Stripe + Supabase.

## Funktionen

- Erstellt Stripe Checkout Sessions (inkl. user_id)
- Empfängt Stripe Webhooks bei Zahlung
- Aktualisiert automatisch `plan = pro` in Supabase
- Unterstützt mehrere Abo-Modelle (Basic, Premium, Pro)

## Anleitung

1. `.env.example` ausfüllen → `.env` nennen
2. `npm install`
3. `npm start`
4. Stripe Webhook einrichten unter `/webhook`

📎 Mehr Hilfe? Frag ChatGPT 😉
