# MADNI Token

**What is MADNI Token?**  
MADNI Token is a digital loyalty token designed specifically for refill drink purchases at small shops, warungs, or cafes. It’s a simple, blockchain-based token (for example, built on the SIP-010 token standard) that replaces traditional manual recording methods with a secure, transparent, and tamper-proof system.

---

**Why MADNI Token?**  
Many refill drink vendors currently rely on manual systems — such as paper cards, stamps, or punch cards — to track customer purchases and reward loyal customers. However, these manual systems have several issues:

- **Easy to lose or damage:** Paper cards can get lost or worn out.  
- **Susceptible to fraud:** Stamps or punch cards can be faked or duplicated.  
- **Difficult to track:** Vendors struggle to maintain accurate, real-time records of customer loyalty.

MADNI Token solves these problems by creating a digital, verifiable record of each refill purchase.

---

**How Does MADNI Token Work?**

- **Minting Tokens:**  
  When a customer buys a refill drink, the shop owner (or cashier) mints MADNI Tokens to the customer’s digital wallet. The number of tokens minted corresponds to the number of purchases.

- **Holding Tokens:**  
  Customers accumulate MADNI Tokens in their wallets, which serve as proof of their purchase history.

- **Redeeming Tokens:**  
  When the customer wants a free refill or discount, they redeem (burn) a certain amount of MADNI Tokens to claim the offer.

- **Transferring Tokens:**  
  Customers can also transfer tokens to friends or family — for example, to treat someone to a refill.

---

**Key Features of MADNI Token**

| Function           | Description                                                                                      |
|--------------------|------------------------------------------------------------------------------------------------|
| `mint(to, amount)`     | Only the shop owner’s wallet can mint tokens to customers, preventing unauthorized creation. |
| `transfer(to, amount)` | Customers can send tokens to others easily, enabling gifting or sharing refill credits.     |
| `redeem(amount)`       | Customers redeem tokens for free refills or discounts; tokens are burned to prevent reuse. |
| `balanceOf(address)`   | Anyone can check token balance, making it easy to verify earned refills.                     |

---

**Benefits of Using MADNI Token**

- **Transparency:** All transactions recorded on the blockchain are secure and immutable.  
- **Fraud prevention:** Digital tokens cannot be forged or duplicated.  
- **Customer engagement:** Incentivizes repeat visits through earning and redeeming tokens.  
- **Flexibility:** Tokens can be transferred, allowing gifting and enhancing experience.  
- **Convenience:** Eliminates physical cards or stamps, reducing costs and hassle.

---

**Example User Flow**

1. Customer buys a refill drink.  
2. Shop owner calls `mint(customer_wallet, number_of_tokens)` to credit the customer.  
3. Customer accumulates tokens and can check their balance anytime.  
4. When ready, customer calls `redeem(number_of_tokens)` to exchange tokens for a free or discounted refill.  
5. Tokens are burned upon redemption, and the customer enjoys the offer.

---

## 🚀 CONTRACT ADDRESS TESTNET  
ST36VRBBMD4PRSAAR4R9V09J7936JTTSZP79DG3MD

