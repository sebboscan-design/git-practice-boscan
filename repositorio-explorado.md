# Repositorio Explorado

- **Nombre:** JSON for Modern C++
- **Autor:** Niels Lohmann (nlohmann)
- **URL:** https://github.com/nlohmann/json
- **Qué hace:** Librería de un solo archivo (`json.hpp`) para leer, crear y escribir JSON en C++ con una sintaxis parecida a la de Python o JavaScript.

## Comandos usados
- `git clone https://github.com/nlohmann/json.git`
- `git log --oneline -10`
- `git remote -v`
- `git show <hash>`

## Commits interesantes
- `5683f5e` Define less_general() only without three-way comparison (#5859): ajuste para compiladores con el operador `<=>` de C++20.
- `4da73dc` Fix compiler warnings on develop from the API performance stack (#5858): elimina advertencias del compilador.
- `dcb96e8` Escape characters below 0x60 from a table straight into the write buffer (#5822): mejora de rendimiento al escribir JSON.
- `c7fd5ac` Bump the codeql-action group with 4 updates (#5846): actualización automática de dependencias (Dependabot).

## Lo que aprendí
- Los mensajes de commit son cortos, en imperativo y enlazan al Pull Request (`#número`).
- Muchos commits los hacen bots que actualizan dependencias.
- `git remote -v` muestra que `origin` apunta al repositorio original.
