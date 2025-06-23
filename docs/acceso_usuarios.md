# Políticas de Acceso a Usuarios

Se simulan 3 roles en el equipo:

### Roles:

- **Líder del Proyecto** (TechnoBlaa): Acceso completo, puede hacer push directo a `main` y `release`.
- **Desarrollador**: Trabaja con ramas `feature/` o `bugfix/`, hace Pull Requests.
- **Colaborador Externo**: Colabora mediante fork del repo y PR.

### Reglas:

- Solo el **líder** puede hacer push a `main` y `release`.
- Todos los cambios deben pasar por Pull Request.
