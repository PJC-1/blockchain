Building a Simple Blockchain in JavaScript
===================
> Following Savjee's youtube tutorial on [Creating a blockchain with Javascript](https://www.youtube.com/watch?v=zVqczFZr124). The following includes notes, links, and examples from the tutorial and other resources.

Helpful Links
-------------

>
>  [crypto-js](https://github.com/brix/crypto-js)
>  
> a medium article [a block chain in 200 lines of code](https://medium.com/@lhartikk/a-blockchain-in-200-lines-of-code-963cc1cc0e54)
>


----------


Blockchain
-------------

**Genesis block**

>
> The first block in a *blockchain* is known as a **genesis block**. Modern versions of Bitcoin number it as *block 0*, thought very early version counted it as *block 1*.
>
> The *genesis block* is almost always hardcoded into the software of the applications that utilize its block chain.
> It is a special case in that it does not reference a previous block, and for *Bitcoin* and almost all of its derivatives, it produces an unspendable subsidy.
>
> For more information on the **genesis block** of a blockchain, here is a [link](https://en.bitcoin.it/wiki/Genesis_block) to bitcoinwiki.
>  

**Difficulty**

>
> **Difficulty** is a measure of how difficult it is to find a hash below a given target.
>  
> The Bitcoin network has a global block difficulty. Valid blocks must have a hash below this target. Mining pools also have a pool-specific share difficulty setting a lower limit for shares.
>  
> For more information and examples on the **difficulty** of a blockchain, here is a [link](https://en.bitcoin.it/wiki/Difficulty) to bitcoinwiki.
>  
