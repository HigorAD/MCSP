# Pacote de imagens — Missão: Monte seu PC

Este pacote contém três opções visuais completas para o jogo da oficina:

- `opcao_1_vetorial`: ilustração 2D limpa e colorida;
- `opcao_2_pixel_art`: visual de jogo retrô em pixel art;
- `opcao_3_3d`: ilustração 3D estilizada.

Para manter a identidade visual do jogo, recomenda-se escolher uma pasta e usar todos os elementos dela.

## Arquivos e objetos no GDevelop

| Arquivo | Nome sugerido do objeto | Tipo de objeto |
|---|---|---|
| `jogador.png` | `Jogador` | Sprite |
| `robo.png` | `Robo` | Sprite |
| `placa_mae.png` | `PlacaMae` | Sprite |
| `processador.png` | `Processador` | Sprite |
| `memoria_ram.png` | `MemoriaRAM` | Sprite |
| `ssd.png` | `SSD` | Sprite |
| `placa_video.png` | `PlacaVideo` | Sprite |
| `fonte.png` | `Fonte` | Sprite |
| `computador_montado.png` | `ComputadorMontado` | Sprite |
| `computador_incompleto.png` | `ComputadorIncompleto` | Sprite |
| `fundo_laboratorio.png` | `FundoLaboratorio` | Sprite ou Painel de mosaico |

## Dimensões

- Personagens, componentes e computadores: `512 × 512 px`, com fundo transparente.
- Cenário do laboratório: `1280 × 720 px`.

## Como importar

1. Abra a cena **Jogo** no GDevelop.
2. Crie ou edite o objeto correspondente.
3. Escolha o tipo **Sprite**.
4. Adicione a imagem da opção visual selecionada.
5. Ajuste o tamanho do objeto na cena sem alterar a proporção.
6. Para o cenário, coloque `FundoLaboratorio` atrás dos demais objetos.

## Sugestão de tamanhos na cena

- `Jogador`: entre 80 e 110 px de altura.
- `Robo`: entre 80 e 110 px de altura.
- Componentes coletáveis: entre 45 e 70 px.
- Computador montado ou incompleto: entre 120 e 180 px.

Os tamanhos são apenas um ponto de partida e podem ser ajustados conforme a resolução escolhida para o jogo.
