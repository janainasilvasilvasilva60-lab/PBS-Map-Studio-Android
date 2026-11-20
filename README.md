# PBS Map Studio 0.26.13

Atualização experimental construída sobre a versão 0.26.11.

## Abrir no celular ou computador
Extraia o ZIP e abra `index.html` em navegador moderno com internet (Three.js é carregado por CDN).

## Mudanças nesta versão
- Viewport 3D maior e mais espaço de câmera/zoom.
- Removida a névoa que escurecia a cena à distância.
- Botões de desfazer/refazer para transformações e operações de lista (criar/importar, duplicar, excluir), com histórico de estados.
- Modo de seleção por face/triângulo que mostra o índice da face selecionada.
- Importação de imagem com recorte configurável por porcentagem (largura, altura e posição), antes de aplicar ao canvas de textura.
- Desfazer/refazer pintura no canvas.
- Interface adaptada para viewport maior e modo fullscreen.
- Importadores OBJ/MTL e 3DS existentes mantidos.

## Limitações importantes / o que ainda não é completo
- O modo face identifica a face/triângulo clicado, mas ainda não atribui materiais/texturas de forma independente por face.
- Recorte de imagem usa caixas de diálogo de porcentagem, não uma interface de recorte arrastável.
- Undo/redo geral cobre estados de objetos e transformações; não é um histórico unificado para cada edição de textura.
- 3DS/OBJ continuam dependentes dos importadores existentes; arquivos com materiais externos podem exigir que texturas/MTL estejam disponíveis e compatíveis.
- Não exporta mapa final de Proton Bus nem gera APK neste pacote.
- Não foi possível executar teste visual em navegador/Android nesta sessão; apenas conferência de sintaxe do JavaScript foi realizada.

## Conteúdo
- `index.html` — app web principal
- `assets/app-icon.png` — ícone existente
