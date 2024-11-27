# Documento de visão

## Plataforma (IFocus)

### Histórico da Revisão 

|  Data  | Versão | Descrição | Autores |
|:-------|:-------|:----------|:------|
| 27/11/2024 |  **`0.1`** | Início do documento de visão do projeto  | Rodrigo de Oliveira |


### 1. Objetivo do Projeto 

O projeto __IFocus__ tem como objetivo criar uma plataforma educacional em formato de curso para estudantes que querem ingressar no IFRN.
 

### 2. Descrição do problema 

|         __        | __   |
|:------------------|:-----|
| **_O problema_**    | A falta de direcionamento ao acesso de material de qualidade para ingresso no IFRN. |
| **_afetando_**      | Alunos, principalmente de escola pública, dos 8°s e 9°s anos. |
| **_cujo impacto é_**| Causa a dificuldade do ingresso ao IFRN.|
| **_Uma boa solução seria_** | Criar uma plataforma online e de fácil acesso para esses estudantes. |


### 3. Descrição dos usuários

| Nome | Descrição | Responsabilidades |
|:---  |:--- |:--- |
| Estudantes  | Estudantes do 8° e 9° ano. | Logar e deslogar na conta para acessar a plataforma; Assistir as aulas; Fazer os exercícios; Fazer os seminários; favoritar e comentar nas placas; Pôr uma descrição em seu perfil, que ficará público na aba da turma;|
| Visitante  | Usuário externo não cadastrado como membro da plataforma. | Acessar o site; ver as listas de conteúdos.|
| Administrador | Alunos desenvolvedores. | Gerenciar as matérias; Gerenciar as aulas; Gerenciar os conteúdos.|

### 4. Descrição do ambiente dos usuários

As aulas devem poder ser acessadas a qualquer momento, o sistema deve funcionar 24h por dia, 7 dias por semana. Sendo necessario apenas a contexão a internet para que o usuário acesse os conteúdos.
Nenhum usuário tem ambiente fixo para ser acessar a plataforma.

### 5. Principais necessidades dos usuários
Os alunos do 8° ao 9 ano, principalmente de escolas publicas, precisam de uma forma de estudar que consiga garantir a aprovação no IFRN.

### 6.	Alternativas concorrentes
Como alternativas concorrentes podemos colocar os cursinhos presenciais.

Instagram:
Pontos fortes: A sua estrutura permite uma visualização boa das postagens das pessoas que você está seguindo.
Pontos fracos: Não permite somente a visualização das postagens de forma mais exclusiva ou visualização dos usuários, te mostrando diversos outros conteúdos.

Parte do site da UniFacema que permite a visualização das placas:
Pontos fortes: É um dos poucos sites que tem essa proposta.
Pontos fracos: Existem erros de design que podem gerar desconforto visual durante a navegação.

### 7.	Visão geral do produto
A plataforma em desenvolvimento deve ser feita para ser utilizada em navegadores (browsers);
Será possível ao administrador e aos alunos vincular seu email ao site.
O site tem 3 tipos de usuário. O usuário visitante, quando não é cadastrado, pode acessar o site e visualizar as materias disponíveis, mas não pode acessar as aulas e os materiais. 
O aluno seria um usuário cadastrado, podendo assistir as aulas, acompanhar seu desempenho, realizar questões e simulados.
O administrador será um moderador do sistema, não necessariamente usufruindo desse.
 
### 8. Requisitos Funcionais

| Código | Nome | Descrição |
|:---  |:--- |:--- |
| RF01 | Fazer o login de usuário | Para fazer o primeiro login o usuário precisará preencher um campo formulário com seu nome, e-mail e senha, e confirmar o seu e-mail. Os logins seguintes poderão ser feitos inserindo a matricula e senha. Logo após o login o usuário será redirecionado para a página inicial do site. |
| RF02 | Assistir aulas | O aluno pode visualizar as aulas listas de aula existentes, separadas por assunto, e acessar uma aula em formato de vídeo e com uma breve descrição de texto. |
| RF03 | Realizar as listas de questões | O aluno pode visualizar as listas de questões existentes, podendo responde-las e verificar a sua resposta, recebendo um em texto ou vídeo como correção, caso tenha. |
| RF04 | Visualizar simulados | O aluno pode visualizar as listas de questões existentes, podendo responde-las e verificar a sua resposta, recebendo uma descrição em texto ou vídeo como correção. |
| RF05 | Visualizar desempenho | O aluno pode visualizar as listas de questões existentes, podendo responde-las e verificar a sua resposta, recebendo uma descrição em texto ou vídeo como correção. |
| RF06 | Realizar listas de questões | O aluno pode visualizar as listas de questões existentes, podendo responde-las e verificar a sua resposta, recebendo uma descrição em texto ou vídeo como correção. |
| RF07 | Deve ser possível visualizar o seu dempenho geral na plataforma | O aluno pode visualizar as listas de questões existentes, podendo responde-las e verificar a sua resposta, recebendo uma descrição em texto ou vídeo como correção. |

### 9. Requisitos não-funcionais

 Código | Nome | Descrição | Categoria | Classificação
|:---  |:--- |:--- |:--- |:--- |
| RNF01 | Design responsivo | O sistema deve adaptar-se a qualquer tamanho de tela de dispositivo, seja, computador, tablets ou smart phones. | Usabilidade | Obrigatório |
| RNF02 | Privacidade | O sistema não deve revelar informações pessoais sobre seus usuários | Segurança | Obrigatório |
| RNF03 | Facilidade de uso | O sistema deve ter uma interface de fácil entendimento | Usabilidade | Obrigatório |
| RNF04 | Acesso inclusivo | Ser acessível para todos os usuários, independentemente de suas habilidades | Acessibilidade | Obrigatório |
| RNF05 | | Os dados devem ser gravados de forma criptografada no banco de dados | Segurança | Obrigatório |

