# Karpathy Skill (one-file)

**Fuente:** AICodeKing — Karpathy-Skill (síntesis)

## Descripción
Skill minimalista inspirada en la filosofía de Andrej Karpathy: "Let's build software that writes software". Diseñada para Claude/Pi/OpenCode como un archivo único y fácil de entender que permite al agente auto-extenderse y aplicar reglas simples de estilo y comportamiento.

## Cuándo usar
- Cuando necesitás que el agente genere código o skills y querés evitar complejidad.
- Para proyectos donde la reproducibilidad y la explicabilidad importan.

## Instrucciones (para el agente)
1. Si el usuario pide una nueva skill, generar un archivo único `SKILL.md` con:
   - Nombre
   - Cuándo usar
   - Lista de pasos concretos
   - Anti-patrones
   - Ejemplos mínimos de uso
2. Preferir soluciones de una sola responsabilidad.
3. Evitar dependencias externas innecesarias.
4. Si el skill modifica archivos, crear un commit provisional y describir cambios en el mensaje del commit.

## Plantilla (one-file)
```markdown
# NombreSkill

## Cuando usar
- Breve frase

## Pasos
1. Paso 1
2. Paso 2

## Anti-patrones
- ❌ No hacer X

## Ejemplo
- Comando de ejemplo o prompt
```

## Buenas prácticas
- Mantener el archivo < 500 líneas
- Documentar la intención antes del código
- Incluir ejemplos reproducibles
- Mantener las instrucciones orientadas a acciones

## Notas
- Este SKILL.md es el source-of-truth. Mantenerlo versionado por Git.
- El agente puede editar este archivo para extenderse, pero debe dejar claro en el commit message qué cambió y por qué.

---

(Esquina: minimalista, legible y práctica — Karpathy style.)
