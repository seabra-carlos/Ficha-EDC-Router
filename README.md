# Ficha EDC Router

Ficha de rastreabilidade — EDC Router (interface estática)

## Visão geral
Este projeto é uma interface web estática para registrar e acompanhar lotes de peças e materiais, incluindo:

- cadastro de lote
- dados de entrada e operador
- massa bruta, tara e massa líquida
- materiais por fração
- valor estimado por material
- status do lote
- etapas do processo
- referências/documentos
- exportação em CSV e JSON
- impressão em PDF

## Como abrir localmente

### Opção 1: abrir diretamente no navegador
Abra o arquivo `index.html` no navegador.

### Opção 2: Rodar com servidor local
```bash
cd Ficha-EDC-Router
python -m http.server 8000
```

Depois acesse:

```text
http://localhost:8000
```

## Estrutura do projeto

```text
Ficha-EDC-Router/
├── index.html
├── README.md
└── .gitignore
```

## Funcionalidades principais

- seleção de lote
- cadastro e edição de dados do lote
- cálculo automático de massa líquida
- gerenciamento de materiais e preços
- registro de etapas do processo
- histórico de documentos e evidências
- relatórios e exportações

## Observações

- Os dados são armazenados no navegador (`localStorage`) deste dispositivo.
- O protótipo não emite documentos oficiais como MTR ou laudo técnico.
- O uso comercial deve considerar validação técnica e cotação com fornecedores/autorizados.

## Licença
Este projeto foi criado para uso interno e operacional. Ajustes de licença podem ser definidos conforme necessidade da organização.
