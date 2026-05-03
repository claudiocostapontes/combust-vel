Bootstrap Theme v3.3.7 - Estilização Visual

Este arquivo contém as definições de estilo para o tema opcional do Bootstrap 3. Ele é responsável por adicionar uma estética mais refinada aos componentes básicos, utilizando gradientes lineares, sombras projetadas (box-shadow) e relevos.

🎨 Características do Tema

Diferente da versão "flat" (plana) padrão do Bootstrap, este tema aplica:

Botões Relevados: Adiciona gradientes e sombras internas nos estados normal, :hover e :active para as classes .btn-primary, 
.btn-success, .btn-danger, etc.

Componentes de Alerta: Aplica gradientes de fundo e sombras para tornar as mensagens de alerta (.alert) mais proeminentes.

Barras de Progresso: Adiciona profundidade visual e suporte a listras animadas nas barras de carregamento.

Painéis e Poços (Wells): Melhora a definição visual dos contêineres .panel e .well com bordas e sombras suaves.

Barras de Navegação: Estiliza tanto a .navbar-default quanto a .navbar-inverse com gradientes verticais.

🛠️ Detalhes Técnicos
Compatibilidade Retroativa: Inclui filtros específicos para suporte a gradientes no Internet Explorer (filtros DXImageTransform).

Suporte a Prefixos: Utiliza -webkit- e -o- para garantir a renderização correta em navegadores baseados em Webkit e 
versões mais antigas do Opera.

Responsividade: Contém regras de @media para ajustar o comportamento de menus suspensos (dropdowns) em telas de até 767px.

🚀 Como Utilizar

Para aplicar este tema ao seu projeto, você deve incluí-lo no <head> do seu HTML após a importação do CSS principal do Bootstrap:
<!-- 1. Bootstrap Principal -->
<link rel="stylesheet" href="css/bootstrap.min.css">

<!-- 2. Tema Opcional (Este arquivo) -->
<link rel="stylesheet" href="css/bootstrap-theme.min.css">

📁 Localização e Referência

Versão: 3.3.7

Licença: MIT

Dependência: Requer o núcleo do Bootstrap 3.x para funcionar corretamente.

Stacks modernas (Java 21, Spring Boot, Angular 19), o uso desta biblioteca sugere a 
manutenção de um painel administrativo legado ou uma integração que ainda utiliza o ecossistema Bootstrap 3.

Dica de Especialista: Se estiver modernizando este projeto, considere a migração para o Bootstrap 5 ou 
bibliotecas nativas de Angular (como PrimeNG ou Angular Material), que não dependem de jQuery.
