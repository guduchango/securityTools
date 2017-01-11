# ### Grabber
### Dependencias Ubuntu

```
sudo apt-get -y install python-pip
sudo apt-get install python
sudo pip install beautifulsoup
```
### Descargar Grabber

* ir a -> http://rgaucher.info/beta/grabber/
* descargar directamente de http://rgaucher.info/beta/grabber/Grabber.zip

### Ejecutar Grabber

```
cd ./Grabber
python grabber.py --spider 1 --sql --xss --url http://192.168.8.90:9999/
python grabber.py --spider 1 --sql --xss --url http://192.168.8.90:9999/saiyajin
```

# ### Zed Attack Proxy
### Instalar java en ubuntu 

* http://www.ubuntu-guia.com/2012/04/instalar-oracle-java-7-en-ubuntu-1204.html

### Descargar Zed Attack Proxy

* https://github.com/zaproxy/zaproxy/wiki/Downloads

### Ejecutar Zed Attack Proxy

```
cd ./ZAP_2.5.0

./zap.sh
```

# ### w3af

### Dependencias ubuntu 

```
sudo apt-get -y install python-webkit python-gtksourceview2 libxslt1-dev graphviz
```

### Dependencias python

```
sudo pip install pyClamd==0.3.15 PyGithub==1.21.0 GitPython==0.3.2.RC1 pybloomfiltermmap==0.3.14 esmre==0.3.1 phply==0.9.1 nltk==3.0.1 chardet==2.1.1 tblib==0.2.0 pdfminer==20140328 futures==2.1.5 ndg-httpsclient==0.3.3 pyasn1==0.1.8 lxml==3.4.4 scapy-real==2.2.0-dev guess-language==0.2 cluster==1.1.1b3 msgpack-python==0.4.4 python-ntlm==1.0.1 halberd==0.2.4 darts.util.lru==0.5 Jinja2==2.7.3 vulndb==0.0.19 markdown==2.6.1 psutil==2.2.1 termcolor==1.1.0 mitmproxy==0.13 ruamel.ordereddict==0.4.8 Flask==0.10.1 tldextract==1.7.2 xdot==0.6
```

### Descargar w3af

```
git clone --depth 1 https://github.com/andresriancho/w3af.git
```

### Ejecutar w3af

```
cd w3af
./w3af_gui
```

# ### Vega

### Dependencias ubuntu

```
sudo apt-get install libwebkitgtk-1.0
```

### Descargar Vega

https://subgraph.com/vega/download/index.en.html

### Ejecutar Vega

```
cd ./vega
./vega/Vega
```

# ### Wapiti

### Descargar

http://wapiti.sourceforge.net/

### Ejecutar

```
cd ./wapiti-2.3.0
./bin/wapiti http://192.168.8.90:9999  -u -f json -m "-all"
```







