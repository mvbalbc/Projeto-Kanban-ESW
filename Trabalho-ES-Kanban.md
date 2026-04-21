___
# Objetivo
Construir de modo iterativo e incremental os artefatos propostos. O sistema de software a ser desenvolvido deve prover suporte à equipe que gerencia projetos por meio da técnica Kanban.

# Requisitos Funcionais
1. O sistema que dá suporte à técnica kanban deve:
	+ Ter interface com usuário;
	+ Cadastrar e autenticar usuário; (persistência)
2. Depois de autenticado, o usuário deve ter aceso aos seguintes serviços:
	+ O usuário pode participar de um ou mais projetos;
3. Os seguintes serviços devem ser disponíveis para o usuário:
	1. Participar de projeto
	2. Criar projeto
	3. Quadro: criar, ler, atualizar e excluir
	4. Coluna: A FAZER, FAZENDO, FEITO
	5. Raia: criar, ler, atualizar e excluir
	6. Cartão de Atividade: criar, ler, atualizar, excluir, mover entre colunas e rais, estabelecer número limite em colunas (work-in-progress), identificador, nome, responsável, data limite para término, prioridade e descrição.
	7. Cálculo de métricas: cycle time, lead time, throughput e work-in-progress

# Entregáveis[^10]
1. Descrição do processo de gerenciamento contendo informação acerca do quadro e dos cartões usados.[^1]
	1. SWEBOk - Chapter 10
	2. https://kanban.university/wp-content/uploads/2021/04/The-Official-Kanban-Guide_Portuguese_A4.pdf
2. Documento de visão e escopo (vision).[^2]
3. Especificação de requisitos não funcionais por meio de artefato para esse fim (system-wide requirements).[^3] 
4. Especificação de requisitos funcionais por meio de histórias de usuário (user story).[^4]
5. Descrição da arquitetura do software (architecture notebook).[^5]
6. Projeto de interface com o usuário.[^6]
7. Projeto físico de banco de dados.[^7]
8. Protótipo do sistema e vídeo demonstrando teste de sistema do protótipo.[^8]
9. Descrição da infraestrutura de implantação (infrastructure) contemplando hardware, software e serviços.[^9]

# Dúvidas
1. Como fazer o processo ser iterativo com o método Kanban ?
2. 

[^1]: Descritas atividades realizadas no gerenciamento do projeto.
	Adotado método Kanban no gerenciamento do projeto.
	Criado quadro Kanban com colunas apropriadas.
	Provida descrição do propósito de cada coluna do quadro Kanban.
	Criados cartões para gerenciamento do projeto por meio do método Kanban.
	Provida informação sobre cada cartão criado.

[^2]: Descrito o problema resolvido pelo sistema de software.
	Descrita a posição que o sistema de software pretende ocupar no mercado.
	Descritas as partes interessadas (stakeholders) e suas responsabilidades.
	Descrito o ambiente de trabalho dos futuros usuários.
	Descritas as necessidades atendidas pelo sistema de software.
	Descritas resumidamente as funcionalidades a serem providas.
	Descritos resumidamente requisitos não funcionais.
	Descritos resumidamente elementos da solução proposta pela equipe de desenvolvimento.

[^3]: Descritos requisitos funcionais que não tenham sido especificados nas histórias de usuários.
	Descritos atributos de qualidade requeridos (usabilidade, desempenho etc.).
	Descritos requisitos quanto à interface com o usuário.
	Descritos requisitos quanto à interface com dispositivos externos.
	Descritos requisitos quanto à interface do sistema de software com outros sistemas.
	Relacionados aspectos aos quais o sistema de software deve estar conforme (normas, leis etc.).
	Documento relaciona restrições a serem observadas quando do projeto (design).
	Descritos aspectos de licenciamento.
	Descritos requisitos quanto à documentação.

[^4]: Cada requisito funcional descrito por história de usuário.
	Cada história de usuário é descrição segundo perspectiva do usuário final.
	Cada história de usuário escrita em linguagem informal.
	Cada história de usuário adota modelo (Como ….. Eu quero ….. Para …..).

[^5]: Descritos objetivos de arquitetura.
	Descritas suposições relativas à arquitetura.
	Descritas dependências consideradas na definição da arquitetura.
	Descritos requisitos relativos à arquitetura.
	Descritas decisões, restrições e justificativas relativas à arquitetura.
	Descritos mecanismos de arquitetura.
	Descritas abstrações relativas à arquitetura.
	Descrita arquitetura segundo determinadas perspectivas.
	Provida informação sobre impacto das ferramentas usadas (frameworks etc.) na arquitetura.

[^6]: Projeto de interface com o usuário composto por storyboards.
	Cada storyboard descreve cenário de uso do sistema de software.
	Cada storyboard composto por sequência de wireframes.
	Cada wireframe é esboço simples de tela.

[^7]: Projeto físico do banco de dados composto por diagrama e texto.
	Fornecido diagrama que identifica tabelas e relacionamentos entre tabelas.
	Para cada tabela, é informado nome, colunas, chaves, relacionamentos etc.
	Para cada tabela é fornecida descrição textual do propósito da tabela.

[^8]: Protótipo de acordo com o projeto (design).
	Protótipo demonstra sistema integrado (apresentação, negócio, armazenamento etc.).
	Protótipo provê as funcionalidades corretamente.

[^9]: Provida informação sobre software necessario à implantação do sistema de software.
	Provida informação sobre hardware necessario à implantação do sistema de software.
	Provida informação sobre serviços necessarios à implantação do sistema de software.

[^10]: As notas se referem aos critérios de avaliação descritos na descrição do trabalho.
