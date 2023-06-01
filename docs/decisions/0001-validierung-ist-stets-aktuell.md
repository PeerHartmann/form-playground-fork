# Validierung ist stets aktuell

* Status: proposed
* Date: 2023-06-01

## Context and Problem Statement

Es steht zur Frage wann die Validierung durchgeführt wird und somit der Validierungsstatus bekannt ist

## Considered Options

* Nach jeder Änderung
* Zu bestimmten, vom Entwickler wählbaren Zeitpunkten  (etwa: blur, change)

## Decision Outcome

Chosen option: "Zu bestimmten, vom Entwickler wählbaren Zeitpunkten", because Performance muss gewahrt werden ausserdem kann man so auch async sinnvoll validieren.
