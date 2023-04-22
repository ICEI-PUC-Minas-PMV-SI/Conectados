# Especificações do Projeto

Definição do problema e ideia de solução a partir da perspectiva do usuário. É composta pela definição do  diagrama de personas, histórias de usuários, requisitos funcionais e não funcionais além das restrições do projeto.

Apresente uma visão geral do que será abordado nesta parte do documento, enumerando as técnicas e/ou ferramentas utilizadas para realizar a especificações do projeto

## Personas
**PERSONA**

| Persona                     | Nome   | Idade | Ocupação                                              | Hobbies                                              | Frustrações                                                                                                                        | Motivações                                                                                                                                                                                                                   | Aplicativos                                                          |
|-----------------------------|--------|-------|-------------------------------------------------------|------------------------------------------------------|------------------------------------------------------------------------------------------------------------------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------|
| Estudante de tecnologia     | Ricardo  | 20    | Estudante de Ciência da Computação na universidade X | Jogar videogames, assistir a séries e filmes, e ler livros de ficção | Dificuldade em conciliar as atividades acadêmicas e o tempo livre, falta de conexão com as disciplinas e dificuldades em algumas matérias | Aprender novas habilidades de programação, participar de projetos de programação, se preparar para o mercado de trabalho e se formar na área.                             | Visual Studio Code, GitHub, LinkedIn, Stack Overflow                   |
| Desenvolvedor de software   | Lucas  | 28    | Desenvolvedor de software na empresa XPTO             | Jogar videogame, tocar guitarra, assistir filmes e séries | Problemas técnicos difíceis de solucionar, prazos apertados e bugs no código | Aprender novas tecnologias, melhorar suas habilidades de programação, trabalhar em projetos desafiadores e contribuir para a equipe. | Visual Studio Code, GitHub, Stack Overflow, Steam             |
| Estudante de tecnologia     | Ana    | 22    | Estudante de Engenharia de Software na universidade Y | Dançar, ouvir música, ler e praticar esportes           | Sobrecarga de trabalho, dificuldades em matérias específicas e problemas em trabalhos em grupo | Aprender a desenvolver software de qualidade, encontrar uma posição de trabalho na área após a graduação e contribuir para projetos de código aberto | Notion, Visual Studio Code, GitHub, Stack Overflow                        |
| Influenciador de tecnologia | Julia  | 32    | Jornalista especializada em tecnologia e influenciadora de redes sociais | Viajar, jogar jogos de RPG, ler livros e assistir filmes de ficção científica | Produtos de tecnologia ruins ou com problemas, comentários negativos de haters nas redes sociais e falta de tempo para se manter atualizada sobre as últimas novidades em tecnologia | Compartilhar sua opinião sobre produtos de tecnologia, ajudar as pessoas a tomar decisões informadas, conectar-se com sua audiência e crescer sua influência nas redes sociais. | Instagram, Twitter, YouTube, Reddit            |






