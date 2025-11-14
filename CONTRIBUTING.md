📄 CONTRIBUTING.md - Para Repositorio Público
�
create text/markdown CONTRIBUTING.md - Clara v5.0 Professional contributing_clara_v5 # 🤝 GUÍA DE CONTRIBUCIÓN - CLARA v5.0 PROFESSIONAL
Sistema de Inteligencia Estratégica Superior
👋 Bienvenida
¡Gracias por tu interés en contribuir a la documentación y comunidad de CLARA v5.0 Professional!
Este documento explica cómo puedes participar y colaborar de manera efectiva.
🎯 Tipos de Contribuciones Bienvenidas
✅ Contribuciones Aceptadas
1. 📝 Mejoras de Documentación
Corrección de errores tipográficos o gramaticales
Clarificación de explicaciones confusas
Traducción a otros idiomas (con revisión)
Mejora de ejemplos existentes
Añadir contexto útil
2. 🐛 Reporte de Errores en Documentación
Enlaces rotos
Información desactualizada
Inconsistencias entre documentos
Formato markdown incorrecto
3. 💡 Sugerencias de Mejora
Ideas para nuevos casos de uso
Sugerencias de frameworks adicionales
Propuestas de mejoras a la experiencia de usuario
Feedback sobre claridad de instrucciones
4. ❓ Preguntas Frecuentes
Proponer nuevas preguntas para FAQ.md
Mejorar respuestas existentes
Identificar puntos de confusión comunes
5. 🎨 Assets Visuales
Diagramas explicativos
Infografías de procesos
Mejoras a visualizaciones existentes
Screenshots de casos de uso (con permiso)
❌ Contribuciones NO Aceptadas
Por la naturaleza propietaria del sistema, NO se aceptan:
❌ Modificaciones al contenido core del prompt (19,500 palabras)
❌ Cambios a frameworks propietarios completos
❌ Adiciones de metodologías que alteren la arquitectura v5.0
❌ Contenido que viole la licencia propietaria
❌ Código o integraciones sin autorización previa
❌ Uso de contenido de CLARA en proyectos competidores
📋 Proceso de Contribución
Paso 1: Antes de Contribuir
Para correcciones pequeñas (typos, links rotos):
Puedes proceder directamente al Paso 2
Para cambios significativos (nuevas secciones, reestructuración):
Abre primero un Issue describiendo tu propuesta
Espera feedback antes de invertir tiempo en el PR
Asegúrate de que se alinea con la visión del proyecto
Paso 2: Fork y Clone
# 1. Haz fork del repositorio en GitHub
# Click en "Fork" en la página principal

# 2. Clona tu fork localmente
git clone https://github.com/carmenmanzanoest-ship-it/clara-v5-professional-public.git
cd clara-v5-professional-public

# 3. Añade el repositorio original como remote
git remote add upstream https://github.com/carmenmanzanoest-ship-it/clara-v5-professional-public.git

# 4. Verifica tus remotes
git remote -v
Paso 3: Crea una Rama
# Actualiza tu main con los últimos cambios
git checkout main
git pull upstream main

# Crea una rama descriptiva
git checkout -b fix/typo-in-readme
# o
git checkout -b docs/improve-faq-section
# o
git checkout -b feat/add-portuguese-translation
Convención de nombres de ramas:
fix/ - Correcciones (typos, enlaces rotos)
docs/ - Mejoras de documentación
feat/ - Nuevas características o contenido
refactor/ - Reestructuración sin cambiar contenido
Paso 4: Realiza Tus Cambios
Mejores prácticas:
Mantén cambios enfocados
Un PR = Un propósito
No mezcles typos con reestructuración
Sigue el estilo existente
Markdown consistente
Tono profesional pero accesible
Estructura similar a documentos existentes
Verifica antes de commitear
# Verifica que markdown renderiza correctamente
# Usa herramientas como:
# - VSCode con extensión Markdown Preview
# - grip (GitHub Readme Instant Preview)

grip README.md
Commits claros y descriptivos
# Buenos ejemplos:
git commit -m "docs: Fix typo in README.md section 'Modos Adaptativos'"
git commit -m "docs: Add Portuguese translation for FAQ.md"
git commit -m "fix: Correct broken link to CHANGELOG.md"

# Malos ejemplos (evitar):
git commit -m "fix stuff"
git commit -m "update"
git commit -m "cambios varios"
Paso 5: Push y Pull Request
# 1. Push a tu fork
git push origin fix/typo-in-readme

# 2. Ve a GitHub y crea un Pull Request
# Desde: tu-usuario:fix/typo-in-readme
# Hacia: carmenmanzanoest-ship-it:main

