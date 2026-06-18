# Gizlilik Politikası

Bu gizlilik politikası, Portal+ for Hattrick Portal adlı tarayıcı uzantısının hangi verileri topladığını, bu verileri nasıl kullandığını ve kullanıcı olarak hangi haklara sahip olduğunuzu açıklar. Son güncelleme: 18 Haziran 2026.

## Veri Toplama Kategorileri (Mozilla AMO)

Bu uzantı Mozilla'nın tarayıcı eklenti veri sınıflandırmasına göre aşağıdaki kategorilerde veri toplar. Firefox kurulum ekranında bu bilgiler `data_collection_permissions` bildirimiyle kullanıcıya sunulur ve opsiyonel olarak devre dışı bırakılabilir.

**Kişisel Veriler (Personal Data — opsiyonel):** Yalnızca ekip işbirliği özellikleri için hesap açtığınızda toplanır. Hesap açmadan uzantının tüm temel özelliklerini kullanabilirsiniz.

* `authenticationInfo`: Kayıt için kullandığınız Hattrick kullanıcı adı veya e-posta adresiniz ve parolanız (Firebase tarafından şifrelenmiş, uzantı tarafından görülmez)
* `personallyIdentifyingInfo`: Hesap kimliğiniz (UID), üyesi olduğunuz ekiplerin kodları, ekip hatırlatıcılarında paylaştığınız oyuncu numaraları
* `personalCommunications`: Ekip ile paylaştığınız hatırlatıcı, not, duyuru içerikleriniz ve hatırlatıcı yanıtlarınız
* `websiteContent`: Hattrick Portal sayfalarından okunan ve ekip ile paylaştığınız oyuncu yetenek değerleri ve kısa liste bilgileri

**Teknik ve Etkileşim Verileri (Technical & Interaction Data):** Toplanmaz. Uzantı hiçbir analitik, telemetri, çökme raporu veya kullanım izleme aracı kullanmaz.

Hesap açtığınızda gizlilik politikasını kabul ettiğiniz tarihi `consentAcceptedAt` alanında denetim amacıyla saklarız. Bu bilgi KVKK/GDPR kapsamında onay kanıtı olarak kullanılır ve sonradan değiştirilemez.

## Toplanan Veriler

Uzantı verileri iki yerde tutar: kendi cihazınızda yerel olarak ve ekip özellikleri için bulutta.

### Cihazınızda Saklanan Veriler

Aşağıdaki bilgiler yalnızca tarayıcınızın kendi depolama alanında tutulur ve hiçbir sunucuya gönderilmez:

* Uzantı ayarlarınız (koyu tema, liste vurguları, sütun sıralaması ve görünürlüğü)
* Antrenman hesaplayıcısına girdiğiniz ve gördüğünüz sonuçlar
* Sezon takvimindeki seçimleriniz ve kısa listenizdeki oyuncular
* Kişisel notlarınız ve kişisel hatırlatıcılarınız
* Hattrick Portal sayfalarından okunan oyuncu bilgileri

Uzantıyı kaldırdığınızda bu verilerin tamamı silinir.

### Bulutta Saklanan Veriler

Ekip işbirliği özelliklerini kullanmak isterseniz bir hesap açmanız gerekir. Bu tamamen isteğe bağlıdır. Hesap açmadan uzantının diğer tüm özelliklerini kullanabilirsiniz.

Hesap oluşturduğunuzda aşağıdaki bilgiler Google Firebase hizmeti üzerinden saklanır:

* Giriş için kullandığınız Hattrick kullanıcı adınız veya e-posta adresiniz
* Profilinizdeki kullanıcı adınız
* Üyesi olduğunuz ekipler ve ekip kodları
* Ekip ile paylaştığınız hatırlatıcılar (başlık, içerik, tarih, oyuncu numaraları ve antrenman türü tercihleri)
* Ekip notları (başlık ve içerik)
* Ekip duyuruları
* Ekip ile paylaştığınız kısa liste oyuncuları
* Hesabınıza ilişkin bildirim kayıtları ve hatırlatıcı yanıtlarınız

Giriş parolanız Google Firebase tarafından şifrelenmiş biçimde saklanır ve uzantı tarafından hiçbir aşamada görülmez.

## Veriler Nasıl Kullanılır

