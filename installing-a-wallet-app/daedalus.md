---
description: Here you will learn about Daedalus, its features and its interface.
---

# Daedalus

{% hint style="danger" %}
As of the last revision of this document (May 2024) a mobile version of Daedalus has **NOT** been released. Numerous **scams** have been reported, claiming Daedalus can be used on mobile. This is **NOT** the case and you should **NOT** trust these claims. &#x20;
{% endhint %}

## About Daedalus

Daedalus is a **Cardano Wallet** made by [IOG ](https://iohk.io/)(the developing company behind Cardano). It is a desktop application, which works with **all major Operating Systems** (Windows, MacOS and Linux).&#x20;

{% hint style="warning" %}
Daedalus requires a relatively high-specification desktop machine for good performance. It is ideal for those who want accurate blockchain data, but should not be the go-to wallet for everyday, minor transactions.
{% endhint %}

> Daedalus is a full node wallet. This means that unlike light wallets (e.g.Yoroi, Adalite etc.) Daedalus downloads a full copy of the Cardano blockchain and independently validates every transaction in its history. That way you get maximum security and completely trustless operation, without centrally hosted 3rd party servers.

**Daedalus** can be downloaded here: [https://daedaluswallet.io/](https://daedaluswallet.io/)

![The splash page from Daedalus' Website.](../.gitbook/assets/daedalus\_splash.PNG)

{% hint style="danger" %}
Do **not** trust any other sources than the one linked above for Daedalus downloads. **Always check the URL** you are downloading from!
{% endhint %}

{% hint style="danger" %}
Always check that you are downloading verified software. **Follow the instructions** on the Download page, and verify signature and checksum!
{% endhint %}

## Let Daedalus sync to the blockchain

Once you have downloaded and verified Daedalus (see previous section) configure options as needed:

![Initial Daedalus splash](../.gitbook/assets/Daedalus\_options\_init.png)

Accept the Terms and Conditions:

![Terms of Service checkbox](../.gitbook/assets/Daedalus\_TandC\_accept.png)

{% hint style="danger" %}
At this time it is **important** to let the software **sync to the blockchain**. This process will take time (hours). Wait until it has completed **before creating or restoring a wallet**.
{% endhint %}

To check synchronisation progress you can hover over **the circular arrows icon** in the top right corner:

![](../.gitbook/assets/Daedalus\_let\_sync.png)

Once Daedalus has **synced to the blockchain** a check mark will appear in the top right corner:

![](../.gitbook/assets/daedalus\_sync\_done.png)

## Creating a wallet

Now it's time to create a new wallet! Choose a name for your wallet and a **strong** password (you will need this to authorise **outgoing** transactions):&#x20;

![](../.gitbook/assets/daedalus\_create\_wallet.png)

{% hint style="warning" %}
Your wallet name and password are only stored locally. If you were to loose access to your wallet, the **recovery phrase** (see below) is the only means to recover your wallet. If you need to do this, you will be prompted for a new name and password. &#x20;
{% endhint %}

{% hint style="danger" %}
From this point onward **follow the onscreen instructions to the letter**. Please make sure you understand what the **recovery phrase** is for, and how to best **keep it safe**.
{% endhint %}

![](../.gitbook/assets/daedalus\_rec\_phrase\_disc.png)

Once you have noted and secured your **recovery phrase** you will be asked to enter it, as a means to confirm you have the correct sequence of 24 words. **Your wallet is now created** and ready to be funded, please wait for it to fully sync its transaction history:

![](../.gitbook/assets/daedalus\_wallet\_sync.png)

{% hint style="info" %}
Take your time to navigate Daedalus' interface and familiarise yourself with it. Below you will learn what to do in case you should loose access to your wallet.&#x20;
{% endhint %}

## Recovering a Daedalus wallet

Should you loose access to your Daedalus software for whichever reason (machine broken/lost/stolen), please use your **mnemonic phrase** to restore it. Choose **restore** in the following menu:

![](../.gitbook/assets/daedalus\_restore.PNG)

You will be taken to a menu, asking to choose what type of wallet to restore, flag **Daedalus wallet**:

![](../.gitbook/assets/daedalus\_restore\_type.PNG)

When prompted for the **kind** of Daedalus wallet, choose **24 words (Shelley wallet)**:

![](../.gitbook/assets/daedalus\_restore\_type\_2.PNG)

{% hint style="info" %}
This method of recovery works for older Daedalus wallets as well, and for Yoroi wallets. &#x20;
{% endhint %}

Now it's time to enter your **mnemonic phrase**:

![](../.gitbook/assets/daedalus\_restore\_phrase.PNG)

As you can see, once you enter your **mnemonic phrase** and verify it, you are prompted for a **new** wallet **name** and **password**. This was already noted above, and is important because:

{% hint style="danger" %}
Should someone get a hold of your **mnemonic phrase**, they can restore your wallet and **gain full control** of it, **even if they don't know your spending password** (they will be asked, like you just then, to make a new password).
{% endhint %}

{% hint style="danger" %}
Should you ever **loose** a copy of your **mnemonic phrase**, you must consider **your wallet compromised**, and transfer its contents to a new one.
{% endhint %}

![](../.gitbook/assets/daedalus\_restore\_config.PNG)

{% hint style="info" %}
You now have all the tools you need to **manage your Daedalus wallets**. Please use your judgement and take time to practice **creating**, **deleting** and **restoring** wallets, in order to gain confidence.
{% endhint %}
