# Modelo 3D da BIA Tech

`Prévia 5.5.4` · `13/11/2026` · `Uso interno`

Modelo 3D da BIA Tech com esqueleto, animações e expressões, feito a partir do turnaround e do retrato oficial (`08-personagem/fichas/`). As vistas, as animações e as regras de uso estão na seção 16 do manual (`brandbook-html/index.html`).

Para ver o modelo no navegador, sem instalar nada, abra o visualizador em [`visualizador-3d/`](../visualizador-3d/LEIAME.md).

## Arquivos

| Arquivo | Para que serve | Tamanho |
|---|---|---|
| `bia-tech.blend` | Arquivo de trabalho do Blender 5.3 ou mais novo, com luzes de estúdio e câmera. Para renders, poses novas e animações | 82 MB |
| `textures/` | As 10 texturas do `.blend`, em PNG | 32 MB |
| `bia-tech.glb` | Modelo completo com esqueleto e animações, para outros programas 3D e motores de jogo | 24,7 MB |
| `bia-tech-web.glb` | Versão leve para sites e apps, com texturas em WebP e malha quantizada | 12,6 MB |

## Como abrir

- **Blender:** abra `bia-tech.blend` no Blender 5.3 ou mais novo, com a pasta `textures/` ao lado do arquivo. As texturas ficam fora do `.blend` porque o GitHub não aceita arquivos acima de 100 MB. Se o modelo abrir cor-de-rosa, a pasta não está no lugar: use **Arquivo → Dados externos → Localizar arquivos ausentes** e aponte para `textures/`.
- **GLB:** `bia-tech.glb` abre em qualquer programa que leia glTF 2.0 (Blender, Unity, Unreal, Godot, visualizadores de glTF).
- **Web:** `bia-tech-web.glb` usa as extensões `EXT_texture_webp` e `KHR_mesh_quantization`. O three.js lê as duas sem configuração extra.

## O que vem no modelo

| Item | Valor |
|---|---|
| Malha | 295.400 triângulos, em peças separadas: corpo e figurino, cabeça, rosto, olhos, boca, óculos, lente e HUD |
| Escala | Em metros. A BIA mede 1,25 m da sola das botas à ponta das orelhas |
| Esqueleto | 101 ossos (`BIA_Tech_Rig`), com ossos próprios para orelhas, cauda, mandíbula e cantos da boca |
| Animações de corpo | `Parada` (4 s), `Acenando` (5,3 s), `Explicando` (4 s), `Concordando` (13 s), `Comemorando` (9,8 s), `DandoDeOmbros` (2 s), `Andando` (1 s, em laço) e `Correndo` (0,6 s, em laço) |
| Expressões de rosto | `Expr_Neutra`, `Expr_Sorriso`, `Expr_Conversando`, `Expr_Gargalhada`, `Expr_Surpresa`, `Expr_Pensativa`, `Expr_Piscadela`, `Expr_Piscar`, `Expr_Preocupada`, `Expr_Determinada` e `Expr_Empolgada`, cada uma como uma pose de um quadro |
| Texturas | Cor, normal, ORM (oclusão, rugosidade e metal) e emissão em 4096 × 4096 px, mais as dos olhos, do rosto, do HUD e da malha do abdômen |
| Pelo | Curvas de pelo no `.blend`. Nos GLB vai a pelagem como superfície pintada; as camadas e os fios de pelo do visualizador são desenhados por ele em tempo real |

## Regras de uso

- As 14 marcas da anatomia (seção 03 do manual) valem em 3D: 2 braços, 3 dedos + polegar, os dois olhos castanhos, HUD sobre o olho direito dela e crachá no peito esquerdo dela.
- Anime pelo esqueleto. Não escale ossos nem a malha para mudar as proporções.
- Use os materiais e as texturas do arquivo. Não recolora o pelo nem o figurino.
- Não espelhe o modelo e não coloque logos em objetos de cena.
- Render que vira peça passa pela checklist da seção 15 do manual e pela aprovação da equipe b.ia tech.

## Limites desta prévia

O modelo ainda está em revisão contra as fichas. O que difere hoje: o topete é mais largo e mais em pé que a mecha do retrato, a divisa entre o pelo branco e o vermelho da bochecha é mais reta de perfil, as orelhas têm a borda mais grossa e a ponta mais arredondada, e as botas e as bolsas do cinto têm superfície lisa, sem o grão do couro. Enquanto for prévia, use o modelo em testes e peças internas.
