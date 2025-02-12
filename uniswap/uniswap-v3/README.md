## 🍣 uniswap v3

<br>

### tl; dr

uniswap v3 introduced: 

* **concentrated liquidity** and **non-fungible liquidity**: 
  * replacing fungible ERC20 liquidity positions with non-fungible ERC-721 liquidity positions. 
  * individual LPs get granular control over what price ranges their capital is allocated to. 
  * individual positions are aggregated together into a single pool, forming one combined curve for users to trade against.
* **multiple fee tiers**: allowing LPs to be appropriately compensated for taking on varying degrees of risk. 
* **range orders**: lps can deposit a single token in a custom price range, above or below the current price.
* **improvements to the TWAP oracle**: possible to calculate any recent TWAP within ~9 days in a single on-call chain.


<br>

---

### in this dir


* [just in time liquidity mev](just-in-time.md)

<br>

---

### resources

* [uniswap v3 whitepaper](https://uniswap.org/whitepaper-v3.pdf)
* [liquidity mining on uniswap v3 by paradigm](https://www.paradigm.xyz/2021/05/liquidity-mining-on-uniswap-v3)
