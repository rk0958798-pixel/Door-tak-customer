# Door Tak Customer App — Supabase Connected

This version is connected to the Door Tak Supabase project.

## Already configured
- Supabase Project URL
- Supabase Publishable Key
- Customer home screen
- Nearby approved shops query
- Products query service

## Supabase database
Run the SQL from:
`supabase/migrations/001_initial_schema.sql`

The database should contain tables such as profiles, addresses, shops, categories, products, carts, cart_items, orders and order_items.

## Run the app
On a computer with Flutter installed:

```bash
flutter pub get
flutter run
```

## Important
The publishable key is a client-side key. Do NOT replace it with a Supabase Secret/Service Role key.

## Current stage
This is the Customer MVP foundation. Login/OTP, real cart checkout, payments, push notifications, maps/live delivery tracking and the seller/delivery/admin apps are still to be added.
