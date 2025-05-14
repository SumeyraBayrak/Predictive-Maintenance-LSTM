# 📊 Proje: Üretim Makinelerinde Bakım İhtiyacı Tahmini

## 👩‍💻 1. Giriş

### 🎯 Proje Amacı

Bu projenin temel amacı, üretim makinelerine ait sensör verilerini analiz ederek,  
makinelerin bakım gerektirip gerektirmediğini tahmin eden bir **makine öğrenmesi modeli** geliştirmektir.

---

## 📁 2. Veri Seti Hakkında

### 📌 Kullanılan Veri Seti

**Smart Manufacturing IoT-Cloud Monitoring Dataset**

### 📄 Veri Seti İçeriği

#### 🔧 Sensör Verileri:
- 🌡️ **Sıcaklık (Temperature)**
- 📳 **Titreşim (Vibration)**
- 💧 **Nem (Humidity)**
- 🧯 **Basınç (Pressure)**
- ⚡ **Enerji Tüketimi (Energy Consumption)**

#### ⚙️ Makine Durumu:
- 💤 **Idle (Boşta)**
- 🏃 **Running (Çalışıyor)**
- ❌ **Failure (Arızalı)**

#### 🎯 Etiket (Target):
- **Maintenance Required**
  - `1` : Bakım Gerekli
  - `0` : Bakım Gerekli Değil
