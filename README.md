# Mudança de Clima e Sociedade

Trabalho da avaliação final da disciplina **Mudança de Clima e Sociedade**, turma Integral, da Universidade Federal de São Paulo (Unifesp), campus São José dos Campos.

**Integrantes do grupo** — Thiago Heleno, Enzo Baldinotti e Luisa Souza Monteiro.

## Tema 5 do Eixo II — Economia, consumo e sociedade

> Se conhecemos as causas das mudanças climáticas há décadas, por que as emissões globais continuam tão elevadas?

O trabalho responde à pergunta com um carrossel de seis imagens para público não especializado. Ele compara as emissões globais de 1990 e 2025, usa uma frota hipotética para mostrar como o consumo total pode subir mesmo com veículos mais eficientes e discute o apoio público aos combustíveis fósseis e a distribuição desigual das emissões do consumo familiar. A última imagem usa o transporte coletivo para explicar a diferença entre mitigação e adaptação.

A ficha científica reúne três conclusões, as evidências e seus limites de interpretação, cinco referências clicáveis e a declaração de uso de IA. Ela explica por que os dados mostram um aumento das emissões entre 1990 e 2025, embora a diferença entre 2024 e 2025 esteja dentro da margem de incerteza.

## Estrutura do projeto

### PDFs para entrega

| Arquivo | Conteúdo |
| --- | --- |
| [Tema 5 - Carrossel.pdf](output/pdf/Tema%205%20-%20Carrossel.pdf) | Carrossel completo em seis páginas, na ordem de leitura. |
| [Tema 5 - Ficha de fundamentacao cientifica.pdf](output/pdf/Tema%205%20-%20Ficha%20de%20fundamentacao%20cientifica.pdf) | Ficha científica compilada em uma página A4. |

### Fonte LaTeX da ficha

| Arquivo | Conteúdo |
| --- | --- |
| [output/latex/ficha/main.tex](output/latex/ficha/main.tex) | Documento principal em LaTeX. Contém a identificação do grupo, as conclusões, as evidências, as referências e a diagramação da ficha em abnTeX2, com fonte Latin Modern de 12 pontos. |
| [output/latex/ficha/logo.png](output/latex/ficha/logo.png) | Logo da Unifesp usada no cabeçalho, extraída do enunciado da avaliação. |
| [Ficha - Projeto Overleaf.zip](output/latex/Ficha%20-%20Projeto%20Overleaf.zip) | Pacote com `main.tex` e `logo.png` na raiz, pronto para importar no Overleaf. |

### Imagens do carrossel

Os PNGs de `output/instagram/` têm **1080 × 1350 pixels**. Os números nos nomes dos arquivos indicam a ordem de publicação.

| Arquivo | Conteúdo |
| --- | --- |
| [01-Capa.png](output/instagram/01-Capa.png) | Apresenta a pergunta e o que a ciência já conhecia em 1990. |
| [02-Emissoes-globais.png](output/instagram/02-Emissoes-globais.png) | Compara as emissões globais anuais de 1990 e 2025 e explica o limite da comparação com 2024. |
| [03-Caminhoes.png](output/instagram/03-Caminhoes.png) | Mostra, com um exemplo hipotético, como a frota pode usar mais diesel mesmo gastando menos por quilômetro. |
| [04-Combustiveis-fosseis.png](output/instagram/04-Combustiveis-fosseis.png) | Apresenta a estimativa do apoio público a carvão, petróleo e gás em 2024. |
| [05-Consumo-das-familias.png](output/instagram/05-Consumo-das-familias.png) | Compara a parcela das emissões do consumo familiar atribuída às 10 famílias que mais emitem por pessoa e às 50 que menos emitem, a cada 100 famílias. |
| [06-Transporte-e-clima.png](output/instagram/06-Transporte-e-clima.png) | Usa o ônibus e a sombra no ponto para ilustrar mitigação e adaptação. |

## Como editar e compilar no Overleaf

1. Baixe o [ZIP da ficha](output/latex/Ficha%20-%20Projeto%20Overleaf.zip). Na página de projetos do Overleaf, selecione **New Project → Upload Project** e envie o ZIP.
2. Nas configurações do projeto, confirme **pdfLaTeX** como compilador e `main.tex` como documento principal. Mantenha `logo.png` na mesma pasta que `main.tex`.
3. Edite o texto em `main.tex`. Clique em **Recompile** e confira se o resultado ocupa uma página A4, exibe a logo e mantém as cinco referências clicáveis.
4. Use **Download PDF** para baixar a versão compilada. Se atualizar o material no repositório, atualize também o PDF da ficha e o ZIP com os dois arquivos-fonte.

Para um projeto já aberto no Overleaf, envie `main.tex` e `logo.png` separadamente usando o botão de upload da lista de arquivos. [Documentação do Overleaf](https://docs.overleaf.com/managing-projects-and-files/uploading-a-project)
