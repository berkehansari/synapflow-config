# Privacy Policy for SynapFlow / SynapFlow Gizlilik Politikası

**Effective Date / Yürürlük Tarihi:** November 1, 2026  
**Application Name / Uygulama Adı:** SynapFlow  
**Developer / Geliştirici:** Berkehan Sarı  

---

## 🇬🇧 ENGLISH VERSION

### 1. Overview and Privacy First Commitment
**SynapFlow** ("the Application"), developed by **Berkehan Sarı** ("the Developer"), is built with a strict **Offline-First and Privacy-By-Design** architecture. We do not collect, transmit, store, sell, or share any of your personal data, focus logs, or behavioral analytics on external servers. All data generated while using SynapFlow remains exclusively on your local device.

### 2. Data Stored Locally on Your Device
To provide its core cognitive tracking and gamification features, SynapFlow stores the following operational data locally on your device using encrypted/sandboxed system storage (`AsyncStorage`):
* **Focus & Session Telemetry:** Timer logs, focus duration, break duration, focus purity percentages, distraction reasons, and daily heatmap history.
* **Gamification & Progression:** Earned XP, current rank/level, unlocked achievement badges, and daily streak counts.
* **User Preferences & Custom Content:** Language selection, timer divisors, custom focus categories, parked context notes (Zeigarnik notes), daily micro-goals (To-Do items), and pinned exam/milestone countdowns.

**Important:** None of this data leaves your device unless you explicitly export a backup file (`.json`) or share a visual Focus Card (`.png`) using your device's native sharing menu.

### 3. Network Access & External Requests
SynapFlow operates offline by default. The only external network request made by the Application is a read-only fetch to retrieve the public, static exam calendar configuration (`exams.json` hosted via GitHub Raw Content) to keep public exam dates up to date. During this request:
* No user identifiers, device IDs, location data, or personal information are transmitted by the Application.

### 4. Device Permissions Used
SynapFlow requests only the minimum technical permissions required for core functionality:
* **Local Notifications (`POST_NOTIFICATIONS` / Scheduled Alarms):** Used solely to alert you locally when a focus target is reached, when a break ends, when your 5-minute Focus Shield is fully recharged, or when a pinned exam deadline approaches.
* **Wake Lock / Keep Screen Awake (`WAKE_LOCK`):** Used optionally during active focus sessions to prevent the screen from dimming while the timer cockpit or OLED Zen Mode is open.
* **Audio Playback & Foreground Service:** Used to play synthesized ambient focus sounds (Brown Noise, 40Hz Gamma Rhythm, Cosmic Drone) and timer completion alerts while your screen is locked or the app is in the background. SynapFlow **never** accesses your microphone or records audio.
* **Vibration / Haptics (`VIBRATE`):** Used to provide tactile feedback for buttons and timer phase transitions.

### 5. Third-Party SDKs, Advertising, and Analytics
* **Zero Ads:** SynapFlow contains no third-party advertising SDKs.
* **Zero Tracking:** SynapFlow does not use third-party behavioral tracking, profiling, or analytics services (such as Google Analytics, Firebase Analytics, or Meta SDK).

### 6. Data Retention and Deletion (Your Control)
Because all data is stored locally on your device, you have 100% control over its retention and deletion at any time:
1. **In-App Factory Reset:** You can permanently erase all recorded sessions, XP, badges, and settings immediately by navigating to **Settings -> Data & Backup -> Reset All Data (Factory Reset)** inside the Application.
2. **Uninstalling the Application:** Uninstalling SynapFlow from your device automatically and permanently deletes all local application data from your device storage.

### 7. Children's Privacy
SynapFlow does not knowingly collect any personal information from anyone, including children under the age of 13 (or the applicable age of digital consent in your jurisdiction). All features operate locally on the user's device.

### 8. Changes to This Privacy Policy
If we update this Privacy Policy to reflect new features, we will update the "Effective Date" at the top of this document. Continued use of the Application after any modifications constitutes acceptance of the updated Privacy Policy.

### 9. Contact Us
If you have any questions or concerns regarding this Privacy Policy or SynapFlow's privacy practices, please contact the Developer at:
* **Developer:** Berkehan Sarı
* **Email:** studiolunarts@gmail.com

---

## 🇹🇷 TÜRKÇE SÜRÜM

### 1. Genel Bakış ve Gizlilik Taahhüdü
**Berkehan Sarı** ("Geliştirici") tarafından geliştirilen **SynapFlow** ("Uygulama"), **Çevrimdışı Öncelikli (Offline-First)** ve **Tasarımdan İtibaren Gizlilik** mimarisiyle inşa edilmiştir. Kişisel verilerinizi, odaklanma kayıtlarınızı veya kullanım istatistiklerinizi hiçbir harici sunucuda toplamaz, saklamaz, işlemez, satmaz ve üçüncü taraflarla paylaşmayız. Uygulama içinde oluşan tüm veriler yalnızca kendi cihazınızda yerel olarak barındırılır.

