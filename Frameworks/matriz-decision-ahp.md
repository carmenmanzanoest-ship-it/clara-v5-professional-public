📄 DOCUMENTO 3: Carpeta Frameworks/ - Matriz de Decisión AHP
�
create text/markdown Frameworks/matriz-decision-ahp.md - Framework Muestra ahp_framework_muestra # 🎯 FRAMEWORK: MATRIZ DE DECISIÓN MULTICRITERIO (AHP)
Parte de la Biblioteca de 40+ Frameworks de CLARA v5.0 Professional
⚠️ NOTA: Esta es una versión de muestra simplificada. El sistema completo incluye calculadora Excel automática, metodología AHP completa de Saaty, y ejemplos de 15 casos reales.
🎯 ¿Qué es la Matriz de Decisión Multicriterio?
Una herramienta para tomar decisiones complejas comparando múltiples alternativas contra múltiples criterios con pesos diferentes.
Problema que resuelve:
"Tengo 5 opciones de software/proveedores/estrategias y 10 criterios a evaluar. ¿Cuál elijo?"
Método utilizado: AHP (Analytic Hierarchy Process) de Thomas Saaty
📋 ESTRUCTURA BÁSICA
PASO 1: Define Criterios y Pesos
┌─────────────────────────────────────────────────────────┐
│ CRITERIOS DE EVALUACIÓN                                 │
├──────────────────────┬──────────┬────────────────────────┤
│ Criterio             │ Peso (%) │ Justificación          │
├──────────────────────┼──────────┼────────────────────────┤
│ Costo Total (TCO)    │   30%    │ Presupuesto limitado   │
│ Funcionalidad        │   25%    │ Core requirement       │
│ Facilidad de uso     │   20%    │ Adopción usuario clave │
│ Soporte técnico      │   15%    │ Sin equipo IT interno  │
│ Escalabilidad        │   10%    │ Crecimiento proyectado │
├──────────────────────┼──────────┼────────────────────────┤
│ TOTAL                │  100%    │                        │
└──────────────────────┴──────────┴────────────────────────┘

⚠️ Regla: Suma de pesos = 100%
💡 Tip: El criterio más pesado no debe > 40% (evita sesgo excesivo)
PASO 2: Evalúa Cada Alternativa por Criterio
Escala de evaluación: 1-10 (donde 10 = excelente, 1 = pésimo)
┌──────────────┬───────┬───────┬───────┬───────┬───────┐
│ Criterio     │  Peso │ Opt A │ Opt B │ Opt C │ Mejor │
├──────────────┼───────┼───────┼───────┼───────┼───────┤
│ Costo TCO    │  30%  │  8.5  │  6.0  │  7.5  │   A   │
│ Funcionalidad│  25%  │  7.0  │  9.0  │  8.0  │   B   │
│ Facilidad uso│  20%  │  9.0  │  6.5  │  7.0  │   A   │
│ Soporte      │  15%  │  8.0  │  8.5  │  6.0  │   B   │
│ Escalabilidad│  10%  │  7.5  │  9.0  │  8.5  │   B   │
├──────────────┼───────┼───────┼───────┼───────┼───────┤
│ SCORE TOTAL  │ 100%  │ 7.93  │ 7.68  │ 7.43  │   A   │
└──────────────┴───────┴───────┴───────┴───────┴───────┘

FÓRMULA:
Score Total = Σ (Evaluación × Peso)

Opción A: (8.5×0.30) + (7.0×0.25) + (9.0×0.20) + (8.0×0.15) + (7.5×0.10)
        = 2.55 + 1.75 + 1.80 + 1.20 + 0.75 = 7.93
📖 EJEMPLO SIMPLIFICADO: Selección de CRM
Contexto
Empresa: Agencia de marketing digital, 25 empleados
Necesidad: CRM para gestionar 200+ clientes
Presupuesto: $15,000/año máximo
Timeline: Implementar en 60 días
Alternativas Evaluadas
Opción A: Salesforce Essentials
Opción B: HubSpot CRM Pro
Opción C: Zoho CRM Plus
Matriz Completa
═══════════════════════════════════════════════════════════
MATRIZ DE DECISIÓN: SELECCIÓN DE CRM
Agencia Marketing Digital | Presupuesto: $15K/año
═══════════════════════════════════════════════════════════

CRITERIOS Y PESOS:
┌────────────────────────┬────────┬──────────────────────┐
│ Criterio               │  Peso  │ Justificación        │
├────────────────────────┼────────┼──────────────────────┤
│ 1. Costo TCO (3 años)  │  30%   │ Budget tight         │
│ 2. Funcionalidad       │  25%   │ Must-have features   │
│ 3. Integraciones       │  20%   │ Conecta con stack    │
│ 4. Facilidad de uso    │  15%   │ Sin training extenso │
│ 5. Soporte en español  │  10%   │ Equipo no bilingüe   │
├────────────────────────┼────────┼──────────────────────┤
│ TOTAL                  │ 100%   │                      │
└────────────────────────┴────────┴──────────────────────┘

