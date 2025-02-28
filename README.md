# mindmaps

Mermaid kullanarak bir akış diyagramı oluştur. Ana başlık "Bug Hunting Metodolojisi" olacak. Diyagram aşağıdaki gibi hiyerarşik bir yapıya sahip olmalı:

1. **Find Domain** (Domain Bulma)
   - Cache Base
   - bgr.bne.net
   - Snlookup
   - Metabigor
   - Amass Intel - ASN
   - Domaink Tool
   - Jet.relationships.PT
   - Shodan
   - Findomain
   - Benzer Domainleri Bulmak İçin: Threatcrowd

2. **Find Subdomain** (Alt Domain Bulma)
   - Burp Suite Spider
   - Hakrawler
   - GeSpider
   - Amass
   - Subfinder
   - Shosubgo
   - Curl Buffer-Owner.Run

3. **Subdomain Takeover** (Alt Domain Ele Geçirme)
   - Subover
   - Nuclei

4. **Find URL** (URL Bulma)
   - Kohza
   - Waybackurls
   - Burp Suite (Sitemap)

5. **Live URL** (Aktif URL Kontrolü)
   - Httpx
   - Probe

6. **Port Analysis** (Port Analizi)
   - Masscan
   - DnsMasscan

7. **Service Scan** (Servis Taraması)
   - Nmap Service Scan
   - OG

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
    - Tee -2

13. **404 Handling** (404 Hataları İçin)
    - Fuff config dosyaları

14. **Inscope** (Yetkili Bilgi Toplama)
    - Sadece deneme yetkili bilgileri topla

15. **Github Repo Copy** (Github Repo Kopyalama)
    - Ghrepo
    - Gitdump (Eski commitleri bul)
    - GitObject

16. **Webpaste** (Google Üzerinden Bilgi Toplama)
    - Google’da gezinerek sayfalardan linkleri toplar

17. **Github Dorking**
    - Gist Github
    - Gdalik
    - Github-Dorks

18. **Log ve Arama İşlemleri**
    - Find
    - Vim
    - Grep

Diyagram, hiyerarşik bir ağaç yapısında olmalı. Ana başlık "Bug Hunting Metodolojisi" olacak ve alt başlıklar yukarıdaki sırayla dallanacak.