### 2. Cihazınızda Yerel Olarak Saklanan Veriler
SynapFlow; sayaç, analiz ve oyunlaştırma özelliklerini sunabilmek için aşağıdaki verileri yalnızca cihazınızın güvenli uygulama belleğinde (`AsyncStorage`) yerel olarak tutar:
* **Odak ve Oturum Verileri:** Çalışma süreleri, mola süreleri, odak saflığı yüzdeleri, dikkat dağılma sebepleri ve 84 günlük ısı haritası geçmişi.
* **Gelişim ve Başarım Verileri:** Kazanılan XP, mevcut seviye/rütbe, açılan başarım rozetleri ve günlük seri sayıları.
* **Kullanıcı Tercihleri:** Dil seçimi, mola böleni ayarları, özel kategoriler, bağlam notları, günlük hedefler (To-Do) ve sabitlenen sınav/hedef geri sayımları.

**Önemli:** Bu verilerin hiçbiri, siz kendi isteğinizle yedekleme dosyası (`.json`) dışa aktarmadığınız veya Odak Kartı (`.png`) paylaşmadığınız sürece cihazınızdan dışarı çıkmaz.

### 3. Ağ Erişimi ve Harici İstekler
SynapFlow varsayılan olarak internet bağlantısına ihtiyaç duymadan çalışır. Uygulamanın yaptığı tek ağ isteği, genel sınav takvimini güncel tutmak amacıyla herkese açık statik `exams.json` dosyasını (GitHub Raw üzerinden) okumaktır. Bu işlem sırasında cihazınızdan hiçbir kişisel veri veya kimlik bilgisi gönderilmez.

### 4. Kullanılan Cihaz İzinleri
Uygulama yalnızca temel işlevlerin çalışması için gerekli minimum sistem izinlerini kullanır:
* **Yerel Bildirimler (`POST_NOTIFICATIONS`):** Odak süresi dolduğunda, mola bittiğinde, 5 dakikalık Dikkat Kalkanı şarj olduğunda veya sabitlenen sınav tarihi yaklaştığında cihaz içinde bildirim göndermek için kullanılır.
* **Ekranı Açık Tutma (`WAKE_LOCK`):** Odak oturumu veya OLED Zen Modu aktifken ekranın kapanmasını önlemek için kullanılır.
* **Ses Çalma ve Arka Plan Ses Desteği:** Dahili olarak sentezlenen odak ambiyans seslerini (Kahverengi Gürültü, 40Hz Gama Ritim, Uzay Kabini) ve sayaç uyarılarını ekran kilitliyken çalabilmek için kullanılır. Uygulama mikrofonunuza **asla** erişmez ve ses kaydı yapmaz.
* **Titreşim (`VIBRATE`):** Buton etkileşimleri ve faz geçişlerinde dokunsal geri bildirim (haptics) sağlamak için kullanılır.

### 5. Üçüncü Taraf Yazılımlar, Reklam ve Takip
* **Sıfır Reklam:** SynapFlow içinde hiçbir reklam ağı veya reklam SDK'sı bulunmaz.
* **Sıfır Analitik Takibi:** Uygulama içinde kullanıcı davranışlarını izleyen üçüncü taraf takip araçları (Google Analytics, Firebase, Meta SDK vb.) kullanılmaz.

### 6. Verilerin Saklanması ve Silinmesi
Tüm veriler yalnızca cihazınızda tutulduğu için verileriniz üzerinde tam kontrole sahipsiniz:
1. **Uygulama İçi Sıfırlama:** Uygulama içindeki **Ayarlar -> Veri & Yedekleme -> Tüm Verileri Sıfırla (Fabrika Ayarları)** seçeneğini kullanarak tüm geçmişinizi ve istatistiklerinizi anında kalıcı olarak silebilirsiniz.
2. **Uygulamayı Kaldırma:** SynapFlow uygulamasını cihazınızdan sildiğinizde, yerel bellekteki tüm veriler işletim sistemi tarafından otomatik ve kalıcı olarak silinir.

### 7. Çocukların Gizliliği
SynapFlow, 13 yaşın altındaki çocuklar dahil olmak üzere hiçbir kullanıcıdan kişisel veri toplamaz.

### 8. İletişim
Bu Gizlilik Politikası ile ilgili her türlü soru ve görüşünüz için geliştiriciyle iletişime geçebilirsiniz:
* **Geliştirici:** Berkehan Sarı
* **E-posta:** studiolunarts@gmail.com
