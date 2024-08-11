Introdução 
O sucesso de um negócio depende da sua capacidade de adaptar rapidamente seus processos e sistemas de informação, permitindo uma reação eficiente às mudanças no mercado. O levantamento de requisitos é crucial nesse contexto, pois identifica e modela as necessidades do negócio que os sistemas de informação devem atender, tornando-se cada vez mais relevante em um cenário dinâmico.
Para se manterem competitivas, as organizações modernas precisam constantemente evoluir e inovar em seus processos de negócios e nos sistemas de informação que os suportam. A integração entre os objetivos de negócio, processos e sistemas de informação é essencial para essa dinâmica, sendo um desafio para os gerentes. Nesse contexto, os sistemas de informação precisam estar alinhados com os objetivos reais do negócio. Existem várias técnicas e ferramentas de modelagem para facilitar a compreensão da complexidade das organizações modernas, como discutido por Kalpic e Bernus (2002), Li e Williams (2002), e Vernadat (2002). Essas ferramentas ajudam a tornar a realidade organizacional mais compreensível. No entanto, ainda há uma falta de integração entre a análise de negócios e a dos sistemas que os suportam, como apontado por Odeh e Kamm (2003) e Shen (2004).
O Processo Unificado (UP) é uma metodologia de desenvolvimento de software que tem ganhado destaque, mas a atividade de levantamento de requisitos ainda é tratada de forma empírica, sem considerar sistematicamente o foco nos objetivos do negócio. Assim, surge a necessidade de aproximar o levantamento de requisitos de software das necessidades reais do negócio. No paradigma de orientação a objetos, essa análise é frequentemente baseada em Casos de Uso da UML (Unified Modeling Language). Embora existam heurísticas para a identificação de casos de uso, como as propostas por Schneider e Winters (1998), Jacobson, Booch e Rumbaugh (1999), e Lilly (1999), ainda não há métodos estabelecidos para tornar essa atividade mais sistemática.
O alinhamento entre os requisitos de software e as necessidades de informatização do negócio pode ser aprimorado através de técnicas de modelagem de negócios, e a tecnologia de orientação a objetos com a UML permite a integração desses modelos nos domínios de negócio e software. No entanto, faltam metodologias completas que alinhem sistematicamente o levantamento de requisitos de software aos objetivos reais do negócio (Azevedo Jr., 2003).
Este trabalho apresenta uma metodologia que incorpora atividades de levantamento de requisitos baseadas na arquitetura de modelagem de negócios de Eriksson e Penker (2000), visando sistematizar essa etapa do desenvolvimento de sistemas. Essas atividades podem ser aplicadas em qualquer metodologia de desenvolvimento que siga os princípios do UP.
A pesquisa foi fundamentada em uma revisão bibliográfica extensa, na elaboração e descrição de atividades baseadas em uma arquitetura de modelagem de negócios, na aplicação dessas atividades na metodologia de desenvolvimento de uma empresa, e em testes com o desenvolvimento de parte de um sistema de informação, com o objetivo de avaliar a proposta.
Neste artigo, serão propostas atividades de modelagem baseadas na arquitetura de modelagem de negócios para serem integradas em metodologias de desenvolvimento de sistemas de informação baseadas no UP. O objetivo é melhorar a definição e o alinhamento dos requisitos do sistema com os objetivos reais do negócio de forma sistemática. A próxima seção aborda definições relacionadas à Engenharia de Requisitos e ao UP, apresentando conceitos sobre a modelagem de processos de negócios com a UML e a identificação de casos de uso de negócios. Em seguida, as atividades propostas serão descritas e integradas ao UP, com fluxogramas e descrições de uma metodologia completa de desenvolvimento de software, incluindo os artefatos resultantes e as considerações finais.
A eficácia de um empreendimento é diretamente influenciada por sua habilidade em ajustar rapidamente seus processos e sistemas de informação para responder com agilidade às mudanças do mercado. Nesse cenário, o levantamento de requisitos desempenha um papel essencial ao identificar e modelar as necessidades empresariais que os sistemas de informação devem atender. Essa prática se torna ainda mais importante em um ambiente de negócios dinâmico.
Para se manterem competitivas, as organizações modernas precisam estar em constante evolução e inovação, tanto em seus processos de negócios quanto nos sistemas de informação que os suportam. A integração entre os objetivos empresariais, os processos e os sistemas de informação é vital para essa evolução, representando um desafio significativo para os gestores. Nesse contexto, é crucial que os sistemas de informação estejam alinhados com as metas reais do negócio. Diversas técnicas e ferramentas de modelagem existem para ajudar a entender a complexidade das organizações modernas, conforme discutido por Kalpic e Bernus (2002), Li e Williams (2002), e Vernadat (2002). Essas ferramentas são essenciais para tornar a realidade organizacional mais acessível. Contudo, ainda há uma lacuna significativa na integração entre a análise de negócios e a análise dos sistemas que os sustentam, como apontam Odeh e Kamm (2003) e Shen (2004).
O Processo Unificado (UP) tem se destacado como uma metodologia de desenvolvimento de software, mas a fase de levantamento de requisitos ainda é frequentemente abordada de maneira empírica, sem uma ênfase sistemática nos objetivos do negócio. Isso evidencia a necessidade de alinhar o levantamento de requisitos de software com as necessidades reais do negócio. No paradigma orientado a objetos, a análise frequentemente se baseia em Casos de Uso da UML (Unified Modeling Language). Apesar da existência de heurísticas para identificar casos de uso, como as propostas por Schneider e Winters (1998), Jacobson, Booch e Rumbaugh (1999), e Lilly (1999), ainda faltam métodos estabelecidos que tornem essa atividade mais sistemática.
A integração entre os requisitos de software e as necessidades de informatização do negócio pode ser aprimorada por meio de técnicas de modelagem de negócios. A tecnologia orientada a objetos, especialmente com o uso da UML, permite integrar esses modelos nos domínios de negócios e software. No entanto, há uma carência de metodologias completas que alinhem de maneira sistemática o levantamento de requisitos de software aos objetivos reais do negócio (Azevedo Jr., 2003).
Este estudo propõe uma metodologia que incorpora atividades de levantamento de requisitos com base na arquitetura de modelagem de negócios de Eriksson e Penker (2000), com o objetivo de sistematizar essa fase no desenvolvimento de sistemas. Essas atividades podem ser aplicadas a qualquer metodologia de desenvolvimento que siga os princípios do UP.
A pesquisa foi sustentada por uma extensa revisão bibliográfica, pela elaboração e descrição de atividades fundamentadas em uma arquitetura de modelagem de negócios, pela aplicação dessas atividades na metodologia de desenvolvimento de uma empresa, e por testes conduzidos durante o desenvolvimento de parte de um sistema de informação, com a intenção de avaliar a proposta.
Neste artigo, serão sugeridas atividades de modelagem baseadas na arquitetura de modelagem de negócios, visando a sua integração em metodologias de desenvolvimento de sistemas de informação baseadas no UP. O objetivo é aprimorar de maneira sistemática a definição e o alinhamento dos requisitos do sistema com os objetivos reais do negócio. A seção seguinte aborda conceitos relacionados à Engenharia de Requisitos e ao UP, introduzindo noções sobre a modelagem de processos de negócios com a UML e a identificação de casos de uso de negócios. Em seguida, as atividades propostas serão descritas e integradas ao UP, com a apresentação de fluxogramas e descrições de uma metodologia completa de desenvolvimento de software, incluindo os artefatos gerados e as considerações finais.