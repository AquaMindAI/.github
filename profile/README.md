# 🌊 AquaMind AI — Ağıllı Akvakültür və Akvaponika Ekosistemi

<p align="center">
  <img src="https://raw.githubusercontent.com/AquaMindAI/AquaMindAI.github.io/main/AquaMind-AI.png" alt="AquaMind AI Logo" width="220" />
</p>

<p align="center">
  <strong>Real-vaxtlı IoT Telemetriyası və Süni İntellekt Əsaslı Su Ekosistemi Monitorinq Platforması</strong><br>
  <em>Next-Generation Real-Time IoT & Artificial Intelligence Platform for Smart Aquaculture & Aquaponics</em>
</p>

<p align="center">
  <a href="https://aquamindai.github.io"><img src="https://img.shields.io/badge/Canlı%20Veb%20Sayt-aquamindai.github.io-0284c7?style=for-the-badge&logo=githubpages&logoColor=white" alt="Live Demo" /></a>
  <img src="https://img.shields.io/badge/Status-Aktiv%20İstehsalat-22c55e?style=for-the-badge" alt="Status" />
  <img src="https://img.shields.io/badge/Məkan-Bakı%2C%20Azərbaycan-blue?style=for-the-badge" alt="Location" />
  <img src="https://img.shields.io/badge/Lisenziya-Apache%202.0-orange?style=for-the-badge" alt="License" />
</p>

---

## 📌 Haqqında (About)

**AquaMind AI**, Azərbaycan Respublikasında müasir intensiv qapalı su dövriyyəli təsərrüfatlar (RAS — *Recirculating Aquaculture Systems*) və inteqrasiya olunmuş akvaponika kompleksləri üçün hazırlanmış real vaxtlı monitorinq, risk qiymətləndirməsi və maşın öyrənməsi platformasıdır.

Sistem su mühitinin kritik fiziki-kimyəvi parametrlərini fasiləsiz analiz edir, anomaliyaları erkən aşkar edir və süni intellekt vasitəsilə qabaqlayıcı qərarlar təklif edir.

---

## 🏛️ Təşkilatın Əsas Repozitoriyaları (Repositories)

| Repozitoriya | Növü | Təsvir | Texnologiyalar |
| :--- | :---: | :--- | :--- |
| **[`AquaMindAI.github.io`](https://github.com/AquaMindAI/AquaMindAI.github.io)** | `Public` 🌍 | **Rəsmi Veb Tətbiq & Canlı İdarəetmə Paneli**: Real vaxtlı telemetriya, hovuz seçimləri, stress simulyasiyası və AI xəbərdarlıq sistemi. | Next.js 14, Tailwind CSS, TypeScript, Recharts, GitHub Pages |
| **[`AquaMindAI`](https://github.com/AquaMindAI/AquaMindAI)** | `Private` 🔒 | **Əsas Monorepo**: FastAPI REST API, MySQL verilənlər bazası, Random Forest / Isolation Forest modelləri, ESP32 mikrokontroler proqramı, Streamlit analitika və elmi nəşrlər. | Python 3.11, FastAPI, Scikit-Learn, Docker Compose, C++ (Arduino/ESP32), MySQL |

---

## 🔬 Əsas Texnoloji Komponentlər

### 1. IoT Sensor Şəbəkəsi (Hardware & Firmware)
* **DS18B20:** Rəqəmsal yüksək dəqiqlikli su temperaturu sensoru ($\pm 0.5^\circ\text{C}$).
* **HC-SR04:** Ultrasəs su səviyyəsi və sızma monitorinqi sensoru.
* **DHT22:** Ətraf mühit hava temperaturu və nisbi rütubət sensoru.
* **DO & pH:** Həll olunmuş oksigen və turşuluq-qələvilik dərəcəsi indikatorları.
* **Mikrokontroler:** ESP32 / Arduino (Wi-Fi / MQTT / REST telemetriya axını).

### 2. Süni İntellekt və Analitika (Machine Learning Engine)
* **Random Forest Regressor:** Sutkalıq günəş/istilik dövriyyəsi və gecikmə xüsusiyyətləri (*lag features*) əsasında su temperaturunun $+1$, $+3$ və $+6$ saatlıq qabaqlayıcı proqnozu ($R^2 \ge 0.94$).
* **Isolation Forest:** Çoxölçülü sensor kəsişmələrində nəzarətsiz (*unsupervised*) anomaliya və qəza aşkarlanması.
* **0–100 Dinamik Ekosistem Sağlamlıq İndeksi:** Balıq növünün optimal bioloji hədlərinə uyğunlaşdırılmış real vaxt keyfiyyət skoru.

### 3. Dəstəklənən Bioloji Hovuz Profilləri
* **Kür Nərəsi (*Acipenser gueldenstaedtii*):** Optimal $20\text{--}26^\circ\text{C}$, yüksək oksigen tələbatı.
* **Nil Tilapiyası (*Oreochromis niloticus*):** Optimal $25\text{--}30^\circ\text{C}$, sürətli metabolizm.
* **Göyqurşağı Foreli (*Oncorhynchus mykiss*):** Optimal $14\text{--}18^\circ\text{C}$, soyuq dağ suları.

---

## 🌐 Rəsmi Keçidlər & Əlaqə

* **Canlı Veb Sayt:** [https://aquamindai.github.io](https://aquamindai.github.io)
* **Təşkilat:** [AquaMind AI Organization](https://github.com/AquaMindAI)
* **Müəllif & Rəhbər:** [Suleyman Hajizadeh](https://github.com/SuleimanHajizadeh)
* **Məkan:** Bakı, Azərbaycan Respublikası
