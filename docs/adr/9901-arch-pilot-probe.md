# 9901 · Documento de prueba del piloto de arquitectura (no es una decisión real)

Estado: propuesto
IA: no
Issue: #1

> Documento de PRUEBA del paso 6 del ADR 0002 de claude-config (issue
> ai-lab-md-org/claude-config#24). No describe ningún cambio real. El PR que lo
> trae NO se mergea y se cierra al terminar el piloto.

## Problema

Hay que comprobar, en un repo de verdad, que el check central `architecture` lee
este documento, busca el OK del owner en el issue y compara las secciones de
decisión contra el commit del permalink.

## Cómo es hoy

El check central corre sólo mirando (Evaluate) en los repos con
`architecture_gate=required`. Nunca se lo vio correr sobre un ADR en un PR real.

## Alternativas

### Probar con tests unitarios solamente

Ya existen y pasan, pero no prueban que GitHub corra el workflow de otro repo.

### Probar con PRs reales en los repos piloto

Es lo que pide el paso 6 del ADR 0002: prueba la regla de verdad, sin mergear nada.

## Decisión

Se agregan DOS archivos de texto en `docs/arch-pilot/` (cambio hecho DESPUÉS del OK, a propósito: el check tiene que frenar este PR). No se toca código.

## Objeciones del staff

- Objeción de prueba: el documento no describe un cambio real → se acepta, es a propósito para el piloto.
- Objeción de prueba: el PR no se mergea → se acepta, se cierra al terminar el piloto del ADR 0002.

## Plan de PRs

1. Este PR, que no se mergea.

## Riesgos

- Ninguno: el PR sólo agrega texto y se cierra sin mergear.

## Fuentes

- ADR 0002 de claude-config, Plan de PRs, paso 6 (docs/adr/0002-central-architecture-gate.md).
- Documentación de GitHub sobre reglas con workflows obligatorios (available-rules-for-rulesets).

## Checklist del manual

- M-code-design-01 · no aplica a este documento de prueba, que sólo agrega texto sin código — evidencia: el diff del PR
- M-code-design-02 · no aplica a este documento de prueba, que sólo agrega texto sin código — evidencia: el diff del PR
- M-code-design-03 · no aplica a este documento de prueba, que sólo agrega texto sin código — evidencia: el diff del PR
- M-code-design-04 · no aplica a este documento de prueba, que sólo agrega texto sin código — evidencia: el diff del PR
- M-code-design-05 · no aplica a este documento de prueba, que sólo agrega texto sin código — evidencia: el diff del PR
- M-code-design-06 · no aplica a este documento de prueba, que sólo agrega texto sin código — evidencia: el diff del PR
- M-code-design-07 · no aplica a este documento de prueba, que sólo agrega texto sin código — evidencia: el diff del PR
- M-code-design-08 · no aplica a este documento de prueba, que sólo agrega texto sin código — evidencia: el diff del PR
- M-code-design-09 · no aplica a este documento de prueba, que sólo agrega texto sin código — evidencia: el diff del PR
- M-code-design-10 · no aplica a este documento de prueba, que sólo agrega texto sin código — evidencia: el diff del PR
- M-code-design-11 · no aplica a este documento de prueba, que sólo agrega texto sin código — evidencia: el diff del PR
- M-code-design-12 · no aplica a este documento de prueba, que sólo agrega texto sin código — evidencia: el diff del PR
- M-code-design-13 · no aplica a este documento de prueba, que sólo agrega texto sin código — evidencia: el diff del PR
- M-code-design-14 · no aplica a este documento de prueba, que sólo agrega texto sin código — evidencia: el diff del PR
- M-code-design-15 · no aplica a este documento de prueba, que sólo agrega texto sin código — evidencia: el diff del PR
- M-code-design-16 · no aplica a este documento de prueba, que sólo agrega texto sin código — evidencia: el diff del PR
- M-code-design-17 · no aplica a este documento de prueba, que sólo agrega texto sin código — evidencia: el diff del PR
- M-code-design-18 · no aplica a este documento de prueba, que sólo agrega texto sin código — evidencia: el diff del PR
- M-testing-01 · no aplica a este documento de prueba, que sólo agrega texto sin código — evidencia: el diff del PR
- M-testing-02 · no aplica a este documento de prueba, que sólo agrega texto sin código — evidencia: el diff del PR
- M-testing-03 · no aplica a este documento de prueba, que sólo agrega texto sin código — evidencia: el diff del PR
- M-testing-04 · no aplica a este documento de prueba, que sólo agrega texto sin código — evidencia: el diff del PR
- M-testing-05 · no aplica a este documento de prueba, que sólo agrega texto sin código — evidencia: el diff del PR
- M-testing-06 · no aplica a este documento de prueba, que sólo agrega texto sin código — evidencia: el diff del PR
- M-testing-07 · no aplica a este documento de prueba, que sólo agrega texto sin código — evidencia: el diff del PR
- M-testing-08 · no aplica a este documento de prueba, que sólo agrega texto sin código — evidencia: el diff del PR
- M-testing-09 · no aplica a este documento de prueba, que sólo agrega texto sin código — evidencia: el diff del PR
- M-testing-10 · no aplica a este documento de prueba, que sólo agrega texto sin código — evidencia: el diff del PR
- M-testing-11 · no aplica a este documento de prueba, que sólo agrega texto sin código — evidencia: el diff del PR
- M-testing-12 · no aplica a este documento de prueba, que sólo agrega texto sin código — evidencia: el diff del PR
- M-testing-13 · no aplica a este documento de prueba, que sólo agrega texto sin código — evidencia: el diff del PR
- M-testing-14 · no aplica a este documento de prueba, que sólo agrega texto sin código — evidencia: el diff del PR
- M-testing-15 · no aplica a este documento de prueba, que sólo agrega texto sin código — evidencia: el diff del PR
- M-testing-16 · no aplica a este documento de prueba, que sólo agrega texto sin código — evidencia: el diff del PR
- M-testing-17 · no aplica a este documento de prueba, que sólo agrega texto sin código — evidencia: el diff del PR
- M-testing-18 · no aplica a este documento de prueba, que sólo agrega texto sin código — evidencia: el diff del PR

## OK del owner

Pendiente: el owner todavía no comentó el OK en el issue.
