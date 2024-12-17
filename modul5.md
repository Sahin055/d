# Crash Course: Cloud Computing for Cloud Engineers

---

# Modul 5: Cloud-Sicherheit und Compliance

## Ziel dieses Moduls

In diesem Modul lernst du:
- Sicherheitsrisiken bei verschiedenen Cloud-Modellen und wie man sie reduziert
- Best Practices für Cloud-Sicherheit und die Rolle von Identity & Access Management (IAM)
- Strategien zur Kostenoptimierung in der Cloud
- Praktische Umsetzung: Budget-Alarm erstellen und Kosten überwachen

---

## 1. Cloud-Sicherheitsrisiken

### Risiken der Deployment-Modelle

#### Alle Deployment-Modelle
- Personal: Fehler oder absichtlicher Missbrauch durch Mitarbeiter. Bei verwalteten Diensten bestehen zusätzliche Risiken durch externe Administratoren.
- Naturkatastrophen: Ereignisse wie Erdbeben oder Unwetter können die physische Infrastruktur beeinträchtigen.
- Cyberangriffe: Bedrohungen wie DDoS-Angriffe und Schadsoftware stellen ein Sicherheitsrisiko dar.
- Compliance-Verstöße: Verstöße gegen gesetzliche Vorschriften können rechtliche Konsequenzen haben.

#### Public Cloud
- Vendor Lock-In: Abhängigkeit von einem Anbieter durch nicht-standardisierte Formate.
- Vendor Lock-Out: Verlust des Zugangs zu Daten und Diensten, falls der Anbieter ausfällt.
- Multi-Tenant-Umgebung: Daten von Kunden in geteilten Umgebungen können unbefugt zugänglich sein.

#### Hybrid Cloud
- Kombination der Risiken aus Public Cloud und Private Cloud.

---

### Risiken der Service-Modelle

IaaS (Infrastructure as a Service)
- Personalrisiken: Wie bei den Deployment-Modellen.
- Cyberangriffe: Infrastrukturbezogene Bedrohungen.
- Mangelndes Know-how: Der Kunde trägt die Verantwortung für Sicherheit und Betrieb des Software-Stacks.

PaaS (Platform as a Service)
- Kompatibilitätsprobleme: Änderungen durch den Anbieter können Probleme mit der Software verursachen.
- Unbeabsichtigte Hintertüren: Testzugänge können versehentlich in Produktionsumgebungen übernommen werden.
- Ressourcenteilung: Mehrere Kunden teilen sich die gleichen Ressourcen, was Risiken birgt.

SaaS (Software as a Service)
- Vendor Lock-In: Wechsel zu einem anderen Anbieter kann durch Datenformate erschwert werden.
- Ressourcenteilung: Risiken wie bei PaaS.
- Web-App-Sicherheit: Schwachstellen in öffentlich zugänglichen Anwendungen sind besonders kritisch.

---

## 2. Best Practices für Cloud-Sicherheit

### Identity & Access Management (IAM)
- Verwendung von IAM zur zentralen Verwaltung von Zugriffsrechten und Identitäten.
- Prinzip der geringsten Berechtigung: Nutzer erhalten nur die Rechte, die sie wirklich benötigen.
- Regelmäßige Überprüfung von Berechtigungen und Identitäten zur Vermeidung von Missbrauch.

### Verschlüsselung
- Verschlüsselung von Daten während der Übertragung (in-transit) und Speicherung (at-rest).
- Nutzung von Managed Encryption Services zur sicheren Schlüsselverwaltung.

### Monitoring und Logging
- Implementierung von Monitoring-Tools zur Überwachung von Anomalien und Sicherheitsereignissen.
- Logging von Zugriffen und Aktivitäten zur Nachverfolgbarkeit.

### Sicherheitsupdates und Patching
- Regelmäßige Aktualisierung von Betriebssystemen und Anwendungen zur Schließung von Sicherheitslücken.

---

## 3. Cloud-Kostenmanagement

### Einführung
Cloud-Kosten können bei ineffizienter Nutzung schnell steigen. Häufige Herausforderungen sind:
- Überprovisionierung von Ressourcen
- Mangelnde Transparenz bei der Nutzung
- Ineffiziente Skalierung von Workloads

---

### Optimierungsstrategien

#### Reserved Instances
- Langfristige Reservierungen für häufig genutzte Workloads bieten erhebliche Rabatte.
- Ideal für vorhersehbare und langfristig stabile Anforderungen.

#### Spot Instances
- Nutzung von nicht ausgelasteter Cloud-Kapazität zu stark reduzierten Preisen.
- Geeignet für flexible, unterbrechbare Workloads wie Batch-Prozesse.
- Risiko: Ressourcen können jederzeit zurückgezogen werden.

#### Automatisierte Skalierung
- Dynamische Anpassung von Ressourcen basierend auf der aktuellen Auslastung.
- Verhindert Überprovisionierung und spart Kosten in Zeiten geringer Nutzung.

---

## Abschluss

In diesem Modul hast du gelernt:
- Welche Sicherheitsrisiken bei verschiedenen Cloud-Modellen und Service-Modellen auftreten
- Best Practices für Cloud-Sicherheit, wie IAM und Verschlüsselung
- Strategien zur Kostenoptimierung, wie Reserved Instances und automatisierte Skalierung
---
