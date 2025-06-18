# Universal

### 1. [Link](Automations\dim-lights-elevation.yaml)

 - Passt die Helligkeit von Lichtern automatisch an die aktuelle Sonnenhöhe an.

# ZigBee

## Sonstiges

### 1. Universale Debug Automatisierung

 -  #### [Beliebige ZigBee-Fernbedienung (ZHA)](Automations\ZigBee\ZHA-debug-remote.yaml)

    Einsatzzweck: 
      - Debugging: Zeigt empfangene ZigBee-Befehle und Argumente in Hilfstexten an.
      - Speichert Befehle in Text Input Helpern

### 2. Shelly i4 Taster-Modul

 -  #### [Event gesteuerte Automatisierung](Automations\Shelly\Event-Shelly-i4.yaml)

    - Gerät: Shelly i4 Taster-Modul
    - Einsatzzweck: Reagiert auf Tastendrücke des Shelly i4 und führt je nach Taste Aktionen aus

## Fernbedinungen

### 1. IKEA SYMFONISK Sound Controller (E1744) - ZigBee-Drehregler

 -  #### [Hook mit AHB Controller Events](Automations\ZigBee\Ikea\ZHA-ikea-E1744-lights-hook.yaml)

    Einsatzzweck: 
      - Erstellt AHB Controller Events 
      - Setzt einen Boolean, um anzuzeigen, dass der Controller nicht mehr gedreht wird (z.B. für Dimmer-Stop).

-   #### [Lichtsteuerung auf Basis von AHB Controller Events](Automations\ZigBee\Ikea\ZHA-ikea-E1744-lights.yaml)

    Einsatzzweck: 
      - Steuert beliebige Aktionen (z.B. Licht) mit Einzel-/Doppel-/Dreifachklick und Drehbewegungen.

### 1. IKEA TRÅDFRI E1766 (Open/Close Remote)

 - #### [An/Aus Automatisierungen](Automations\ZigBee\Ikea\ZHA-tradfri-E1766-open-close.yaml)

    Einsatzzweck:
      - Steuert Aktionen für Öffnen und Schließen (z.B. Rollos).

### 2. IKEA TRÅDFRI E1743 (On/Off Switch)

-  #### [Lichtsteuerung und Dimmen](Automations/ZigBee/Ikea/ZHA-tradfri-E1743-lights.yaml)

    Einsatzzweck: 
      - Steuert Ein/Aus und Dimmen, inkl. Loop-Funktion für langes Drücken.

-  #### [Dimmer-Stop Hook](Automations/ZigBee/Ikea/ZHA-tradfri-E1743-lights-hook.yaml)

    Einsatzzweck: 
      - Setzt einen Boolean, um Dimmen zu stoppen (z.B. bei Loslassen der Taste).

### 3. Tradfri Remote 2 [E1524] 5 Button

-  #### [Aktionen für jede Taste](Automations\ZigBee\Ikea\ZHA-ikea-E1810-E1524-5-button-remote.yaml)

    Einsatzzweck: 
      - Führt beliebige Aktionen für jede Taste (kurz/lang) aus, inkl. Loop für langes Drücken.
### 4. Lidl FB20 002 (Silvercrest)

-  #### [Aktionen für jede Taste](Automations/ZigBee/Lidl/ZHA-lidl-FB20-002-action.yaml)

    Einsatzzweck: 
      - Führt beliebige Aktionen für jede Taste (kurz/lang) aus, inkl. Loop für langes Drücken.

-  #### [AHB Hook für eigene Events](Automations/ZigBee/Lidl/ZHA-lidl-FB20-002-ahb-hook.yaml)

    Einsatzzweck: 
      - Sendet eigene Events für jede Taste, um weitere Automatisierungen flexibel zu gestalten.

### 5. Philips Hue Dimmer V2 (RWL022)

-  #### [Dimmer Automatisierung](Automations/ZigBee/Philips/ZHA-hue-RWL022-dimmer.yaml)

    Einsatzzweck: 
      - Steuert beliebige Aktionen für Power, Dim Up/Down und verschiedene Tastendrücke.