Toplanan veriler yalnızca uzantının sunduğu özellikleri çalıştırmak için kullanılır. Hedefli reklam gösterilmez, pazarlama amacıyla profil çıkarılmaz, kullanıcı davranışları izlenmez ve istatistiksel analiz yapılmaz. Verileriniz reklam veya pazarlama amacıyla üçüncü kişilere satılmaz veya paylaşılmaz.

## Üçüncü Taraf Hizmetleri

Uzantı ekip özellikleri için yalnızca Google Firebase hizmetlerini kullanır:

* Firebase Authentication, hesap oluşturma ve giriş işlemleri için
* Cloud Firestore, ekip verilerinin saklanması için

Bu hizmetler Google gizlilik politikasına tabidir. Uzantı, Firebase ile yalnızca kimlik doğrulama ve ekip verileri için haberleşir. Analiz, izleme, çerez veya reklam amaçlı başka bir araç kullanılmaz.

## Tarayıcı İzinleri

Uzantının çalışması için istediği izinler ve bunların kullanım amaçları şöyledir:

* **Depolama:** Ayarlarınızı ve verilerinizi cihazınızda tutmak için.
* **Bildirimler:** Oyuncu güncellemelerini ve hatırlatıcıları size göstermek için.
* **İndirme:** Tabloları CSV ve görüntü dosyası olarak kaydetmek için.
* **Sekmeler:** Yalnızca hattrickportal.online açık olan sekmeleri algılamak için.
* **Alarmlar:** Zamanlanmış bildirimleri belirli saatlerde tetiklemek için.
* **Yan panel:** Uzantı arayüzünü tarayıcının yan panelinde tutmak için.

Uzantı yalnızca hattrickportal.online sayfalarında çalışır. Diğer sitelerdeki gezinme geçmişinize, başka sekmelerin içeriğine veya site dışı kişisel verilerinize erişmez.

## Veri Güvenliği

Bulutta tutulan veriler Firebase güvenlik kurallarıyla korunur ve yalnızca yetkili kullanıcılar tarafından erişilebilir. Cihazınızdaki veriler tarayıcınızın kendi güvenlik sınırları içinde kalır. Hesap parolanız uzantı üzerinden değil doğrudan Firebase üzerinden iletilir ve doğrulanır.

## Kullanıcı Hakları

Hesabınız ve verilerinizle ilgili olarak şu haklara sahipsiniz:

* **Hesabı silme:** Uzantı arayüzü üzerinden hesabınızı kalıcı olarak silebilirsiniz. Bu işlem giriş kaydınızı, profilinizi ve ilişkili ekip verilerinizi kaldırır.
* **Ekipten ayrılma:** Üyesi olduğunuz bir ekipten istediğiniz zaman ayrılabilirsiniz.
* **Yerel verileri temizleme:** Uzantıyı kaldırdığınızda cihazınızdaki tüm yerel veriler otomatik silinir.
* **Verilerinize erişim:** Hesabınıza bağlı verilere uzantı arayüzü üzerinden ulaşabilirsiniz.

## Çocuklar

Uzantı, Hattrick'in hedef kitlesi olan yetişkin ve genç oyunculara yöneliktir. Kayıt formu 13 yaşını doldurduğunuza dair açık onay gerektirir; 13 yaşından küçüklerden bilerek kişisel veri toplanmaz.

Eğer bir çocuğun kişisel veri sağladığını düşünüyorsanız portalplussupport@gmail.com adresine bildirin. Bildirimi aldığımızda, COPPA ve GDPR Madde 8 uyumlu şekilde hesabı ve ilişkili tüm verileri derhal sileriz.

## İletişim

Bu gizlilik politikasıyla ilgili sorularınızı portalplussupport@gmail.com adresine iletebilirsiniz.

## Değişiklikler

Bu politika gerektiğinde güncellenebilir. Önemli değişiklikler uzantı içinde duyurulur. Politikanın yürürlükte olan sürümü her zaman bu sayfada yayınlanır.

---

# Privacy Policy (English)

This privacy policy explains what data the Portal+ for Hattrick Portal browser extension collects, how that data is used, and what rights you have as a user. Last updated: June 18, 2026.

## Data Collection Categories (Mozilla AMO)

This extension collects data in the following categories according to Mozilla's browser add-on data classification. This information is presented to the user in the Firefox installation prompt via the `data_collection_permissions` declaration and can be optionally disabled.

**Personal Data (optional):** Collected only when you create an account for the staff collaboration features. You can use all basic features of the extension without an account.

