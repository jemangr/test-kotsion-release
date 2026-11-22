# Changelog — Έχεις Κότσια; (`Do You Have the Guts?`)

## v1.4.0 (2026-11-23)
* ⚠️ **Ουδέτερη Οθόνη Προειδοποίησης & Ασφάλειας (Bilingual EL / EN):**
  * Προσθήκη ουδέτερης οθόνης προειδοποίησης σε όλα τα links δοκιμασιών (`eye.html`, `diff.html`, `hearing.html`, `maze.html`, `basement.html`, `camera.html` και URL queries): «Περιέχει ξαφνικούς δυνατούς ήχους και εικόνες που αναβοσβήνουν. Όχι για άτομα με φωτοευαίσθητη επιληψία ή καρδιολογικά προβλήματα.» / «Contains sudden loud sounds and flashing images. Not for people with photosensitive epilepsy or heart conditions.»
  * Εμφανίζεται **κάθε φορά** στα αυτόνομα links φάρσας (για να προστατεύει τον παραλήπτη χωρίς να προδίδει τη φάρσα), και **μόνο την πρώτη φορά** μέσα στην εφαρμογή (αποθηκεύεται τοπικά).
  * Πλήρως προσβάσιμη (WCAG AAA contrast, αυτόματο focus στο «Συνέχεια», πλοήγηση με πληκτρολόγιο Tab/Esc και υποστήριξη TalkBack/VoiceOver).
* ⚡ **Πλήρης Συμμόρφωση με WCAG 2.3.1 (Three Flashes or Below Threshold):**
  * Μείωση αναλαμπών σε όλα τα jumpscares και glitch εφέ σε αυστηρά ≤ 2 αναλαμπές ανά δευτερόλεπτο (όριο WCAG ≤ 3).
  * Πλήρης αφαίρεση όλων των έντονων κόκκινων full-screen flashes.
  * Ήρεμα VHS glitch slices χωρίς γρήγορες εναλλαγές που θα μπορούσαν να προκαλέσουν φωτοευαισθησία. Ο ήχος και η εικόνα του jumpscare παραμένουν αναλλοίωτα.
* 📝 **Νομική Αναθεώρηση Κειμένων:**
  * Αφαίρεση παραπλανητικών ή απόλυτων ισχυρισμών περί απουσίας προειδοποιήσεων.
  * Προσθήκη σαφούς οδηγίας υπεύθυνης χρήσης: «Στείλε τα links φάρσας μόνο σε όσους ξέρεις ότι το αντέχουν.».

### English Summary
* ⚠️ **Neutral Safety Warning Screen (Bilingual EL / EN):**
  * Added neutral warning screens to all prank links and on first app launch with options to Continue or Leave. Protects users with photosensitive epilepsy or heart conditions.
  * Appears every time on prank links without saving preferences, and once on first app launch (persists locally).
  * Fully accessible with high contrast, focus trapping, keyboard navigation, and screen reader labels.
* ⚡ **Full WCAG 2.3.1 Compliance (Flash Reduction):**
  * Flash frequency reduced to ≤ 2 flashes/sec (strictly below WCAG 2.3.1 threshold of 3/sec).
  * Eliminated all full-screen intense red strobing; smoothed out VHS glitch tears while keeping audio stinger and horror visuals intact.
* 📝 **Legal & Text Refinement:**
  * Updated descriptions to eliminate absolute pre-scare claims and added responsible sharing notice.

## v1.3.2 (2026-11-21)
* 🔊 **2 Νέες Κοφτές & Πεντακάθαρες Κραυγές (`0.67″` & `0.65″`, 0ms επίθεση):** Αφαιρέθηκαν όλες οι 4 παλιές κραυγές και αντικαταστάθηκαν με 2 πολύ σύντομες, κρυστάλλινες CC0 ανθρώπινες κραυγές ξαφνιάσματος (`-6.1 dB` / `-6.8 dB`, peak `0 dB`).
* 🎛️ **Καθαρό Audio Mastering χωρίς Synth Mud:** Αφαιρέθηκε το τεχνητό synth sub-boom κάτω από την κραυγή και ρυθμίστηκε διάφανος limiter στο bus (`-2 dB`), ώστε η κραυγή να ακούγεται 100% καθαρή & αιφνιδιαστική.

