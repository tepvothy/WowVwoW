
<h1 align="center">Hi 👋, I'm Wow.V.woW</h1>
<h3 align="center">Network Engineer from Cambodia</h3>

<h3 align="left">Connect with me:</h3>
<p align="left">
<img src="telegram_QR.png" alt="telegram_QR" width="200" height="200">
</p>

<h3 align="left">Direct link below</h3>
<a href="https://github.com/tepvothy/WowVwoW/blob/main/README.md#install-socks-a-single-command-line-" target="blank"><img align="center" src="https://github.com/tepvothy/WowVwoW/blob/main/images/socks.png" alt="https://github.com/cheysethi1999/BRAVO/blob/master/README.md#install-socks-a-single-command-line-"/></a>
<a href="https://github.com/tepvothy/WowVwoW/blob/main/README.md#http-proxy" target="blank"><img align="center" src="https://github.com/cheysethi1999/BRAVO/blob/master/images/http.png" alt="https://github.com/cheysethi1999/BRAVO/blob/master/README.md#http-proxy"/></a>
<a href="https://github.com/tepvothy/WowVwoW/blob/main/README.md#shadowsocks" target="blank"><img align="center" src="https://github.com/cheysethi1999/BRAVO/blob/master/images/shadowsocks.png" alt="https://github.com/cheysethi1999/BRAVO/blob/master/README.md#shadowsocks"/></a>
<a href="https://github.com/tepvothy/WowVwoW/blob/main/README.md#l2tp-server-by-teddysun" target="blank"><img align="center" src="https://github.com/cheysethi1999/BRAVO/blob/master/images/l2tp.png" alt="https://github.com/cheysethi1999/BRAVO/blob/master/README.md#l2tp-server-by-teddysun"/></a>
<a href="https://github.com/tepvothy/WowVwoW/blob/main/README.md#mtproxy-install-in-ubuntu" target="blank"><img align="center" src="https://github.com/cheysethi1999/BRAVO/blob/master/images/mtproxy.png" alt="https://github.com/cheysethi1999/BRAVO/blob/master/README.md#mtproxy-install-in-ubuntu"/></a>
<a href="https://github.com/tepvothy/WowVwoW/blob/main/README.md#install-openvpn-server-a-single-command-by-yeasin989" target="blank"><img align="center" src="https://github.com/cheysethi1999/BRAVO/blob/master/images/openvpn.png" alt="https://github.com/cheysethi1999/BRAVO/blob/master/README.md#install-openvpn-server-a-single-command-by-yeasin989"/></a>


<h1 id="socks5">install socks a single command line </h1>
<p><code class="language-plaintext highlighter-rouge">curl https://raw.githubusercontent.com/tepvothy/WowVwoW/refs/heads/master/socks.txt | sudo bash</code></p>

<p>If you would like to manually set port and/or password:</p>

<div class="language-bash highlighter-rouge"><div class="highlight"><pre class="highlight"><code><span class="nb">export </span><span class="nv">PORT</span><span class="o">=</span>8080<span class="p">;</span> <span class="nb">export </span><span class="nv">PASSWORD</span><span class="o">=</span>mypass
curl https://raw.githubusercontent.com/tepvothy/WowVwoW/refs/heads/master/socks.txt | <span class="nb">sudo</span> <span class="nt">--preserve-env</span> bash
</code></pre></div></div>

<p>This creates self-hosted <a href="https://en.wikipedia.org/wiki/SOCKS">SOCKS5</a> server powered by <a href="http://www.inet.no/dante/">Dante</a>. Supported Linux distributions:</p>

<ul>
  <li>Ubuntu 16.04 Xenial</li>
  <li>Ubuntu 18.04 Bionic</li>
  <li>Ubuntu 20.04 Focal</li>
  <li>CentOS 7 and Oracle Linux 7.5 (thanks to <a href="https://github.com/vladsf">Vlad Safronov</a>)</li>
</ul>

<h1 id="shadowsocks">shadowsocks <a href="https://github.com/cheysethi1999/BRAVO/blob/master/README.md#direct-link-below" target="blank"><img align="right" src="https://thumbnail.imgbin.com/23/6/16/imgbin-button-return-s-mSaKDepmjzAignfPP9c5QrPnx_t.jpg" alt="https://github.com/cheysethi1999/BRAVO/blob/master/README.md#direct-link-below" height="30" width="40" /></a></h1>

<p><code class="language-plaintext highlighter-rouge">curl https://raw.githubusercontent.com/BRAVO-IT/VPN/refs/heads/master/shadowsocks.txt | sudo bash</code></p>

<p>If you would like to manually set port and/or password:</p>

