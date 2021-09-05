<h1><strong>BestBuy-KeepAlive</strong></h1>
<h2>Description</h2>
<p>BestBuy-KeepAlive is a script based on <a href="https://github.com/kkapuria3/BestBuy-GPU-Bot">kkapuria3&rsquo;s BestBuy-GPU-Bot</a> that&rsquo;s been modified to simulate a purchase of an in stock item every set interval to maintain the validity of the Best Buy Verification Status. Best Buy often gives an extra step to manually enter a verification code that is sent via SMS in between Cart Page and the Final Checkout Page. After going through the verification step successfully, Best Buy doesn&rsquo;t seem to ask for it again for another 20-30 minutes. The only way to extend the verification validity is by going through the purchase process until you get to the Final Checkout Page. This script automates that process and clears your cart without completing the purchase.</p>
<h3>Dependencies</h3>
<ol>
<li>Install <a href="https://github.com/kkapuria3/BestBuy-GPU-Bot">kkapuria3&rsquo;s BestBuy-GPU-Bot</a> and all its dependencies</li>
</ol>
<h3>Installing</h3>
<ol>
<li>Successfully download and install both extensions in your browser</li>
<li>Go to tampermonkey dashboard from broswer extension and create a new script</li>
<li>Delete all the contents and copy full code from <a href="https://github.com/rnario85/BestBuy-KeepAlive/blob/main/best-buy-keep-alive-tm.js">best-buy-keep-alive-tm.js</a></li>
<li>Save the script</li>
<li>Updated REQUIRED FLAGS to your specifications.</li>
</ol>
<h3>How To Use</h3>
<ol>
<li>Open your <a href="https://www.bestbuy.com/site/customer/myaccount">Best Buy Account Page.</a></li>
<li>Let the script run until it asks for the last 4 digits of your SMS for verification (This should be automated if you fill in the flag for it).</li>
<li>Enter the verification code.</li>
<li>The script should continue to run and do a purchase simulation every set number of minutes (15 minute is default) as long as you leave the Account Page open.</li>
<li>Open other windows or tabs to run the regular script for the items you're hunting using <a href="https://github.com/kkapuria3/BestBuy-GPU-Bot">kkapuria3&rsquo;s BestBuy-GPU-Bot.</a></li>
</ol>
<p>&nbsp;</p>