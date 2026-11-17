# Brief

**Question:** The person asked for 'a website for my bakery' and added 'make an order system'. There is no original target: rebuild the established four-page warm artisan placeholder site (Home, Menu, Our Story, Visit) in Vite + React + TypeScript, and add a working order/cart/checkout flow.

**Purpose:** Deliver the requested bakery website with a usable order system as a static build under app/dist.

**Targets:**
- app/ (Vite + React + TypeScript source)
- app/dist (static output)

**Constraints:**
- No original target - the earlier plain-JS build is the only design reference
- Neutral placeholder brand 'Hearth & Crumb' and original line-art icons, no copied logos/photos
- Static build with relative base './' ; no dev servers or watchers started by hand
- Branding/style choices remain open with the person

**Done when:** npm run build succeeds, the four original pages plus a new order page render as static files, the cart persists and checkout confirms an order, and rebuild_check results are reported with any limits.
