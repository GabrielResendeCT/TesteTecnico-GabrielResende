# Questionário conceitual

Responda as questões neste mesmo arquivo, por favor, responda com suas próprias palavras, com sinceridade quando não conhecer determinado assunto.

1. Conhece GIT? Já o utilizou em algum projeto?
R: Sim, estou familiarizado com o Git e o utilizei em diversos projetos. No entanto, minha experiência também inclui o uso extensivo do Azure DevOps para gerenciamento de projetos e integração contínua.

2. Qual a diferença entre GIT e GITHUB?
R: O Git é uma ferramenta de controle de versão usada para rastrear alterações em código-fonte. O GitHub, por outro lado, é uma plataforma online que utiliza o Git para hospedar projetos de código-fonte e facilitar a colaboração entre desenvolvedores. Resumindo, o Git é a ferramenta, e o GitHub é o serviço online que a utiliza.

3. Conhece ou tem experiência com desenvolvimento Web? Descreva como se dá a requisição HTTP entre um cliente e o servidor, e como se dá a resposta.
R: Sim, tenho experiência em desenvolvimento web. Atualmente, trabalho em diversos projetos como freelancer, incluindo sites e sistemas web.
A comunicação entre um cliente (como um navegador) e um servidor ocorre por meio do protocolo HTTP (Hypertext Transfer Protocol). Quando o cliente deseja acessar uma página da web, ele envia uma mensagem de solicitação HTTP para o servidor, indicando a ação desejada, como recuperar uma página específica. O servidor processa essa solicitação e envia uma mensagem de resposta HTTP de volta ao cliente. Essa resposta pode conter os dados solicitados, como o conteúdo de uma página da web, juntamente com informações de cabeçalho que descrevem o status da resposta (como "200 OK" para sucesso) e outros detalhes importantes. Essa troca de mensagens permite que os clientes acessem e interajam com os recursos na web.

4. Conhece API REST? Para que são utilizadas? Cite dois exemplos.
R: Sim, conheço muito bem as APIs REST. Uma das minhas principais responsabilidades é desenvolver APIs REST para integrações diversas com nosso sistema principal, incluindo integrações relacionadas a Nota Fiscal (NF). As APIs REST são usadas para permitir a comunicação e a troca de dados entre sistemas de forma padronizada pela web, tornando possível a integração entre diferentes aplicativos e serviços. Dois exemplos comuns de APIs REST são as APIs de pagamento, que permitem que sistemas aceitem pagamentos online, e as APIs de redes sociais, que possibilitam a integração com plataformas como o Facebook e o Twitter para compartilhar conteúdo e interagir com usuários.

5. Conhece o conceito de AJAX? Descreva a tecnologia utilizada.
R: O AJAX (Asynchronous JavaScript and XML) é uma tecnologia web que permite que partes específicas de uma página da web sejam atualizadas dinamicamente sem recarregar a página inteira. Isso é feito usando JavaScript para fazer solicitações assíncronas ao servidor e receber dados, geralmente em formato JSON, que podem ser usados para atualizar o conteúdo da página em tempo real.

6. Conhece o conceito de assincronicidade ? Como usar na tecnologia deste desafio ?
R: Sim, estou bem familiarizado com o conceito de assincronicidade. Já trabalhei com programação em C e C++, onde frequentemente utilizamos Threads para tarefas assíncronas, o que pode ser um pouco mais complexo.

Na tecnologia deste desafio, que envolve desenvolvimento em C#, a assincronicidade pode ser aplicada usando métodos assíncronos (com as palavras-chave async e await). Isso é particularmente útil ao fazer chamadas de rede para obter informações externas, como dados de um serviço da web. Utilizando métodos assíncronos, podemos fazer com que a aplicação continue respondendo a eventos do usuário ou a outras tarefas enquanto aguarda a resposta do servidor, melhorando a responsividade e a eficiência da aplicação.

7. Conhece padrões de projeto ? Descreva um cenário onde usaria um padrão de projeto que implementa IoC, e qual seria este padrão.
R: Sim, estou familiarizado com padrões de projeto.

Um cenário onde usaria um padrão de projeto que implementa IoC (Inversão de Controle) seria ao desenvolver uma aplicação que necessita de flexibilidade na configuração de componentes e dependências, principalmente quando se deseja desacoplar componentes e facilitar a injeção de dependências.

O padrão de projeto comumente utilizado para implementar IoC é o "Injeção de Dependência" (Dependency Injection - DI). Com o DI, você pode configurar a injeção de dependências em tempo de execução, permitindo que componentes dependentes recebam suas dependências de forma mais flexível.

Por exemplo, em uma aplicação que requer diferentes provedores de armazenamento de dados (por exemplo, banco de dados SQL, NoSQL e armazenamento em memória), o uso do padrão de Injeção de Dependência permitiria alternar facilmente entre essas implementações, sem modificar o código principal da aplicação. Isso melhora a testabilidade, manutenção e escalabilidade da aplicação. O padrão DI é comumente implementado com bibliotecas como o "Microsoft.Extensions.DependencyInjection" em projetos C#.



