Looker no GIt 

Este projeto é uma integração de ferramentas: ele demonstra como incorporar um Dashboard do Looker Studio em um site hospedado no GitHub Pages, oferecendo uma solução prática e dinâmica para visualização de dados.

O mais incrível? As atualizações feitas no Looker Studio são automaticamente refletidas no site! Não é necessário um novo deploy — apenas recarregar a página (F5) já traz os dados mais recentes. 🚀

🎯 Destaques do Projeto
Integração com Looker Studio:

O dashboard é integrado ao site através de um iframe.
Permite exibir dados dinâmicos de campanhas ou relatórios.
Atualizações Automáticas:

O Looker Studio pode ser configurado para realizar atualizações programadas nos dados.
Assim que os dados são atualizados no Looker Studio, o site também reflete as mudanças ao recarregar a página (sem a necessidade de um novo deploy no GitHub Pages).
Facilidade de Deploy:

O site foi hospedado no GitHub Pages, aproveitando a simplicidade e acessibilidade dessa plataforma.
Nenhuma configuração complexa foi necessária para que o dashboard funcionasse perfeitamente.

🔗Acesse o dashboard online: https://dhsilveira.github.io/html--looker/

🛠️ Como Funciona?

Configuração do Looker Studio:


Crie um dashboard no Looker Studio.
Publique o dashboard e copie o link de incorporação (iframe).
Adicionando ao Site:


No arquivo index.html, inclua o código do iframe fornecido pelo Looker Studio.
Exemplo de código usado neste projeto:

<iframe>
  
    width="600"   
    height="450"    
    src="https://lookerstudio.google.com/embed/reporting/.../page/sMqNE"    
    frameborder="0"    
    style="border:0"     
    allowfullscreen     
    sandbox="allow-storage-access-by-user-activation allow-scripts allow-same-origin allow-popups allow-popups-to-escape-sandbox">    
</iframe>

Publicação no GitHub Pages:

Faça o commit do projeto no GitHub.
Ative o GitHub Pages no repositório.
Atualizações Programadas:

Configure no Looker Studio as atualizações automáticas dos dados (por exemplo, a cada 24 horas).
Com isso, os dados exibidos no site estarão sempre atualizados.

📝 Benefícios da Integração

Atualização Contínua: dados frescos sem o trabalho de novos deploys.
Acessibilidade Simples: o dashboard pode ser visualizado de qualquer lugar, sem complicações.
Automação: ideal para relatórios, campanhas ou qualquer situação em que os dados mudam com frequência.
