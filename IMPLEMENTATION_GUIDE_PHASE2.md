# LUMIVOX IMPLEMENTATION GUIDE - PHASE 2

## ✅ What's Been Created

### Templates Created
1. **index-lumivox.json** - Complete homepage with all sections
2. **collection.lumivox.json** - Product listing page with SEO content
3. **page.contact.json** - Contact page with form
4. **page.guide.json** - Long-form guide template (already created)
5. **page.comparison.json** - Product comparison (already created)
6. **page.faq.json** - FAQ page (already created)

### Sections Created
1. **lumivox-hero.liquid** - Hero with trust badges
2. **lumivox-why-replace.liquid** - 3-column benefits
3. **lumivox-usps.liquid** - 4 USP blocks
4. **lumivox-faq-quick.liquid** - Quick FAQ accordion
5. **breadcrumbs.liquid** - SEO breadcrumbs

### Snippets Created
1. **product-card-lumivox.liquid** - Custom product card
2. **seo-schema-product.liquid** - Product schema markup
3. **breadcrumbs.liquid** - Breadcrumb snippet

### Translations
- **fr.json** - Complete French translations

---

## 🚀 NEXT STEPS TO LAUNCH

### Step 1: Activate Templates in Shopify

**Homepage:**
1. Go to: **Online Store → Themes → Customize**
2. At top, click dropdown → **Change template**
3. Select **index-lumivox**
4. Click **Save**

**Collection Page:**
1. Go to: **Products → Collections → projecteurs-portables**
2. Click **Edit**
3. Under **Template**, select **collection.lumivox**
4. Click **Save**

**Pages:**
1. Create pages in **Online Store → Pages**:
   - `/pages/guide-remplacer-tv-par-projecteur` → Template: **page.guide**
   - `/pages/comparatif-projecteurs` → Template: **page.comparison**
   - `/pages/faq` → Template: **page.faq**
   - `/pages/contact` → Template: **page.contact**

---

### Step 2: Add Content (CRITICAL)

#### A. Create Products
**Product 1: LumiMax 900**
- Title: `LumiMax 900 - Projecteur Home Cinéma 8K`
- Price: 170€ (Compare at: 210€)
- Description: 400-500 words (use brief content)
- Images: 5-6 product images
- Tags: `bestseller`, `8k`, `home-cinema`
- Collection: `projecteurs-portables`

**Product 2: LumiPlay One**
- Title: `LumiPlay One - Mini Projecteur Portable`
- Price: 120€ (Compare at: 170€)
- Description: 400-500 words
- Images: 5-6 product images
- Tags: `portable`, `compact`, `full-hd`
- Collection: `projecteurs-portables`

#### B. Create Collection
1. **Products → Collections → Create collection**
2. Name: `Projecteurs portables`
3. Handle: `projecteurs-portables`
4. Description: 150-200 words (SEO optimized)
5. Add both products
6. Template: **collection.lumivox**

#### C. Create Navigation Menu
**Main Menu** (handle: `main-menu`):
```
- Accueil → /
- Projecteurs → /collections/projecteurs-portables
- Guide → /pages/guide-remplacer-tv-par-projecteur
- Comparatif → /pages/comparatif-projecteurs
- Blog → /blogs/guides
- FAQ → /pages/faq
- Contact → /pages/contact
```

#### D. Create Pages with Content

**1. Guide Page** (`/pages/guide-remplacer-tv-par-projecteur`)
- Template: **page.guide**
- Content: 2000+ words from brief
- Title: `Le Guide Complet 2025 : Remplacer sa Télévision par un Projecteur`
- SEO title: `Remplacer sa TV par un Projecteur : Le Guide Complet 2025 | Lumivox`
- Meta description: From brief

**2. Comparison Page** (`/pages/comparatif-projecteurs`)
- Template: **page.comparison**
- Content: Comparison content from brief
- Title: `Comparatif : LumiMax 900 vs LumiPlay One`

**3. FAQ Page** (`/pages/faq`)
- Template: **page.faq**
- Content: 20-25 FAQ questions from brief

**4. Contact Page** (`/pages/contact`)
- Template: **page.contact**
- Auto-generated form

**5. About Page** (`/pages/a-propos`)
- Template: **page** (default)
- Content: Company story, mission, values

---

### Step 3: Create Blog Structure

1. **Online Store → Blog posts → Manage blogs**
2. Create blog: `Guides` (handle: `guides`)
3. Create 3-5 initial articles:
   - `TV vs Projecteur : Le guide complet 2025`
   - `Comment installer un projecteur dans son salon`
   - `Top 5 erreurs à éviter avant d'acheter un projecteur`
   - `Projecteur portable : Quel budget prévoir en 2025 ?`
   - `Home cinéma maison : Guide complet`

Each article: 1000-1500 words, SEO optimized

---

### Step 4: SEO Configuration

#### A. Theme Settings
1. **Theme settings → SEO**
2. Homepage title: `Projecteur Portable - Remplacez votre TV | Lumivox France & Belgique`
3. Homepage meta description: From brief
4. Social sharing image: Upload logo/hero image

#### B. Product SEO
For each product:
- SEO title: Include keyword + price
- Meta description: 150-160 characters
- URL handle: `/projecteur/lumimax-900/`

#### C. Collection SEO
- Title: `Projecteurs Portables Full HD & 8K | À partir de 120€ | Lumivox`
- Meta description: From brief
- URL: `/collections/projecteurs-portables/`

#### D. Install SEO Apps (Recommended)
- **SEO Manager** or **Plug in SEO** (free)
- **JSON-LD for SEO** (schema markup)
- **Smart SEO** (auto-optimization)

