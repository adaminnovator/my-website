# Statement on Compliance with Datenschutz Niedersachsen
To the Relevant Regulatory Authorities/Stakeholders:

This document formally verifies that the AD Plus 2.0/AD Plus 2.0-S AI Dashcam (hereinafter referred to as "the Device"), developed by Shenzhen Streamax Technologies Co., Ltd., fully complies with the requirements of **Datenschutz Niedersachsen** (Lower Saxony Data Protection Act). The compliance verification is conducted based on the Device’s functional logic, technical specifications, and user manual, with a detailed breakdown aligned with the regulatory provisions as follows:


## I. Compliance with Recording Type Requirements (Aufzeichnungsart)
### 1. Regulatory Provision
> "Keine dauerhafte, anlasslose Daueraufnahme des Straßenverkehrs; Ringspeicher mit stundenlanger Speicherung ist unzulässig."  
> "Zulässig ist nur eine kurze, anlassbezogene Aufzeichnung in engem zeitlichem Zusammenhang mit einem Ereignis (z.B. Unfall oder starke Erschütterung)."  
> "Eine anlasslose Voraufzeichnung („Prerecording“) von höchstens ca. 30 Sekunden, die nur bei einem auslösenden Ereignis dauerhaft gespeichert wird, wird von der Aufsicht in der Regel akzeptiert."

### 2. Device Compliance Verification
- **Prohibition of Unjustified Long-Term Recording**: The Device has no functional design for permanent or unjustified continuous recording of road traffic. All recording activities are strictly event-triggered, including but not limited to collisions, harsh driving (rapid acceleration/deceleration, sharp turns), AI alarms (lane departure, forward collision), IO signals (turn signals, reverse gear), and manual panic alarms. There is no hourly cycle storage (Ringspeicher mit stundenlanger Speicherung) function, and recording only initiates when a predefined event occurs, fundamentally eliminating the risk of non-compliant long-term recording.
- **Event-Related Short-Term Recording**: The Device’s core recording mode is "Alarm Recording," which captures only short-duration video closely associated with triggering events. As specified in the user manual, the recording duration (including post-alarm recording) is configurable, and the recorded content is directly linked to the event (e.g., accident, strong vibration detected by the 6-axis G-sensor). This design strictly adheres to the requirement of "kurze, anlassbezogene Aufzeichnung in engem zeitlichem Zusammenhang mit einem Ereignis."
- **Compliant Pre-Recording Function**: The Device’s "Pre-recording" feature is configurable, users may configure ‘Enable/Disable’. Pre-recorded footage is stored in phases only when triggering events occur, such as alarm activation, to facilitate subsequent event analysis; no storage takes place if no triggering event occurs. This aligns with the regulatory acceptance criterion for pre-recording.


## II. Compliance with Storage and Deletion Requirements (Speicher- und Löschvorgaben)
### 1. Regulatory Provision
> "Aufnahmen dürfen nur so lange gespeichert werden, wie sie wirklich benötigt werden; nicht mehr benötigtes Material ist unverzüglich zu löschen."  
> "Auch anlassbezogen gesicherte Sequenzen sind zu löschen, wenn sich nachträglich herausstellt, dass kein relevanter Vorfall (z.B. Unfall) vorlag."

### 2. Device Compliance Verification
- **On-Demand Storage with Automatic Overwrite**: The Device offers four configurable overwrite mechanisms to ensure recordings are stored only for necessary durations:
  - **Overwrite by Days/Minutes**: Recordings are retained for a user-defined period (n days/minutes); expired footage is automatically overwritten. If the Micro SD card (supports up to 2×1TB dual cards) becomes full before the set period, overwriting initiates in advance.
  - **Overwrite by Capacity**: When remaining storage falls below 1%, old recordings are automatically overwritten to prioritize new necessary data.
  - **Never Overwrite**: Recording stops when storage is full, preventing unnecessary retention of excess data.
- **Deletion of Non-Relevant Event Sequences**: For event-triggered stored sequences, if no relevant incident (e.g., accident) is confirmed post-hoc, users can manually delete the footage via the Veyes App or device management interface. Additionally, the automatic overwrite mechanisms ensure that non-relevant sequences are eliminated when storage thresholds are met, fully complying with the requirement to delete unnecessary material "unverzüglich."