* `authenticationInfo`: The Hattrick username or email address you use to sign in, and your password (encrypted by Firebase, never seen by the extension)
* `personallyIdentifyingInfo`: Your account identifier (UID), the codes of staff groups you belong to, and player IDs you share in staff reminders
* `personalCommunications`: The reminders, notes, and announcement content you share with your staff group, and your responses to reminders
* `websiteContent`: Player skill values and shortlist information read from Hattrick Portal pages that you share with your staff group

**Technical & Interaction Data:** Not collected. The extension uses no analytics, telemetry, crash reporting, or usage tracking tools.

When you create an account, we store the date you accepted this privacy policy in the `consentAcceptedAt` field for audit purposes. This information is used as proof of consent under GDPR/equivalent regulations and cannot be modified afterward.

## About the Extension

Portal+ is a browser extension aimed at Hattrick players who use hattrickportal.online. It offers a dark theme, file export of tables, player update notifications, a training calculator, a season calendar, a player shortlist, and staff collaboration tools. The extension runs only on pages at hattrickportal.online.

## Data We Collect

The extension keeps data in two places: locally on your own device, and in the cloud for staff features.

### Data Stored on Your Device

The following information is kept only in your browser's own storage area and is never sent to any server:

* Your extension settings (dark theme, list highlights, column order and visibility)
* The results you enter and view in the training calculator
* Your selections in the season calendar and the players on your shortlist
* Your personal notes and personal reminders
* Player information read from Hattrick Portal pages

When you uninstall the extension, all of this data is deleted.

### Data Stored in the Cloud

Staff collaboration features require you to create an account. This is entirely optional. You can use every other feature of the extension without creating an account.

When you create an account, the following information is stored through Google Firebase:

* The Hattrick username or email address you use to sign in
* The username on your profile
* The staff groups you belong to and the staff codes
* Reminders you share with your staff group (title, content, dates, player IDs, and training type preferences)
* Staff notes (title and content)
* Staff announcements
* Shortlist players you share with your staff group
* Notification records related to your account and your responses to reminders

Your sign-in password is stored in encrypted form by Google Firebase and is never seen by the extension at any point.

## How Data Is Used

The collected data is used only to run the features the extension provides. No targeted advertising is shown, no behavioral profiling for marketing is done, no user behavior is tracked, and no statistical analysis is performed. Your data is not sold or shared with third parties for advertising or marketing purposes.

## Third-Party Services

The extension uses only Google Firebase services for staff features:

* Firebase Authentication, for account creation and sign-in
* Cloud Firestore, for storing staff data

These services are subject to Google's privacy policy. The extension communicates with Firebase only for authentication and staff data. No analytics, tracking, cookie, or advertising tool is used.

## Browser Permissions

The permissions the extension requests and what each one is used for:

* **Storage:** To keep your settings and data on your device.
* **Notifications:** To show player updates and reminders to you.
* **Downloads:** To save tables as CSV and image files.
* **Tabs:** To detect only the hattrickportal.online tabs that are open.
* **Alarms:** To trigger scheduled notifications at set times.
* **Side panel:** To keep the extension interface in the browser side panel.

The extension runs only on hattrickportal.online pages. It does not access your browsing history on other sites, the contents of other tabs, or personal data outside the site.

## Data Security

Data kept in the cloud is protected by Firebase security rules and can be accessed only by authorized users. Data on your device stays within your browser's own security boundaries. Your account password is sent and verified directly through Firebase, not through the extension.

## Your Rights

Regarding your account and your data, you have the following rights:

* **Account deletion:** You can permanently delete your account through the extension interface. This removes your sign-in record, your profile, and the related staff data.
* **Leaving a staff group:** You can leave any staff group you belong to at any time.
* **Clearing local data:** Uninstalling the extension automatically deletes all local data on your device.
* **Access to your data:** You can reach the data linked to your account through the extension interface.

## Children

The extension is aimed at the adult and teenage audience that Hattrick targets. The registration form requires affirmative confirmation that you are at least 13 years old; we do not knowingly collect personal data from children under 13.

If you believe a child has provided personal data, contact portalplussupport@gmail.com. Upon notification, we will promptly delete the account and all related data, in compliance with COPPA and GDPR Article 8.

## Contact

If you have questions about this privacy policy, you can reach us at portalplussupport@gmail.com.

## Changes

This policy may be updated when necessary. Important changes will be announced within the extension. The version of the policy currently in effect will always be published on this page.