## v1.3.1 (2026-11-20)
* 🌐 **6 Αυτόνομα Links Δοκιμασιών (`eye.html`, `diff.html`, `hearing.html`, `maze.html`, `basement.html`, `camera.html`):** Κάθε δοκιμασία έχει πλέον δική της ξεχωριστή σελίδα και καθαρό social preview (`og:title` / `og:description`) χωρίς καμία αναφορά σε *«Έχεις Κότσια;»* ή τρόμο — ώστε ο παραλήπτης να βλέπει ΜΟΝΟ τη συγκεκριμένη δοκιμασία που επέλεξες!
* 🔗 **Κουμπί «Στείλε Link μόνο για αυτό» (`🔗`) σε κάθε κάρτα:** Στέλνει κατευθείαν το επιλεγμένο τεστ με 1 πάτημα από την αρχική οθόνη (και μέσω native Android Share Sheet στο APK).
* 🔒 **Κλείδωμα πριν το Jumpscare:** Αν ο φίλος πατήσει `✕` πριν σκάσει η σκηνή, μένει στην αθώα οθόνη εισόδου και δεν βλέπει την αρχική οθόνη τρόμου.

## v1.3.0 (2026-11-20)
* 🔗 **Κρυφά Links Φάρσας (`?mode=eye`, `?mode=diff`, `?mode=hearing`):** Στέλνεις link σε φίλο που ανοίγει **κατευθείαν** το αθώο τεστ (με διακριτικό περιβάλλον δοκιμασίας) — και μετά το σοκ βλέπει την κάρτα του **Pass & Play Terror** + link για να το στείλει παρακάτω!
* 🖼️ **Νέα Δοκιμασία «Βρες τις 3 Διαφορές»:** Βρίσκει 2 εύκολες διαφορές ανάμεσα στις δύο εικόνες — η 3η δεν υπάρχει, οπότε κολλάει στην οθόνη μέχρι να σκάσει!
* 🎧 **Νέα Δοκιμασία «Τεστ Ηλικίας Ακοής (Hz)»:** Κλινικό τεστ συχνοτήτων (`16.500 Hz → 14.000 Hz → 11.500 Hz`) που κάνει τον παίκτη να δυναμώσει μόνος του τον ήχο στο 100% πριν την κραυγή!

## v1.2.3 (2026-11-20)
* 👻 **Pass & Play Terror Promo Above the Fold:** Εμφάνιση της κάρτας **«👻 Pass & Play Terror»** ως βασικής πρότασης τρόμου στην οθόνη αποτελέσματος 100% ορατής **χωρίς scrolling** (μαζί με σκορ, mini preview κάρτας `🔍 9:16`, Αποθήκευση & Κοινοποίηση), καθώς και στο footer της εξαγόμενης 9:16 PNG κάρτας.

## v1.2.2 (2026-11-20)
* 🎨 **Custom Android Launcher, Adaptive & Splash Icons:** Αντικατάσταση των default εικονιδίων του Capacitor με το αυθεντικό εικονίδιο παλμού ECG σε όλα τα Android mipmap μεγέθη (`mdpi`–`xxxhdpi`), round/adaptive foreground & σκοτεινό `#07070A` splash screen.

## v1.2.1 (2026-11-20)
* 🏷️ **Επίσημο Rebrand:** Μετονομασία της εφαρμογής σε **«Έχεις Κότσια; — Do You Have the Guts?»** (PWA, Android app label, κάρτα 9:16, split-screen watermark, GitHub showcase & Releases — διατηρώντας το σταθερό APK download `test-kotsion.apk` και το PWA path `/test-kotsion/`).

