## Validação

Segundo o MPS BR(MPS BR, 2020) o propósito do processo de Validação é testificar que o produto ou seu componente atende aos requisitos determinados quando colocado no ambiente operacional, ou seja, confirma que esse cumpre suas especificações. 
Esse processo certifica que o software corresponde às necessidades e expectativas do cliente, determinando dessa forma, o nível de qualidade do sistema/software desenvolvido. A pergunta a ser respondida aqui é " Fizemos o software correto ?". Nesse processo avaliamos se o que foi desenvolvido atende a regra de negócio do cliente e se ele literalmente está pagando por algo que supri suas necessidades, provavelmente definidas no levantamento de requisitos.

A norma pertinente a esse processo é a IEEE 1012, sendo utilizada para padronizar os processo que serão utilizados pela organização na Validação. Dentre seus processos estão a análise, revisão, inspeção, avaliação e teste de produto. A norma ajuda a definir tarefas, entradas, saídas esperadas em cada ciclo de vida e o Plano de verificação e validação, incluindo exemplos e formas que servem de diretivas.
Segundo Sommerville(Sommerville, 2011), existem muitos processos de software diferentes, mas todos devem incluir quatro atividades fundamentais para a engenharia de software. Entre essas 4 atividades está o processo de validação de software. Segundo o autor, o Teste de programa, em que o sistema é executado com dados de testes simulados, é a principal técnica de validação. 

Para ele, esse processo é iterativo e se divide em 3, Teste de desenvolvimento, de sistema e de aceitação.
O Testes de desenvolvimento é onde os componentes do sistema são testados pelas pessoas que o desenvolveram. Ferramentas de automação de teste, como JUnit* (MASSOL e HUSTED, 2003), que podem reexecutar testes de componentes quando as novas versões dos componentes são criadas, são comumente usadas.
Já nos Testes de sistema, componentes do sistema são integrados para criar um sistema completo. Preocupando-se em encontrar os erros resultantes das interações inesperadas entre componentes e problemas de interface do componente. Também visa mostrar que o sistema satisfaz seus requisitos funcionais e não funcionais, bem como testar as propriedades emergentes do sistema.

Por último, estão os Testes de aceitação, onde o sistema é testado com dados fornecidos pelo cliente, e não com dados advindos de testes simulados.
O teste de aceitação pode revelar erros e omissões na definição dos requisitos do sistema, pois dados reais exercitam o sistema de formas diferentes dos dados de teste, revelando problemas de requisitos em que os recursos do sistema não atendam às necessidades do usuário ou o desempenho do sistema seja inaceitável.

Dessa forma, fica visível a grande importância desse processo quando se deseja produzir softwares de alta qualidade.

* JUnit - https://junit.org/junit5/

## Validação sob a ótica do SWEBOK V 3.0

Segundo o Swebok(Swebok, 2004), a qualidade do software é definida como a capacidade do produto de software de satisfazer as necessidades declaradas e implícitas sob condições especificadas, e como o grau em que esse produto de software atende aos requisitos estabelecidos, ressaltando assim, a importância da elaboração, manutenção e qualidade dos requisitos de software.
A qualidade de software, de acordo com o Swebok(Swebok, 2004), está dividida em 4 tópicos, Fundamentos de qualidade de software, Processos de gerenciamento de qualidade de software, Considerações práticas e  Ferramentas de qualidade de software.

O processo de Validação está incluso no tópico Processos de gerenciamento de qualidade de software, que define processos, proprietários de processos, requisitos para os processos, medições do processos e suas saídas e canais de feedback ao longo de todo o ciclo de vida do software.Dessa forma, o processo de Validação busca garantir que o produto cumpre com a finalidade pretendida e especificada, tendo como objetivo, juntamente com o processo de Verificação, ajudar o setor de desenvolvimento a construir o sistema com qualidade durante o ciclo de vida do software.

Sob essa perspectiva, a Validação inicia-se já no início do processo de desenvolvimento ou manutenção do software, fornecendo um exame das principais características do produto em relação às  versões anteriores e às especificações a serem atendida. Esse exame, visa demonstrar se os requisitos são corretos, completos, precisos, consistentes e testáveis.

Como todo processo, a Validação também deve possuir planejamento, a fim de garantir que cada recurso, função e responsabilidade é claramente atribuído. Nessa fase serão gerados documentos, que devem descrever recursos, funções, atividades, técnicas e ferramentas a serem usadas no processo. Além disso,  irá incluir fases de análise,revisão, inspeção, avaliação e teste de produtos,abrangendo em seu escopo sistemas, software e hardware.

Em todo o processo de V&V, serão abordados a gestão, comunicação, políticas e procedimentos das atividades de V&V e sua interação, bem como relatórios de defeitos e requisitos de documentação.

Assim sendo, observa-se que a Validação é um importante processo dentro de todo o ciclo de vida do software quando se pretende garantir sua qualidade e que suas saídas, quando aprovadas,  servirão como entradas para o processo seguinte ou como evidências para a correção de algum ponto no software que esteja em desacordo com os requisitos estabelecidos.


## Referências

PESSONI, Vinicius. Normas ISO / IEEE Importantes no Teste de Software. TESTER GLOBAL. 2012. Disponível em: https://viniciuspessoni.com/2012/01/11/normas-iso-ieee-importantes-no-teste-de-software/#:~:text=O%20IEEE%20Std%201012%2D2004,os%20quais%20servem%20de%20diretivas. Acesso em: 16 set. 2020.

SOMMERVILLE,  Ian. Engenharia de Software. Tradução Ivan Bosnic e Kalinka G. de O. Gonçalves. 9. ed. São Paulo: Pearson Prentice Hall, v. 1, 2011. Tradução de: Software Engineering.

MASSOL, V.; HUSTED,T. JUnitin Action. Greenwich, Conn.: Manning Publications Co., 2003.

Wikimedia Foundation. Verificação e validação. Wikipédia, a enciclopédia livre. 2018. Disponível em: https://pt.wikipedia.org/wiki/Verifica%C3%A7%C3%A3o_e_valida%C3%A7%C3%A3o. Acesso em: 16 set. 2020.

IEEE. IEEE Standard for Software Verification and Validation. In: IEEE Software Engineering Standards Collection. Los Alamitos, Ca.: IEEE Computer Society Press, 1998.

SWEBOK. Guide to the Software Engineering Body of Knowledge. 2004 Version.project of the IEEE Computer Society Professional Practices Committee. Disponível em: <http://www.swebok.org/>. Acesso em: 30 de Setembro de 2020.

MPS.br SOFTEX, MPS.BR - Guia Geral, versão 1,Jan. 2020. Disponível em:file:///C:/Users/wesley/Downloads/MPS.BR_Guia_Geral_Software_2020.pdf . Acesso em 16 set. 2020.
