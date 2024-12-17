# Skalierbarkeit und Verfügbarkeit 

## Skalierbarkeit

### Optimierung der Ressourcen für wachsende Anforderungen

- Vertikale Skalierung: Hinzufügen von Leistung (z. B. CPU, RAM) zu bestehenden Ressourcen.

- Horizontale Skalierung: Hinzufügen weiterer Instanzen, um Lasten zu verteilen.

- Auto-Scaling: Automatische Anpassung der Ressourcen basierend auf definierten Metriken

## Elastizität

- Dynamische Anpassung der Ressourcen an schwankende Anforderungen, um Kosten zu sparen und Effizienz zu gewährleisten.
- Predictive Scaling: Vorausschauende Ressourcenanpassung basierend auf historischen Daten

## Strategien für Hochverfügbarkeit

- Load Balancing: Verteilung der Anfragen auf mehrere Ressourcen, um Engpässe zu vermeiden.

- Redundanz: Bereitstellung mehrfacher Systeme als Backup für Ausfälle.

- Failover-Mechanismen: Automatische Umschaltung auf ein Backup-System bei einem Ausfall.
- Service Level Agreements (SLAs): Definition von Verfügbarkeitszielen
- Disaster Recovery: Strategien zur Wiederherstellung nach Systemausfällen
- Multi-Region Deployment: Verteilung über geografische Regionen

# Containerisierung 

## Einführung in Container-Technologien

- Container wie Docker ermöglichen das Verpacken von Anwendungen und deren Abhängigkeiten in isolierte Einheiten.
- Container Images und Builds
- Container Lifecycle Management

## Vorteile der Containerisierung

- Portabilität: Container können nahtlos zwischen verschiedenen Umgebungen verschoben werden.

- Konsistenz: Einheitliche Laufzeitumgebungen vermeiden Kompatibilitätsprobleme.

- Effizienz: Weniger Overhead im Vergleich zu virtuellen Maschinen.

- Isolation: Verbesserte Sicherheit durch Trennung der Prozesse

## Vergleich von Containern und virtuellen Maschinen

- Container sind leichtgewichtig und teilen den Host-Kernel, während virtuelle Maschinen eine vollständige Hardwareemulation bieten.
- Ressourcennutzung und Performance-Vergleich
- Use-Case-Szenarien für beide Technologien

## Container-Orchestrierung

- Tools wie Kubernetes automatisieren die Verwaltung, Skalierung und Bereitstellung von Containern.

# Microservices 

## Definition und Merkmale

- Microservices sind unabhängige, modularisierte Services, die jeweils eine spezifische Funktion erfüllen und eigenständig deploybar sind.

## Vorteile

- Flexibilität: Unabhängige Entwicklung und Bereitstellung von Services.

- Skalierbarkeit: Jeder Service kann individuell skaliert werden.

- Robustheit: Fehler in einem Service beeinträchtigen andere Services nicht.

## Herausforderungen

- Komplexität: Verwaltung und Integration zahlreicher Services.

- Kommunikation zwischen Services: Bedarf an zuverlässigen und effizienten Schnittstellen (z. B. APIs).

# Minikube
## Definition 
- Minikube ist ein Tool zur lokalen Ausführung eines Single-Node-Kubernetes-Clusters
## Zweck
- Ermöglicht das Experimentieren mit Kubernetes und die Entwicklung von Kubernetes-basierten Anwendungen auf dem lokalen Rechner
## Funktionen
-Unterstützt viele Kubernetes-Features wie DNS, NodePorts, ConfigMaps, Secrets, Dashboards und Ingress