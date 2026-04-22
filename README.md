# Protocolo Gênese — Guia Digital Interativo

> De e-book estático a experiência de leitura navegável, direto no navegador.

---

## Sobre o Projeto

O **Protocolo Gênese** é um guia técnico-executivo para arquitetura de agentes de Inteligência Artificial — originalmente desenvolvido como e-book em PDF. Este repositório apresenta sua versão como **Guia Digital Interativo**: um arquivo HTML autocontido que roda diretamente no navegador, sem instalação, sem dependências externas e sem necessidade de leitor de PDF.

O conteúdo permanece integralmente o mesmo. A experiência de leitura é completamente diferente.

---

## Funcionalidades

- **Navegação lateral** com índice completo por módulo — acesse qualquer página diretamente
- **Botões Anterior / Próxima** em todas as 34 páginas
- **Barra de progresso** de leitura no topo
- **Navegação por teclado** — setas direita/esquerda ou cima/baixo
- **Suporte a swipe** em dispositivos touch
- **Zero dependências** — um único arquivo `.html` autocontido
- **Design responsivo** — funciona em desktop e mobile

---

## Estrutura do Conteúdo

| Módulo | Tema | Páginas |
|--------|------|---------|
| 01 | A Introdução — O Fim do Prompt Genérico | 04 – 09 |
| 02 | A Alma Operacional — Engenharia de System Prompt | 10 – 13 |
| 03 | A Biblioteca — RAG e Hierarquia da Verdade | 14 – 16 |
| 04 | A Memória & O Custo — Tokens e Janela de Contexto | 17 – 19 |
| 05 | As Ferramentas — Do Raciocínio à Execução | 20 – 23 |
| 06 | O Primeiro Agente — Tutorial Prático | 24 – 29 |
| — | Encerramento — O Novo Padrão | 30 – 34 |

---

## Como Usar

Sem instalação. Sem servidor. Sem build.

```bash
# Clone o repositório
git clone https://github.com/seu-usuario/protocolo-genese.git

# Abra o arquivo no navegador
open protocolo-genese-executivo.html
```

Ou simplesmente faça o download do arquivo `.html` e abra com qualquer navegador moderno.

---

## Tecnologias

Este projeto é intencionalmente minimalista — construído com o básico da web, sem frameworks.

- **HTML5** — estrutura e conteúdo
- **CSS3** — layout, tipografia e animações
- **JavaScript vanilla** — navegação, swipe e lógica de estado
- **Google Fonts** — Cormorant Garamond, Outfit, DM Mono

---

## Decisão de Design

O formato foi migrado de PDF para HTML por razões práticas e estratégicas:

- PDF depende de leitor externo; HTML abre em qualquer dispositivo com um clique
- PDF não tem estado — HTML mantém progresso, animações e interatividade
- PDF é download — HTML pode ser hospedado e acessado por link direto
- PDF é estático — HTML permite futuras evoluções sem gerar nova versão do arquivo

---

## Autor

Desenvolvido por **Lucas Costa Nogueira**

---

## Licença

© 2025 · Protocolo Gênese · Todos os direitos reservados.

Este material é protegido contra reprodução, transmissão ou compartilhamento sem autorização expressa. Consulte o aviso legal completo na página 02 do guia.
