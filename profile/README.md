# AquaMind AI: Ağıllı Akvakultura və Akvaponika Platforması

<p align="center">
  <img src="https://raw.githubusercontent.com/AquaMindAI/AquaMindAI.github.io/main/AquaMind-AI.png" alt="AquaMind AI Logo" width="220" />
</p>

<p align="center">
  <strong>Real vaxtlı IoT telemetriyası və süni intellekt əsaslı su ekosistemi monitorinq platforması</strong><br>
  <em>Real-Time IoT & Artificial Intelligence Platform for Smart Aquaculture & Aquaponics</em>
</p>

<p align="center">
  <a href="https://aquamindai.github.io"><img src="https://img.shields.io/badge/Canlı%20Veb%20Sayt-aquamindai.github.io-0284c7?style=flat-square" alt="Live Demo" /></a>
  <img src="https://img.shields.io/badge/Tədqiqat%20Dataları-Private-ef4444?style=flat-square" alt="Private Data" />
  <a href="mailto:suleyman.hacizade1@gmail.com"><img src="https://img.shields.io/badge/Giriş%20Müraciəti-suleyman.hacizade1%40gmail.com-22c55e?style=flat-square" alt="Email Access" /></a>
  <img src="https://img.shields.io/badge/Məkan-Bakı%2C%20Azərbaycan-blue?style=flat-square" alt="Location" />
</p>

---

> ### Məlumatların Məxfiliyi və Giriş İcazəsi (Private Data & Access Request)
> Bu təşkilatın əsas tədqiqat dataları, eksperimental telemetriya bazası, maşın öyrənməsi modelləri, mikrokontroller proqram təminatı və tam mənbə kodu (`AquaMindAI` monorepo) məxfidir (`Private`).
>
> Akademik tədqiqat, elmi rəy (peer-review), tərəfdaşlıq və ya məxfi repozitoriyalara və datalara giriş icazəsi (access) əldə etmək üçün rəsmi elektron poçt ünvanları vasitəsilə müraciət edə bilərsiniz:
> - Əsas elektron poçt: [suleyman.hacizade1@gmail.com](mailto:suleyman.hacizade1@gmail.com)
> - Akademik elektron poçt: [suleyman.hacizade.232bioing@wcu.edu.az](mailto:suleyman.hacizade.232bioing@wcu.edu.az)

---

## Haqqında

AquaMind AI, qapalı su dövriyyəli balıqçılıq təsərrüfatları (RAS — Recirculating Aquaculture Systems) və inteqrasiya olunmuş akvaponika kompleksləri üçün hazırlanmış telemetriya, risk analizi və proqnozlaşdırma sistemidir.

Platforma su mühitinin fiziki-kimyəvi parametrlərini real vaxt rejimində təhlil edir, anomaliyaları erkən mərhələdə müəyyənləşdirir və maşın öyrənməsi modelləri ilə temperatur və oksigen risklərini qabaqcadan proqnozlaşdırır.

---

## Təşkilatın Repozitoriyaları

| Repozitoriya | Status | Təsvir | Texnoloji Baza |
| :--- | :---: | :--- | :--- |
| [`AquaMindAI.github.io`](https://github.com/AquaMindAI/AquaMindAI.github.io) | Public | Rəsmi veb tətbiq və canlı idarəetmə paneli: real vaxt telemetriyası, hovuz seçimləri, stress simulyasiyası və analitika. | Next.js 14, Tailwind CSS, TypeScript, Recharts, GitHub Pages |
| [`AquaMindAI`](https://github.com/AquaMindAI/AquaMindAI) | Private | Əsas monorepo: FastAPI arxitekturası, MySQL verilənlər bazası, Random Forest / Isolation Forest modelləri, Arduino/ESP32 firmware, Streamlit analitika paneli və elmi nəşr materialları. *(Giriş üçün müraciət edin)* | Python 3.11, FastAPI, Scikit-Learn, Docker Compose, C++ (Arduino/ESP32), MySQL |

---

## Texnoloji Komponentlər

### 1. IoT Sensor Şəbəkəsi (Hardware və Firmware)
- DS18B20: Rəqəmsal yüksək dəqiqlikli su temperaturu sensoru (±0.5°C).
- HC-SR04: Ultrasəs su səviyyəsi və sızma monitorinqi sensoru.
- DHT11 / DHT22: Ətraf mühit hava temperaturu və nisbi rütubət sensoru.
- DO və pH: Həll olunmuş oksigen və turşuluq dərəcəsi indikatorları.
- Mikrokontroller: Arduino Uno (ATmega328P) və ESP32 (UART və REST telemetriya axını).

### 2. Süni İntellekt və Analitika Mühərriki
- Random Forest Regressor: Sutkalıq temperatur dövriyyəsi və gecikmə xüsusiyyətləri (lag features) əsasında suyun temperaturunun 1, 3 və 6 saatlıq qabaqlayıcı proqnozu.
- Isolation Forest: Çoxölçülü sensor oxunuşlarında anomaliya və qəza şəraitinin nəzarətsiz aşkarlanması.
- Dinamik Sağlamlıq İndeksi (0–100): Balıq növünün optimal bioloji hədlərinə uyğunlaşdırılmış keyfiyyət qiymətləndirilməsi.

### 3. Dəstəklənən Bioloji Hovuz Profilləri
- Kür Nərəsi (*Acipenser gueldenstaedtii*): Optimal 20–26°C, yüksək oksigen tələbatı.
- Nil Tilapiyası (*Oreochromis niloticus*): Optimal 25–30°C, sürətli metabolizm.
- Göyqurşağı Foreli (*Oncorhynchus mykiss*): Optimal 14–18°C, soyuq su mühiti.

---

## Əlaqə və Giriş Müraciəti

- Canlı Veb Sayt: [https://aquamindai.github.io](https://aquamindai.github.io)
- Təşkilat: [AquaMind AI Organization](https://github.com/AquaMindAI)
- Müəllif: [Süleyman Hacızadə](https://github.com/SuleimanHajizadeh) (Qərbi Kaspi Universiteti)
- E-poçt: [suleyman.hacizade1@gmail.com](mailto:suleyman.hacizade1@gmail.com) | [suleyman.hacizade.232bioing@wcu.edu.az](mailto:suleyman.hacizade.232bioing@wcu.edu.az)
- Məkan: Bakı, Azərbaycan
