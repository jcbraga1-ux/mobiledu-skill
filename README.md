# MobileDU Skill – Diretrizes de Desenho Universal para aplicações móveis
[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.23809315.svg)](https://doi.org/10.5281/zenodo.23809315)

Agent Skill com as **60 diretrizes da Biblioteca MobileDU**, organizadas em 8 categorias (Ambiente, Texto, Som, Vídeo, Zoom, Entrada de dados, Notificações e alertas, Gestos), para usar com assistentes de IA compatíveis com o padrão aberto [Agent Skills](https://agentskills.io/).

A ideia central da MobileDU: **o aplicativo deve deixar cada pessoa ajustar a interface do seu jeito**, em vez de oferecer uma única versão para todos. As diretrizes se apoiam em três ideias: flexibilidade de uso, redundância sensorial e independência de dispositivo.

## O que a skill faz

- **Consulta:** “O que diz a diretriz 6.6 da MobileDU?”
- **Auditoria:** avalia um app ou protótipo diretriz por diretriz (atende / não atende / não se aplica), com o critério WCAG relacionado.
- **Requisitos:** transforma diretrizes em requisitos de um projeto, com critério de aceitação.
- **Ensino:** explica cada categoria, quem se beneficia e um exemplo prático (caso fictício da UBS Jardim Esperança).

Cada diretriz traz suas referências de origem: diretrizes de Nery (Módulo Configurador), WCAG, GDAMA (Guia de Diretrizes de Acessibilidade para Aplicações Móveis) e ABNT NBR 17060:2022.

## Como instalar

A skill é a pasta [`mobiledu-diretrizes/`](mobiledu-diretrizes/), com o arquivo `SKILL.md`.

- **Claude e Gemini:** baixe o arquivo `mobiledu-diretrizes.zip` na página de [Releases](../../releases), em *Assets*, e envie sem mudar o nome do arquivo (o Gemini exige que o nome do .zip seja igual ao nome da skill). No Claude, envie em *Configurações › Capacidades › Skills*; no Gemini, na página de *Skills*, opção de enviar arquivo. O mesmo arquivo serve para os dois.
- **Claude Code:** copie a pasta para `~/.claude/skills/` (uso pessoal) ou para `.claude/skills/` dentro do seu projeto.
- **Outras ferramentas compatíveis com Agent Skills** (como Codex, Cursor, GitHub Copilot): copie a pasta para o diretório de skills indicado na documentação da ferramenta.

Depois de instalada, basta pedir em linguagem natural, por exemplo: *“Avalie este protótipo com as diretrizes da MobileDU.”*

## Fonte e créditos

As diretrizes (nome, descrição e referências) seguem os Quadros 1 a 8 da tese:

> COLETTO, Carlos Jair. **Diretrizes para o Desenvolvimento de Aplicações Móveis Voltadas para o Desenho Universal: A Biblioteca MobileDU**. Tese (Doutorado em Ciência da Computação) – Universidade Federal do ABC, Santo André, 2026. Orientação: Juliana Cristina Braga.

Desenvolvido no grupo de pesquisa **INTERA** (Inteligência em Tecnologias Educacionais e Recursos Acessíveis) da **Universidade Federal do ABC (UFABC)**.

Os textos “quem se beneficia” e “exemplo UBS” são explicações didáticas elaboradas para a disciplina de Interação Humano-Computador da UFABC.

## Como citar

Use o botão *Cite this repository* do GitHub (arquivo [`CITATION.cff`](CITATION.cff)) e cite também a tese acima.

## Licença

Conteúdo licenciado sob [Creative Commons Atribuição 4.0 Internacional (CC BY 4.0)](https://creativecommons.org/licenses/by/4.0/deed.pt-br): você pode usar, adaptar e redistribuir, inclusive comercialmente, desde que cite a fonte.

## Contribuições

Sugestões e correções são bem-vindas por meio de *issues* ou *pull requests*.
