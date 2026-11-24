# Marcus Nunes Photo Portfolio

Este é o portfólio de fotografia de [Marcus Nunes](https://marcusnunes.me/) construído com **hugo** e um tema próprio e minimalista (`themes/minimo`), sem dependências externas.  

# Descrição

Sou Marcus Nunes, professor do [Departamento de Estatística da UFRN](http://www.estatistica.ccet.ufrn.br/) e leciono disciplinas de estatística para os alunos do Bacharelado em Estatística e outros cursos da universidade. Minhas disciplinas preferidas são [Introdução à Modelagem de Big Data](https://introbigdata.org/), Métodos Estatísticos e Estatística Descritiva.

Estes são os arquivos do meu portfólio fotográfico autoral. O site pode ser acessado em [https://fotografia.marcusnunes.me/](https://fotografia.marcusnunes.me/).

# Instalação / Uso

Caos queira criar a sua versão deste repositório, siga os passos a seguir:

1. **Clone** este repositório:

   ```bash
   git clone https://github.com/mnunes/photo_portfolio.git
   cd photo_portfolio
   ```

2. **Execute localmente** o servidor Hugo:

   ```bash
   hugo server
   ```

# Organização

- `content/projetos/`: os projetos exibidos na página inicial. Cada projeto é um arquivo `.md` com título, subtítulo, ordem (`weight`), um texto curto e a lista `fotos`, com caminhos para imagens dos álbuns (ex.: `paisagem/mendoza/01.jpg`). Para trocar a legenda de uma foto use `- {src: paisagem/mendoza/01.jpg, legenda: "Texto"}`; para escolher a capa, `capa: caminho/da/foto.jpg`.
- `content/paisagem/` e `content/street/`: os álbuns originais por lugar, listados na página **Arquivo**.
- `content/exposicoes/`: exposições, com o catálogo em PDF indicado pelo campo `catalogo`.
- `content/sobre.md`: a página Sobre.

