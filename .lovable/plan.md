## Objetivo

Recriar neste projeto a mesma LP visual de `agro-golden-goal.lovable.app` (campanha "Gol de Placa" — A9 Massey Ferguson), trocando o conteúdo de **venda de máquinas** para **funil de peças**, conforme texto enviado.

## Imagem recebida

Banner com peças Massey Ferguson (filtros AGCO Parts, disco/cilindro, Diesel Pro, Diesel Guard, óleo hidráulico MF Power Plus) sobre fundo escuro com fragmentos vermelhos. **Será usada como imagem principal da seção "O Que Oferecemos"** (e/ou destaque da Oferta), substituindo as 4 fotos de máquinas do projeto original.

## O que será portado do projeto original

**Assets (cross-project copy):**
- `logo-gol-de-placa.png`, `massey-a9-branco.png`, `massey-a9-preto.png`
- `hero-stadium.jpg` (fundo do hero)
- `about-a9.jpg` (seção "Quem é a A9")

**Design system:**
- `src/styles.css` completo (vermelho A9, dourado, verde-campanha, preto estádio, fontes, sombras)
- Mesma paleta + tipografia display amarela/branca + CTAs vermelhos + animações framer-motion

**Estrutura:**
- Header fixo com logo + nav + botão "Falar Agora"
- Botão flutuante WhatsApp
- Footer com tagline + "Powered by Omnia"

## Seções da nova LP

1. **Hero** — "A peça certa. Na hora certa." + logo Gol de Placa + estádio + CTA WhatsApp
2. **Oferta Saldão Agrishow** — 15% OFF, 10x sem juros, parcela mín R$ 500
3. **Quem é a A9** — bloco institucional + imagem
4. **Diferenciais** — 3 cards (entrega SP, equipe técnica MF, atendimento direto com gestores)
5. **Unidades** — grid 8 cidades (Avaré, Piedade, Bragança Paulista, Itapeva, Piracicaba, Itapetininga, Jaú, Campos de Holambra)
6. **O Que Oferecemos** — destaque com o **banner de peças enviado** + 4 categorias (Peças Originais, Manutenção, Sazonalidade, Pneus/Emergências)
7. **Depoimentos** — 3 cards (Roberto, Livia, Henrique)
8. **Reiteração da Oferta** — bloco final
9. **Fechamento** — pós-venda, logística, estoque + CTA
10. **Footer** — A9 Máquinas | Seg-Sáb | Powered by Omnia

## Detalhes técnicos

- Stack idêntica (TanStack Start + Tailwind + framer-motion + lucide-react)
- Tudo em `src/routes/index.tsx`, igual ao original
- Substituo o placeholder atual da home
- Meta tags ajustadas para "Peças A9 Massey Ferguson"
- WhatsApp: mantenho `551155551346` do original — me diga se for outro
