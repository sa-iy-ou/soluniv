# What does 'bundle' mean on pump.fun?

If you've been exploring decentralized exchanges (DEX) like **pump.fun**, you've probably come across the term **"bundle"** in the comments section or Telegram discussions. But what exactly is a bundle, and why should you care?

In this post, we’ll break down:
1. What bundles are.
2. Why they can be a red flag for investors.
3. How tools like **TrenchRadar** can help you identify bundle activity.
4. Practical ways to use this information to make smarter investment decisions.

---

## 1. What Are Bundles?

Bundles refer to the practice of **simultaneously purchasing a large amount of tokens through multiple wallets in one transaction or block**. It’s a common strategy used by token creators or insiders to manipulate the market or secure token supplies during the early stages of a coin launch.

### Why Bundles Happen:
- **Market Control**: Teams or insiders use bundles to acquire large amounts of tokens early, giving them control over supply and the ability to manipulate prices later.
- **Avoiding Detection**: Instead of using one wallet to buy tokens, spreading purchases across multiple wallets makes it harder to track insider activities.

---

## 2. Why Are Bundles a Potential Problem?

Bundles themselves aren’t inherently bad, but they pose significant risks for regular investors. Here's why:

### (1) **Price Manipulation**
Large bundle purchases can artificially inflate a token's price early on. Once prices rise, the same wallets may "dump" their holdings, causing sudden and severe price crashes.

### (2) **False Popularity**
Bundle activity can create the illusion that a token is highly in demand. This can mislead investors into thinking the token is gaining traction, only to discover that the activity was orchestrated.

### (3) **Unfair Advantage**
Bundles are often used to "front-run" regular traders. By executing large trades within the same block, bundle wallets can secure tokens at favorable prices before other investors even have a chance.

---

## 3. Spotting Bundle Activity

### Using Pump.fun Transaction Data
Pump.fun provides visual transaction data that can help detect bundle activity. Look for the following:
- **Simultaneous Transactions in the Same Block**: Transactions that occur within milliseconds of each other in the same slot are likely bundles.
- **Large Token Purchases Across Multiple Wallets**: If several wallets make large purchases within the same block, it could indicate coordinated bundle activity.

![Pump.fun Transaction Data]({{ site.baseurl }}/images/4-1.png)


For example:
- A single slot contains 3 buy transactions executed within milliseconds.  
- The likelihood of this happening naturally on a busy blockchain like Solana is extremely low, especially for an early-stage token.

---

### Using TrenchRadar to Identify Bundles

**TrenchRadar** is a Telegram bot that analyzes bundle activity. It’s a popular tool for evaluating tokens listed on pump.fun.

### How to Use TrenchRadar:
1. Add the bot to your Telegram account: [TrenchScannerBot](https://t.me/TrenchScannerBot).  
2. Paste the **contract address (CA)** of the token you want to analyze into the bot’s chat.  
3. Review the results, focusing on these key metrics:
   - **Current Held Percentage**: This indicates how much of the total supply is held by bundle wallets. Higher percentages are a red flag.  
   - **Top 5 Bundles**: Check how much of the supply is concentrated in the top bundles. A single bundle holding over 10% of the supply is concerning.  

![TrenchRadar Data]({{ site.baseurl }}/images/4-2.png)

For example:
- A token with a **16.96% Current Held Percentage** by bundle wallets may suggest significant insider control.  
- If the **Top 5 Bundles** collectively hold 12% of the token supply, it’s a warning sign.

---

## 4. Real-World Risks of Bundle Activity

Here’s a practical example of why bundles matter:

1. A token is launched, and bundle wallets collectively buy 12% of the supply.  
2. As the token gains traction, these wallets begin dumping their holdings.  
3. The price crashes dramatically, leaving regular investors with worthless tokens.  


---

## 5. When Are Bundles Less Concerning?

Bundles aren’t always a red flag. Here are scenarios where bundle activity might not be a deal-breaker:
- **Bundles Below 10%**: If bundle wallets collectively hold less than 10% of the token supply, the risk is generally lower.  
- **Top Bundles Hold Small Shares**: If the top 5 bundles each hold only 1-2%, it indicates better token distribution.  
- **Price Stability**: If bundle wallets reduce their holdings without crashing the price, it suggests the token may have strong community support.

---

## 6. Can I Use Bundles for My Own Projects?

This isn’t a topic I typically like to discuss in my blog, but if you’re creating a **pump.fun** coin yourself, you might consider using bundles strategically.

When creating a coin, using **sniping** is often the simplest way to make initial purchases with one or two wallets. However, if you want to distribute the tokens across multiple wallets and secure a significant amount early, incorporating bundles into your coin creation process is a more effective method.

There are even services available that help you create coins with bundled purchases.

### Example Tool:
- [WIF Bundles Bot](https://t.me/wif_bundles_bot)  
  This Telegram bot appears to offer services for linking multiple wallets and automating bundled purchases for a small fee. *(This is a referral link with discounted fees.)*

Although I haven’t personally used it, from what I’ve seen, you can input details about your coin and wallets, and the service handles the rest—including bundled token purchases.

> **Please don’t use this for rug-pull! 😂😂😂**


## 7. Tips for Evaluating Tokens with Bundle Activity

If you encounter a token with bundle activity, here’s how to assess its risk:

1. **Check Current Held Percentage**: Use TrenchRadar to identify how much of the token supply is concentrated in bundle wallets.  
2. **Analyze Top Holder Concentration**: Avoid tokens where the top holders control more than 5% of the supply.  
3. **Evaluate Liquidity**: Ensure the token has sufficient liquidity to avoid price manipulation.  
4. **Research the Project**: Look for transparency in the team’s plans and tokenomics.

---

## Conclusion

Bundles are an important concept to understand when trading on pump.fun or other DEX platforms. While they aren’t inherently bad, they can signal potential risks like price manipulation or insider control.

Tools like **TrenchRadar** and transaction data on pump.fun can help you identify bundle activity and make more informed investment decisions. By staying vigilant and analyzing data carefully, you can navigate the volatile world of crypto with confidence.

**Remember**: Always DYOR (Do Your Own Research) and approach new tokens with caution!
