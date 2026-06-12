## 🤖 Comandos de IA Disponibles

Tu bot ahora tiene **inteligencia artificial** integrada con Claude. Aquí están todos los comandos:

### 🌡️ Comandos de Clima
| Comando | Alias | Descripción |
|---------|-------|-------------|
| `!weather <ciudad>` | `!w` | Clima actual de una ciudad |
| `!forecast <ciudad>` | `!f` | Pronóstico de 5 días |

### 🧠 Comandos de IA (¡NUEVO!)
| Comando | Alias | Descripción |
|---------|-------|-------------|
| `!analyze <ciudad>` | `!a` | 🤖 Análisis inteligente del clima |
| `!activities <ciudad>` | `!act` | 🎯 Recomendaciones de actividades |
| `!interpret <ciudad>` | `!int` | 📊 Interpretación del pronóstico |
| `!ask <pregunta>` | - | 💬 Pregunta lo que quieras a Claude |

### ⚙️ Otros
| Comando | Descripción |
|---------|-------------|
| `!help` | Mostrar esta ayuda |
| `!ping` | Verificar latencia |

---

## 📝 Ejemplos de Uso

### Análisis de Clima con IA
```
!analyze New York
```
Claude analizará las condiciones actuales y dará recomendaciones inteligentes.

### Actividades Recomendadas
```
!activities London
```
El bot sugerirá 3 actividades divertidas basadas en el clima.

### Interpretación del Pronóstico
```
!interpret Tokyo
```
Claude analizará la tendencia de 5 días y te dirá qué esperar.

### Preguntar a Claude
```
!ask ¿Cuál es la mejor ropa para llevar en clima templado?
!ask ¿Cómo afecta la humedad a mi salud?
!ask ¿Qué es un frente frío?
```

---

## 🌐 Endpoints de API Web

Si usas el dashboard web, tienes estos endpoints:

### Análisis de Clima
```
GET /api/analyze/:ciudad
```

### Actividades Recomendadas
```
GET /api/activities/:ciudad
```

### Preguntar a Claude
```
POST /api/ask
Content-Type: application/json

{
  "question": "tu pregunta aquí"
}
```

---

## ⚡ Características de IA

✨ **Lo que Claude puede hacer:**
- Analizar patrones de clima
- Hacer recomendaciones personalizadas
- Interpretar datos meteorológicos
- Responder preguntas sobre clima
- Sugerir actividades según el tiempo
- ¡Y mucho más!

---

## 🚀 Cómo Empezar

1. **Inicia el bot:**
   ```bash
   npm start
   ```

2. **En Discord, escribe:**
   ```
   !help
   ```

3. **Prueba los comandos de IA:**
   ```
   !analyze Madrid
   !activities Barcelona
   !ask ¿Cómo protegerme del calor?
   ```

---

## 💡 Consejos

- Los comandos de IA pueden tardar 2-3 segundos más (están procesando con Claude)
- Usa `!ask` para preguntas creativas y personalizadas
- Combina `!weather` + `!analyze` para obtener toda la información
- Los análisis son únicos cada vez que preguntas

---

**¡Disfruta tu bot inteligente! 🤖🌤️**
