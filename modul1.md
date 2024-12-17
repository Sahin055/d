# Crash Course: Cloud Computing for Cloud Engineers

---

# Modul 1: Grundlagen des Cloud Computing<br>

## Ziel dieses Moduls

In diesem Modul lernst du:
- Was Cloud Computing ist und warum es relevant ist
- Die wichtigsten Service- und Deployment-Modelle
- Kernvorteile und Eigenschaften der Cloud
- Strategien zur Cloud-Migration und praktische Anwendungsfälle

---

## Einführung

<p> Cloud Computing ermöglicht es, IT-Ressourcen flexibel und kosteneffizient zu nutzen.  
Es revolutioniert die Art, wie Unternehmen Anwendungen und Daten bereitstellen, verarbeiten und speichern.
</p>
---

## Was ist Cloud Computing? 🌥️


### Grundprinzip:

- Zugriff auf Computer-Ressourcen (Rechenleistung, Speicher, Netzwerk) über das Internet
- Keine lokale Installation erforderlich

### Funktionsweise:
1. Nutzer stellen Anfragen an Webdienste
2. Ressourcen (z.B. Speicher, Rechenkapazität) werden dynamisch zugeteilt
3. Nach der Nutzung werden Ressourcen freigegeben

- Pay-as-you-go-Modell: Zahle nur, was du tatsächlich nutzt!

---

### Verfügbare Ressourcen (Bild 1 nutzen)


<p> Cloud Computing stellt verschiedene Ressourcen bereit:</p>
- Hardware: Computer, Server
- Netzwerkkapazitäten
- Speicherplatz
- Betriebssysteme und Softwaredienste

---

<div style="display: flex; align-items: center;">
  <div style="flex: 1;">
    ![Bild 1](Bild1.png)
  </div>
  <div style="flex: 1; padding-left: 20px;">
    Hier schreiben Sie den Text, der neben dem Bild erscheinen soll.
  </div>
</div>


---

## Vorteile von Cloud Computing

1. Flexibilität: Ressourcen passen sich dynamisch dem Bedarf an
2. Kosteneffizienz: Zahle nur für tatsächlich genutzte Ressourcen
3. Skalierbarkeit: Ressourcen können jederzeit erhöht oder verringert werden
4. Ortsunabhängigkeit: Zugriff von überall möglich

---

## Service-Modelle: IaaS, PaaS, SaaS (Bild 2 nutzen)

---

### Modelle erklärt

## IaaS (Infrastructure as a Service) (Bild 10)

---

### Modelle erklärt

## IaaS (Infrastructure as a Service) (Bild 11)

---

### Modelle erklärt

## IaaS (Infrastructure as a Service) (Bild 12)

---

### Erweiterte Darstellung des Schichtenmodells(Bild 3)

---

### Beispiel IaaS-Provider(Bild 4)

---

### Erklärung durch Bild (5)

---

### Beispiel PaaS-Provider(Bild 6)

---

### Erklärung durch Bild (7)

---

### Beispiel SaaS-Provider(Bild 8)

---

### Erklärung durch Bild (9)

---

### Infrastructure as Code (IaC) mit Terraform
#### Terraform ist ein Tool zur Verwaltung von Infrastruktur als Code:
- Automatisierung: Automatisiert das Deployment von Ressourcen, minimiert manuelle Fehler
- Flexibilität: Unterstützt verschiedene Cloud-Anbieter und Dienste
- Transparenz: Dokumentiert und versioniert Infrastrukturcode, erleichtert Nachverfolgbarkeit und Fehleridentifikation
- Effizienz: Reduziert administrativen Aufwand und Kosten durch optimale Ressourcennutzung

## Deployment-Modelle 🚀 Public, Private

#### Public Cloud

- Ressourcen werden öffentlich über das Internet bereitgestellt
- Verwaltung durch externe Dienstanbieter wie STACKIT
- Kostengünstig durch gemeinsame Ressourcennutzung
- Hohe Skalierbarkeit und einfache Implementierung

