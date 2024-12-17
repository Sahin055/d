# Crash Course: Cloud Computing for Cloud Engineers

---

# Modul 3: Cloud-Architekturen

## Ziel dieses Moduls

In diesem Modul lernst du:
- Konzepte von Skalierbarkeit und Hochverfügbarkeit
- Die Rolle von Containern und Microservices in modernen Cloud-Architekturen
- Kubernetes als zentralen Orchestrierungsdienst für containerisierte Anwendungen
- Praktische Anwendung von Kubernetes und den Einstieg in STACKIT Kubernetes Engine

---

## Skalierbarkeit und Verfügbarkeit

### Skalierbarkeit
Skalierbarkeit ermöglicht es, Ressourcen an wachsende Anforderungen anzupassen:

- Vertikale Skalierung: Hinzufügen von Leistung wie CPU oder RAM zu bestehenden Ressourcen
- Horizontale Skalierung: Hinzufügen weiterer Instanzen, um Lasten auf mehrere Ressourcen zu verteilen
- Auto-Scaling: Dynamische Anpassung der Ressourcen basierend auf vordefinierten Metriken

### Elastizität
Elastizität beschreibt die automatische und dynamische Anpassung von Ressourcen an schwankende Anforderungen:
- Verhindert Überprovisionierung und spart Kosten
- Predictive Scaling: Vorhersage von Ressourcenbedarf basierend auf historischen Daten

### Strategien für Hochverfügbarkeit
Hochverfügbarkeit stellt sicher, dass Anwendungen kontinuierlich verfügbar sind:
- Load Balancing: Verteilung der Anfragen auf mehrere Instanzen
- Redundanz: Mehrfache Systeme als Backup für Ausfälle
- Failover-Mechanismen: Automatische Umschaltung auf Backup-Systeme bei Fehlern
- Multi-Region Deployment: Verteilung der Systeme auf geografische Regionen zur Minimierung von Ausfällen

---

## Containerisierung und Microservices

### Containerisierung
Container bündeln Anwendungen und deren Abhängigkeiten in isolierten Einheiten:
- Sie nutzen das Betriebssystem des Hosts anstatt vollständige Hardware zu emulieren.
- Ressourcenverbrauch ist geringer als bei virtuellen Maschinen.

### Microservices
Microservices zerlegen Anwendungen in unabhängige, kleinere Dienste:
- Jeder Microservice erfüllt eine spezifische Funktion und kommuniziert über APIs.
- Vorteile: Unabhängige Entwicklung, Skalierbarkeit und Fehlertoleranz.
- Herausforderungen: Erhöhte Komplexität bei der Verwaltung und Integration vieler kleiner Dienste.

---

## Kubernetes als Orchestrierungsplattform

Kubernetes löst die Herausforderungen der Container-Orchestrierung, indem es:
- Automatisiertes Deployment, Skalierung und Wartung von Containern ermöglicht
- Selbstheilende Mechanismen bereitstellt, um fehlerhafte Container neu zu starten oder zu ersetzen
- Ressourcen effizient verteilt, um Lasten auszugleichen

### Kubernetes im Überblick
- Deployment: Rollout neuer Anwendungen oder Updates über deklarative Konfiguration
- Skalierung: Automatisches Hoch- oder Herunterskalieren von Ressourcen je nach Lastanforderungen
- Storage-Orchestrierung: Verwaltung von persistentem Speicher für zustandsbehaftete Anwendungen

---

## Praktische Umsetzung mit Kubernetes

### Minikube
Minikube ermöglicht die lokale Ausführung eines Single-Node-Kubernetes-Clusters:
- Einfacher Einstieg in Kubernetes für Entwickler und Testumgebungen

**Aufgabe:**
1. Installiere Minikube auf deinem Rechner.
2. Starte ein Kubernetes-Cluster.
3. Erstelle ein Deployment und skaliere es nach oben und unten.

---

## STACKIT Kubernetes Engine (SKE)

### Definition und Merkmale
- Managed Kubernetes Service, der die Bereitstellung von Kubernetes-Clustern vereinfacht

### Vorteile
- Reduzierter Betriebsaufwand durch Automatisierung
- Pay-per-Use-Kostenmodell für optimierte Ressourcennutzung
- Abschaltmöglichkeiten zur Kostensenkung

### Anwendungsfälle
1. Migration bestehender Anwendungen:
    - Containerisierung von Legacy-Anwendungen für den Betrieb in einer modernen Cloud-Umgebung

2. Cloud-native Entwicklung:
    - Entwicklung modularer Microservices-Anwendungen mit CI/CD-Pipelines und Service Mesh-Integration

3. Stateful Anwendungen:
    - Verwaltung zustandsbehafteter Anwendungen durch Kubernetes mit persistentem Speicher

---

## Von Containern zu Kubernetes in der Cloud-Architektur

1. Skalierbarkeit und Hochverfügbarkeit
    - Wie Cloud-Architekturen es ermöglichen, flexibel auf Anforderungen zu reagieren und Ausfallzeiten zu minimieren.

2. Containerisierung und Microservices
    - Wie Container und Microservices effiziente und flexible Cloud-Anwendungen ermöglichen.

3. Kubernetes als Lösung
    - Kubernetes orchestriert die Verwaltung von Containern und automatisiert zentrale Aufgaben.

4. Praktische Anwendung
    - Einstieg in Kubernetes mit Minikube und praktischer Einsatz der STACKIT Kubernetes Engine.

---

## Abschluss

In diesem Modul hast du gelernt:
- Wie Skalierbarkeit und Hochverfügbarkeit in Cloud-Architekturen umgesetzt werden
- Die Rolle von Containern und Microservices bei modernen Anwendungen
- Kubernetes als Plattform zur Orchestrierung und Automatisierung von containerisierten Workloads
- Praktische Umsetzung von Kubernetes-Clustern für Entwicklung und Produktion

---

## 8. Nächste Schritte

- Gehe auf https://docs.stackit.cloud/stackit/en/getting-started-ske-10125565.html
  und werde vertraut mit dem Cluster Management
---

