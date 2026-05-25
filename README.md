# Einführung in das NHibernate-Framework für die .NET-Plattform

[Einführung in das NHibernate-Framework für die .NET-Plattform (2011)](https://stahe.github.io/de-nhibernate-dotnet-dec-2011/)

Dieses Repository begleitet einen Einführungskurs zu **NHibernate**, das als das .NET-Äquivalent des Java-Frameworks **Hibernate** vorgestellt wird. Das Dokument bietet einen prägnanten Überblick über die Verwendung eines **ORM** (*Object Relational Mapper*) im .NET-Ökosystem.

## Überblick

Ein ORM ist eine Sammlung von Bibliotheken, die es einer datenbankbasierten Anwendung ermöglicht, die Datenbank **ohne explizites Schreiben von SQL-Abfragen** und **ohne Abhängigkeit von den Spezifikationen des verwendeten DBMS** zu bearbeiten.

Dieses Material dient als **kurze Einführung** in NHibernate. Für eine vertiefte Auseinandersetzung empfiehlt das Dokument das folgende Buch:

- **NHibernate in Action**
- **Autor**: Pierre-Henri Kuaté
- **Verlag**: Manning
- **ISBN-13**: 978-1932394924

## Niveau und Voraussetzungen

Auf einer Skala von **Anfänger / Mittelstufe / Fortgeschritten** ordnet sich dieses Dokument der **Mittelstufe** zu.

Zum Verständnis sind verschiedene Voraussetzungen erforderlich, darunter:

1. **C# 2008**  
   *Kenntnisse der Sprache C# 3.0 mit dem .NET 3.5 Framework*

2. **Spring IoC für .NET**  
   Einführung in die Grundlagen der **Inversion of Control (IoC)** und der **Dependency Injection** mit **Spring.NET**

Das Dokument enthält zudem am Anfang einiger Absätze empfohlene Literaturhinweise zu diesen einführenden Ressourcen.

## Verwendete Tools

Die Fallstudie nutzt Tools, die kostenlos im Internet verfügbar sind, in den ab **Dezember 2011** aufgeführten Versionen:

- **NHibernate 3.2**  
- **Spring.NET 1.3.2**  
  Hier verwendet für Bibliotheken, die die Nutzung von NHibernate erleichtern  
- **log4net 1.2.10**  
  Von NHibernate verwendetes Logging-Framework  
- **NUnit 2.5**  
  Unit-Test-Framework, das .NET-Äquivalent zu JUnit
- **ADO.NET-Treiber 6.4.4 für MySQL 5**  
  
## Ziel des Kurses  
  
Dieser Kurs zielt darauf ab, die Grundlagen von **NHibernate** im .NET-Kontext vorzustellen und zu zeigen, wie der Datenzugriff durch einen objektorientierten Ansatz vereinfacht werden kann, wobei ergänzende Tools für Konfiguration, Protokollierung und Tests genutzt werden.

