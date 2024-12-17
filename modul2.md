# Modul 2: Von VMs zu Containern zu Kubernetes

---
# Einführung in Virtual Machines (VMs)
## Was sind Virtual Machines?
- Software, die eine virtuelle Umgebung schafft, die wie ein eigenständiger Computer funktioniert
- Emuliert Hardware eines physischen Computers
- Abstrahiert und isoliert Ressourcen wie CPU, Speicher, Netzwerk und Speicher

## Vorteile von VMs
- Isolation: Jede VM ist von anderen VMs und dem Host-System isoliert
- Effizienz: Konsolidierung von Servern auf weniger physische Maschinen
- Flexibilität: Leichte Migration zwischen Servern oder in die Cloud
- Schnelle Bereitstellung: Schnelle Duplizierung und Bereitstellung neuer Umgebungen

--- 

# Was sind Container?
- Leichtgewichtige Alternative zu VMs
- Virtualisieren das Betriebssystem, nicht die Hardware
- Isolierte Umgebung für Anwendungen mit allen notwendigen Abhängigkeiten
# Vorteile von Containern
- Portabilität: Hochportabel, können in verschiedenen Umgebungen ausgeführt werden
- Effiziente Ressourcennutzung: Weniger Ressourcenbedarf, höhere Dichte an Anwendungen pro Server
- Skalierbarkeit: Schnelle Skalierung, beschleunigt Entwicklung, Tests und Produktionszyklen
- Kostenreduktion: Geringere Kosten für Hardware und Lizenzen

---

## Vergleich: Virtual Machines vs. Container

### Virtual Machines:
- Virtualisierungsebene: Hardware
- Ressourcenverbrauch: Hoch
- Startzeit: Minuten
- Isolation: Vollständige Isolation
- Use-Case: Legacy-Anwendungen

### Container:
- Virtualisierungsebene: Betriebssystem
- Ressourcenverbrauch: Gering
- Startzeit: Sekunden
- Isolation: Prozessbasierte Isolation
- Use-Case: Microservices und Cloud-Native Anwendungen

---

# Einführung in Kubernetes (K8s)
## Was ist Kubernetes?
- Open-Source-Plattform zur Verwaltung von containerisierten Workloads und Services
- Automatisiert Bereitstellung, Skalierung und Verwaltung von Containern
## Vorteile von Kubernetes
- Automatisierung: Automatisiert Bereitstellung, Skalierung und Wartung von Containern
- Selbstheilung: Überwacht Container-Gesundheit und ersetzt oder startet sie neu bei Fehlern
- Lavstverteilung: Verteilt Netzwerkverkehr auf Container für stabile Leistung
- Speicherorchestrierung: Automatische Bereitstellung und Verwaltung von Speicher
- Erweiterbarkeit: Erweiterbar durch CRDs, Operatoren und benutzerdefinierte APIs

--- 

## Der Weg: Von VMs zu Containern zu Kubernetes

1. Virtual Machines
    - Konsolidierung von Servern
    - Isolation und Flexibilität
    - Ressourcenintensiv

2. Containerisierung
    - Leichtere Alternative zu VMs
    - Höhere Effizienz und Portabilität
    - Optimierte Entwicklung und Skalierung

3. Kubernetes
    - Automatisierte Orchestrierung und Verwaltung von Containern
    - Selbstheilung, Skalierung und Integration in moderne Architekturen  