# Apuntes de Claude Code

Apuntes de una formación completa sobre los flujos agénticos de Claude Code — desde la configuración base hasta orquestar equipos de agentes en producción. Construidos y probados contra un proyecto real, no a partir de teoría suelta.

## 🔗 Ver la web

👉 **https://juandamt.github.io/apuntes-claude-code/#hooks**

## Qué cubre

- **Fundamentos** — CLAUDE.md, permisos y modos, MCP
- **El bucle de trabajo** — verificación, plan mode, gestión de contexto
- **Subagentes** — frontmatter completo, invocación proactiva vs. manual
- **Hooks** — eventos, exit codes, automatización determinista
- **Skills** — conocimiento reutilizable bajo demanda
- **Plugins** — empaquetar y distribuir todo lo anterior
- **Paralelismo** — git worktrees, agent teams
- **Automatización en producción** — GitHub Actions, routines, `/goal`
- **Coste y economía de tokens**

## Cómo verlo en local

No requiere instalación ni build — es un único archivo HTML autocontenido.

```bash
git clone https://github.com/JuandaMT/apuntes-claude-code.git
cd apuntes-claude-code
open index.html   # o ábrelo directamente en el navegador
```

## Estado

En construcción activa — se amplía a medida que avanza el aprendizaje.

**Pendiente:**
- [ ] Sección de seguridad del agente (prompt injection, riesgos de MCP y plugins)

## Cómo está hecho

Un único archivo HTML/CSS/JS sin dependencias de build, pensado para ser fácil de desplegar (GitHub Pages, Netlify) y fácil de editar directamente sin herramientas adicionales.

## Contribuir

Es un documento vivo. Si algo está desactualizado — y con Claude Code cambiando cada pocas semanas, tarde o temprano lo estará — un PR o un issue son bienvenidos.

---

Escrito por [Juanda](https://github.com/JuandaMT), con Claude como profesor.