---

### Step 5: Legal Pages

Create these pages (required for EU):

**1. Mentions Légales** (`/pages/mentions-legales`)
- Company info
- Registration number
- VAT number
- Contact details

**2. CGV** (`/pages/conditions-generales-vente`)
- Terms of sale
- Payment terms
- Delivery terms
- Return policy

**3. Politique de Confidentialité** (`/pages/politique-confidentialite`)
- GDPR compliant
- Data collection
- Cookie policy
- User rights

Use a legal template generator or consult a lawyer.

---

### Step 6: Configure Shipping & Payments

#### Shipping
1. **Settings → Shipping and delivery**
2. Create zone: **France & Belgique**
3. Add rate: **Livraison gratuite** (Free shipping)
4. Set processing time: 24-48h

#### Payments
1. **Settings → Payments**
2. Enable: Shopify Payments, PayPal, Credit Cards
3. Consider: Klarna (3x payment)

---

### Step 7: Add Images

**Required Images:**
- Logo (transparent PNG, 200x60px)
- Favicon (32x32px)
- Hero background (1920x1080px)
- Product images (1200x1200px, 5-6 per product)
- Blog featured images (1200x630px)
- Social sharing image (1200x630px)

Upload via: **Settings → Files** or directly in sections

---

### Step 8: Configure Theme Settings

1. **Theme settings → Colors**
   - Primary: Brand color
   - Secondary: Accent color
   - Background: White/Light gray

2. **Theme settings → Typography**
   - Headings: Modern sans-serif
   - Body: Readable sans-serif

3. **Theme settings → Cart**
   - Enable cart notes
   - Show vendor: No
   - Show ratings: Yes

4. **Theme settings → Social media**
   - Add Facebook, Instagram links
   - Upload social sharing image

---

## 📊 SEO CHECKLIST

### On-Page SEO
- [ ] All pages have unique titles (50-60 chars)
- [ ] All pages have meta descriptions (150-160 chars)
- [ ] H1 tags on every page (only one per page)
- [ ] H2-H6 hierarchy correct
- [ ] Images have alt text
- [ ] Internal linking between pages
- [ ] Breadcrumbs on all pages
- [ ] Schema markup on products
- [ ] FAQ schema on FAQ page
- [ ] Mobile responsive
- [ ] Page speed optimized

### Content SEO
- [ ] Homepage: 500+ words
- [ ] Product pages: 400+ words each
- [ ] Guide page: 2000+ words
- [ ] Collection page: 300+ words
- [ ] Blog articles: 1000+ words each
- [ ] Natural keyword density (1-2%)
- [ ] Long-tail keywords included
- [ ] LSI keywords used

### Technical SEO
- [ ] Sitemap submitted to Google
- [ ] Google Search Console configured
- [ ] Google Analytics installed
- [ ] Robots.txt configured
- [ ] Canonical URLs set
- [ ] 301 redirects for old URLs
- [ ] SSL certificate active (HTTPS)
- [ ] Page load time < 3 seconds

---

## 🎯 LAUNCH CHECKLIST

### Pre-Launch
- [ ] All products added with images
- [ ] All pages created with content
- [ ] Navigation menu configured
- [ ] Legal pages created
- [ ] Shipping zones configured
- [ ] Payment methods enabled
- [ ] Theme customized (colors, fonts, logo)
- [ ] Test orders completed
- [ ] Mobile version tested
- [ ] All links working
- [ ] Contact form tested
- [ ] SEO settings configured

### Launch Day
- [ ] Remove password protection
- [ ] Submit sitemap to Google
- [ ] Set up Google Analytics
- [ ] Set up Facebook Pixel (if using ads)
- [ ] Announce on social media
- [ ] Send email to existing contacts

### Post-Launch (Week 1)
- [ ] Monitor Google Search Console
- [ ] Check for 404 errors
- [ ] Monitor page speed
- [ ] Collect first customer feedback
- [ ] Start blog content schedule
- [ ] Begin link building
- [ ] Set up email marketing

---

## 📝 CONTENT WRITING PRIORITIES

### Week 1 (Launch)
1. Product descriptions (2 products)
2. Homepage content
3. Guide page (2000 words)
4. FAQ page (20 questions)

### Week 2
1. Comparison page content
2. About page
3. First 3 blog articles
4. Legal pages

### Week 3-4
1. Additional blog articles (2 per week)
2. Product page enhancements
3. Collection descriptions
4. Email templates

---

## 🔧 MISSING FEATURES TO ADD LATER

### Phase 3 (Optional Enhancements)
1. **Product reviews app** (Judge.me, Loox)
2. **Live chat** (Tidio, Gorgias)
3. **Email marketing** (Klaviyo, Omnisend)
4. **Upsell/Cross-sell** (Bold Upsell)
5. **Wishlist** (Wishlist Plus)
6. **Size/Distance calculator** (custom app)
7. **Video testimonials** section
8. **Instagram feed** integration
9. **Exit-intent popup** (discount offer)
10. **Abandoned cart recovery**

---

## 📞 SUPPORT

If you need help with:
- Content writing → Hire copywriter
- Images/Design → Hire designer
- SEO optimization → SEO consultant
- Legal pages → Legal template service

---

## 🎉 YOU'RE READY TO LAUNCH!

Once you complete Steps 1-8, your Lumivox website will be:
✅ Fully functional
✅ SEO optimized
✅ Mobile responsive
✅ Ready to sell

**Estimated time to complete:** 2-3 weeks (with content creation)

Good luck! 🚀
