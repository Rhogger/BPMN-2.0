<h1 align="center">Resultado</h1>

<br>
<br>

## &nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Tópicos

[Introdução](#introducao) <br> [Etapa 1: Solicitação do Cliente](#etapa1)<br>
[Etapa 2: Projeto](#etapa2)<br> [Etapa 3: Desenvolvimento](#etapa3)<br>
[Etapa 4: Testes](#etapa4)<br> [Etapa 5: Manutenção e Evolução](#etapa5)<br>
[Descrição das ferramentas utilizadas no processo](#ferramentas)<br>

- [Projeto](#ferramentas_projeto)
- [Desenvolvimento](#ferramentas_desenvolvimento)
- [Testes](#ferramentas_testes)
- [Manutenção e evolução](#ferramentas_manutencao)

<br>
<br>

## &nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Introdução <a name = "introducao"></a>

<br>

Chegando na empresa vimos que não seria fácil a adequação de melhoria do processo com que a empresa
leva o software até hoje, vendo que os problemas já começam nas etapas primárias que são os
requisitos de mudanças do usuário e o suporte ao cliente. A pressão externa que vêm dos clientes que
estão querendo que o software mude, e a pressão interna por conta do espaço que a empresa está
perdendo no mercado está influenciando negativamente a equipe e acarretando diversos problemas no
processo como um todo. Tendo em vista a problemática enfrentada pela empresa , resolvemos solucionar
utilizando os conceitos de DevOps para unir nossa equipe juntamente com o Sprint Planning da
metodologia ágil Scrum para ser nossa etapa de projeto. Implementando os conceitos de DevOps em
nossa equipe aumenta o envolvimento entre todos os membros , redução de custos e maior eficiência e
agilidade combinado ao poder de projeto em forma de Sprints para que as mudanças de sistemas sejam
feitas de forma bem planejada e com uma melhor rastreabilidade. Foi decidido também por nós que
iremos fazer a mudança da linguagem que o software foi desenvolvido para uma mais atual e para que
isso aconteça contrataremos uma equipe que tenha como especialidade uma linguagem intermediária
entre a linguagem ultrapassada, que é utilizada, e a que irá ser implementada na nova versão do
software, linguagem moderna. Com isso não iremos parar o nosso software, pois estaremos realizando a
manutenção e atualizando (migrando) aos poucos para uma nova e melhor versão, sendo assim, não
iremos ter prejuízos, estaremos investindo em equipes e decisões internas dentro da empresa, não
teremos tanta demanda na lista de espera, a renda continua entrando na empresa e não precisaremos
ter 2 equipes separadamente destinadas para cada um dos softwares (legado e novo).

<br>
<br>

## &nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Etapa 1: Solicitação do Cliente <a name = "etapa1"></a>

<br>

O cliente solicita algo, seja uma mudança, funcionalidade nova, solução de bugs, entre outras
coisas, tudo por meio de tickets atendidos pela equipe de suporte. A equipe de suporte analisa o
ticket, vê se é da competência da equipe de projeto,

arquitetura ou desenvolvimento e só depois é passado para a equipe de relações com o cliente. A
equipe de relações conversa com o cliente para entender o que ele realmente precisa, de forma
detalhada e sem omissão de informação para que possa ser enviado um relatório técnico para as
equipes responsáveis pela análise e modelagem, se necessário, e também de implementação. Ainda nessa
etapa, o governante de projeto analisa a demanda. Se aprovado, verifica se é necessário um
orçamento, se sim, ele faz um e entrega para o cliente e após a confirmação do cliente é passado
para a equipe de projeto se for algo complexo ou funcionalidade nova, senão (correção de bug), passa
direto pra equipe de desenvolvimento.

<br>
<br>

## &nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Etapa 2: Projeto <a name = "etapa2"></a>

<br>

Se o relatório técnico for para a análise e modelagem, a equipe de projeto entra em ação,
classificando o tipo de solicitação (solução de bug, implementação de funcionalidades novas, etc),
nível de prioridade do problema e classifica também o nível de risco e urgência que isso tem para
ser desenvolvido, seguindo um SLA, para que esses sejam atendidos de forma ágil. Depois disso,
coloca o projeto na lista de espera, define a equipe que trabalhará nesse projeto e um prazo de
entrega que atende ao SLA da empresa utilizando o Azure Boards. Pensando na parte evolutiva do nosso
software, para um novo framework mais atualizado e com maior capacidade e suporte às tecnologias
atuais, as solicitações de nossos clientes serão planejadas e modeladas nessa etapa já utilizando o
novo conjunto de tecnologias como a linguagem intermediária, por exemplo. A etapa de projeto das
mudanças será baseada em sprints, onde a equipe de projeto e implementação em conjunto com a equipe
de teste, discutem e planejam o que irá ser feito durante aquele ciclo da sprint. A Sprint possui no
máximo 3 reuniões, onde a 1°, no início da semana, será abordado o que será feito no projeto como um
todo, o que falta ser feito, o que será feito na Sprint e a atribuição de cada equipe ao projeto. Na
2°, é durante o meio de semana, será realizada a reunião somente se houver necessidade, abordando
problemas enfrentados no

<br>
<br>

## &nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Etapa 3: Desenvolvimento <a name = "etapa3"></a>

<br>

Se o relatório técnico for direto para a etapa de desenvolvimento, quer dizer que não foi necessário
fazer um orçamento e o problema é resolvido sem a necessidade de atuação da equipe de projeto. Essa
etapa começa com o desenvolvimento do projeto solicitado pelo cliente, que pode ser realizado
individualmente ou em equipe, dependendo do tamanho e complexidade do projeto. A equipe de
desenvolvimento deve seguir boas práticas de codificação, garantindo a legibilidade e manutenção do
código, além de realizar testes unitários para garantir a qualidade do código. Durante essa etapa, a
equipe também pode utilizar ferramentas de controle de versão para gerenciar as mudanças no
código-fonte, permitindo que os desenvolvedores trabalhem de forma colaborativa em um mesmo projeto.
Será utilizado o Git como ferramenta principal para essa etapa do desenvolvimento, podendo trabalhar
com branches, ou seja, ambiente de desenvolvimentos para testes, produção, desenvolvimento,
atualizações, etc. Uma vez que o código-fonte esteja desenvolvido e testado, a equipe de
desenvolvimento pode trabalhar na integração contínua, que consiste em integrar o código- fonte com
o repositório central do projeto, permitindo que outras equipes possam testar e validar as mudanças.
Essa integração pode ser automatizada através de ferramentas de integração contínua, como o Jenkins.

<br>
<br>

## &nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Etapa 4: Testes <a name = "etapa4"></a>

<br>

Com a equipe integrada, os testes serão realizados tanto pela equipe de desenvolvimento quanto por
uma equipe focada só em criação de casos de testes. Primeiramente será feito os testes das unidades
de código , que serão automatizados e bem rápidos. Caso passe os testes de unidade , essas linhas
testadas serão implementadas assim criando os módulos que serão testados.

Também vão ser feitos testes de performance ,utilizando a ferramenta JMeter que vai simular uma
grande quantidade de acessos simultâneos, isso é de grande valia pois conseguiremos medir o
desempenho de performance de forma automatizada. Passando pelo teste de performance, serão feitos
testes de segurança para verificar se aquilo desenvolvido não impacta a segurança que o software já
tinha contra ameaças externas e acesso a algumas funcionalidades que alguns usuários não devem ter
(controle de acessos).Depois de todos esses testes, a solicitação é aprovada para entrega ao
cliente, para que ele mesmo possa testar com dados reais e nos dar o feedback.

<br>
<br>

## &nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Etapa 5: Manutenção e Evolução <a name = "etapa5"></a>

<br>

Com a equipe bem integrada e extremamente colaborativa, torna mais fácil a manutenção, pois os
problemas são resolvidos de forma mais rápida e eficiente. Utilizaremos o Nagios que fará o papel de
monitorar constantemente o software, que possibilita detectar problemas de desempenho, falhas de
segurança e entre outros que afetam ou possam vir a afetar de maneira direta o funcionamento do
software. Sendo possível até mesmo tomar medidas antecipadas para que esse problema não venha a se
tornar algo maior no futuro. Essa equipe vai começar a desenvolver a camada de tradução, que é a
parte do software que vai fazer a comunicação entre as diferentes tecnologias e linguagens de
programação. Logo após essa criação e com os módulos sendo integrados por essa linguagem
intermediária, a mesma será utilizada para desenvolvimento da nova versão do sistema. Essa tomada de
decisão de mudar de tecnologia vai gerar um software que vai ser mais atual e que permitirá a ele
evoluir por muito mais tempo. Assim retornaremos com mais força ao mercado, possibilitando uma maior
visibilidade da empresa , causando uma maior aderência de clientes ao software e aumento da
lucratividade.

<br>
<br>

## &nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Descrição das ferramentas utilizadas no processo <a name = "ferramentas"></a>

<br>

### **Projeto:** <a name = "ferramenta_projeto"></a>

- Azure boards É uma ferramenta da Microsoft, que tem recursos que ajudam em nosso processo,
  permitindo o planejamento, armazenamento e gerenciamento dos requisitos dos usuários. Utilizaremos
  essa ferramenta como nosso backlog.

### **Desenvolvimento:** <a name = "ferramenta_desenvolvimento"></a>

- Git O Git permite o controle de versões e controlar também o código-fonte. Vai permitir que nossos
  desenvolvedores trabalhem de forma simultânea em melhorias ou manutenções e tendo como vantagem o
  registro das mudanças feitas.

- Jenkins O Jenkins permite a integração contínua do código desenvolvido, pode auxiliar na
  automatização dos processos de compilação , da fase de testes e da implantação.

### **Testes:** <a name = "ferramenta_testes"></a>

- JMeter Para testar o desempenho do software ou de melhorias feitas em um módulo do sistema, por
  exemplo , por meio de testes de stress do sistema. Ela permite também testar servidores , teste de
  redes e etc.

### **Manutenção e evolução:** <a name = "ferramenta_manutencao"></a>

- Nagios É uma ferramenta de monitoramento , que permite tanto monitoramento de rede, quanto o de
  banco de dados , disponibilidade de servidores. Pode fornecer relatórios para notificar possíveis
  falhas críticas do sistema.
