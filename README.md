🌊 ADB Project WAVEoS 🚀

📖 Überblick

ADB Project WAVEoS ist weit mehr als eine einfache Toolbox. Es ist eine virtuelle OS-Umgebung für Android-Entwickler, die direkt in einer hochoptimierten Windows-CMD-Schnittstelle läuft. Mit integriertem Kernel-Management und Echtzeit-Sicherheitsprüfungen bietet es eine stabile Basis für Modding und ROM-Entwicklung.

📋 Inhaltsverzeichnis

Hauptmerkmale

Installation

WAVEoS Security & Brick-System

Downloads

Mitwirken

🛠 Hauptmerkmale

⚡ WAVEoS Kernel: Simulation eines echten OS-Dateisystems (system.img, boot.img, vendor.img, product.img, system_ext.img).

🔐 VBMeta Security: Einzigartiges Integritäts-Management mit dem Sicherheitsschlüssel 1605112006.

🔄 Cloud-Sync: Automatische Prüfung auf neue System-Releases (update.img) direkt über die GitHub API bei jedem Start.

📁 Project Master: Intelligentes Scannen von Treiber-Verzeichnissen und automatisierte Erstellung von Projekt-Umgebungen.

🎯 Smart Pick: Native Windows-Explorer Integration zur Multiselektion von Flash-Dateien.

📥 Downloads & Releases

Die offizielle Version von ADB Project WAVEoS findest du exklusiv in unseren GitHub-Releases:

🚀 HIER DIE NEUESTE VERSION HERUNTERLADEN

🧱 WAVEoS Security & Brick-System

Sicherheit steht bei WAVEoS an erster Stelle. Das System verfügt über eine integrierte Schutz-Logik, um fehlerhafte Flash-Vorgänge oder Manipulationen zu verhindern:

VBMeta-Authentifizierung: Jedes Mal, wenn das System bootet, wird der VBMeta-Schlüssel verifiziert.

Dateiprüfung: Fehlen wichtige Kern-Komponenten (wie system.img), verweigert das System den Dienst.

Brick-Simulation (Bootloop): Bei fehlgeschlagener Verifizierung wechselt die Konsole in den kritischen Fehlermodus (Rot), um eine Beschädigung der Arbeitsumgebung zu signalisieren.

🚀 Installation

Repository beziehen: Klone das Repo oder lade das neueste Release-Paket herunter.

Treiber vorbereiten: Kopiere deine benötigten ADB/Fastboot Treiber in den Ordner treiber.

Starten: Rechtsklick auf adb_manager.cmd -> Als Administrator ausführen.

Initialisierung: Warte, bis die WAVEoS-Bootsequenz abgeschlossen ist und das Dashboard (Weißes Design) erscheint.

🤝 Mitwirken

Werde Teil der Entwicklung!

Fork das Projekt.

Erstelle einen Feature Branch (git checkout -b feature/NeuesFeature).

Commit deine Änderungen (git commit -m 'Add: Neues Feature').

Push den Branch (git push origin feature/NeuesFeature).

Öffne einen Pull Request.

📜 Lizenz

Dieses Projekt ist unter der MIT-Lizenz lizenziert. Weitere Details findest du in der Datei LICENSE.