### Private Cloud

- Exklusive Nutzung durch eine einzelne Organisation
- Höhere Kontrolle und Sicherheit
- Kann intern oder extern gehostet werden
- Ideal für sensible Daten und kritische Anwendungen

---

## Deployment-Modelle 🚀 Hybrid, Community

### Hybrid Cloud

- Kombination aus Public und Private Cloud
- Flexible Verteilung der Workloads
- Sensible Daten in Private Cloud, skalierbare Dienste in Public Cloud
- Verbindung über LANs oder WANs

### Community Cloud

- Gemeinsame Nutzung durch Organisationen mit ähnlichen Anforderungen
- Geteilte Infrastruktur und Kosten
- Ideal für Branchen mit gleichen Sicherheits- oder Compliance-Anforderungen
- Fördert Zusammenarbeit zwischen Partnern
- Einsatzgebiete: 
1. Gesundheitswesen
2. Bildungseinrichtungen
3. Finanzsektoren 

---

## Die wichtigsten Eigenschaften von Cloud Computing

1. Elastizität
    - Dynamische Anpassung der Ressourcen an den Bedarf

2. Skalierbarkeit
    - Beliebige Ausweitung oder Reduzierung von Kapazitäten

3. Pay-as-you-go
    - Kosten fallen nur für tatsächlich genutzte Ressourcen an

4. Omnipräsenz
    - Zugriff jederzeit und überall über das Internet
   
---

# Gründe für eine Cloud Migration
## Einsparung Capital Expenditure
- Investitionskosten = gebundene Kosten für HW, Räume, Software etc.
- Beispiel: Lastspitzen z.B. Saisonal bedingt, HW muss trz. Restl. Zeit vorgehalten &
betrieben werden
- CPEX soll in OPEX umgewandelt werden
- OPEX (Operational Expenditure) Betriebskosten = variabel, richten sich nach dem
Bedarf
- Durch Cloud Charakteristika (z.B. Rapid Elasticity, Metered Service) erst möglich

---

# Gründe für eine Cloud Migration

## Service Level Agreements (SLAs)

### Verfügbarkeit und Performance: Diese Definieren Leistungsparameter wie Systemverfügbarkeit, Reaktionszeiten und Zuverlässigkeit der Services
### Sicherheit und Datenschutz
- Es gibt klare Regelungen über die Eigentumsrechte an den gespeicherten Daten und deren Schutz
- Die Infrastruktur- und Sicherheitsanforderungen, die der Provider leisten muss, werden klar festgelegt

### Vorteil
- Der Dienstleister haftet, soweit festgelegt, bei Problemen wie Verlust von Daten 
- Kompensationen bei Nichteinhaltung der vereinbarten Leistungen
---

# Gründe für eine Cloud Migration
## Reduzierung des IT-Personals
### Automatisierung
- Cloud-Dienste bieten automatisierte Prozesse für Updated, Backups und Sicherheitspatches, was den manuellen Eingriff reduziert
### Weniger Wartungsaufwand
- Durch die Auslagerund der IT-Infrastruktur entfällt der Großteil der Wartungsarbeiten von Servern und Rechenzentren 

---

## Strategie zur Cloud Migration

1. Rehosting
    - Lift and Shift – Anwendungen werden unverändert migriert

2. Replatform
    - Geringe Anpassungen zur Optimierung der Umgebung

3. Repurchasing
    - Umstellung auf neue SaaS-Produkte

4. Refactoring
    - Neuentwicklung der Anwendung für die Cloud

5. Retire
    - Abschalten veralteter Anwendungen

6. Retain
    - Beibehaltung bestehender Anwendungen ohne Änderungen
---

## Zusammenfassung von Modul 1

- Grundlagen und Vorteile von Cloud Computing verstanden
- Unterschiedliche Service- und Deployment-Modelle kennengelernt
- Cloud-Migration hilft Unternehmen, Kosten zu reduzieren und Innovationen zu fördern

### Weiter geht es mit Modul 2: Cloud-Architekturen!

