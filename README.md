# Vocaloid / Utauloid Songs Database

Este repositório contém um arquivo JSON com mais de 500 músicas famosas de Vocaloid e Utauloid, incluindo informações como nome, artista, vocaloid utilizado e duração.

---

## Formato dos Dados

Cada música segue a estrutura abaixo:

```json
{
  "name": "Nome da Música",
  "artist": "Produtor/Compositor",
  "vocaloid": "Vocaloid/Utauloid utilizado",
  "duration": "mm:ss"
}
```

---

## Como Usar

Você pode baixar o arquivo diretamente:

```bash
curl -O https://raw.githubusercontent.com/seu-usuario/vocaloid-songs/main/songs.json
```

Ou importar em seus projetos:

**JavaScript/Node.js:**

```javascript
const songs = require('./songs.json');
console.log(songs[0].name);
```

**Python:**

```python
import json

with open('songs.json', 'r', encoding='utf-8') as f:
    songs = json.load(f)
    print(songs[0]['name'])
```

---

## Licença

Este projeto está licenciado sob a licença MIT – sinta-se à vontade para usar e modificar.
