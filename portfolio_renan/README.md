# Portfólio — Renan Rodrigues Monteiro

Site pessoal desenvolvido para a atividade da disciplina Interface Homem-Máquina.

## Tecnologias
- HTML5 semântico
- CSS3
- Flexbox e CSS Grid
- Variáveis CSS
- Media queries para responsividade
- Validação nativa de formulário (`required`, `type="email"` e `:user-invalid`)

O projeto não utiliza JavaScript nem bibliotecas externas.

## Estrutura
```text
portfolio_renan/
├── index.html
├── style.css
├── README.md
└── assets/
    └── renan.jpg
```

## Como visualizar
1. Extraia a pasta do arquivo ZIP.
2. Abra `index.html` no navegador.
3. Para editar, abra a pasta no Visual Studio Code.

## Antes de publicar
No arquivo `index.html`, procure por `SEU_EMAIL_AQUI` e substitua pelo endereço de e-mail que receberá as mensagens do formulário.

O formulário usa o protocolo `mailto:`. O navegador tentará abrir o aplicativo de e-mail configurado no dispositivo; esse método depende dessa configuração e não substitui um serviço de processamento de formulários.

## Personalização
- Para trocar a foto, substitua `assets/renan.jpg`, mantendo o mesmo nome, ou atualize o caminho no HTML.
- Para alterar cores, edite as variáveis no início de `style.css`.
- Para adicionar projetos reais futuramente, atualize a seção `04 / Projetos`.

## Publicação no GitHub Pages
1. Crie um repositório no GitHub.
2. Envie todos os arquivos e pastas deste projeto.
3. Nas configurações do repositório, abra **Pages**.
4. Em **Build and deployment**, selecione a publicação a partir da branch principal e da pasta raiz (`/root`).
5. Salve e aguarde a geração do endereço público.

Lembre-se de manter a foto dentro da pasta `assets`, pois a atividade exige que as imagens façam parte do repositório.
