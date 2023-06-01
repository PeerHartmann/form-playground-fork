# Validierung ist stets aktuell

* Status: proposed
* Date: 2023-06-01

## Context and Problem Statement

Es steht zur Frage wann die Validierung durchgeführt wird und somit der Validierungsstatus bekannt ist

## Considered Options

* Nach jeder Änderung
* Zu bestimmten, vom Entwickler wählbaren Zeitpunkten  (etwa: blur, change)

## Decision Outcome

Chosen option: "Nach jeder Änderung", because so ist immer ein komplettes Validierungsmodell vorhanden. Synchrone Validierung sollte immer schnell genug sein.
