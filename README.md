# The Rabbits App – Mail Companion

Paneel naast Apple Mail met contacten, projecten, taken en afspraken uit The Rabbits App.
Alleen te gebruiken met een account bij Shoot the Rabbit.

**Download:** [nieuwste versie (.dmg)](https://github.com/shoottherabbit/mail-companion-releases/releases/latest)

---

## Installeren (eenmalig)

### 1. Downloaden en plaatsen
1. Download het `.dmg`-bestand via de link hierboven (onder **Assets**).
2. Dubbelklik op het bestand. Er opent een venster met de app en een map **Programma's**.
3. **Sleep** *MailCompanion* naar *Programma's*.
4. Sluit het venster en werp de schijf uit (rechtsklik op "Mail Companion" in Finder → Verwijder).

### 2. De eerste keer openen (macOS-beveiliging)
De app is niet via de App Store verspreid, dus macOS geeft de eerste keer een waarschuwing:
*"MailCompanion niet geopend – Apple kon niet verifiëren…"*

1. Open **Programma's** en dubbelklik op *MailCompanion*.
2. Klik op **Gereed** (niet op "Verplaats naar prullenmand").
3. Open **Systeeminstellingen → Privacy en beveiliging**.
4. Scroll naar beneden tot je *"MailCompanion is geblokkeerd…"* ziet en klik op **Toch openen**.
5. Bevestig met je wachtwoord of Touch ID en klik nogmaals op **Open**.

> Lukt dit niet? Open **Terminal** en voer uit:
> `xattr -cr /Applications/MailCompanion.app`
> Start de app daarna opnieuw.

Dit hoeft maar één keer. Updates daarna gaan vanzelf.

### 3. Inloggen
1. Klik in het paneel op **Inloggen met Google** en log in met je Shoot the Rabbit-account.
2. Je komt automatisch terug in de app.

### 4. Rechten geven in Systeeminstellingen
De app heeft twee rechten nodig. Vraagt macOS erom, klik dan op **Open Systeeminstellingen**; anders ga je er zelf naartoe.

**a. Toegankelijkheid** – nodig om het paneel netjes naast het Mail-venster te houden
1. **Systeeminstellingen → Privacy en beveiliging → Toegankelijkheid**
2. Zet de schakelaar naast **MailCompanion** aan (staat hij er niet, klik dan op **+** en kies de app in *Programma's*).
3. Start MailCompanion opnieuw (menu **MailCompanion → Stop MailCompanion**, daarna weer openen).

**b. Automatisering (Mail)** – nodig om de geselecteerde mail te lezen
1. Open in de app **Instellingen** (⌘ ,) en zet **Mail-toegang (Automation)** aan.
2. macOS vraagt: *"MailCompanion wil Mail bedienen"* → klik op **OK**.
3. Controleer in **Systeeminstellingen → Privacy en beveiliging → Automatisering** dat onder *MailCompanion* de schakelaar bij **Mail** aanstaat.

**c. Toetsenbord (alleen als nodig)**
Werkt het paneel niet bij als je met de pijltjestoetsen door mails loopt? Zet MailCompanion dan ook aan onder **Privacy en beveiliging → Toetsenbordcontrole**.

### 5. Automatisch starten
Bij de eerste start zet de app **Start bij inloggen** vanzelf aan. Controleer of wijzig dit onder:
- **Instellingen (⌘ ,) → Start bij inloggen**, of
- **Systeeminstellingen → Algemeen → Inlogonderdelen en extensies**

---

## Gebruiken
- Open **Mail** en selecteer een mail. Het paneel verschijnt rechts naast Mail.
- Klik op een project om de mail eraan te koppelen (nogmaals klikken ontkoppelt).
- Uitnodigingen kun je direct **Accepteren** of **Afwijzen**; dan staat de afspraak ook in The Rabbits App.

## Updaten
De app zoekt zelf naar updates. Handmatig: **MailCompanion → Zoek naar updates…** (app-menu, of via het envelop-icoon in de menubalk).

## Problemen oplossen
| Probleem | Oplossing |
|---|---|
| Paneel staat niet naast Mail | Toegankelijkheid aan? (4a) App opnieuw starten. |
| Paneel toont geen contacten/projecten bij een mail | Mail-toegang aan in Instellingen en Automatisering → Mail aan (4b). |
| Na een update vraagt macOS opnieuw om rechten | Normaal bij deze app: schakelaar uit en weer aan zetten in Toegankelijkheid / Automatisering. |
| App opent niet ("niet geopend") | Zie stap 2, of gebruik de Terminal-opdracht. |
| Uitloggen / opnieuw inloggen | **MailCompanion → Instellingen → Uitloggen**, daarna weer **Inloggen met Google**. |