<div class="language-bash highlighter-rouge"><div class="highlight"><pre class="highlight"><code><span class="nb">export </span><span class="nv">PORT</span><span class="o">=</span>8080<span class="p">;</span> <span class="nb">export </span><span class="nv">PASSWORD</span><span class="o">=</span>mypass
curl https://raw.githubusercontent.com/BRAVO-IT/VPN/refs/heads/master/shadowsocks.txt | <span class="nb">sudo</span> <span class="nt">--preserve-env</span> bash
</code></pre></div></div>

<p>This creates self-hosted <a href="https://shadowsocks.org/">shadowsocks</a> server. Clients:</p>
<ul>
  <li>Android: <a href="https://play.google.com/store/apps/details?id=com.github.shadowsocks">shadowsocks by Max Lv</a></li>
  <li>Other devices: <a href="https://shadowsocks.org/en/download/clients.html">shadowsocks clients</a></li>
</ul>

<p>Supported Linux distributions:</p>

<ul>
  <li>Ubuntu 16.04 Xenial</li>
  <li>Ubuntu 18.04 Bionic</li>
  <li>CentOS 7 and RHEL 7 (thanks to Octavian Dodita octavian2204[anti-spam-dog]gmail.com )</li>
</ul>
 <h1 id="HTTP Proxy">HTTP Proxy <a href="https://github.com/cheysethi1999/BRAVO/blob/master/README.md#direct-link-below" target="blank"><img align="right" src="https://thumbnail.imgbin.com/23/6/16/imgbin-button-return-s-mSaKDepmjzAignfPP9c5QrPnx_t.jpg" alt="https://github.com/cheysethi1999/BRAVO/blob/master/README.md#direct-link-below" height="30" width="40" /></a></h1>

 <p>Set up squid server in Centos 7 follow command below:</p>
 <p>1. command line Install squid</p>
 <p><code class="language-plaintext highlighter-rouge">yum -y install squid httpd-tools</code></p>
<p>2. command line go config file</p>
<p><code class="language-plaintext highlighter-rouge">vim /etc/squid/squid.conf</code></p>
<p>3. Config follow this command line</p>
<p><code class="language-plaintext highligter-rouge">acl lan src all
auth_param basic program /usr/lib64/squid/basic_ncsa_auth /etc/squid/.htpasswd
auth_param basic children 5
auth_param basic realm Squid Basic Authentication
auth_param basic credentialsttl 5 hours
acl password proxy_auth REQUIRED
http_access allow password</code></p>
<p>4. Add this command to access list</p>
<p><code class="language-plaintext highligter-rouge">http_access allow lan</code></p>
<p>5. Add this commnad to the end off config file</p>
<p><code class="language-plaintext highligter-rouge">#Add Follows To The end
request_header_access Referer deny all
request_header_access X-Forwarded-For deny all
request_header_access Via deny all
request_header_access Cache-Control deny all
#Do not display IP address
forwarded_for off</code></p>
<p>6. Create user/pass for client</p>
<p><code class="language-plaintext highligter-rouge">htpasswd -c /etc/squid/.htpasswd vpnuser</code></p>
<p>Start Squid and Enable</p>
<p><code class="language-plaintext highligter-rouge">systemctl start squid && systemctl enable squid</code></p>
<p>7. Turn on firewall</p>
<p><code class="language-plaintext highligter-rouge">systemctl start firewalld
systemctl status firewalld</code></p>
<p>8. Reload firewall and tcp port</p>
<p><code class="language-plaintext highligter-rouge">firewall-cmd --zone=public --add-port=3128/tcp --permanent && firewall-cmd --reload</code></p>
<p>9. Check Squid status and Connection</p>
<p><code class="language-plaintext highligter-rouge">systemctl status squid
tail -f /var/log/squid/access.log</code></p>

<p>That's all enjoy your http proxy</p>

<h1>L2TP Server by <a href="https://github.com/teddysun">teddysun</a><a href="https://github.com/cheysethi1999/BRAVO/blob/master/README.md#direct-link-below" target="blank"><img align="right" src="https://thumbnail.imgbin.com/23/6/16/imgbin-button-return-s-mSaKDepmjzAignfPP9c5QrPnx_t.jpg" alt="https://github.com/cheysethi1999/BRAVO/blob/master/README.md#direct-link-below" height="30" width="40" /></a></h1>

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

<h1>MTPROXY install in Ubuntu <a href="https://github.com/cheysethi1999/BRAVO/blob/master/README.md#direct-link-below" target="blank"><img align="right" src="https://thumbnail.imgbin.com/23/6/16/imgbin-button-return-s-mSaKDepmjzAignfPP9c5QrPnx_t.jpg" alt="https://github.com/cheysethi1999/BRAVO/blob/master/README.md#direct-link-below" height="30" width="40" /></a></h1>
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

 <h1 id="Contact me">Contact me</h1>
<ul>
  <li>Telegram: <a href="https://t.me/BRAVO_IT">BRAVO_IT</a></li>
  <li>Youtube: <a href="https://youtube.com/@littleskill168?si=VEru_lzwOXJg5Wk9">Littleskill</a></li>
</ul>




 
