# SOC Security Simulation Projects

Bu repository, **Blue Team Uygulamalı Eğitim Serisi** kapsamında gerçekleştirilen projeleri içerir. Amaç, katılımcıların gerçek dünyadaki siber saldırıları analiz etme ve tehdit tespiti becerilerini geliştirmektir.

---

## 🗂 Projeler ve İçerikleri

### 1. E-Posta Güvenliği ve Header Analizi
- **Amaç:** Şüpheli e-postaların header analizi ve IoC çıkarımı ile tehdit seviyesini belirlemek.  
- **Yapılanlar:**  
  - 5 farklı şüpheli e-posta seçildi ve detaylı header analizi yapıldı.  
  - SPF, DKIM ve DMARC doğrulamaları gerçekleştirildi.  
  - Gönderici IP ve domainler AbuseIPDB, VirusTotal gibi kaynaklarla sorgulandı.  
  - Relay zinciri ve zaman çizelgesi görselleştirildi.  
  - IoC tespit edildi ve SIEM sorguları için örnekler hazırlandı.  

### 2. LOLBAS Analizleri
- **Amaç:** Saldırganların sistemde var olan araçları kötüye kullanma yöntemlerini anlamak.  
- **Yapılanlar:**  
  - En az 10 farklı LOLBAS örneği incelendi.  
  - Kullanım amacı, saldırı senaryoları ve log görünürlüğü değerlendirildi.  

### 3. Windows Log Analizi
- **Amaç:** Windows Security, Sysmon ve PowerShell logları üzerinden saldırı davranışlarını tespit etmek.  
- **Yapılanlar:**  
  - Security Event ID’leri (4624, 4625, 4673, 4688, 4697, 4720, 1102) analiz edildi.  
  - Sysmon Event ID’leri (1, 3, 7, 11, 13, 22) ile ağ ve dosya aktiviteleri incelendi.  
  - PowerShell logları (4103, 4104, 4688) üzerinden script ve komut davranışları takip edildi.  
  - Her Event ID için MITRE ATT&CK teknikleri ile eşleştirme yapıldı.  

### 4. DFIR Report Analizi
- **Amaç:** Gerçek saldırı raporları üzerinden IoC çıkarımı ve SIEM entegrasyonu pratiği yapmak.  
- **Yapılanlar:**  
  - Seçilen rapordan en az 10 IoC çıkarıldı.  
  - IoC’ler ilgili log kaynakları ile eşleştirildi ve SIEM sorgu örnekleri hazırlandı.  
  - Threat Intelligence platformları üzerinden doğrulama gerçekleştirildi.  
  - MITRE ATT&CK teknikleri ile eşleştirme yapıldı.  

---

## 🛠 Kullanılan Araçlar ve Teknolojiler
- **Log ve Analiz:** Sysmon, Windows Event Log, PowerShell  
- **SIEM ve Ağ Analizi:** Splunk SIEM, Wireshark  
- **Saldırı ve Test Araçları:** Atomic Red Team, LOLBAS, YARA, Sigma kuralları  
- **Diğer:** Draw.io, Lucidchart (zaman çizelgesi ve görselleştirme için)  

---

## 📁 Dosya Yapısı

