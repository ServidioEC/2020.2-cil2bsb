# Princípios Gerais de Projeto

## Histórico de Versões
| Data       | Versão | Descrição                               | Autores           | Revisor  |
| ---------- | ------ | --------------------------------------- | ----------------- | ---------|
| 22/03/2021 | 0.1    | Criação e elaboração do documento       | Giovana Dionisio  | -------- |

## Introdução 
<p align="justify"> Dentro da literatura de IHC, princípios e diretrizes representam objetivos e regras gerais que são comumente aplicados na construção da interface de usuário, auxiliando o processo de design. Geralmente, os princípios e diretrizes propostos giram em torno de tópicos específicos que, em conjunto, compõem os Princípios Gerais de Projeto. Estes tópicos são divididos em: </p>

### Correspondência com as expectativas dos usuários
<p align="justify"> Aborda a necessidade de que haja um alinhamento entre o mundo real e o sistema que está sendo projetado, levando em conta as variáveis mentais e físicas e as tarefas e controle que são utilizados na manipulação dessas variáveis. Para isso, é necessário que se certifique se é possível para o usuário determinar relacionamentos entre intenções e possíveis ações, entre o estado do sistema e a sua percepção sensorial e entre o estado percebido do sistema e suas necessidades, intenções e expectativas. </p>

### Simplicidade nas estruturas das tarefas
<p align="justify"> Se refere à simplificação, sempre que possível, das estruturas das tarefas que o usuário irá realizar, de maneira que se reduza a quantidade de planejamento e resolução de problemas que elas exigem. Para que haja essa diminuição de complexidade, as tarefas dentro do sistema podem ser reestruturadas através de abordagens tecnológicas. São essas: </p>

* <p align="justify"> Manter a tarefa a mesma mas fornecer apoio para que os usuários aprendam a realizá-la; </p>
* <p align="justify"> Utilizar a tecnologia para que se torne visível aspectos que seríam invisíveis, aprimorando o feedback e melhorando a capacidade de controle do usuário sobre a tarefa; </p>
* <p align="justify"> Automatizar a tarefa, parcial ou totalmente, mas mantendo-a a mesma e tomando cuidado para não retirar demais o controle do usuário; </p>
* <p align="justify"> Modificar a natureza da tarefa. </p>

### Equilíbrio entre controle e liberdade do usuário
<p align="justify"> Corresponde à ideia de que o computador, a interface e o ambiente de trabalho são de propriedade do usuário, logo este precisa estar no controle do sistema. Desta maneira, o usuário pode aprender rapidamente e desenvolver a sensação de destreza. Entretanto, quando essa liberdade é colocada sem limites ou restrições, o usuário pode sentir-se confuso com o excesso de decisões que ele precisa tomar. Por isso, é necessário que haja um equilíbrio, onde sejam explorados o poder das restrições para que o usuário possua o sentimento de que a alternativa que existe é realizar a coisa certa. </p>

### Consistência e padronização
<p align="justify"> Está relacionada a padronização aplicada ao sistema para que a aprendizagem da sua utilização possa ser mais simples. Assim, é assegurada a consistência da interface do sistema junto ao seu modelo conceitual. Para isso, todos os artefatos relacionados ao sistema necessitam estar consistentes, exemplificando a operação do modelo conceitual adequado. </p>

### Promoção da eficiência do usuário
<p align="justify"> Considera que a eficiência do usuário deve estar sempre à frente a do computador, pois as pessoas são mais custosas que máquinas. Logo, uma economia de tempo e esforço do usuário é muito mais vantajosa que do computador, então é recomendado que os processamentos não prendam a interação do usuário, pois isso pode causar perda de produtividade e dinheiro. Com um bom projeto de arquitetura de software advindo de uma cooperação e parceria entre engenheiros e designers de IHC, é possível permitir que os usuário interajam com outras partes do sistema enquanto um processo é executado em background. </p>

### Antecipação das necessidades do usuário
<p align="justify"> Relaciona-se com a ideia de que, em vez de esperar que o usuário vá atrás das informações ou da execução de ferramentas, o sistema já preveja quais serão suas necessidades e forneça ao usuário essas informações e ferramentas que são necessárias ao longo da utilização do software. </p>

### Visibilidade e reconhecimento
<p align="justify"> Está ligado à necessidade de que as coisas estejam visíveis ao usuário. Ele deve visualizar o que é possível realizar e como se deve realizar uma ação previamente, deve ter como opção as ações que correpondam às suas intenções, que estejam disponíveis e que façam sentido na situação em que ele se encontra e deve ser informado de maneira consistente sobre o estado do sistema logo após realizar uma ação. </p>

