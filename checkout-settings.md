---
layout: default
title: Checkout & Markets Settings - Maison Theme
---

# 🌍 Checkout & Markets Settings Guide

## Common Issue: Limited Countries in Checkout

If your checkout is only showing 2 or a limited number of countries in the region/country dropdown during checkout, this is controlled by Shopify's **Markets** settings, not your theme.

This guide will help you enable more countries and configure international selling.

---

## 📋 Table of Contents
- [Quick Fix: Enable More Countries](#quick-fix-enable-more-countries)
- [Understanding Markets](#understanding-markets)
- [Adding Countries Worldwide](#adding-countries-worldwide)
- [Shipping Configuration](#shipping-configuration)
- [Tax & Duties Setup](#tax--duties-setup)
- [Currency Settings](#currency-settings)
- [Payment Configuration](#payment-configuration)
- [Testing Your Checkout](#testing-your-checkout)
- [Troubleshooting](#troubleshooting)

---

## Quick Fix: Enable More Countries

### Method 1: Markets Settings (Recommended)

1. Go to your **Shopify Admin**
2. Click **Settings** (bottom left corner)
3. Click **Markets**
4. Click on your **Primary market** (usually "International" or your default market)
5. Under **Countries/regions**, click **Manage**
6. You'll see the list of countries currently enabled
7. Click **Add countries** to add more countries
8. Search and select the countries you want to sell to
9. Click **Add** then **Save**

### Method 2: Shipping Settings

If you want to enable countries for shipping only:

1. Go to **Settings → Shipping and delivery**
2. Click **Manage** next to your shipping profile
3. Under **Markets**, click **Add countries/regions**
4. Select additional countries
5. Set up shipping rates for those countries
6. Click **Save**

**Note:** Countries must be in your Markets AND have shipping configured to appear in checkout.

---

## Understanding Markets

### What Are Markets?

Markets are Shopify's way of organizing where you sell. Each market can have:
- **Specific countries/regions**: Which countries belong to this market
- **Custom pricing**: Different prices for different markets
- **Localized domains**: Country-specific URLs
- **Custom currency**: Display prices in local currency
- **Tax settings**: Market-specific tax rules
- **Shipping rates**: Market-specific shipping

### Default Markets

Every Shopify store has:
- **Primary Market**: Usually "International" or your home country
- You can create additional markets for specific regions

---

## Adding Countries Worldwide

**⚠️ Important:** Only enable countries where you can legally ship and comply with tax laws.

### Step-by-Step: Add Multiple Countries

1. Go to **Settings → Markets**
2. Click your **Primary market** (or create a new market)
3. Click **Add countries/regions**
4. **Select by region** (easiest method):
   - Click **Europe** to add all European countries
   - Click **North America** for US, Canada, Mexico
   - Click **Asia** for all Asian countries
   - Click **Africa** for African countries
   - Click **South America** for South American countries
   - Click **Oceania** for Australia, New Zealand, Pacific islands
5. **Or search individual countries**:
   - Use the search box to find specific countries
   - Click countries to select them
6. Click **Add countries**
7. Click **Save**

### Adding All Countries (Global Selling)

To enable worldwide selling:

1. Go to **Settings → Markets**
2. Click **Primary market**
3. Click **Add countries/regions**
4. Select all regions:
   - Europe
   - North America
   - Asia
   - Africa
   - South America
   - Oceania
5. Review the list (195+ countries)
6. Click **Add countries**
7. Click **Save**

**✅ Result:** All selected countries will now appear in checkout dropdown.

---

## Shipping Configuration

After adding countries to markets, configure shipping for each region.

### Setting Up Shipping Zones

1. Go to **Settings → Shipping and delivery**
2. Click your **Shipping profile** (or create new one)
3. Click **Add zone**
4. **Configure zone**:
   - **Zone name**: e.g., "Europe", "Asia", "Rest of World"
   - **Countries**: Select countries for this zone
5. Click **Done**

### Adding Shipping Rates

For each zone:

1. Click **Add rate**
2. **Rate name**: e.g., "Standard Shipping", "Express"
3. **Price**: Shipping cost (can be free)
4. **Conditions** (optional):
   - **Based on order price**: e.g., Free over $50
   - **Based on weight**: e.g., $5 for 0-1kg
5. Click **Done**
6. Repeat for each zone
7. Click **Save**

### Shipping Best Practices

**Zone Organization:**
- **Domestic**: Your home country (fastest, cheapest)
- **Regional**: Nearby countries (medium speed/cost)
- **International**: Rest of world (slower, more expensive)

**Rate Strategies:**
- **Flat rate**: Same price for all orders in zone
- **Free shipping**: Over a threshold (e.g., $75+)
- **Calculated rates**: Use carrier rates (requires Shopify plan)
- **Weight-based**: Different rates by order weight

**Popular Carriers:**
- **Domestic**: USPS, Royal Mail, Canada Post, Australia Post
- **International**: DHL Express, FedEx, UPS
- **Economy**: USPS First Class International, Royal Mail International
- **Express**: DHL Express Worldwide, FedEx International Priority

---

## Tax & Duties Setup

Configure taxes for international selling to ensure compliance.

### Taxes & Duties
- Research tax requirements for each country
- Shopify can automatically calculate taxes for many countries
- Enable **Include or exclude tax based on customer's country** in **Settings → Taxes**

### Payment Methods
- Ensure your payment gateway supports international payments
- Check currency settings in **Settings → Payments**

### Legal Compliance
- Only sell to countries where you can legally operate
- Some products may be restricted in certain countries
- Check import/export regulations

---

## Testing Your Checkout

Test your international settings before going live.

### Testing Checklist

**1. Test in Incognito/Private Mode:**
- Open your store in incognito/private browsing
- Prevents caching issues
- Shows customer experience

**2. Verify Country Dropdown:**
1. Add a product to cart
2. Go to checkout
3. Check **Country/Region** dropdown
4. Verify all enabled countries appear
5. Test a few different countries

**3. Test Shipping Calculation:**
1. Select different countries in checkout
2. Verify shipping rates calculate correctly
3. Check that free shipping thresholds work
4. Test express vs. standard rates

**4. Test Currency Display:**
1. Change currency (if multi-currency enabled)
2. Verify prices convert correctly
3. Check cart and checkout show same currency
4. Test currency selector in header/footer

**5. Test Tax Calculation:**
1. Select countries with different tax rates
2. Verify tax calculates correctly
3. Test tax-inclusive vs. tax-exclusive display
4. Check duty/import tax messages

**6. Test Payment Methods:**
1. Proceed to payment step
2. Verify correct payment methods show
3. Test with different countries
4. Check local payment methods appear

**7. Place Test Orders:**
1. Complete test orders for different countries
2. Use Shopify's test payment mode
3. Check order confirmation emails
4. Verify order appears correctly in admin

### Using Shopify's Test Mode

**Test Credit Cards:**
- Test Visa: 4242 4242 4242 4242
- Test Mastercard: 5555 5555 5555 4444
- Any future expiry date
- Any 3-digit CVV

**Bogus Gateway (Test Mode):**
1. Go to **Settings → Payments**
2. Click **Add payment method**
3. Search for "Bogus Gateway"
4. Enable and save
5. Use for testing (no real charges)
6. Disable before going live!

**Testing Tips:**
- Use VPN to test geolocation currency
- Test on different devices (mobile, tablet, desktop)
- Check different browsers
- Test with real customers (friends/family) in target countries

---

## Troubleshooting

### Still Only Seeing 2 Countries?

#### Check Your Shipping Settings
1. Go to **Settings → Shipping and delivery**
2. Make sure shipping zones cover all countries you want to sell to
3. **Key rule**: If a country doesn't have shipping set up, it won't appear in checkout
4. Add missing countries to appropriate shipping zones

#### Check Your Domain Settings
1. Go to **Settings → Domains**
2. Ensure your primary domain is set correctly
3. Some domain restrictions can limit available countries
4. Check for country-specific domain restrictions

#### Check Shopify Plan
1. Some Shopify plans have limitations on international selling
2. **Shopify Lite**: Limited international features
3. **Basic**: Full international support
4. **Shopify/Advanced**: Enhanced international features
5. **Plus**: Advanced multi-market features
6. Consider upgrading if you need extensive international sales

#### Check Market Configuration
1. Go to **Settings → Markets**
2. Verify countries are added to active markets
3. Check that markets are not paused
4. Ensure no conflicting market rules

### Common Error Messages

**"Shipping not available to this country"**
- **Solution**: Add country to a shipping zone in **Settings → Shipping**
- Create new zone if needed
- Add at least one shipping rate

**"Currency not supported"**
- **Solution**: Enable currency in **Settings → Markets → Products and pricing**
- Check payment gateway supports the currency
- Shopify Payments supports 130+ currencies

**"Tax cannot be calculated"**
- **Solution**: Enable tax collection for that region in **Settings → Taxes**
- Add tax registration if selling in EU/UK
- Contact Shopify support for complex tax situations

**"Payment method not available"**
- **Solution**: Enable payment methods in **Settings → Payments**
- Check payment gateway supports the country
- Consider adding local payment methods

### Quick Troubleshooting Table

| Problem | Solution |
|---------|----------|
| Countries appear but shipping is $0 | Set up shipping rates in **Settings → Shipping** |
| Countries don't show in dropdown | Add them to your Market in **Settings → Markets** |
| Customers see wrong currency | Configure currencies in **Settings → Markets** |
| Tax not calculating | Enable tax settings in **Settings → Taxes and duties** |
| Payment fails for some countries | Check payment provider's supported countries |
| Free shipping not working | Check threshold amount and zone configuration |
| Duties not showing | Configure DDP in **Settings → Markets → Duties** |
| Local payment methods missing | Enable in **Settings → Payments → Alternative payments** |

---

## Best Practices for International Selling

### Start Small, Scale Up

1. **Phase 1**: Home country + neighboring countries
2. **Phase 2**: Major markets (US, UK, EU, Canada, Australia)
3. **Phase 3**: Expand to more regions
4. **Phase 4**: Global selling (195+ countries)

### Optimize for Conversion

**Display Local Currency:**
- Customers 3x more likely to buy in local currency
- Use automatic conversion or manual pricing
- Show clear currency selector

**Offer Multiple Payment Methods:**
- Accept local popular payment methods
- Enable Apple Pay and Google Pay
- Offer "Buy Now, Pay Later" options (Klarna, Afterpay)

**Calculate Total Costs Upfront:**
- Include shipping in product pages
- Show total cost (including duties) at checkout
- Use DDP for better customer experience

**Localize Content:**
- Translate product descriptions
- Use local measurements (cm vs. inches)
- Show local holidays and shipping times

### Legal & Compliance

**Research Regulations:**
- Import/export restrictions
- Product safety standards
- Labeling requirements
- Data protection (GDPR, CCPA)

**Register for Taxes:**
- EU VAT: Register if sales exceed threshold
- UK VAT: Register if required
- GST: Various countries require registration
- **Consult tax professional** for complex situations

**Customer Service:**
- Provide contact in local business hours
- Offer support in local languages
- Clear return and refund policies
- International return options

---

## Additional Resources

### Shopify Documentation

- **[Markets Documentation](https://help.shopify.com/en/manual/markets)** - Complete markets guide
- **[International Shipping](https://help.shopify.com/en/manual/shipping/understanding-shipping/international)** - Shipping setup
- **[Tax Settings](https://help.shopify.com/en/manual/taxes)** - Tax configuration
- **[Multi-Currency](https://help.shopify.com/en/manual/payments/shopify-payments/multi-currency)** - Currency setup
- **[Payment Gateways](https://help.shopify.com/en/manual/payments)** - Payment options

### Tools & Apps

**Shipping Apps:**
- **ShipStation**: Multi-carrier shipping
- **Easyship**: International shipping rates
- **Shippo**: Discounted shipping labels

**Tax Apps:**
- **Avalara**: Automated tax calculation
- **TaxJar**: Sales tax automation
- **Quaderno**: VAT and tax compliance

**Currency Apps:**
- **BEST Currency Converter**: Advanced currency features
- **MLV Auto Currency Switcher**: Automatic currency detection
- **Shopify Markets** (built-in): Multi-currency support

**Translation Apps:**
- **Langify**: Multi-language stores
- **Weglot**: Automatic translation
- **Shopify Markets** (built-in): Basic translation features

---

## Need Help?

### Support Contacts

- **📧 Theme Support**: mdhyder402@gmail.com
- **💬 Shopify Support**: [Shopify Help Center](https://help.shopify.com/en/questions)
- **📞 Shopify Phone**: Available for paid plans
- **👥 Community**: [Shopify Community Forums](https://community.shopify.com)

### When Contacting Support

Please include:
1. Store URL
2. Screenshot of issue
3. Countries you're trying to enable
4. Steps you've already taken
5. Any error messages
6. Your Shopify plan

---

**💡 Remember:** Checkout country settings are in **Shopify Settings → Markets**, not in your theme files. Your theme displays the checkout correctly—it's Shopify's settings that control which countries appear!

### Automatic Tax Collection

Enable automatic tax calculation:

1. Go to **Settings → Taxes and duties**
2. **Tax collection**: Review your home country tax (automatically enabled)
3. **International taxes**:
   - Click **Collect tax** for regions you sell to
   - Shopify calculates VAT/GST for supported countries
4. **EU VAT**: Enable if selling to Europe
5. **UK VAT**: Enable if selling to UK
6. **Registration numbers**: Add tax registration IDs if required
7. Click **Save**

### Duties & Import Taxes

For countries with import duties:

1. Go to **Settings → Markets**
2. Click the market
3. Scroll to **Duties and import taxes**
4. Choose:
   - **Customer pays duties** (default): Customer pays at delivery
   - **DDP (Delivered Duty Paid)**: You pay duties upfront
5. Click **Save**

**Note:** DDP provides better customer experience but requires you to calculate and pay duties.

### Tax Exemptions

Handle tax-exempt customers:

1. Enable tax exemptions in **Settings → Taxes**
2. **Customer accounts**: Create customer accounts for exempt customers
3. **Add exemption**: Edit customer, add tax exemption certificate
4. **B2B selling**: Consider Shopify Plus for advanced B2B features

---

## Currency Settings

Display prices in customers' local currencies for better conversion rates.

### Enabling Multiple Currencies

**Requirements:**
- Shopify Payments or supported multi-currency gateway
- Shopify Basic plan or higher

**Setup:**

1. Go to **Settings → Markets**
2. Click a market
3. Scroll to **Products and pricing**
4. Under **Currency**, click **Add**
5. Select currencies for this market
6. **Price adjustments**:
   - **Automatic**: Shopify converts using current exchange rates
   - **Manual**: Set custom prices per currency
7. Click **Save**

### Currency Conversion Options

**Automatic Conversion:**
- Pros: Easy, always up-to-date rates
- Cons: Prices might have odd decimals (e.g., $19.73)

**Manual Pricing:**
- Pros: Clean prices (e.g., €19.99), better control
- Cons: More work, need to update regularly

**Rounding Rules:**
- **Round to nearest**: $19.99 → €18.49 → €18.50
- **Round up**: Always round up to next increment
- **Round down**: Always round down

### Currency Display

How customers see currency:

1. **Geolocation**: Shopify detects country, shows local currency
2. **Currency selector**: Customer can manually change currency
3. **Theme integration**: Currency picker in header/footer

**Adding Currency Selector:**
- Most themes include currency selectors
- Enable in **Theme Editor → Header** or **Footer**
- Some themes use Shopify's built-in currency selector

---

## Payment Configuration

Ensure customers can pay in their preferred methods.

### Payment Gateways

**Shopify Payments (Recommended):**
- Built-in, easy setup
- Supports 130+ currencies
- Multi-currency checkout
- Lower transaction fees
- Available in 20+ countries

**Alternative Gateways:**
- PayPal: Global, widely trusted
- Stripe: Popular, developer-friendly
- Authorize.net: US-focused
- Square: US, Canada, UK, Australia

### Enabling Payment Methods

1. Go to **Settings → Payments**
2. **Shopify Payments**:
   - Click **Complete account setup** (if not done)
   - Enable supported payment methods (cards, Apple Pay, Google Pay, Shop Pay)
3. **Alternative payment methods**:
   - Click **Add payment method**
   - Select method (PayPal, Amazon Pay, etc.)
   - Follow setup instructions
4. **Manual payment methods** (optional):
   - Cash on delivery
   - Bank transfer
   - Money order
5. Click **Save**

### Local Payment Methods

Enable popular local payment methods by region:

**Europe:**
- iDEAL (Netherlands)
- Bancontact (Belgium)
- Klarna (Nordics, DACH)
- SEPA Direct Debit

**Asia:**
- Alipay (China)
- WeChat Pay (China)
- PayPay (Japan)
- GrabPay (Southeast Asia)

**Latin America:**
- Mercado Pago
- OXXO (Mexico)
- Boleto (Brazil)

**Enable via Shopify Payments → Alternative payment methods**

---
