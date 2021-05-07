# Setting Up Your Wallet 
<br>

__⚠ CRYPTO MARKET CAN BE VOLATILE. INVEST AT YOUR OWN RISK ⚠__
<br>
__⚠ PLEASE READ EVERY SENTENCE OF THIS TUTORIAL ⚠__
<br>
<br>

# Install the Official Chia Client
Visit [Chia's website](https://chia.net) and click the green ``Install Chia Blockchian`` button. Download the appropriate client for your operating system. 

![Alt text](/pic/download.png)

Run the installer and follow the instructions. 
<br>
<br>

# Create a Chia Wallet
As you open the client. You should see a page similar to this. Click the ``CREATE A NEW PRIVATE KEY`` button. 

![Alt text](/pic/wallet1.png)
<br>
You will be provided with a 24-word mnemonics. 

![Alt text](/pic/wallet2.png)

__⚠DO NOT GIVE THESE 24 WORDS TO ANYONE__ including us. He who controls the mnemonics, controls the wallet. CelesChia cannot do anything if your wallet is compromised. 

__⚠CREATE SECURE BACKUPS OF THE MNEMONICS RIGHT IMMEDIATELY__. Upload to your Google Drive, save to a flash drive, tattoo them on your butt, etc... CelesChia cannot do anything if you lose access to your wallet. 

Do keep the Chia client running for now. 
<br>
<br>

# Pooling
Farming chia with a pool does __NOT__ increase your chance of winning chia coins. In fact, the pool takes a __0.1%__ (rate may change) cut from the coins you farm. However, pooling does provide a more consistent and reliable output and is therefore strongly recommended by CelesChia. If you do not wish to pool with others and want to farm on your own, you can skip the next few sections. 

Go to [HPool](https://www.hpool.com). In the top right corner, change your language preference and ``Sign Up`` for an account. You will need to verify your email address and phone number. 
<br>
<br>

# Setting Up Withdrawl 

After you have your account set up, follow these steps closely: 
<ol>
<li> Click on your email and then go into Personal Center. </li>
<li> Go to Address under Security </li>
<li> Set your coin type of CHIA </li>
<li> Click Add Address </li>
</ol>

![Alt text](/pic/pool1.png)

Now go back to your Chia client and copy your ``Receive Address``.

![Alt text](/pic/pool2.png)

Paste that into ``Address:`` on HPool. Hit ``Confirm`` and you should be all set. 

![Alt text](/pic/pool3.png)

At this point, the Chia coins you farm will be withdrawn to your wallet. If you want Bernard to ~~laundry~~ _process_ them for you, ask for his receiving address instead. 

# Get Your Pool Keys
Welcome to the final steps, you are almost done! 

Visit [HPool's GitHub](https://github.com/hpool-dev/chia-plotter/releases) and download ``chia-plotter-gui-vX.XX-win64.exe``

![Alt text](/pic/pool4.png)

Run ``chia-plotter-gui``. Type in your 24 words and hit ``Sign``. 

![Alt text](/pic/pool5.PNG)

Make sure the ``FingerPrint`` matches that shown in the Chia client. 
Copy the ``Farmer Public Key`` and ``Pool Public Key`` and send them to mjin@CelesChia.com.

__⚠PLEASE NOTE__ that this is a throw-away wallet. Don't actually show your mnemonics to anyone. I'm very serious about this.

__⚠PLEASE NOTE__ that plots created using your Farmer Public Key is tied exclusively to your wallet. If you lose access or a maliscious person gains access to your wallet, CelesChia may not be able to re-farm your existing plots using your new wallet. 

### __CELESCHIA DOES NOT COVER YOUR LOSS OR PROVIDE REFUND FOR YOUR PLOTS IN THE CASES OF ABOVE SCENARIOS__ 

HPool doesn't see your mnemonics either. This application simply generates the keys from your mnemonics, so the pool can associate your plots with your account. You can disconnect your internet connection for this step to be extra safe. 

You may close your Chia client after this step is done. 
<br>
<br>

# Register Your Keys with HPool

First to go ``Open Pool`` and open a ``CHIA ECO`` pool. 

![Alt text](/pic/pool6.png)

Go to ``Configuration`` and copy your ``Signature `` from ``chia-plotter-gui`` into ``Bind signature data``. Hit Bind to register your key. 

Copy your ``API Key`` and email it to mjin@celeschia.com.
