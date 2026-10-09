# Agência Pixel — CSS refatorado

Projeto original da Agência Criativa Web, refatorado sem criar um site novo. A estrutura e o conteúdo foram preservados, com organização do CSS e classes BEM.

## Arquivos
- `index.html`: página e componentes com classes semânticas.
- `estilos.css`: variáveis, estilos globais, componentes, seções, media queries e acessibilidade.
- `script.js`: menu responsivo, formulário demonstrativo e animação de escrita do logo.

## O que foi refatorado
- Removida a regra duplicada de `.logo`.
- Classes reorganizadas para o padrão BEM, por exemplo `cabecalho__conteudo`, `hero__conteudo`, `servicos__grid`, `formulario__campo` e `botao--formulario`.
- O estado aberto do menu agora usa o modificador `navegacao--aberta`.
- Os IDs das seções e dos campos foram mantidos para âncoras, acessibilidade e associação de labels; não são usados como seletores de estilo.
- Estilos agrupados por fundamentos globais, componentes, seções, responsividade e acessibilidade.

## Como executar
Abra `index.html` no navegador. Não há dependências de instalação.

## Teste responsivo sugerido
No Chrome/Edge, pressione `F12` e ative a barra de dispositivos. Verifique pelo menos:
- 1440 × 900 (desktop)
- 768 × 1024 (tablet)
- 390 × 844 (celular)

Confira o menu recolhido/aberto, a grade de serviços e depoimentos, o formulário e a ausência de rolagem horizontal. O breakpoint do menu é `56rem`; o layout de coluna única é aplicado em `40rem`.

**Nota:** os testes acima são um roteiro para conferência manual no DevTools. O projeto foi revisado estaticamente, mas não foi executado em um navegador com DevTools nesta sessão.
