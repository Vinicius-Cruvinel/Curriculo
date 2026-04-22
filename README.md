# Curriculo Interativo - Sistema Solar

Projeto de curriculo em HTML com narrativa visual em formato de jornada pelo sistema solar, apresentando a trajetoria profissional de **Vinicius Cruvinel**.

## Visao geral

O arquivo `Solar.html` contem uma experiencia interativa com:

- renderizacao 3D com Three.js;
- navegacao por scroll em rota cinematografica;
- cards informativos por planeta (experiencias e competencias);
- reveal final com posicionamento profissional e contatos.

## Estrutura atual

```text
.
└── Solar.html
```

## Como executar localmente

Voce pode abrir direto no navegador, mas o ideal e rodar via servidor local:

```bash
python -m http.server 8000
```

Depois acesse:

```text
http://localhost:8000/Solar.html
```

## Como exportar para PDF

Para gerar uma versao PDF a partir da pagina:

1. Abra `Solar.html` no navegador.
2. Use `Ctrl + P`.
3. Escolha **Salvar como PDF**.
4. Ative **Graficos em segundo plano** para preservar o visual.

## Pontos de customizacao rapida

No `Solar.html`, os ajustes principais ficam em:

- bloco `PLANETS`: textos, periodos, titulos e ordem narrativa;
- `curve` (CatmullRomCurve3): rota e ritmo de aproximacao entre planetas;
- estilos do `#hero`, `.planet-card` e `#sun-reveal`: identidade visual;
- links de contato e botao de download no bloco final.

## Repositorio remoto

Origin configurado para:

- [https://github.com/Vinicius-Cruvinel/Curriculo.git](https://github.com/Vinicius-Cruvinel/Curriculo.git)
