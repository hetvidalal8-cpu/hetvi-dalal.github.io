# LUMÉ — Design Approach

**Assignment:** E-commerce Homepage (Beauty Products) · Responsive (Desktop + Mobile)

---

## 1. Concept

I designed **LUMÉ**, a clean-beauty brand selling skincare, makeup, haircare, and body products. The goal was an interface that feels **premium but approachable** — the visual language of high-end beauty retail (Aesop, Glossier, Fenty) without intimidating the first-time buyer.

The chosen direction is **warm editorial luxury**: a soft ivory canvas, deep aubergine/plum for contrast and trust, and a terracotta/clay accent reserved almost exclusively for calls-to-action. This keeps the palette calm while making every "buy" moment unmistakable.

## 2. Design principles applied

**Visual hierarchy.** Each section follows the same rhythm — a small uppercase eyebrow label, a large serif headline, then supporting content. The eye always knows where it is. The serif display font (Fraunces) carries personality and signals "premium"; a clean sans (Manrope) keeps body text and UI legible.

**One accent, one job.** Terracotta is used almost only for primary actions (Shop Now, Add to Cart, Subscribe). Because it appears sparingly, conversion-critical buttons never compete for attention.

**Content over decoration.** Product cards lead with the image, then name, rating, and price, with the add-to-cart button anchored bottom-right where the thumb expects it on mobile. Nothing on the card is decorative-only.

**Trust signals.** Beauty buyers convert on credibility, so the page layers in star ratings, review counts, a value strip (free shipping, cruelty-free, 30-day returns, dermatologist-tested), and visible security/payment badges in the footer.

## 3. Section-by-section decisions

- **Header / Nav** — Sticky, with logo, expanding search, category menu, and account/wishlist/cart icons. The cart shows a live item count. On mobile the menu and search collapse into a hamburger drawer so the bar stays uncluttered.
- **Hero** — Asymmetric split: bold value proposition and dual CTAs on the left, a featured product "stage" with floating bestseller/price badges on the right. Quick stats (50k reviews, 100% cruelty-free) build instant credibility.
- **Categories** — Four tall image tiles (Skincare, Makeup, Haircare, Body) with hover lift and reveal arrow — the fastest path for shoppers who already know what they want.
- **Product listing** — Four best-sellers in a consistent card system: tag (Bestseller / New / sale %), wishlist toggle, image, rating, name, price (with strike-through when discounted), and add-to-cart.
- **Offers / Promotions** — A high-contrast plum banner with a live countdown to create urgency, plus a clear sale CTA.
- **Footer** — Brand blurb, social links, and grouped navigation (Shop, Company, Help) covering the required About / Contact / Help links, plus payment trust badges.

## 4. Responsive strategy

The layout is built mobile-first in spirit and adapts at three breakpoints:

| Breakpoint | Categories | Products | Key changes |
|---|---|---|---|
| Desktop (>1024px) | 4 columns | 4 columns | Full nav + search visible |
| Tablet (≤1024px) | 2 columns | 2 columns | Grids halve |
| Mobile (≤860px) | 2 columns | 2 columns | Hamburger drawer, hero stacks (visual first), full-width CTAs |
| Small phone (≤520px) | 1 column | 1 column | Single-column everything, stacked newsletter |

On mobile the hero **image leads** (beauty is visual-first), CTAs become full-width tap targets, and the offer banner flips so the discount reads before the copy.

## 5. User flow

Land on hero → grasp the brand promise → either tap **Shop Now** or browse **Categories** → scan **Best-sellers** → **Add to Cart** → the offer banner and newsletter re-engage browsers who aren't ready to buy → footer for support and trust.

## 6. Deliverables in this submission

1. **High-fidelity responsive homepage** (`index.html`) — interactive; resize the browser to see desktop → mobile adaptation.
2. **Low-fidelity wireframes** (`wireframes.html`) — desktop + mobile, showing layout, content hierarchy, and the annotated user flow.
3. **This design-approach document.**

---

*Note: All products, prices, and imagery are fictional/placeholder. Product visuals are rendered as lightweight inline SVG illustrations so the design is fully self-contained.*
