# 🧘‍♂️ ProgramaZen API

Un repositorio público que funciona como una API estática para obtener frases que conectan conceptos del desarrollo de software y la programación con el bienestar diario y la psicología.

## 🚀 Cómo usar

Puedes consumir el endpoint realizando una petición `GET` a la siguiente URL Raw:

`https://raw.githubusercontent.com/monibe-code/ProgramaZen/main/ProgramaZen.json`

### Ejemplo de uso con Fetch:
```javascript
fetch('[https://raw.githubusercontent.com/monibe-code/ProgramaZen/main/ProgramaZen.json](https://raw.githubusercontent.com/monibe-code/ProgramaZen/main/ProgramaZen.json)')
  .then(response => response.json())
  .then(data => console.log(data.frases));
