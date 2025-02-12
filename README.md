# 🦈⛓ mev toolkit


<br>

<p align="center">
<img src="https://user-images.githubusercontent.com/1130416/210285135-2d0c3965-a3cd-44f7-a167-3ec14a9ad695.png" width="50%" align="center" style="padding:1px;border:1px solid black;"/>
 </p>


<br>

### tl; dr

#### the concept of maximal extractable value (mev) - a revenue stream generated from priority gas auction (PGA) - was coined by the 2019 research paper [flash boys 2.0](https://arxiv.org/abs/1904.05234), and encompasses the profits generated by participant parties when producing new blocks on a blockchain.

#### the resources in this repository are from my own research, which is intermittent and boundless. therefore, no guarantees, no promises; use it at your own risk.

<br>

<br>


## 🍕 notes && code in this repo

<br>

### extraction strategies

<br>

* [arbitrage](arbitrage)
* [sandwich](sandwich)
* [liquidations](liquidations)
* [nft arbitrage](nft_arbitrage)
* [front-running](front_running)
* [back-running](back_running)
* [just-in-time](uniswap/uniswap-v3/just-in-time.md)
* [flashloans](flashloans)
* [sniping](sniping)


<br>

### building a toolkit

* [pvp battles](pvp_war)
* [build your mev bot](anatomy_of_mev_bots)
* [latency optimization](latency)





<br>

### mev on the chains

* [mev on ethereum](MEV_on_Ethereum)
* [mev on avalanche](MEV_on_Avalanche)
* [mev on arbitrum](MEV_on_Arbitrum)
* [mev on solana](MEV_on_Solana)
* [mev on cosmos](MEV_on_Cosmos)
* [mev on binance](MEV_on_Binance)
* [mev on polygon](MEV_on_Polygon)


<br>

### projects


* [flashbots](flashbots)
* [cow protocol](cow_protocol)
* [rook dao](rook)


<br>

### related defi stuff

* [uniswap](uniswap)
* [oracles and twap](oracles)
* [twamm designs](twamm)
* [0x protocol and rfq](0x_protocol)
* [defi and day trading](defi_and_trading)
* [tokenomics](tokenomics)


<br>



---

## 🍟 resources && tools


<br>

### mev explorers

