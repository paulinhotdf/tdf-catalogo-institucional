# Tudo de Filtro — Catálogo Institucional
## Direção de Arte, Imagens e Copy

> Documento-guia para diagramação, troca de imagens e adaptação do catálogo (web e impresso).
> O catálogo final já está diagramado em `index.html` — este doc orienta ajustes e a produção de novas imagens.

---

### 1. Conceito criativo
**"Eleve o nível da sua água."**
Linguagem de empresa industrial de água de alto padrão (3M, Pentair, Culligan, WEG): sóbria, confiante, técnica e limpa. Vende **confiança, autoridade e experiência** — não desconto, não produto isolado. Tom editorial: frases curtas, afirmativas, humanas.

### 2. Sistema visual
| Elemento | Especificação |
|---|---|
| **Azul-tinta (ink)** | `#0A2540` — fundos institucionais, títulos |
| **Azul primário** | `#0C5BD6` — destaques, kickers, números |
| **Aqua (água)** | `#2BC4E6` — acento, gradientes, gota |
| **Névoa / cinza claro** | `#EAF2FB` / `#F4F9FE` — fundos de cartão |
| **Cinza texto** | `#5C7185` |
| **Branco** | `#FFFFFF` |
| **Gradiente** | `135° #0A2540 → #0C3D7A → #0C5BD6` (capas/seções) |
| **Tipografia display** | Fraunces (serifada editorial, premium) |
| **Tipografia corpo** | Inter |
| **Elementos de água** | gota chanfrada, "waveline" (barras), gradiente aqua, halo radial |

### 3. Formato
- 28 páginas, proporção A4 retrato (1:1,414).
- Funciona como **site/apresentação** (rolagem, tela cheia) e exporta em **PDF A4** pronto para impressão (`catalogo.pdf`).
- Pronto para hospedar no Hugging Face (Static Space), GitHub Pages ou WordPress.

### 4. Direção de arte por página
| # | Página | Imagem ideal / tratamento |
|---|---|---|
| 1 | Capa | Fundo gradiente azul + halo aqua. (Opção: macro de água cristalina ao fundo, escurecido.) |
| 3 | Quem somos | **Foto real** de instalação/equipe (atual: `install-fachada`). Trocar por foto da equipe/loja se houver. |
| 4 | Trajetória | Sem foto — timeline numerada. (Opção: foto antiga da empresa.) |
| 5 | Propósito | Cartões missão/visão/valores + citação. |
| 9 | Filtro de Entrada | **Foto do produto** em fundo escuro (atual: `unidade_view`). Ideal: still premium do inox 304. |
| 10 | Tecnologia FE | **Foto elemento novo×usado** (atual: `elemento_novo_usado`). Forte prova visual. |
| 11 | Água de poço | **Foto** de água com ferro (copo turvo) — atual `agua_ferrugem`. |
| 13 | Ozônio | Sem foto (infográfico). Ideal: macro de bolhas/água oxigenada. |
| 23 | Cases (logos) | Logos oficiais em PNG/SVG, escala de cinza. **Faltam logos:** De Nigris, Katoen Natie, Daido, Aberden, VF, Quaglia, Zag, Harmonya, Vila Mar, EDL (hoje wordmark tipográfico). |
| 24 | Cases (instalações) | **Fotos reais** de instalações (atuais: `install-grande/condominio/flores`). Quanto mais, melhor. |

### 5. Imagens a produzir (para elevar ainda mais)
1. **Foto da fachada/loja e da equipe** Tudo de Filtro (autoridade real).
2. **Still premium** de cada linha: Iron Free (poço), Scale Stop (abrandador), bebedouro industrial inox, purificador.
3. **Macro de água** cristalina/bolhas para divisores de seção.
4. **Logos oficiais** dos clientes em alta resolução (substituir wordmarks).
5. **Foto de bastidor**: técnico instalando, troca de refil (humaniza o "a gente vai até você").

### 6. Diretrizes de copy (compliance)
- ✅ "água tratada", "água de qualidade", "retém sedimentos", "água mais limpa".
- ⚠️ Evitar "água pura" como promessa de saúde; evitar claims medicinais.
- ✅ Claims aprovados pelo Paulo (assumidos): "único do Brasil" (inox 304 + 10 anos + INMETRO), "menor perda de pressão do mercado", "10 anos de garantia", "certificação INMETRO".
- ✅ Dados oficiais do site: +38 anos, +8.000 clientes, multimarca, SJC + envio Brasil, WhatsApp (12) 98285-5000.

### 7. Como editar / exportar
- **Editar conteúdo:** abrir `index.html` (texto direto no HTML, sem build).
- **Gerar PDF:** abrir no Chrome → Imprimir → Salvar como PDF → A4 → margens "Nenhuma" → ativar "Gráficos de plano de fundo". (Ou usar o `catalogo.pdf` já gerado.)
- **Trocar imagem:** substituir o arquivo em `assets/img/` mantendo o nome.
- **Publicar no Hugging Face:** criar um *Static Space* e subir `index.html` + pasta `assets/`.
