# ENGENHARIA DE SOFTWARE
### FATEC SÃO JOSÉ DOS CAMPOS - JESSEN VIDAL 
Repositório criado e destinado para as atividades realizadas em sala de aula, sob orientação do professor Giuliano Araujo Bertoti, na disciplina de Engenharia de Software em Banco de Dados - 2º Semestre/2023.

## AULA 11/08/23
### ATIVIDADE 1 - Comentários do livro "Software Engineering at Google"
### TEXTO 1:
We see three critical differences between programming and software engineering: time, scale, and the trade-offs at play. On a software engineering project, engineers need to be more concerned with the passage of time and the eventual need for change. In a software engineering organization, we need to be more concerned about scale and efficiency, both for the software we produce as well as for the organization that is producing it. Finally, as software engineers, we are asked to make more complex decisions with higher-stakes outcomes, often based on imprecise estimates of time and growth.

#### COMENTÁRIOS:
Existem três tipos de diferenças criticas na programação: Tempo, escala e Trade-offs.  No contexto de projetos de engenharia de software, é necessário considerar mais a passagem do tempo e a necessidade futura de mudanças. Em organizações de engenharia de software, a preocupação deve ser maior em relação à escala e eficiência, tanto para o software produzido quanto para a própria organização.

## AULA 14/08/23
### TEXTO 2:
Within Google, we sometimes say, “Software engineering is programming integrated over time.” Programming is certainly a significant part of software engineering: after all, programming is how you generate new software in the first place. If you accept this distinction, it also becomes clear that we might need to delineate between programming tasks (development) and software engineering tasks (development, modification, maintenance). The addition of time adds an important new dimension to programming. Cubes aren’t squares, distance isn’t velocity. Software engineering isn’t programming.

#### COMENTÁRIOS:
No texto acima é comentado que programação é uma parte significante da Engenharia de Software, porém é evidenciado que somente a programção não é Engenharia de Software, assim como cubos não são quadrados e distâncias não é velocidade em si. 

### ATIVIDADE 2 - TRADE-OFFS
#### 3 EXEMPLOS DE TRADE-OFFS:
  1 - Desempenho x Custo: No desenvolvimento de softwares quando queremos uma funcionalidade ou aplicação com maior desempenho automaticamente implicará num custo maior para a confecção desse software.
  2 - Complexidade do Software x Simplicidade do código: Quanto mais complexo do software maior será o detalhamento do software, que implicará no número de linhas digitadas, bem como no "tamanho" do arquivo.
  3 - Java x Python : Software mais completo e com maior segurança e portabilidade quando comparado ao Python, que por sua vez é mais leve, e mais fácil de implementar quando não se há familiariade. 

#### REQUISITOS NÃO FUNCIONAIS:
Um exemplo de comparação de requisitos não funcionais é a usabilidade do google como site de buscas rápidas quando comparadas a outros sites como bing, yahoo, entre outros, sendo a google uma aplicação direta, que não possue propagandas desnecessárias e de baixissimo tempo de resposta, além de possuir um enorme banco de dados de informações.

## AULA 18/08/23
### ATIVIDADE 3 - Requisitos não funcionais de usabilidade - Avaliação de 10 Heurísticas
#### 1 ACERTO E 1 ERRO DE CADA HEURÍSTICA: "10 Usability Heuristics for User Interface Design".

1: Visibility of system status
  - Acerto: Familiaridade do usuário com o sistema, através das interações previsiveis do sistema, tornando-o mais simples na sua utilização.
  - Erro: Itens ou falta de indicação ao usuário em qual processo ou etapa que ele se encontra.

2: Match between system and the real world
  - Acerto: Semelhanças de itens do sistema com o mundo real, por exemplo metáforas trazendo maior simplicidade e familiaridade do usuário.
  - Erro: Utilização de termos ou jargões técnicos que por mais que existam, não são do cotidiano do usuário.

3: User control and freedom
  - Acerto: O usuário possue total liberdade para navegar e controlar o sistema, colocando as modificações que mais lhe agradam, seja no aspecto visual ou funcional do sistema.
  - Erro: Quando o sistema oferece muitas opções de modificação ou de operação pode acontecer do sistema ficar sobrecarregado e uma vez que não possua um código/ servidor apurado, pode vir a ter travamentos ou lentidôes.

4: Consistency and standards
  - Acerto: Apresentar funções padrões que intuitivamente indicam ao usuário o caminho a ser seguido - ex: logout
  - Erro: Apresentar itens, palavras ou expressões que possuam causar dualidade de entendimento ao usuário.

5: Error prevention
  - Acerto: Formatação de informações e dados de entrada para o tratamento facilitado do sistema, prevenindo que o usuário faça erros desnecessários
  - Erro: Permissão que o usuário insira caracteres no sistema que não são reconhecidas pelo sistema, sendo que poderia ser resolvida na criação do código.

6: Recognition rather than recall
 - Acerto: Pré definição de itens e opções que facilitam a utilização do sistema, por exemplo o calendário na seleção do dia
 - Erro: Fazer com que o usúario lembre de dados ou informações que poderiam ser pré definidas pelo sistema.

