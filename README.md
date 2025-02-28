# mindmaps

Mermaid kullanarak bir akış diyagramı oluştur. Ana başlık "Bug Hunting Metodolojisi" olacak. Diyagram aşağıdaki gibi hiyerarşik bir yapıya sahip olmalı:

1. **Find Domain** (Domain Bulma)
   - Cache Base
   - bgr.bne.net
   - nslookup
   - Metabigor
   - Amass Intel - ASN
   - Domnlink Tool
   - Jet.relationships.PT
   - Shodan
   - Findomain
   - getrelationship.py
      -echo "uber.com" | getrelationship.py   
   - Benzer Domainleri Bulmak İçin: Threatcrowd
   - "© 2019 Twitch Interactive , Inc." inurl:twitch

2. **Find Subdomain** (Alt Domain Bulma)
   - Burp Suite Spider
   - Hakrawler
   - GoSpider
   - Amass
   - Subfinder
   - Shosubgo
   - Curl Buffer-Ower.Run
   - fovicon to hash
   - assetfinder

3. **Subdomain Takeover** (Alt Domain Ele Geçirme)
   - Subover
   - Nuclei

4. **Find URL** (URL Bulma)
   - Katana
   - Waybackurls
   - Burp Suite (Sitemap)

5. **Live URL** (Aktif URL Kontrolü)
   - Httpx
   - httprobe

6. **Port Analysis** (Port Analizi)
   - Masscan
   - DnMasscan

7. **Service Scan** (Servis Taraması)
   - Nmap Service Scan -oG

8. **Service Brute Force** (Servis Brute Force)
   - Brutespray (Nmap çıktısı ile çalışır)

9. **Screenshots** (Web Sayfası Görsellerini Alma)
   - Eyewitness
   - Httpscreenshot
   - Aquatone

10. **URL Header - Body Info** (URL Header ve Body Bilgisi Analizi)
    - FFF
    - HTML-Tool

11. **File Credential Info** (Credential Bilgisi Bulma)
    - GF

12. **Sorting** (Sıralama İşlemi)
    - Anew
    - Tee -a

13. **404 Handling** (404 Hataları İçin)
    - Fuff config dosyaları

14. **Inscope** (Yetkili Bilgi Toplama)
    - Sadece domeine ait bilgileri topla

15. **Github Repo Copy** (Github Repo Kopyalama)
    - Ghcopy
    - Gitdump (Eski commitleri bul)
    - GitObject

16. **Webpaste** (Google Üzerinden Bilgi Toplama)
    - Google’da gezinerek sayfalardan linkleri toplar

17. **Github Dorking**
    - Gist Github jaddix Github-Dorks
    

18. **Search Terminal**
    - Find
    - Vim
    - Grep

graph TD
  A[Bug Hunting Metodolojisi]

  A1[Find Domain (Domain Bulma)]
  A2[Find Subdomain (Alt Domain Bulma)]
  A3[Subdomain Takeover (Alt Domain Ele Geçirme)]
  A4[Find URL (URL Bulma)]
  A5[Live URL (Aktif URL Kontrolü)]
  A6[Port Analysis (Port Analizi)]
  A7[Service Scan (Servis Taraması)]
  A8[Service Brute Force (Servis Brute Force)]
  A9[Screenshots (Web Sayfası Görsellerini Alma)]
  A10[URL Header - Body Info (URL Header ve Body Bilgisi Analizi)]
  A11[File Credential Info (Credential Bilgisi Bulma)]
  A12[Sorting (Sıralama İşlemi)]
  A13[404 Handling (404 Hataları İçin)]
  A14[Inscope (Yetkili Bilgi Toplama)]
  A15[Github Repo Copy (Github Repo Kopyalama)]
  A16[Webpaste (Google Üzerinden Bilgi Toplama)]
  A17[Github Dorking]
  A18[Search Terminal]

  A --> A1
  A --> A2
  A --> A3
  A --> A4
  A --> A5
  A --> A6
  A --> A7
  A --> A8
  A --> A9
  A --> A10
  A --> A11
  A --> A12
  A --> A13
  A --> A14
  A --> A15
  A --> A16
  A --> A17
  A --> A18

  A1 --> |Cache Base| A1a
  A1 --> |bgr.bne.net| A1b
  A1 --> |nslookup| A1c
  A1 --> |Metabigor| A1d
  A1 --> |Amass Intel - ASN| A1e
  A1 --> |Domnlink Tool| A1f
  A1 --> |Jet.relationships.PT| A1g
  A1 --> |Shodan| A1h
  A1 --> |Findomain| A1i
  A1 --> |getrelationship.py| A1j
  A1j --> |echo "uber.com" | getrelationship.py| A1k
  A1 --> |Benzer Domainleri Bulmak İçin: Threatcrowd| A1l
  A1 --> |"© 2019 Twitch Interactive , Inc." inurl:twitch| A1m

  A2 --> |Burp Suite Spider| A2a
  A2 --> |Hakrawler| A2b
  A2 --> |GoSpider| A2c
  A2 --> |Amass| A2d
  A2 --> |Subfinder| A2e
  A2 --> |Shosubgo| A2f
  A2 --> |Curl Buffer-Ower.Run| A2g
  A2 --> |fovicon to hash| A2h
  A2 --> |assetfinder| A2i

  A3 --> |Subover| A3a
  A3 --> |Nuclei| A3b

  A4 --> |Katana| A4a
  A4 --> |Waybackurls| A4b
  A4 --> |Burp Suite (Sitemap)| A4c

  A5 --> |Httpx| A5a
  A5 --> |httprobe| A5b

  A6 --> |Masscan| A6a
  A6 --> |DnMasscan| A6b

  A7 --> |Nmap Service Scan -oG| A7a

  A8 --> |Brutespray (Nmap çıktısı ile çalışır)| A8a

  A9 --> |Eyewitness| A9a
  A9 --> |Httpscreenshot| A9b
  A9 --> |Aquatone| A9c

  A10 --> |FFF| A10a
  A10 --> |HTML-Tool| A10b

  A11 --> |GF| A11a

  A12 --> |Anew| A12a
  A12 --> |Tee -a| A12b

  A13 --> |Fuff config dosyaları| A13a

  A14 --> |Sadece domeine ait bilgileri topla| A14a

  A15 --> |Ghcopy| A15a
  A15 --> |Gitdump (Eski commitleri bul)| A15b
  A15 --> |GitObject| A15c

  A16 --> |Google’da gezinerek sayfalardan linkleri toplar| A16a

  A17 --> |Gist Github jaddix Github-Dorks| A17a

  A18 --> |Find| A18a
  A18 --> |Vim| A18b
  A18 --> |Grep| A18c