─────────────────────────────────────────────────────────

EVALUACIONES DETALLADAS:

┌──────────────┬───────┬────────────┬────────────┬────────────┐
│ Criterio     │ Peso  │ Salesforce │  HubSpot   │   Zoho     │
├──────────────┼───────┼────────────┼────────────┼────────────┤
│ Costo TCO    │  30%  │    6.5     │    8.0     │    9.0     │
│ Funcionalidad│  25%  │    9.5     │    9.0     │    7.5     │
│ Integraciones│  20%  │    8.0     │    9.5     │    7.0     │
│ Facilidad uso│  15%  │    6.0     │    8.5     │    8.0     │
│ Soporte ESP  │  10%  │    7.0     │    8.5     │    9.0     │
└──────────────┴───────┴────────────┴────────────┴────────────┘

─────────────────────────────────────────────────────────

CÁLCULO DE SCORES PONDERADOS:

Salesforce:
(6.5 × 0.30) + (9.5 × 0.25) + (8.0 × 0.20) + (6.0 × 0.15) + (7.0 × 0.10)
= 1.95 + 2.38 + 1.60 + 0.90 + 0.70 = 7.53 / 10

HubSpot:
(8.0 × 0.30) + (9.0 × 0.25) + (9.5 × 0.20) + (8.5 × 0.15) + (8.5 × 0.10)
= 2.40 + 2.25 + 1.90 + 1.28 + 0.85 = 8.68 / 10 ⭐

Zoho:
(9.0 × 0.30) + (7.5 × 0.25) + (7.0 × 0.20) + (8.0 × 0.15) + (9.0 × 0.10)
= 2.70 + 1.88 + 1.40 + 1.20 + 0.90 = 8.08 / 10

─────────────────────────────────────────────────────────

RESULTADO FINAL:

┌────────┬─────────────┬──────────────┬──────────┐
│ Ranking│ Proveedor   │ Score Final  │ Decisión │
├────────┼─────────────┼──────────────┼──────────┤
│  🥇 1  │ HubSpot     │  8.68 / 10   │ ELEGIR   │
│  🥈 2  │ Zoho        │  8.08 / 10   │ Backup   │
│  🥉 3  │ Salesforce  │  7.53 / 10   │ Descarte │
└────────┴─────────────┴──────────────┴──────────┘

═══════════════════════════════════════════════════════════
Recomendación con Justificación
✅ RECOMENDACIÓN: HubSpot CRM Pro

RAZONES:
1. Score más alto (8.68 vs 8.08 vs 7.53)
2. Mejor balance entre criterios clave
3. Integraciones nativas con stack actual
4. Equipo puede adoptar rápidamente
5. Soporte en español crucial

ANÁLISIS DE SENSIBILIDAD:
Si peso de "Costo" bajara a 20%:
→ HubSpot mantiene liderazgo (8.60)
→ Decisión es robusta

RIESGOS:
⚠️ Costo $12K/año vs. Zoho $9K/año
✓ Mitigación: ROI justifica diferencia

PRÓXIMOS PASOS:
1. Demo personalizada HubSpot (30 días prueba)
2. Validar integraciones con equipo técnico
3. Negociar descuento anual (-10%)
💡 LO QUE OBTIENES EN EL SISTEMA COMPLETO
Este ejemplo es ~15% del framework completo en CLARA v5.0:
❌ NO Incluido en Esta Muestra:
Calculadora Excel Automatizada
Ingresa datos, calcula automáticamente
Análisis de sensibilidad con sliders
Gráficos de radar comparativos
Metodología AHP Completa de Saaty
Comparaciones pareadas
Índice de consistencia
Detección de inconsistencias
15 Ejemplos Reales Completos
Software (CRM, ERP, BI)
Proveedores
Inversiones
Estrategias
Hiring
Ubicaciones
Guía de Facilitación
Cómo definir criterios con stakeholders
Cómo asignar pesos sin sesgos
Script de 2 horas para sesión grupal
Integración Multidimensional (v5.0)
Dimensión ética integrada
Scoring dual: técnico + valores
Matriz de trade-offs
Variantes Avanzadas
TOPSIS
ELECTRE
PROMETHEE
🚀 ¿Quieres el Framework Completo?
Este es solo 1 de los 40+ frameworks profesionales incluidos en CLARA v5.0 Professional.
🛒 Obtener CLARA v5.0 Professional
📞 ¿Preguntas?
📧 Email: soporte@clara-v5.com
📚 Docs: Documentación Completa
�

MATRIZ DE DECISIÓN MULTICRITERIO (AHP)
Parte de CLARA v5.0 Professional
📖 Ver todos los frameworks
📦 Volver al repositorio
© 2025 Carmen Delia Manzano. Todos los derechos reservados
