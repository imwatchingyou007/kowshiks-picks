# 🔗 Complete Guide: How to Add Links to Your Website

This guide shows you exactly where to add all types of links in your Amazon affiliate website.

---

## 📍 **1. PRODUCT CARDS - Amazon Affiliate Links**

### Location: `index.html` - Lines 72-177 (Top Picks Section)

**What to do:**
1. Find each product card's "View on Amazon" button
2. Look for the comment: `<!-- 🔗 ADD YOUR AMAZON AFFILIATE LINK HERE -->`
3. Replace `href="#"` with your actual Amazon affiliate link

### Example:
```html
<!-- BEFORE -->
<a href="#" class="btn btn-amazon" target="_blank" rel="noopener noreferrer">View on Amazon</a>

<!-- AFTER (with your affiliate link) -->
<a href="https://www.amazon.com/dp/PRODUCT_ID?tag=YOUR_TAG" class="btn btn-amazon" target="_blank" rel="noopener noreferrer">View on Amazon</a>
```

**There are 6 product cards total** - add links to all of them!

---

## 📂 **2. CATEGORY CARDS - Category Page Links**

### Location: `index.html` - Lines 189-220 (Categories Section)

**What to do:**
1. Find each category card (they're now clickable `<a>` tags)
2. Replace `href="#"` with your category page URL or Amazon category link

### Example:
```html
<!-- BEFORE -->
<a href="#" class="category-card" target="_blank" rel="noopener noreferrer">
    <div class="category-icon">🎧</div>
    <h3 class="category-name">Earbuds & Audio</h3>
    <p class="category-desc">Premium sound experiences</p>
</a>

<!-- AFTER -->
<a href="https://www.amazon.com/s?k=earbuds&tag=YOUR_TAG" class="category-card" target="_blank" rel="noopener noreferrer">
    <div class="category-icon">🎧</div>
    <h3 class="category-name">Earbuds & Audio</h3>
    <p class="category-desc">Premium sound experiences</p>
</a>
```

**There are 6 category cards:**
- Earbuds & Audio
- Laptops & Tech
- Fitness & Health
- Home Essentials
- Mobile Accessories
- Gaming Gear

---

## 📝 **3. BLOG ARTICLE LINKS**

### Location: `index.html` - Lines 232-259 (Blog Section)

**What to do:**
1. Find each article card's "Read More →" link
2. Replace `href="#"` with your actual blog post URL

### Example:
```html
<!-- BEFORE -->
<a href="#" class="article-link">Read More →</a>

<!-- AFTER -->
<a href="https://yourblog.com/wireless-earbuds-guide" class="article-link">Read More →</a>
```

**There are 4 article cards** - add links to all of them!

---

## 📱 **4. SOCIAL MEDIA LINKS**

### Location: `index.html` - Lines 329-333 (Footer Section)

**What to do:**
1. Find the social links in the footer
2. Replace `href="#"` with your actual social media profile URLs

### Example:
```html
<!-- BEFORE -->
<a href="#" class="social-link" aria-label="Instagram" target="_blank" rel="noopener noreferrer">Instagram</a>

<!-- AFTER -->
<a href="https://instagram.com/yourusername" class="social-link" aria-label="Instagram" target="_blank" rel="noopener noreferrer">Instagram</a>
```

**Social links to update:**
- Instagram
- X / Twitter
- LinkedIn

---

## 🎯 **5. NAVIGATION LINKS (Optional)**

### Location: `index.html` - Lines 22-27 (Header Navigation)

**Current status:** These link to sections on the same page (using `#home`, `#categories`, etc.)

**If you want to link to separate pages:**
- Replace `href="#home"` with `href="index.html"` or your homepage URL
- Replace `href="#categories"` with `href="categories.html"` (if you create a categories page)
- Replace `href="#blog"` with `href="blog.html"` (if you create a blog page)

**For now, keep them as-is** - they work perfectly for a single-page website!

---

## 🖼️ **6. ADDING PRODUCT IMAGES (Bonus)**

### Location: `index.html` - Product cards (Lines 73, 91, 109, etc.)

**What to do:**
1. Find the `<div class="image-placeholder">Product Image</div>`
2. Replace it with an actual `<img>` tag

### Example:
```html
<!-- BEFORE -->
<div class="product-image">
    <div class="image-placeholder">Product Image</div>
</div>

<!-- AFTER -->
<div class="product-image">
    <img src="https://images-na.ssl-images-amazon.com/images/I/PRODUCT_IMAGE.jpg" alt="Premium Wireless Earbuds" loading="lazy">
</div>
```

**Pro tip:** Use Amazon product images directly, or host your own images.

---

## ✅ **QUICK CHECKLIST**

- [ ] Added Amazon affiliate links to all 6 product cards
- [ ] Added category links to all 6 category cards
- [ ] Added blog post links to all 4 articles
- [ ] Added social media links (Instagram, Twitter, LinkedIn)
- [ ] (Optional) Added product images
- [ ] Tested all links to make sure they work

---

## 💡 **TIPS FOR AMAZON AFFILIATE LINKS**

1. **Get your affiliate tag** from Amazon Associates
2. **Format:** `https://www.amazon.com/dp/PRODUCT_ID?tag=YOUR_TAG`
3. **Always include** `target="_blank"` and `rel="noopener noreferrer"` (already included!)
4. **Test links** before publishing to ensure they work
5. **Update prices regularly** - Amazon prices change frequently

---

## 🎨 **UNIQUE FEATURES ADDED**

Your website now includes:
- ✨ **Product badges** (Best Seller, Editor's Pick, New)
- 🎯 **Clickable category cards** with hover effects
- 🌟 **Animated background particles**
- 💫 **Enhanced hover effects** on all cards
- 🎭 **Pulsing badge animations**

---

## 📞 **NEED HELP?**

If you need to:
- Add more product cards
- Create additional sections
- Customize colors or fonts
- Add more interactive features

Just ask! I'm here to help make your website even better.

---

**Happy linking! 🚀**

