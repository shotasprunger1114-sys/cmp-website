# CMP Website Rebuild — Full Brief

## Company
**Create More Productions** — Social media marketing + SEO agency based in Dearborn, MI.

## Brand
- **Colors:** Black (#0A0A0A), Red (#E02020), White (#FFFFFF)
- **Font:** Inter (Google Fonts)
- **Vibe:** Dark, premium, confident. Not corporate — real.
- **Logo:** Red "CM" monogram (referenced, not embedded)

## What CMP Actually Sells (TWO core services)
### 1. Social Media Content System — $4,000/month
- 20 strategic reels per month
- Full research, scripting, filming direction, editing, posting
- NOT generic ChatGPT content — real research-driven scripts
- 6-month commitment
- Target: high-ticket local service businesses

### 2. Local SEO & Digital Presence — $1,495/month  
- Full-service SEO (on-page + off-page)
- Google Maps & Local Pack optimization
- 50+ directory listing sync
- Reputation management & review automation
- AI chat receptionist (24/7 lead capture)
- Monthly performance reports
- 90-day performance guarantee
- No contracts

## Target Audience (5 verticals)
1. Med Spas — $500-2K/treatment, $8-15K LTV
2. Mortgage Brokers — $3-8K/close
3. Real Estate Teams — $8-15K/sale
4. Attorneys (PI & Family Law) — $5-50K/case
5. Roofing & Home Renovation — $10-50K/job

## Key Differentiators
- Zero client churn — nobody has ever left
- 100% word of mouth — no outbound, no ads
- Real research, not ChatGPT copy-paste
- Shota has real production background (2 years in Tokyo, built from $0)
- Full content SYSTEM, not just "we'll post for you"

## Real Client Reviews (from current site)
1. "Since teaming up with the Create More team, we've seen a real difference. Our visibility has grown, and we've noticed a solid increase in both sales and customer engagement. They've been super easy to work with and really took the time to understand our brand. It's been a great partnership."
2. "Our digital presence has really improved since working with the team. They gave our website a great refresh and helped us create social media content that feels true to our brand. We've definitely seen more foot traffic and engagement online. It's been a smooth experience from start to finish."
3. "They took the time to really understand what we're about and came up with a marketing plan that works for us. Our social media is much more active now, and we've noticed an uptick in sign-ups for classes. It's been easy to work with them, and the results are clear."

## CTAs
- Social Media: "Book a Demo" → https://www.createmore.us/booking-calendar/demo-call
- SEO: "Get Your Free Audit" → https://bookmenow.info/book/createmore/30-minutes

## Contact Info
- Address: 22370 Michigan Ave Suite 200, Dearborn, MI 48124
- Email: contact@createmoreproduction.com
- Instagram: @createmore.production
- Copyright: © 2026 Create More Productions

## Pages to Build
### 1. Homepage (index.html)
- Hero with bold value prop
- Two service cards (Social Media + SEO) with clear pricing
- Target industries section (the 5 verticals with per-customer value)
- Client reviews/testimonials
- How it works (simple 3-step process)
- Why CMP is different section
- Final CTA

### 2. SEO Landing Page (local.html)
- Already built at projects/seo-landing-page/index.html — COPY THIS FILE as local.html
- Do not rebuild, just copy

## Design Requirements
- Dark theme (black background, red accents, white text)
- Mobile-first responsive
- Smooth scroll animations (IntersectionObserver)
- No external JS libraries
- All CSS/JS inline
- Fast loading
- Proper meta tags and Open Graph
- Sticky nav that solidifies on scroll

## What's WRONG with the current site (problems to fix)
1. Tries to sell EVERYTHING — branding, websites, e-commerce, lead gen, digital campaigns, social media, email, AI tools, content creation, analytics. Way too scattered. Focus on the TWO things: social media + SEO.
2. "Creative Solutions in a Digital World" is the most generic headline possible. Says nothing about what CMP actually does.
3. Lists services in a repeating infinite scroll that literally duplicates the same list 4+ times. Looks broken.
4. No pricing anywhere. Prospects have no idea what to expect.
5. Says "Best Creative Marketing Agency in Dearborn, MI" — sounds desperate, not confident.
6. "Proyect" typo in the site.
7. No clear differentiation from other agencies.
8. No ROI math or business case — just vague promises.
9. Footer still says © 2025.
10. Navigation links (ABOUT US, SERVICES) all point to the same homepage URL — broken nav.

## Navigation Structure
- Logo (left) → links to homepage
- Social Media (nav link) → scrolls to social media section
- SEO (nav link) → scrolls to SEO section or links to /local
- About (nav link) → scrolls to about/differentiator section
- Book a Demo (CTA button, right) → booking link

## DO NOT
- Include any services CMP doesn't actually offer (no email marketing, no branding services, no e-commerce, no paid ads — just social media content + SEO)
- Use generic marketing language ("synergy", "leverage", "innovative solutions")
- Make it feel like a template
- Add external libraries or frameworks
