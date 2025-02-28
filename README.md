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