> **Links Úteis**:
> - [Rock Content](https://rockcontent.com/blog/personas/)
> - [Hotmart](https://blog.hotmart.com/pt-br/como-criar-persona-negocio/)
> - [O que é persona?](https://resultadosdigitais.com.br/blog/persona-o-que-e/)
> - [Persona x Público-alvo](https://flammo.com.br/blog/persona-e-publico-alvo-qual-a-diferenca/)
> - [Mapa de Empatia](https://resultadosdigitais.com.br/blog/mapa-da-empatia/)
> - [Mapa de Stalkeholders](https://www.racecomunicacao.com.br/blog/como-fazer-o-mapeamento-de-stakeholders/)
>
Lembre-se que você deve ser enumerar e descrever precisamente e personalizada todos os clientes ideais que sua solução almeja.

## Histórias de Usuários

Com base na análise das personas forma identificadas as seguintes histórias de usuários:
|**Eu como …  [PERSONA]**|**… quero/desejo …** <br>**[O QUE]**|<p>**… para ....**</p><p>**[POR QUE]**</p>|
| :-: | :-: | :-: |
|Lucas|Um espaço para interagir com as pessoas da área de tecnologia|Ter confiança para conversar com pessoas da minha área de estudo|
|Lucas|Um local de fácil acesso onde encontre pessoal da minha área de atuação|Para encontrar sugestões de cursos, vagas de emprego e conteúdo da área|
|Ricardo|Um espaço aberto para compartilhar dúvidas sobre as matérias que estudo.|Ter mais disposição e incentivo para continuar estudando.|
|<p>Ricardo</p><p></p>|Um local onde encontre pessoal da minha área de atuação|Conversar sobre tecnologia, discutir ideias e compartilhar curiosidades.|
|Julia|Encontrar uma comunidade engajada da área da tecnologia|Me aproximar de pessoas que estudam na área de tecnologia|
|Julia|A oportunidade de me conectar com outras mulheres estudantes e profissionais de TI|Encontrar inspiração com histórias de sucesso de mulheres na indústria de TI, tutoriais e projetos práticos que me ajudariam a me sentir confiante e capacitada|
|Lucas|Uma ferramenta fácil de usar e que oferecesse recursos úteis e inspiradores|Encontar depoimentos de outros estudantes que já enfrentaram dificuldades de automotivação|
|Lucas|Um ambiente que tenha uma comunidade on-line ativa|Receber encorajamento e suporte de colegas|
|Ricardo|Me conectar com outros estudantes|Compartilhar minhas experiências|
|Julia|A oportunidade de me conectar com outras mulheres estudantes e profissionais de TI|<p>Um recurso que me ajude a superar os desafios que eu enfrento como mulher em uma indústria predominantemente masculina</p><p></p>|
|Lucas|Uma espaço com recursos específicos para estudantes de tecnologia da informação|Ter acesso a tutoriais, projetos práticos e dicas de carreira|
|Ricardo|` `Encontrar uma comunidade engajada da área da tecnologia|Encontrar com facilidade pessoal da minha área de estudo|
 |


## <a name="_toc108797062"></a>Requisitos do Projeto
O escopo funcional do projeto é definido por meio dos requisitos funcionais que descrevem as possibilidades interação dos usuários, bem como os requisitos não funcionais que descrevem os aspectos que o sistema deverá apresentar de maneira geral. Estes requisitos são apresentados a seguir.
### <a name="_toc108797063"></a>Requisitos Funcionais
A tabela a seguir apresenta os requisitos do projeto, identificando a prioridade em que os mesmos devem ser entregues.


|**ID**|**Descrição**|**Prioridade**|
| :-: | :-: | :-: |
|RF-01|O site deve apresentar, um fórum que permita a discussão e troca de informação entre os participantes do site, que inclua um sistema de denúncias e notas para respostas|Alta|
|RF-02|O site deve apresentar, um quiz para definir a melhor área da computação para pessoa|Média|
|RF-03|O site deve permitir a organização de grupos de estudos e compartilhamento de link de plataformas como ZOOM, Teams, <a name="_int_ia00ojw1"></a>DIscord etc.|Média|
|RF-04|O site deve conter um menu que permita visualizar as informações de contatos do mantenedor do site, Mecanismo de busca e filtro,|Média|
|RF-05|Criação de perfil com login, links de redes sociais, informações pessoais e profissionais, nota das respostas.|Alta|
|RF-06|O site deve conter uma plataforma para compartilhamento de cursos, artigos, vagas de emprego, processos seletivos etc.|Média|

### <a name="_toc108797064"></a>Requisitos não funcionais
A tabela a seguir apresenta os requisitos não funcionais que o projeto deverá atender.


|**ID**|**Descrição**|**Prioridade**|
| :-: | :-: | :-: |
|RNF-01|O site deve ser publicado em um ambiente acessível publicamente na Internet (Repl.it, GitHub Pages, <a name="_int_odkswyku"></a>Heroku); |Alta|
|RNF-02|O site deverá ser responsivo permitindo a visualização em um celular de forma adequada|Alta|
|RNF-03|O site deve ter bom nível de contraste entre os elementos da tela em conformidade |Média|
|RNF-04|O site deve ser compatível com os principais navegadores do mercado (Google Chrome, Firefox, Microsoft Edge)|Alta|


### <a name="_toc108797065"></a>Restrições
As questões que limitam a execução desse projeto e que se configuram como obrigações claras para o desenvolvimento do projeto em questão são apresentadas na tabela a seguir.


|**ID**|**Descrição**|
| :-: | :-: |
|RE-01|O projeto deverá ser entregue no final do semestre letivo, não podendo extrapolar a data de 01/04/2023|
|RE-02|O aplicativo deve se restringir às tecnologias básicas da Web no <a name="_int_qwrffsdk"></a>Frontend|
|RE-03|A equipe não pode subcontratar o desenvolvimento do trabalho.|

## Metodologia

A metodologia contempla as definições de ferramental utilizado pela equipe tanto para a manutenção dos códigos e demais artefatos quanto para a organização do time na execução das tarefas do projeto.

### Relação de Ambientes de Trabalho

Os artefatos do projeto são desenvolvidos a partir de diversas plataformas e a relação dos ambientes com seu respectivo propósito é apresentada na tabela que se segue.

| Ambiente | Plataforma | Link de Acesso |
| --- | --- | --- |
| Repositório de código fonte | GitHub | https://github.com/ICEI-PUC-Minas-PMV-SI/pmv-si-2023-1-e1-proj-web-t4-projeto-Conectados |
| Documentos do projeto | Sharepoint | https://sgapucminasbr.sharepoint.com/sites/ProjetoAplicaesWeb2023|


