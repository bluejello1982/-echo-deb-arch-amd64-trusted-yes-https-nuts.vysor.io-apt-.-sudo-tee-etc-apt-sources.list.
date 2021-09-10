# -echo-deb-arch-amd64-trusted-yes-https-nuts.vysor.io-apt-.-sudo-tee-etc-apt-sources.list.
(echo 'deb [arch=amd64, trusted=yes] https://nuts.vysor.io/apt ./' | sudo tee /etc/apt/sources.list.d/vysor.list) &amp;&amp; sudo apt update &amp;&amp; sudo apt install vysor
