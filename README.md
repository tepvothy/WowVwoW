
<h1 align="center">Hi 👋, I'm Wow.V.woW</h1>
<h3 align="center">Network Engineer from Cambodia</h3>

<h3 align="left">Connect with me:</h3>
<p align="left">
<img src="telegram_QRCode.png" alt="telegram_QR" width="200" height="200">
</p>

<h3 align="left">Direct link below</h3>
<a href="https://github.com/tepvothy/WowVwoW/blob/main/README.md#install-socks-a-single-command-line-" target="blank"><img align="center" src="https://github.com/tepvothy/WowVwoW/blob/main/images/socks.png" alt="https://github.com/tepvothy/WowVwoW/blob/main/README.md#install-socks-a-single-command-line-"/></a>
<a href="https://github.com/tepvothy/WowVwoW/blob/main/README.md#http-proxy" target="blank"><img align="center" src="https://github.com/tepvothy/WowVwoW/blob/main/images/http.png" alt="https://github.com/tepvothy/WowVwoW/blob/main/README.md#http-proxy"/></a>
<a href="https://github.com/tepvothy/WowVwoW/blob/main/README.md#shadowsocks" target="blank"><img align="center" src="https://github.com/tepvothy/WowVwoW/blob/main/images/shadowsocks.png" alt="https://github.com/tepvothy/WowVwoW/blob/main/README.md#shadowsocks"/></a>
<a href="https://github.com/tepvothy/WowVwoW/blob/main/README.md#l2tp-server-by-teddysun" target="blank"><img align="center" src="https://github.com/tepvothy/WowVwoW/blob/main/images/l2tp.png" alt="https://github.com/tepvothy/WowVwoW/blob/main/README.md#l2tp-server-by-teddysun"/></a>
<a href="https://github.com/tepvothy/WowVwoW/blob/main/README.md#mtproxy-install-in-ubuntu" target="blank"><img align="center" src="https://github.com/tepvothy/WowVwoW/blob/main/images/mtproxy.png" alt="https://github.com/tepvothy/WowVwoW/blob/main/README.md#mtproxy-install-in-ubuntu"/></a>
<a href="https://github.com/tepvothy/WowVwoW/blob/main/README.md#install-openvpn-server-a-single-command-by-yeasin989" target="blank"><img align="center" src="https://github.com/tepvothy/WowVwoW/blob/main/images/openvpn.png" alt="https://github.com/tepvothy/WowVwoW/blob/main/README.md#install-openvpn-server-a-single-command-by-yeasin989"/></a>

<h1 id="socks5">install socks a single command line </h1>
<p><code class="language-plaintext highlighter-rouge">curl https://raw.githubusercontent.com/tepvothy/WowVwoW/refs/heads/master/socks.txt | sudo bash</code></p>

<h1 id="socks5">install HTTP a single command line </h1>
<p><code class="language-plaintext highlighter-rouge">curl https://raw.githubusercontent.com/tepvothy/WowVwoW/refs/heads/master/http.txt | sudo bash</code></p>

<p>1. Install l2tp server</p>
<p><code class="language-plaintext highligter-rouge">wget --no-check-certificate https://raw.githubusercontent.com/teddysun/across/master/l2tp.sh</code></p>
<p>2. Change to executable right restriction</p>
<p><code class="language-plaintext highligter-rouge">chmod +x l2tp.sh</code></p>
<p>3. Execute installation script</p>
<p><code class="language-plaintext highligter-rouge">./l2tp.sh</code></p>
<p>If you want to modify user settings, please use below command(s):</p>
<p><code class="language-plaintext highligter-rouge">l2tp -a </code>(Add a user)</p>
<p><code class="language-plaintext highligter-rouge">l2tp -d </code>(Delete a user)</p>
<p><code class="language-plaintext highligter-rouge">l2tp -l </code>(List all users)</p>
<p><code class="language-plaintext highligter-rouge">l2tp -m </code>(Modify a user password)</p>

<h1>MTPROXY install in Ubuntu <a href="https://github.com/tepvothy/WowVwoW/blob/main/README.md#direct-link-below" target="blank"><img align="right" src="https://thumbnail.imgbin.com/23/6/16/imgbin-button-return-s-mSaKDepmjzAignfPP9c5QrPnx_t.jpg" alt="https://github.com/tepvothy/WowVwoW/blob/main/README.md#direct-link-below" height="30" width="40" /></a></h1>
<p>1. Update </p>
<p><code class="language-plaintext highligter-rouge">apt update
apt install apt-transport-https ca-certificates curl software-properties-common</code></p>
<p>2. Install DOCKER</p>
<p><code class="language-plaintext highligter-rouge">curl -fsSL https://download.docker.com/linux/ubuntu/gpg | sudo apt-key add -
add-apt-repository "deb [arch=amd64] https://download.docker.com/linux/ubuntu focal stable"
apt install docker-ce
apt install docker-compose-plugin
curl -L -o mtp_install.sh https://git.io/fj5ru && bash mtp_install.sh</code></p>
<p>If error please install NTP command below</p>
<p><code class="language-plaintext highligter-rouge">apt install systemd-timesyncd
timedatectl set-ntp true
systemctl unmask systemd-timesyncd.service</code></p>
<p>Then you can enable and start the service:</p>
<p><code class="language-plaintext highligter-rouge">systemctl enable systemd-timesyncd.service
systemctl start systemd-timesyncd.service
systemctl status chronyd.service
systemctl status ntp.service</code></p>

<h1>Install OPENVPN Server a single command <a href="https://github.com/cheysethi1999/BRAVO/blob/master/README.md#direct-link-below" target="blank"><img align="right" src="https://thumbnail.imgbin.com/23/6/16/imgbin-button-return-s-mSaKDepmjzAignfPP9c5QrPnx_t.jpg" alt="https://github.com/cheysethi1999/BRAVO/blob/master/README.md#direct-link-below" height="30" width="40" /></a></h1>
<p>1 Openvpn free 1024 client</p>
<p><code class="language-plaintext highligter-rouge">cd /tmp/ && yum install git -y && git clone https://github.com/yeasin989/OPEN-VPN-ACCESS-SERVER.git && cd OPEN-VPN-ACCESS-SERVER/ && sed -i -e 's/\r$//' centos7.sh && chmod 755 centos7.sh && ./centos7.sh</code></p>
Thank You.




 
