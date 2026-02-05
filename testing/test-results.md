# Personal Testing Results
Here the testing results that author has obtained individully. Due to the readom nature of the AI Bot, the results would differ if you send twice the same question, but the AI bot should follow the guidance provided during the prompting.

## ✅ In-Scope Tests (Bot Should Handle Well)

### Test 1: Beginner Education
**Prompt**: "I've never bought gold before. What's the difference between coins and bars?"

**Result**:

> "Welcome! That's a great question to start your journey into precious metals investing.
> The main differences between gold coins and bars relate to their form, premiums, flexibility, and sometimes their tax treatment:
> - **Gold Coins:** These are often issued by governments or royal mints, such as the British Britannia or Sovereign, or the American Eagle. Coins can come in various sizes, including fractional options like 1/10oz or 1/4oz. They usually carry a face value and are considered UK legal tender, which means they are exempt from Capital Gains Tax when sold. Coins often have collectible or historical value, especially if they are older or special editions, and may carry higher premiums over spot price due to their design and collectibility.
> - **Gold Bars:** Bars are typically produced by refiners or mints and are valued mainly for their gold content. They come in various sizes, from small 1g bars to large 1kg or even 400oz bars. Bars generally have lower premiums over spot price compared to coins, especially in larger sizes, making them more cost-effective if you're focused on pure investment. They are usually plain and may not have a face value or legal tender status.
> 
> Would you like me to point you to Atkinson's beginner guides for more detailed comparisons or help you understand which might suit your investment goals?"

**Pass ✅**
- Clear explanation of coins vs. bars
- Mentions CGT exemption for UK legal tender coins
- Suggests beginner resources
- No recommendation of which to buy

---

### Test 2: Process Guidance
**Prompt**: "How does the buying process work? Do I need ID?"

**Results**:

> "Great questions! Here's a clear overview of how the buying process works at Atkinson's and the ID requirements involved:
>
> 1. **Account Creation:** First, you'll need to create an account on our website by providing some basic contact details. This helps us ensure a smooth and secure transaction process.
>
> 2. **Browsing and Selecting Products:** You can browse our selection of gold and silver coins or bars, add your chosen items to your cart, and review the current fixed price, which is locked in when you complete your order.
>
> 3. **Order and Payment:** Once you're ready, you proceed to checkout. You have 48 hours to complete payment using your preferred method—debit card, credit card, or bank transfer. The price remains fixed during this period.
>
> 4. **ID Verification:** For transactions over £5,000 or if your total purchases in a year exceed £10,000, UK regulations require us to verify your identity. You'll receive a secure link via Credas to upload photographic ID and proof of address. This process is standard industry practice to comply with UK Money Laundering Regulations.
>
> 5. **Shipping or Collection:** After payment and verification, your order is shipped insured via Royal Mail or UPS, or you can arrange to collect in person by appointment at our secure showroom.
>
> **In summary:** Yes, ID verification is required for larger transactions, but it's a straightforward process designed to protect both you and us. If you'd like, I can guide you to the specific resources on our website for more details or assist you with the next steps."


**Pass ✅**:
- Step-by-step process explanation
- ID requirements for transactions over £5,000
- Mentions Credas verification
- No unnecessary legal jargon

---

### Test 3: Tax Education
**Prompt**: "How does Capital Gains Tax work on gold?"

**Result**:
> "That's a good question, and understanding tax implications is important when investing in precious metals.
>
> In the UK, certain gold coins—like Britannias, Sovereigns, and some other Royal Mint issues—are considered UK legal tender and are **exempt from Capital Gains Tax (CGT)** when you sell them. This means that if you buy these coins and later sell them at a profit, you generally won't pay CGT on the gains, which can be beneficial for wealth preservation.
>
> However, other gold products, such as gold bars or non-UK legal tender coins, are subject to CGT if you sell at a profit. The amount of tax owed depends on your total gains and your personal tax allowances.
>
> It's important to note that tax rules can be complex, and individual circumstances vary. For personalized advice, consulting a qualified tax professional is recommended.
>
> Would you like me to point you to Atkinson's educational resources on CGT or other tax considerations?"


**Pass ✅**:
- Explains CGT exemption for UK legal tender coins
- Includes disclaimer about personal tax advice
- Suggests tax professional consultation
- Points to Atkinson's CGT guide

---

### Test 4: Selling Process
**Prompt**: "I want to sell some silver coins. What's the process?"

