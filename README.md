# Swarm Komutları

**İndirme Kodu:**
```bash
cd /root/rl_swarm/keys
tsz swarm.pem
```

**Yükleme Kodu:**
```bash
trz /root/rl_swarm/keys/
```

> Bu komutlar, Swarm anahtar dosyalarının bilgisayara indirilmesi ve sunucuya yüklenmesi için kullanılır.


---

# Telegram Botu Kurma

```bash
wget https://go.dev/dl/go1.24.0.linux-amd64.tar.gz
sudo tar -C /usr/local -xzf go1.24.0.linux-amd64.tar.gz
echo 'export PATH=$PATH:/usr/local/go/bin' >> ~/.bashrc
source ~/.bashrc
git clone https://github.com/Deep-Commit/gswarm.git
cd gswarm
mkdir -p /root/go/bin
make install
screen -S gswarm
cd gswarm
./build/gswarm
```

> Bu kodlar, nodenizin çalışıp çalışmadığını kontrol eden ve istatistiksel sonuçları size bildiren bir Telegram botunun kurulum adımlarını içerir.
