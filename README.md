# Panco × 75 LAB · Presença no PDV

Apresentação comercial da 75 LAB para a Panco: organizar todas as categorias da Panco no ponto de venda em três frentes (gôndola, pontos extras e controle por QR).

Link público: https://projetos.75lab.com.br/panco-75lab-deck/

## Arquivos

- `index.html`: o deck inteiro (palco fixo 1600 × 900 escalado, 14 telas). Setas ou espaço navegam, `M` abre o índice, `P` abre as outras oportunidades.
- `qr/index.html`: a página que abre quando alguém escaneia o QR de demonstração (tela 11). Tem a vista do shopper e a do promotor; nada é enviado para servidor.
- `assets/`: imagens extraídas do deck original (renders, fotos do Trade Visit, peças), logos e a fonte Nunito.
- `vendor/`: `model-viewer` (AR da tela 10) e `qrcode-generator` (QR gerados na própria página).
- `fonte/original.html`: o deck recebido, com as imagens já apontando para `assets/`.

## O que tem em cada tela

Capa com as duas marcas, a 75 LAB em números, o percurso, o contexto de mercado (ABIMAPI e ABRAS), a dor ligada às fotos da loja, dores × frentes com as conexões, a gôndola, os pontos extras com botão de AR em cada estrutura, a Estação Café da Manhã com os pontos ligados ao texto, o AR das seis estruturas, a demonstração do QR, a escolha entre concentrar e espalhar, o próximo passo e o encerramento.

Cada mudança de capítulo passa por uma cortina vermelha com o número do capítulo. Abas, frentes e rotas abrem sozinhas até o primeiro clique.

## PDF

O botão PDF abre `?pdf=1&imprimir=1`: todas as telas uma embaixo da outra, em páginas de 1600 × 900, e a janela de impressão. Para gerar sem diálogo, imprimir `?pdf=1` no Chrome headless com `width: 1600px, height: 900px, printBackground: true`.

## AR

Os modelos ficam no repositório de AR: https://projetos.75lab.com.br/ar/panco-pecas-pdv/ (`?modelo=ilha-1-palete`, `ilha-2-paletes`, `modulo-cabeceira`, `modulo-central`, `cubo`, `portico`).