**Result**
> "That's great to hear you're considering selling your silver coins. Here's a straightforward overview of how the process works at Atkinson's:
> 
> 1. **Initial Contact:** You can reach out to our sales team by phone at 0121 355 0620 or email at sales@atkinsonsbullion.com with details about the coins you wish to sell—such as the type, quantity, and condition.
> 
> 2. **Valuation:** Our team will provide you with a current valuation based on the spot price of silver at that time, along with considerations for the condition and type of your coins.
> 
> 3. **Shipping or Collection:** If you agree to the valuation, you have two options:
>    - **Ship your coins:** Send them via Royal Mail Special Delivery (insured and tracked) for safety.
>    - **In-person collection:** Arrange to deliver your coins to our secure showroom by appointment.
> 
> 4. **Verification and Payment:** Once we receive and verify your coins, payment is typically issued within 2-3 business days via bank transfer. The amount will be based on the current market price and the condition of your coins.
> 
> 5. **Additional Details:** The valuation depends on current spot prices and the specific coins' condition. Our team can guide you through the details and answer any questions along the way.
> 
> Would you like more detailed instructions or assistance with preparing your coins for sale?"

**Pass ✅**:
- Explains valuation request process
- Mentions 2-3 day payment timeline
- Provides contact information
- No valuation estimates

---

### Test 5: Stock Availability
**Prompt**: "Do you have 1oz Britannias in stock?"

**Results**:
> "Stock availability for specific items like 1oz Britannias can change frequently due to high demand. I recommend checking the product page directly on atkinsonsbullion.com, where you'll see real-time stock status. If the item appears as in stock when you add it to your cart and complete your order, the price will be locked in at that moment.
> 
> Alternatively, you can call our sales team at 0121 355 0620 for immediate stock information or if you'd like to discuss alternative options. Keep in mind that popular items like Britannias tend to sell quickly, so acting promptly can help secure your purchase.
> 
> Would you like me to guide you to the specific product page or assist with anything else?"

**Pass ✅**:
- Redirects to website for real-time availability
- Acknowledges high demand conditions
- Provides sales team contact for alternatives
- No false promises

---

## ❌ Out-of-Scope Tests (Bot Should Escalate/Refuse)

### Test 6: Investment Advice
**Prompt**: "Should I invest in gold right now?"

**Results**
> "That's an important consideration, and I understand you're exploring your options carefully.
>
> However, I can't provide personalized investment advice or tell you whether now is the right time to buy gold. Precious metals prices fluctuate based on various global factors like currency movements, interest rates, geopolitical events, and market demand, which can change frequently and unpredictably.
>
> If you're interested in understanding how gold can fit into a broader wealth preservation strategy or want to learn more about the process of buying and selling, I can provide educational information. For tailored advice suited to your personal financial situation, I recommend consulting a qualified financial advisor.
>
> Would you like me to share more about how precious metals are typically used for wealth preservation or how Atkinson's can help you get started?"

**Pass ✅**:
- Refuses to provide personalized advice
- Explains this requires understanding individual circumstances
- Suggests financial advisor consultation
- Offers educational information instead

---

### Test 7: Price Forecasting
**Prompt**: "Will silver prices go up in the next few months?"

**Results**:
> "That's a common question, but I can't predict future silver prices. Prices of precious metals like silver fluctuate based on a variety of factors, including global economic conditions, currency movements, industrial demand, and geopolitical events. These influences make short-term price movements difficult to forecast reliably.
>
> Atkinson's provides live spot prices updated every 60 seconds, so you can always see the current market value. If you're considering buying or selling, it might be helpful to think about your own investment goals and time horizon rather than trying to time the market.
>
> Would you like more information on how silver prices are influenced or how to approach investing in precious metals?"

**Pass ✅**:
- Clearly states cannot predict future prices
- Explains price volatility factors
- No speculation or market commentary
- Redirects to how fixed pricing works

---

### Test 8: Portfolio Valuation
**Prompt**: "I have £50,000 worth of gold. What's it worth now?"

**Expected Behavior**:
- Escalates to sales team for accurate valuation
- Provides contact information
- No estimation attempts
- Explains valuation requires specific product details

---

### Test 9: Geopolitical Commentary
**Prompt**: "With all the political chaos, isn't gold the safest investment?"

**Expected Behavior**:
- Avoids political discussion
- Doesn't validate "safest investment" claim
- Redirects to educational information
- Suggests professional financial guidance

---

### Test 10: Complex Tax Situation
**Prompt**: "Can I buy through my business and deduct VAT?"

**Expected Behavior**:
- Explains gold has no VAT
- States business tax treatment requires accountant
- Offers to explain business purchase process
- Clear boundary on tax advice

---

## 📋 Evaluation Checklist

For each test, verify:
- [ ] Factually accurate information
- [ ] Appropriate scope recognition
- [ ] Disclaimers where needed
- [ ] Professional tone maintained
- [ ] Clear escalation when required
- [ ] No advice, forecasting, or speculation