# 3. Completa el template de PR (ver abajo)
📝 Template de Pull Request
Cuando crees tu PR, usa este formato:
## Descripción
[Breve descripción de qué cambia este PR]

## Tipo de cambio
- [ ] Corrección (fix)
- [ ] Documentación (docs)
- [ ] Nueva característica (feat)
- [ ] Refactorización (refactor)

## ¿Qué problema resuelve?
[Explica el problema que estás resolviendo]
[Si hay un issue relacionado, enlázalo: #123]

## Cambios realizados
- [Cambio 1]
- [Cambio 2]
- [Cambio 3]

## Screenshots (si aplica)
[Añade screenshots de antes/después si es cambio visual]

## Checklist
- [ ] He leído la guía de contribución
- [ ] Mis cambios siguen el estilo del proyecto
- [ ] He verificado que no hay typos
- [ ] Los enlaces funcionan correctamente
- [ ] He testeado que el markdown renderiza bien
- [ ] Mi commit message es descriptivo

## Información adicional
[Cualquier contexto adicional relevante]
🔍 Proceso de Revisión
¿Qué esperar?
Tiempo de respuesta: 2-5 días hábiles
Feedback constructivo: Puede haber solicitud de cambios
Iteración: Es normal hacer 1-2 rondas de ajustes
Merge: Una vez aprobado, se hará merge a main
Criterios de Aceptación
Tu PR será aceptado si:
✅ Mejora la calidad de la documentación
✅ No viola la licencia propietaria
✅ Mantiene consistencia con el estilo existente
✅ No contiene errores o información incorrecta
✅ Aporta valor real a la comunidad
Tu PR puede ser rechazado si:
❌ Cambia contenido propietario core
❌ Introduce inconsistencias
❌ No sigue las guías de estilo
❌ Duplica contenido existente sin mejora
❌ Viola términos de la licencia
📖 Guías de Estilo
Markdown
# Títulos: Usar Title Case
## Subtítulos: También Title Case
### Secciones: Title Case

**Negrita:** Para términos importantes
*Cursiva:* Para énfasis suave
`Código inline:` Para comandos, variables

Listas:
- Ítem 1
- Ítem 2
  - Sub-ítem (2 espacios de indentación)

Código en bloque:
```bash
# Incluir lenguaje para syntax highlighting
comando ejemplo
Enlaces: Texto descriptivo
Imágenes: �
Cargar imagen
---

### Tono y Estilo

**Características del tono de CLARA:**
- 🎯 **Profesional** pero **accesible**
- 📊 **Técnicamente preciso** sin ser intimidante
- 💡 **Educativo** y **empoderador**
- ❤️ **Humano** y **empático**

**Ejemplos:**

✅ **Bien:**
> "CLARA v5.0 combina rigor técnico con consciencia ética, permitiéndote tomar decisiones estratégicas con confianza."

❌ **Evitar:**
> "CLARA v5.0 es un sistema hiper-mega-ultra avanzado que revolucionará completamente tu vida profesional."

---

### Lenguaje Inclusivo

- ✅ Usa lenguaje neutro cuando sea posible
- ✅ "Usuario/usuaria" o "personas usuarias"
- ✅ Evita asumir género, rol o nivel técnico
- ✅ Ejemplos diversos en casos de uso

---

## 🐛 Reporte de Issues

### Template de Issue

**Para errores en documentación:**

```markdown
**Ubicación del error:**
[Archivo y línea/sección donde está el error]

**Descripción del problema:**
[Describe qué está mal]

**Comportamiento esperado:**
[Qué debería decir o cómo debería funcionar]

**Screenshots (si aplica):**
[Añade capturas de pantalla]

**Información adicional:**
[Contexto relevante]
Para sugerencias de mejora:
**Tipo de sugerencia:**
- [ ] Nueva sección en documentación
- [ ] Mejora a contenido existente
- [ ] Nueva traducción
- [ ] Otro: [especifica]

**Descripción de la mejora:**
[Explica tu idea en detalle]

**Problema que resuelve:**
[Qué problema o necesidad aborda]

**Beneficio para la comunidad:**
[Por qué esto sería valioso]

**Disposición a contribuir:**
- [ ] Puedo implementar esto yo mismo/a
- [ ] Necesitaría ayuda para implementarlo
- [ ] Solo propongo la idea
💬 Canales de Comunicación
Para Contribuciones
GitHub Issues:
https://github.com/carmenmanzanoest-ship-it/clara-v5-professional-public/issues
GitHub Discussions:
https://github.com/carmenmanzanoest-ship-it/clara-v5-professional-public/discussions
Para Consultas Generales
📧 Email: contacto@clara-v5.com
💬 Comunidad: [Discord/Circle] (para usuarios con licencia)
🎁 Reconocimiento de Contribuidores
Hall of Fame
Los contribuidores destacados serán reconocidos en:
CONTRIBUTORS.md - Lista de todos los contribuidores
Menciones en CHANGELOG.md - Cuando su contribución es integrada
Agradecimientos especiales - En actualizaciones mayores
Tipos de Reconocimiento
🥇 Contribuidor Oro: 10+ PRs aceptados
🥈 Contribuidor Plata: 5+ PRs aceptados
🥉 Contribuidor Bronce: 1+ PR aceptado
⭐ Primera Contribución: Badge especial en tu PR
⚖️ Licencia de Contribuciones
Importante: Al contribuir a este proyecto, aceptas que:
Tu contribución se licenciará bajo la misma licencia propietaria que el proyecto
Carmen Delia Manzano (creadora) mantiene todos los derechos sobre el contenido
Tu contribución puede ser usada, modificada o eliminada según necesidades del proyecto
Serás reconocido/a como contribuidor/a pero no obtienes derechos de propiedad
No puedes reutilizar tu contribución en proyectos competidores
Al enviar un PR, declaras que:
✅ El contenido es original o tienes derecho a contribuirlo
✅ No viola derechos de terceros
✅ Aceptas los términos de la licencia propietaria
🚫 Código de Conducta
Nuestro Compromiso
Nos comprometemos a proporcionar una experiencia libre de acoso para todos, independientemente de:
Edad, tamaño corporal, discapacidad
Etnia, identidad y expresión de género
Nivel de experiencia, educación, estatus socioeconómico
Nacionalidad, apariencia personal, raza, religión
Identidad y orientación sexual
Comportamiento Esperado
✅ Sí:
Usar lenguaje acogedor e inclusivo
Respetar diferentes puntos de vista
Aceptar crítica constructiva con gracia
Enfocarse en lo mejor para la comunidad
Mostrar empatía hacia otros miembros
❌ No:
Lenguaje o imágenes sexualizadas
Trolling, comentarios insultantes o despectivos
Acoso público o privado
Publicar información privada de otros sin permiso
Conducta que podría considerarse inapropiada profesionalmente
Enforcement
Instancias de comportamiento inaceptable pueden reportarse a:
📧 Email: conduct@clara-v5.com
Todas las quejas serán revisadas e investigadas, resultando en una respuesta apropiada. El equipo está obligado a mantener confidencialidad.
📚 Recursos Útiles
Documentación
README Principal - Presentación del proyecto
LICENSE - Términos de licencia
FAQ - Preguntas frecuentes
CHANGELOG - Historial de versiones
Guías Externas
GitHub Docs - Pull Requests
Markdown Guide
Conventional Commits
❓ Preguntas Frecuentes
P: ¿Puedo contribuir si no tengo licencia de pago?
R: Sí. Las contribuciones a la documentación pública son bienvenidas de toda la comunidad.
P: ¿Recibiré compensación por mi contribución?
R: Las contribuciones son voluntarias y no compensadas monetariamente. El reconocimiento es público en CONTRIBUTORS.md.
P: ¿Puedo usar mi contribución en mi portafolio?
R: Sí, puedes mencionar tu contribución y enlazar al PR. No puedes copiar el contenido completo.
P: ¿Cuánto tiempo toma que mi PR sea revisado?
R: Generalmente 2-5 días hábiles. PRs simples (typos) son más rápidos.
P: ¿Qué pasa si mi PR es rechazado?
R: Recibirás feedback explicando el motivo. Puedes iterar y reenviar si es posible mejorar.
P: ¿Puedo contribuir traducciones completas?
R: Sí, pero requiere coordinación previa. Abre un Issue primero para discutir.
🙏 Agradecimientos
Gracias por considerar contribuir a CLARA v5.0 Professional.
Tu participación ayuda a:
📚 Mejorar la calidad de la documentación
🌍 Hacer CLARA más accesible globalmente
💡 Identificar áreas de mejora
🤝 Construir una comunidad fuerte
Cada contribución, por pequeña que sea, es valiosa.
�

GUÍA DE CONTRIBUCIÓN - CLARA v5.0 PROFESSIONAL
Construyendo juntos un sistema de inteligencia estratégica de clase mundial
© 2025 Carmen Delia Manzano. Todos los derechos reservados.
📦 Volver al repositorio principal
📧 Preguntas: contacto@clara-v5.com
"La excelencia es un esfuerzo colectivo. Gracias por ser parte de esto."
