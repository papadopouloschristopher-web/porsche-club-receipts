# porsche-club-receipts
porsche-club-receipts
# Αποδείξεις πληρωμής – Porsche Club Greece  (v2)

## Τι νέο υπάρχει
- Email μέλους στο αρχείο μελών.
- Αιτιολογίες / events ως λίστα (κουμπί «Λίστα…»), με προαιρετικό προτεινόμενο ποσό.
- Φίλτρο ανά αιτιολογία στο αρχείο πληρωμών (F2), με σύνολο.
- Μετά την έκδοση: «Send it» (email με PDF συνημμένο) ως κύρια ενέργεια, εκτύπωση ως εναλλακτική.
- Εικόνα υπογραφής στην απόδειξη.

## Ρυθμίσεις
Το μοναδικό club.json βρίσκεται στο `Έγγραφα\PorscheClubReceipts\club.json`
(κουμπί «Ρυθμίσεις»). Νέα πεδία: SenderEmail, CcEmail, SubjectPrefix, EmailBody,
EmailMethod, SignatureImage.

## Email
- **Outlook classic / Thunderbird**: ανοίγει έτοιμο μήνυμα με παραλήπτη, Cc, θέμα,
  κείμενο και το PDF συνημμένο. Πατάτε «Αποστολή».
- **Νέο Outlook, Windows Mail, Gmail κ.λπ.**: ανοίγει η φόρμα «Αποστολή email» με
  mailto (όλα εκτός του συνημμένου) και κουμπιά αντιγραφής για κάθε πεδίο και για το PDF.
  Βάλτε `"EmailMethod": "Manual"` για να πηγαίνει κατευθείαν εκεί.

## PDF
Δημιουργούνται με τον «Microsoft Print to PDF» στο `Έγγραφα\PorscheClubReceipts\PDF\`.

## Backup
Αντιγράψτε όλο τον φάκελο `Έγγραφα\PorscheClubReceipts` (βάση, ρυθμίσεις, PDF).