### Conteúdo relevante e expressão adequada
<p align="justify"> Propõe a utilização de expressões adequadas e que se assemelham ao comportamento humano. Para isso, são seguidos os seguintes princípios sobre o conteúdo, gerando assim uma interação polida:
</p>

* <p align="justify"> Qualidade, não prestando informações que não sejam verdadeiras ou que sejam fruto de especulação; </p>
* <p align="justify"> Quantidade, contibuindo em uma fala de maneira que se informe o usuário o quão for necessário e nada além disso; </p>
* <p align="justify"> Relação, de forma que tudo o que for dito tenha relação e seja útil ao que está sendo conversado; </p>
* <p align="justify"> Modo, evitando-se prolixidade e ambiguidade para que a conversa possa ser concisa e organizada. </p>

### Projeto para erros
<p align="justify"> Engloba a projeção do sistema considerando que o usuário irá cometer qualquer erro potencial. Com isso, o usuário precisa ser auxiliado a se recuperar de um erro através de informações sobre o que ocorreu, quais consequências essa ação gera e como reverter os resultados indesejados. Por isso, deve-se facilitar ao usuário a reversão de erros e dificultar a operação de ações que sejam irreversíveis. </p>

## Metodologia
<p align="justify"> A equipe analisou o site <a href = "http://www.cil2bsb.com.br/">http://www.cil2bsb.com.br/</a> a fim de determinar quais princípios gerais possuíriam mais foco ao longo do desenvolvimento deste projeto. Esta análise foi realizada mesclando a visão dos membros da equipe com a ótica das personas que foram levantadas. Desta maneira, foram selecionados os princípios aplicáveis com base no que seria mais relevante para as personas usuárias do site do CIL2 de Brasília e que, na visão da equipe, poderiam ser melhor implementados ou que fazem mais sentido no contexto do sistema. </p>

## Princípios aplicáveis
### Correspondência com as expectativas dos usuários
<p align="justify"> O site apresenta falhas relacionadas às expectativas dos usuário, como o botão "mais fotos" presente na seção "Fotos" da página home que não redireciona para uma página com as fotos postadas no site, somente recarrega a página. </p>

### Simplicidade nas estruturas das tarefas
<p align="justify"> Algumas tarefas poderiam ser realizadas de maneira mais simples. Por exemplo, ao clicar em uma notícia da lateral do carrossel da seção "Notícias" na página home, o site somente exibe a notícia, tendo que o usuário clicar nela ao ser mostrada no carrosel para ser redirecionado, ação que poderia ser realizada no primeiro click. Neste caso, a aplicação do princípio poderia ser realizada através da abordagem tecnológica de melhoria da capacidade de controle do usuário sobre a tarefa. </p>

### Equilíbrio entre controle e liberdade do usuário
<p align="justify"> Existem falhas ao aplicar as restrições aos usuários, como no caso do usuário acessar a página "Professores" da seção "QUEM SOMOS" do cabeçalho. Apesar da página estar vazia, o usuário possui a liberdade para visitá-la, o que deveria ser restringido pelo próprio sistema. </p>

### Consistência e padronização
<p align="justify"> Por vezes, o site foge à consistência e padronização. Por exemplo, opções que não são clicáveis no cabeçalho da página são destacadas quando estimuladas pelo mouse da mesma maneira que as opções clicáveis, o que dificulta a aprendizagem do uso do site. </p>

### Antecipação das necessidades do usuário
<p align="justify"> Em algumas situações o site não antecipa as necessidades do usuário, fazendo-o ter que ir atrás do que ele necessita. Um exemplo disso é a seção "Mais" da barra lateral, que é substituída por "Outras Notícias" quando algum de seus itens são visitados. O usuário que está interessado pelos conteúdos da seção "Mais" precisa retornar à página Home para visualizar os outros. </p>

### Visibilidade e reconhecimento
<p align="justify"> A aplicação deste princípio corrigiria problemas que dificultam a usabilidade do site, como a dificuldade que existe em saber o que se pode fazer (por exemplo, ao clicar na logo da Secretaria de Educação, o usuário é direcionado ao site <a href = "http://www.educacao.df.gov.br/">http://www.educacao.df.gov.br/</a>, possibilidade que não é deixada explícita) ou não (por exemplo, por mais que a opção "CIL 2" seja listada dentro da seção "QUEM SOMOS" do cabeçalho, ela não pode ser visitada). </p>

## Bibliografia
BARBOSA, Simone Diniz Junqueira; DA SILVA, Bruno Santana. **Interação humano-computador**. Elsevier, 2010. Cap. 8: Princípios e Diretrizes para o Design de IHC. 