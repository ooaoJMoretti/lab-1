# lab-1
rebrand do site estatico dele: https://www.lojaohortifruti.com.br/

## Proposta de reestruturação

Site estático em HTML, CSS e JavaScript, sem dependências de instalação ou etapa de build.

### Executar

Na pasta do repositório:

```sh
python3 -m http.server 4173 --bind 127.0.0.1
```

Abra a página servida na porta 4173 no seu navegador. Também é possível abrir `index.html` diretamente. Para hospedar, publique `index.html`, `styles.css`, `script.js` e a pasta `assets` em qualquer hospedagem estática com HTTPS.

### Conteúdo e revisão

- Identidade visual conceitual com base vermelha, ilustração SVG local, três unidades, ofertas pelo WhatsApp e dicas de abastecimento.
- Menu móvel com suporte a teclado e links de mapas e WhatsApp.
- Fontes de sistema, sem dependências externas de fontes.
- Endereços, horários, rotina de abastecimento e WhatsApp foram transcritos dos prints fornecidos pelo usuário. Fotos das fachadas e logotipo original não foram extraídos dos prints; a ilustração é conceitual.
- Antes de publicar: confirmar com o proprietário a atualidade dos endereços, horários e WhatsApp (19) 97160-7354. Validar também identidade visual e textos. O site não coleta informações pessoais; o botão de ofertas abre o WhatsApp com a mensagem OFERTA.
- Não há loja virtual, carrinho, pagamento, preços, painel administrativo ou serviço de formulário.

### Verificação básica

```sh
node --check script.js
git diff --check
```

No navegador, confira os links de mapas e WhatsApp, a navegação por âncoras, o menu móvel e a tecla Escape para fechar o menu.