7: Flexibility and efficiency of use
  - Acerto: Inserção de atalhos que facilitam a vida de usuários mais experientes, mas que seja "ocultos" à usuários novatos, tornando assim o método mais eficiente para ambos.
  - Erro: Não mostrar os atalhados e modificações para os novos usúarios, o que poderia facilitar a interação com o sistema.

8: Aesthetic and minimalist design
  - Acerto: Apresentar apenas informações necessárias, com menos informações terá mais acertividade do usuário.
  - Erro: Apresentar muitas informações simultaneas ao usuário, tornando a atenção dispersa e não sendo possivel a utilização correta do sistema.

9: Help users recognize, diagnose, and recover from errors
  - Acerto: Apresentar informações simples e itens de familiaridade nas mensagens do sistema, tornando-o mais simples a compreensão do usuário.
  - Erro: Apresentar mensagens ou informações técnicas ou mesmo sem solução para o usúario, tornadno assim impossível a solução do problema.

10: Help and documentation
  - Acerto: Apresentar ao usuário uma sequência ou manual que o próprio usuário possa realizar a operação de ajuste do erro.
  - Erro: Mesmo que apresente a documentação necessária, ela possua uma linguagem extremamente técnica que seja impossível a compreensão do erro apresentado.


## AULA 21/08/23
### ATIVIDADE 4 - Diagrama de Caso de Uso (UML) de um sistema simples (Requisitos funcionais).
![Sistema Comparador de Notebooks_Diagrama Caso de Usos](https://github.com/viniciusmangaba/Bertoti/assets/127343200/4c4e3d02-31f8-445f-9e13-df794c63fdbb)

## AULA 25/08/23
### Diagrama de Clases UML + JAVA

Integer = Classe
int = tipo primitivo

Mesma coisa acontece com o double e Double, no primeiro caso é somente um número, exemplo 0,2. Já no Double contém diversos métodos, como métodos de aproximação, métodos de calculo (ex: Latitude e Longitude, com médtodos de aproximação) 

(-) É private, só a classe acessa - Por regra todos os atributos são privados.
(+) É do tipo PUBLIC, pode ser acessado por classes, etc.

1.  Nome da Classe (SUBSTANTIVO com as primeiras letras maiusculas. No caso Sala de Aula).
2.  Atributos (O que a classe conhece - SUBSTANTIVO com a primeira letra minuscula. No caso listaChama).
3.  Método (O que a classe faz - VERBO) - No exemplo, passar o nome, que é uma String com o nome 

| Sala de Aula| NOME DA CLASSE|
|-------------------------| ------------------------|
| - listaChamada: List<Aluno>| ATRIBUTOS | 
| + buscarAlunoNome(String nome):List<Aluno> | MÉTODO | 
|+ buscarAlunoRA(int RA):Aluno| MÉTODO |

List = Classe / Aluno = Objeto

|Aluno | NOME DA CLASSE |
|----------| -----------|
| - nome: String           | ATRIBUTO |

    public List<Aluno> buscarAlunoNome(String nome) {
           List<Aluno> encontrador = new LinkedList<Aluno>();
           for (Aluno aluno: listaChamada){
               if (aluno.getNome().equals(nome))encontrados.add(aluno);
           }
           return encontrados;

#### equals = Utiliza-se esse método pois o nome é uma String, e consequentemente é uma Classe.
  
## AULA 28/08/23
### ATIVIDADE 5 - Inicie seu diagrama de classes UML fazendo-o JUNTO com o JAVA.

- Exemplo mostrado em sala de aula - Biblioteca

![Diagrama de Classes](https://github.com/viniciusmangaba/Bertoti/assets/127343200/fffeffed-e41f-494c-adb8-0296f761993e)

    public class Biblioteca {
        private List<Livro> livros = new LinkedList<Livros>();
        private List<Usuario> usuario = new LinkedList<Usuario>();

        public void addLivro (Livro livro){
         livros add(livro);
        }

        public void addUsuario(Usuario usuario){
          usuarios.add(usuario);
        }

        public List<Livro> buscaLivroNome(String nome){
          List<livro>encontrados = new LinkedList<Livro>();
          for (Livro livro livro){
            if (livro.getNome().equals(nome)).encontraos.add(livro);
            }
            return encontrados;
        }
    }

## AULA 01/09/23
### ATIVIDADE 6 - Atividade prosposta pelo professor - Diagrama de Classes UML - Caso escolhido: Consultório Médico.
- 1ª VERSÃO:

![Diagrama de Classes UML_Consultório Médico_2BD_2023 drawio](https://github.com/viniciusmangaba/Bertoti/assets/127343200/4f9b8306-7ac4-41a9-b545-ab05b21e16d2)

- 2ª VERSÃO:

![Diagrama de Classes UML_Consultório Médico_2BD_2023 drawio (1)](https://github.com/viniciusmangaba/Bertoti/assets/127343200/796bb2b1-0c25-48bf-bfb4-300490e301a3)

- 3ª VERSÃO:

![Diagrama de Classes UML_Consultório Médico_2BD_2023 drawio (2)](https://github.com/viniciusmangaba/Bertoti/assets/127343200/ab09d47e-9ab1-409f-9565-46d07bd733aa)
