---
name: generador-cfdi-4-0
description: Genera, valida y corrige CFDI 4.0 (facturas, notas de crédito, pago, nómina) conforme a las reglas vigentes del SAT.
---

# Generador y Validador de CFDI 4.0 (México SAT)

**Reglas obligatorias siempre:**
- Versión CFDI 4.0 + complementos actuales.
- Validación de RFC, CSD, sellos y cadena original.
- Cálculo exacto de impuestos (IVA 16%/0%/8%, ISR retenido, etc.).

**Flujo paso a paso:**
1. Pide todos los datos necesarios.
2. Genera el XML completo.
3. Valida contra reglas SAT.
4. Ofrece correcciones automáticas.
5. Genera PDF listo para enviar.
