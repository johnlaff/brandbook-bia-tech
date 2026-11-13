# Visualizador 3D da BIA Tech

`Prévia 5.5.4` · `13/11/2026` · `Uso interno`

Página que mostra o modelo 3D da BIA Tech no navegador. Dá para girar a BIA, aproximar, trocar a animação e a expressão do rosto e ligar o modo análise, que deixa o modelo parado na pose neutra. É a mesma página do link citado na seção 16 do manual, agora guardada junto com o modelo.

## Como abrir

1. Baixe o ZIP do repositório e descompacte.
2. Abra `visualizador-3d/index.html` com dois cliques. Ele abre no navegador, sem instalar nada.

O modelo leva alguns segundos para aparecer. O Three.js vai embutido na página; só as fontes vêm da internet (Google Fonts) e, sem conexão, a página usa a fonte padrão do sistema.

Abrir o `index.html` pelo site do GitHub mostra só o código, não a página. Baixe a pasta antes.

## Arquivos

| Arquivo | Para que serve | Tamanho |
|---|---|---|
| `index.html` | A página, com o Three.js embutido | 0,7 MB |
| `bia-tech-web.0.txt` | O modelo e os fios de pelo, compactados sem perdas. É o que a página baixa quando está publicada num servidor | 7,5 MB |
| `bia-tech-web.0.js` | O mesmo conteúdo em forma de script. É o que a página usa quando é aberta direto do arquivo, sem servidor | 7,5 MB |
| `img/` | Wordmark b.ia tech e as 8 imagens da seção de animações | 0,7 MB |

Os quatro itens precisam ficar na mesma pasta.

## Controles

- **Girar:** arraste.
- **Aproximar:** pince, ou clique na BIA e role.
- **Mover:** dois dedos ou o botão direito do mouse.
- **Focar num ponto:** toque duplo ou clique duplo. No fundo, volta à vista inicial.
- **Teclado:** setas, `+` e `−`; espaço pausa.
- **Painel:** animação, expressão do rosto, vistas prontas, modo análise, girar sozinha, piscar, esqueleto, velocidade e qualidade (Auto, Alta ou Leve).

## Relação com o modelo

O visualizador mostra o mesmo modelo de [`10-modelo-3d/`](../10-modelo-3d/LEIAME.md), na mesma prévia. Quando o modelo muda, as duas pastas mudam juntas.

Valem as regras da seção 16 do manual: enquanto for prévia, o modelo serve para testes e peças internas.
