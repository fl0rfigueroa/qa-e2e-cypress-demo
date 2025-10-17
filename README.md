### 🖱️ Proyecto QA E2E - Drag & Drop

**Sitio de práctica:** [The Internet Herokuapp](https://the-internet.herokuapp.com/drag_and_drop)

**Objetivo:** Validar la funcionalidad de intercambio de cajas mediante acción de arrastrar y soltar.

**Cobertura:**
- Interacción avanzada con el DOM.
- Validación del cambio de posición.
- Reporter HTML con evidencia visual.

**Ejecución:**
```bash
npx cypress run --spec "cypress/e2e/drag_and_drop.cy.ts"