* [zero mev](https://www.zeromev.org/)
* [public mev explorer](https://metablock.dev/tools/mev/)
* [dashboard by metablock](https://mev.metablock.dev/1/dashboard)
* [flashbots bundle explorer](https://flashbots-explorer.marto.lol/)



<br>

### tx analysis

<br>


##### ethereum mainnet

<br>

* [ethvm](https://www.ethvm.com/)
* [ethtx transaction decoder](https://ethtx.info/)
* [txn finance](https://txn.finance/)
* [ethereum token explorer](https://ethplorer.io/)
* [anyblock explorer and txs](https://explorer.anyblock.tools/)
* [blockscout block explorer](https://blockscout.com/eth/mainnet/)
* [blockchair blocks explorer](https://blockchair.com/ethereum)
* [oklink block and tokens explorer](https://www.oklink.com/en/eth)
* [phalcon tx explorer](https://phalcon.blocksec.com/)
* [breadcrumbs](https://www.breadcrumbs.app/home)

<br>

##### goerli testnet

<br>

* [etherscan goerli](https://goerli.etherscan.io/)




<br>

### gas trackers

<br>

* [eth gas alert](https://ethgasalerts.xyz/)
* [gas price io](https://www.gasprice.io/)
* [ethereum gas tracker](https://www.useweb3.xyz/gas)
* [nansei gas tracker](https://pro.nansen.ai/gas-tracker)
* [gas fee prediction](https://www.blocknative.com/gas-estimator)
* [gastrology](https://dethgasstation.eth.link/)




<br>

### data && analytics


* [mev dashboard by flashbots](https://explore.flashbots.net/).
* [nansen](https://www.nansen.ai/)
* [token terminal](https://tokenterminal.com/terminal)
* [westerngate, arbitrage measured](Westerngate.xyz)
* [eigenphi arbitrage scan](https://eigenphi.io/)
* [parsec.finance](https://parsec.finance/)
* [flashloans](https://tools.blocksec.com/flashloan/eth)
* [sandwiched?](https://sandwiched.wtf/)
* [etherscan data on flashbots](https://etherscan.io/blocks/label/flashbots)
* [mev data corpus by manifold](https://github.com/manifoldfinance/mev-corpus)
* [ethereum datafarm](https://github.com/Nerolation/ethereum-datafarm)



##### awesome dune boards

* [ethereum tx reverts](https://dune.com/kroeger0x/ethereum-transaction-reverts)
* [dune board for gas prices](https://dune.com/kroeger0x/gas-prices)
* [sleuthing hashed function and event signatures](https://dune.com/agaperste/event-and-function-signature-sleuthing?)
* [mev flashbots unleashed](https://dune.com/ivanmolto/mev-flashbots-unleashed)


<br>





### other supporting tools

<br>

* [eth converter](https://eth-converter.com/)
* [smart contract allowance checker](https://app.unrekt.net/)
* [tornado cash pool anonymity](https://tutela.xyz/)
* [eth detective](https://www.ethtective.com/address/)
* [contracts diff checker](https://etherscan.io/contractdiffchecker)
* [ultrasound money dahsboard](https://ultrasound.money/)
* [revoke.cash](https://revoke.cash/)
* [ankr rpc endpoints](https://www.ankr.com/rpc/)
* [back run me](https://backrunme.com/swap)

<br>


---

## 🍿 general articles

<br>

- [endgame by vitalik](https://vitalik.ca/general/2021/12/06/endgame.html)
- [ethereum is a dark forest by paradigm](https://www.paradigm.xyz/2020/08/ethereum-is-a-dark-forest)
- [escaping the dark forest by samczsun](https://samczsun.com/escaping-the-dark-forest/)
- [how to build an ethereum mining pool by dragonfly](https://medium.com/dragonfly-research/how-to-build-an-ethereum-mining-pool-6be356520b7a)
- [mev and me by paradigm](https://research.paradigm.xyz/MEV)
- [return to the dark forest by rekt](https://rekt.news/return-to-the-dark-forest/)
- [modern mev sandwich attacks by totlsota](https://mirror.xyz/totlsota.eth/9JaNkZ1XQfQD6Y79aLYHC_kb_dSBoJ2JYiag5BuGGM8)
- [how i learned to stop worrying and love mev by sreeni](https://medium.com/dragonfly-research/dr-reorg-or-how-i-learned-to-stop-worrying-and-love-mev-2ee72b428d1d)
- [how to light up the dark forest by robert miller](https://writings.flashbots.net/writings/the-anatomy-of-an-inspector/)
- [hiding in plain sight by samczsun](https://samczsun.com/hiding-in-plain-sight/)
- [we live in a mempool by tom schmidt](https://medium.com/dragonfly-research/we-live-in-a-mempool-backrunning-the-mev-crisis-a4ea0b493b05)
- [wrecking sandwich traders for fun and profit](https://github.com/Defi-Cartel/salmonella)
- [tricking frontrunners into being transaction relayers](https://ethresear.ch/t/surrogeth-tricking-frontrunners-into-being-transaction-relayers/6937/1)
- [The enemy of your enemy is not your friend](https://fiona.mirror.xyz/QXdCOAggA5g_j5R_JpO-V5LqK89EbimnYIV6c2rOsT0)
- [anatomy of an mev strategy: synthetix by robert miller](https://bertcmiller.com/2021/09/05/mev-synthetix.html)
- [mev wat to do by phill daian ](https://pdaian.com/blog/mev-wat-do/)





<br>

---


## 🍌 mev research 

<br>

* [mev.day 2022](https://mevday.org/)
* [the daily ape on mev](https://thedailyape.notion.site/MEV-8713cb4c2df24f8483a02135d657a221)
* [cryptocurrency historical data snapshot](https://coinmarketcap.com/historical/)
* [mev wiki](https://www.mev.wiki/)
* [barnabe.eth on pbs](https://barnabe.substack.com/p/pbs)
* [mev extraction strategies](https://docs.google.com/presentation/d/1YVFLnh_MnDtDDQjucW-UKxLD28iGlyi_Pj1ri_hGqRs/edit#slide=id.g125078237b3_0_84)
* [mev auction](https://ethresear.ch/t/mev-auction-auctioning-transaction-ordering-rights-as-a-solution-to-miner-extractable-value/6788)

<br>

#### research papers

- [flash boys 2.0](https://arxiv.org/pdf/1904.05234.pdf)
- [towards a theory of mev by diamandis et al](https://people.eecs.berkeley.edu/~ksk/files/MEV_CFMM.pdf)
- [transparent dishonesty: front-running attacks on blockchain](https://arxiv.org/pdf/1902.05164.pdf)
- [dex arbitrage, mathematical optimizations & me](https://noxx.substack.com/p/dex-arbitrage-mathematical-optimisations)
- [a list of open problems in defi by emperor](https://mirror.xyz/0xemperor.eth/0guEj0CYt5V8J5AKur2_UNKyOhONr1QJaG4NGDF0YoQ)
- [combining ghost and casper](https://arxiv.org/abs/2003.03052)
- [three attacks on pos ethereum](https://arxiv.org/abs/2110.10086)
- [two attacks on pos ghost/ethereum](https://arxiv.org/abs/2203.01315)



<br>

---


## 🌭 bonus: 𝕞𝕒𝕜𝕖 𝕠𝕗 𝕒 𝕔𝕪𝕡𝕙𝕖𝕣𝕡𝕦𝕟𝕜

<br>

* [a graduate course in applied cryptography](http://toc.cryptobook.us/)
* [the cypherpunk manifest by eric hughes](https://activism.net/cypherpunk/manifesto.html)
* [the hacker manifest by the mentor](http://phrack.org/issues/7/3.html)
* [bitcoin whitepaper by satoshi nakamoto](https://bitcoin.org/bitcoin.pdf)
* [teal organizations](https://reinventingorganizationswiki.com/)
* [decentralization by vitalik](https://medium.com/@VitalikButerin/the-meaning-of-decentralization-a0c92b76a274)


<br>
<br>

