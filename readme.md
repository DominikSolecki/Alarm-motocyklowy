# Alarm motocyklowy - LTE, BLE, STM32 & ATtiny85

System zabezpieczeń motocyklowych z bardzo niskim poborem prądu (700µA).

## 🚀 Zobacz stronę projektu
Strona wizualna z opisem i zdjęciami: 
👉 **[KLIKNIJ TUTAJ](https://dominiksolecki.github.io/Alarm-motocyklowy/)**

## 🛠️ Technologie i Podzespoły
* **MCU:** STM32F401RET6 (Jednostka centralna) & ATtiny85 (Pilot)
* **Łączność:** Moduł LTE A7682E (SMS), Bluetooth AT-09 (Aplikacja BLE)
* **Sensory:** Akcelerometr LIS2DW12 (wykrywanie ruchu w 3 osiach)
* **Zasilanie:** Optymalizacja pod kątem akumulatora 12V i baterii CR2032
* **Kodowanie:** KEELOQ + Rolling Code (pilot)

## 📝 Funkcje systemu
- Powiadomienia SMS o alarmie i stanie akumulatora.
- Konfiguracja parametrów przez dedykowaną aplikację Bluetooth.
- Inteligentne wybudzanie procesora (Duty cycle 500ms/50ms).
- Zabezpieczenie przed nieautoryzowanym dostępem (kodowanie BLE).

---
*Projekt stworzony przez: Dominik Sołecki*