## v1.2.0 (2026-11-20)
* 🤫 **Διακριτικό Περιβάλλον πριν το Jumpscare:** Διακριτικό HUD (`REC`, `ΤΡΕΜ`, `dB`, `G`) & stealth κάμερα κατά τη δοκιμασία, χωρίς ηχητικό crescendo, glitches, blackouts ή spoilers — απόλυτη αντίθεση στην επίθεση.
* 🎯 **4 Ενεργές Δοκιμασίες Συγκέντρωσης:**
  * `Κόκκινο Φως`: 3-level Maze που στενεύει μέχρι το ξαφνικό σοκ.
  * `Φακός στο Υπόγειο`: Φακός στο απόλυτο σκοτάδι για 4 κρυμμένους κωδικούς.
  * `Κάμερα στις 03:00`: Ρύθμιση focus slider μέχρι να καθαρίσει ο κωδικός στην πόρτα.
  * `Κρυφή Φάρσα 20/20`: Κλινικό τεστ 3 βημάτων (Ishihara `42`, χαμηλή αντίθεση `73`, μικρά γράμματα 15 εκ.).
* 🔊 **Υπενθύμιση Έντασης 100%:** Στην αρχή της εφαρμογής (start modal + home banner) ώστε να θυμάσαι να ανεβάσεις ήχο πριν δώσεις το κινητό.
* 🎴 **Προεπισκόπηση Κάρτας 9:16 + Native Αποθήκευση & Κοινοποίηση:** Zoom preview στην κάρτα αποτελέσματος & ξεχωριστά κουμπιά **💾 Αποθήκευση Κάρτας** (Gallery `Pictures/TestKotsion` σε Android) και **📤 Κοινοποίηση** (native Share Sheet / Web Share).

## v1.1.0 (2026-11-20)
* 💀 **4 Φωτορεαλιστικά Jumpscares & 2 Horror Backgrounds:** Αντικατάσταση της vector φιγούρας με 4 αληθοφανείς, ανατριχιαστικές εικόνες τρόμου (+ 2 ατμοσφαιρικά backgrounds για `Υπόγειο` & `Κλήση 03:00`), VHS slice glitch tears, strobe flash & zoom lunge.
* 🔊 **4 Δυνατές, Απότομες Πραγματικές Κραυγές (0ms επίθεση):** 4 διαφορετικές κραυγές τρόμου με sub-bass & impact punch που εναλλάσσονται δυναμικά σε κάθε γύρο χωρίς επανάληψη.
* 📦 Προ-φόρτωση όλων των εικόνων & κραυγών στο Service Worker cache (`test-kotsion-v2`) για μηδενική καθυστέρηση.

## v1.0.0 (2026-11-20)
* 🎉 Αρχική κυκλοφορία Android APK (`test-kotsion.apk`) & Web PWA (`jemangr.app/test-kotsion/`).
* 🎭 4 Σενάρια: `Κόκκινο Φως`, `Βήματα στο Υπόγειο`, `Κλήση στις 03:00` & `Κρυφή Φάρσα: Τεστ Όρασης 20/20`.
* 📡 4 πραγματικοί αισθητήρες on-device: G-Force τινάγματος (με drop detection), dB μικροφώνου, κίνηση προσώπου & τρέμουλο αναμονής.
* 🎬 Αυτόματο Split-Screen 9:16 βίντεο αντίδρασης + 1080×1920 Πιστοποιητικό Ψυχραιμίας PNG.
* 👥 Solo & Party Mode (2–6 παίκτες) με τελική κατάταξη *«👑 Πιο Ψύχραιμος vs 🐔 Κότα της Παρέας»*.
* 🔄 Ενσωματωμένος έλεγχος για νέα έκδοση από το GitHub Releases.
