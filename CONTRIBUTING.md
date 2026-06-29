# Contribuir a VELAR

¡Gracias por tu interés! VELAR es infraestructura pública para la trazabilidad de
bonos políticos sobre Stellar. Estas pautas aplican a todos los repos de la org.

## Flujo

1. Hacé fork o creá una rama desde `main`: `feat/<descripción>` o `fix/<descripción>`.
2. Hacé commits convencionales en español: `feat: ...`, `fix: ...`, `docs: ...`, `chore: ...`.
3. Antes de abrir el PR, corré los checks del repo (`npm run typecheck`, `cargo test`, etc.).
4. Abrí el PR contra `main` describiendo **qué** cambió y **por qué**. Enlazá el issue.

## Reglas

- No rompas funcionalidad existente. Sumá tests cuando agregues lógica.
- Respetá la división backend / frontend (ver `docs/AGENTS.md` en el monorepo).
- Para cambios grandes, abrí primero un issue para discutir el enfoque.

## Repos

| Repo | Qué es |
|---|---|
| [Velar](https://github.com/Velar-Bonds/Velar) | Monorepo principal (API + Web + contrato + DB) |
| [velar-docs](https://github.com/Velar-Bonds/velar-docs) | Documentación |
