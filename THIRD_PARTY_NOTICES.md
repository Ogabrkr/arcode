# Componentes de terceiros

O Arcode é proprietário (ver `LICENSE`). Os itens abaixo são de terceiros e continuam sob as
licenças dos seus autores. Eles **não** tornam o resto do projeto aberto.

| Componente | Onde | Licença |
|---|---|---|
| Template de projeto Expo (arquivos iniciais gerados por `create-expo-app`) | `apps/mobile` | MIT, © 650 Industries (Expo). Texto em `THIRD_PARTY_NOTICES-expo-template.txt` |
| Fluent Emoji (ícones coloridos) | `prototipo/icones`, `apps/mobile/assets/icons` | MIT, © Microsoft. Texto em `prototipo/icones/LICENSE` |
| Devicon (logos das linguagens) | `prototipo/logos` | MIT, © konpa. Texto em `prototipo/logos/LICENSE`. As marcas pertencem aos donos |
| UIcons (ícones de interface) | `prototipo/icones-ui`, `apps/mobile/assets/ui` | Licença gratuita da Flaticon, com atribuição ("Uicons by Flaticon"), exibida no app em Configurações |
| JetBrains Mono (sem ligaduras) | `apps/mobile/assets/fonts` | SIL Open Font License 1.1. Texto em `apps/mobile/assets/fonts/LICENSE_FONT` |
| Fredoka, Nunito, JetBrains Mono (Google Fonts via `@expo-google-fonts`) | dependências npm | SIL Open Font License 1.1 |
| Pyodide (Python no aparelho) | dependência npm `pyodide` 314.0.7 | MPL-2.0. O app inclui uma cópia do `pyodide.asm` com um ajuste feito pelo script de build; o fonte original está em https://github.com/pyodide/pyodide e o ajuste aplicado será disponibilizado a quem receber o app, como a MPL exige |
| CPython (dentro do Pyodide) | dependência npm `pyodide` | Python Software Foundation License |
| React Native, Expo SDK e demais dependências npm | `apps/mobile/package.json` | Licenças de cada pacote (em geral MIT) |

Os efeitos sonoros são sintetizados por `apps/mobile/scripts/gerar-sons.mjs` e o mascote Pip é
desenhado em código no próprio projeto.
