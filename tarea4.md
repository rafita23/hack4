# Práctica 4: Herramientas y técnicas de seguridad para la web

**Fecha de publicación:** 15/11/2024  
**Fecha de presentación:** 22/11/2024  
**Curso:** Seguridad de Software (INF 633)  
**Objetivo:** Comprender y comparar herramientas de seguridad web para proteger aplicaciones.

---

## Introducción

Las herramientas de seguridad web son esenciales para identificar, analizar y mitigar vulnerabilidades en aplicaciones web. Ayudan a proteger contra ataques comunes como inyección SQL, XSS, y otros listados en OWASP Top Ten, asegurando un entorno más confiable tanto para desarrolladores como usuarios finales.

---

## Descripción de las Herramientas

### 1. **ModSecurity**
- **Descripción**: Es un firewall de aplicaciones web (WAF) de código abierto que protege las aplicaciones mediante la inspección de tráfico HTTP.
- **Características principales**:
  - Compatible con servidores como Apache, Nginx y IIS.
  - Soporta reglas personalizadas basadas en el estándar OWASP Core Rule Set (CRS).
  - Detección y mitigación de ataques en tiempo real.
- **Ventajas**:
  - Gratuito y de código abierto.
  - Configuración flexible mediante reglas personalizadas.
  - Amplia comunidad de soporte.
- **Limitaciones**:
  - Requiere conocimientos técnicos avanzados para configurarlo correctamente.
  - Puede generar falsos positivos si no se ajustan las reglas adecuadamente.

---

### 2. **OWASP ZAP**
- **Descripción**: Es una herramienta gratuita y de código abierto diseñada para probar la seguridad de aplicaciones web mediante pruebas automatizadas y exploración manual.
- **Características principales**:
  - Exploración activa y pasiva de vulnerabilidades.
  - Proxy para interceptar y analizar tráfico HTTP.
  - Scripts personalizados para pruebas avanzadas.
- **Ventajas**:
  - Ideal para principiantes y expertos en pruebas de seguridad.
  - Interfaz gráfica amigable.
  - Actualizaciones frecuentes de vulnerabilidades conocidas.
- **Limitaciones**:
  - Limitado en capacidades avanzadas de escaneo automatizado en comparación con herramientas comerciales.
  - Puede ser lento en aplicaciones grandes.

---

### 3. **Acunetix**
- **Descripción**: Es una herramienta comercial automatizada para el análisis de seguridad en aplicaciones web, especializada en la detección de vulnerabilidades como SQLi y XSS.
- **Características principales**:
  - Escaneo automatizado de aplicaciones web y APIs.
  - Informes detallados sobre vulnerabilidades encontradas.
  - Integración con herramientas de desarrollo como Jenkins.
- **Ventajas**:
  - Alta precisión en la detección de vulnerabilidades.
  - Interfaz intuitiva con reportes personalizables.
  - Soporte técnico dedicado.
- **Limitaciones**:
  - Es una herramienta paga, lo que puede ser costoso para pequeñas empresas.
  - Dependencia de licencias para acceder a todas las funcionalidades.

---

## Comparación de Herramientas

| Herramienta     | Costo          | Facilidad de uso   | Capacidades de análisis       | Escenarios recomendados             |
|------------------|----------------|--------------------|--------------------------------|-------------------------------------|
| **ModSecurity**  | Gratuito       | Media              | Análisis basado en reglas      | Servidores web empresariales       |
| **OWASP ZAP**    | Gratuito       | Alta               | Exploración activa y pasiva    | Entornos académicos y startups     |
| **Acunetix**     | Comercial      | Alta               | Análisis avanzado y detallado  | Aplicaciones empresariales grandes |

---

## Conclusión

Para una pequeña empresa con recursos limitados, elegiría **OWASP ZAP** debido a su facilidad de uso, costo gratuito y capacidades suficientes para detectar vulnerabilidades comunes. Sin embargo, para una aplicación empresarial de gran escala donde la precisión y los reportes avanzados son esenciales, optaría por **Acunetix**.

**Justificación**:
- OWASP ZAP es ideal para aprender y realizar pruebas iniciales, lo que la hace perfecta para entornos con menos presupuesto.
- Acunetix, aunque costoso, proporciona una solución más completa para empresas que requieren análisis detallados y soporte técnico especializado.

---

## Referencias
- [OWASP ZAP](https://owasp.org/www-project-zap/)  
- [ModSecurity](https://modsecurity.org/)  
- [Acunetix](https://www.acunetix.com/)

---
