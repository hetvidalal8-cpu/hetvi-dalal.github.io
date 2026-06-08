# Navkar Snacks — Design Approach

**Project:** Homepage + ordering experience for a homemade Gujarati farsan, dry-snacks & chocolates business.
**Type:** Responsive single-page storefront with UPI payment and WhatsApp ordering.

---

## 1. The brief & the real constraint

Navkar Snacks is a home kitchen, not a warehouse. Everything is **made fresh to order in small batches**, payment happens over **UPI**, and orders are confirmed on **WhatsApp**. The design had to honour that reality instead of pretending to be a large-scale store: no fake inventory, no card-checkout theatre, no instant delivery promises. The goal was a homepage that feels **warm, trustworthy, and genuinely homemade**, while making it effortless to browse, price, and place an order on a phone.

## 2. Visual direction

I leaned into a **warm, festive, Indian-sweet-shop palette**: cream paper, deep brick red, and saffron, with a leaf-green accent for "fresh/homemade" cues. A high-contrast serif (**Fraunces**) carries the headlines and the brand seal for a handmade, premium-mithai feel, paired with **Mukta** — a typeface designed for Devanagari and Latin — so the Gujarati brand name (નવકાર સ્નેક્સ) and English text live together comfortably.

Texture matters here: a subtle dot grain, soft radial glows, and a circular brand seal (ન) give it the feel of a festive label rather than a generic web template. The whole page is intentionally tactile and a little celebratory.

## 3. Key UX decisions

**Built for the thumb.** The whole flow assumes a phone. The order button is sticky, quantity steppers are large, and a persistent floating WhatsApp button is always one tap away.

**Honest, low-friction ordering.** Rather than a full e-commerce checkout, the flow is browse → add → pay by UPI → confirm on WhatsApp:
- Product cards carry an image, badge, **price-per-unit pill**, description, a quantity **stepper that enforces minimum order sizes** (e.g. 0.5 kg, theplas from 10 pcs), and an Add button.
- The order drawer totals everything and generates a **UPI QR with the amount pre-filled**, so the customer scans and pays with any UPI app (GPay, PhonePe, Paytm, BHIM).
- A one-tap WhatsApp message confirms the order with the kitchen.

**Set expectations early.** Because food is cooked to order, a clear "order in advance" and "minimum order" notice sits in the *How to order* section, and a 4-step explainer (Pick → Pay → Confirm → Freshly prepared) removes any doubt about how it works.

**Findability.** Category chips (Farsan, Dry Snacks, Chocolates, Gifting) and a live search filter let returning customers jump straight to what they want without scrolling the full menu.

**Festive upsell.** A dedicated gifting band promotes custom Diwali/wedding hampers via WhatsApp enquiry — the highest-value, most personal orders.

## 4. Section structure

Announcement bar → sticky header (seal logo, category nav, order button) → hero (Gujarati + English headline, promise, dual CTA, trust stats, image collage) → scrolling marquee of dishes → category chips + search → menu groups of product cards → festive gifting band → How-to-order steps + advance notice → footer (explore links, contact numbers, payment badges) → persistent WhatsApp button → slide-in order drawer with UPI QR.

## 5. Responsive strategy

Mobile-first in intent. On large screens the hero is a two-column split with an image collage; product menus run 3 across. On tablet/mobile the nav collapses, the hero stacks, menus drop to a 2-column (then single) grid, the steps reflow to 2×2, and the order drawer becomes a full-height sheet. Tap targets and the floating WhatsApp button stay constant across breakpoints.

## 6. Outcome

A storefront that matches how a home kitchen actually sells: visually warm and credible, quick to browse on a phone, and frictionless to pay and confirm — without overpromising on a made-to-order operation.

---

*Note: product imagery is embedded in the page; phone numbers and UPI/WhatsApp links are the live business details.*