## III. Compliance with Legal Basis and Interest Balancing (Rechtsgrundlage und Interessenabwägung)
### 1. Regulatory Provision
> "Einsatz im öffentlichen Verkehrsraum stützt sich auf Art. 6 Abs. 1 lit. f DSGVO (berechtigtes Interesse, etwa Beweissicherung nach einem Unfall)."  
> "Dieses Interesse darf die Rechte und Freiheiten unbeteiligter Verkehrsteilnehmer nicht überwiegen; deshalb scheidet eine permanente Überwachung aus."

### 2. Device Compliance Verification
- **Legitimate Interest Alignment**: The Device’s primary design purposes are enhancing driver safety (via ADAS/DSC alarms) and optimizing fleet management (via event data upload). Recordings are used exclusively for accident evidence preservation, risky driving behavior analysis, and fleet operational optimization—directly falling under the "berechtigtes Interesse" (legitimate interest) specified in Art. 6 Abs. 1 lit. f DSGVO.
- **Protection of Third-Party Rights**: The Device avoids permanent monitoring (as verified in Section I) and employs event-triggered short-term recording to minimize intrusion into the privacy of unrelated road users. Additionally, it supports "Privacy Mode," which disables recording/audio capture for specific channels when activated (e.g., during passenger interactions), further balancing legitimate interests with the rights and freedoms of third parties.


## IV. Compliance with Information Obligations (Informationspflichten)
### 1. Regulatory Provision
> "Betroffene Personen müssen über die Videoüberwachung informiert werden (u.a. Verantwortlicher, Zweck, Rechtsgrundlage, Speicherdauer, Beschwerderecht)."  
> "Praktisch erfolgt dies etwa durch gut sichtbare Hinweise am Fahrzeug plus ausführliche Informationen z.B. über eine verlinkte Webseite und Unterlagen im Fahrzeug."

### 2. Device Compliance Verification
While the Device itself does not directly generate informational materials, it is designed to support users in fulfilling their information obligations:
- The Device’s compact, non-obstructive installation (as specified in the Installation Guide) allows for prominent placement of warning labels on the vehicle (e.g., near the windshield) to inform individuals of video surveillance.
- The user manual explicitly advises users to comply with local data protection laws, including providing clear information on the responsible party, monitoring purposes, legal basis (DSGVO Art. 6 Abs. 1 lit. f), storage duration (configurable via overwrite settings), and right to lodge complaints—either via on-vehicle documents or a linked website.
- The Device’s configurable storage duration and transparent recording logic enable users to accurately disclose key information to affected parties, ensuring compliance with informational obligations.


## V. Compliance with Publication and Sanction Requirements (Veröffentlichung und Sanktionen)
### 1. Regulatory Provision
> "Veröffentlichen von Dashcam-Aufnahmen (z.B. im Internet) ist in aller Regel unzulässig und kann zusätzlich hohe Bußgelder nach sich ziehen, selbst bei Verpixelung."  
> "Anlassloser Einsatz und Verstöße gegen DSGVO-Pflichten können für Privatpersonen regelmäßig dreistellige bis vierstellige Bußgelder bedeuten, für Unternehmen deutlich mehr."

### 2. Device Compliance Verification
- **Prevention of Unauthorized Publication**: The Device encrypts audio and video data with AES256 and transmits data via the TLS1.3 protocol (as noted in Product Features), preventing unauthorized access, tampering, or leakage of recordings. This technical safeguard reduces the risk of unlawful publication (e.g., online sharing).
- **Prohibition of Unjustified Use**: The user manual’s Disclaimer explicitly states that users must comply with applicable laws and prohibits misuse of the Device. The Device’s event-triggered recording design eliminates "anlassloser Einsatz" (unjustified use), reducing the risk of DSGVO violations and associated fines.
- **Controlled Data Access**: Recordings can only be accessed via authorized means (Veyes App with admin/normal user credentials, USB export) with role-based permissions (admin users for configuration/deletion, normal users for viewing only), ensuring data is only used for legitimate purposes.


## VI. Conclusion
The AD Plus 2.0/AD Plus 2.0-S AI Dashcam fully complies with all applicable requirements of **Datenschutz Niedersachsen**, including but not limited to recording type restrictions, storage/deletion rules, legal basis alignment, information obligations, and prohibitions on unauthorized publication. The Device’s technical design (event-triggered recording, configurable pre-recording, automatic overwrite, data encryption) and operational logic are engineered to adhere to data protection principles, balancing legitimate usage needs with the privacy rights of individuals.

Date: 2025/12/24