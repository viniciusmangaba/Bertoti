# ENGENHARIA DE SOFTWARE
### FATEC SÃO JOSÉ DOS CAMPOS - JESSEN VIDAL 
Repositório criado e destinado para as atividades realizadas em sala de aula, sob orientação do professor Giuliano Araujo Bertoti, na disciplina de Engenharia de Software em Banco de Dados - 2º Semestre/2023.

## ATIVIDADE 1 - Comentários do livro "Software Engineering at Google"
### TEXTO 1:
We see three critical differences between programming and software engineering: time, scale, and the trade-offs at play. On a software engineering project, engineers need to be more concerned with the passage of time and the eventual need for change. In a software engineering organization, we need to be more concerned about scale and efficiency, both for the software we produce as well as for the organization that is producing it. Finally, as software engineers, we are asked to make more complex decisions with higher-stakes outcomes, often based on imprecise estimates of time and growth.

#### COMENTÁRIOS:
Existem três tipos de diferenças criticas na programação: Tempo, escala e Trade-offs.  No contexto de projetos de engenharia de software, é necessário considerar mais a passagem do tempo e a necessidade futura de mudanças. Em organizações de engenharia de software, a preocupação deve ser maior em relação à escala e eficiência, tanto para o software produzido quanto para a própria organização.

## TEXTO 2:
Within Google, we sometimes say, “Software engineering is programming integrated over time.” Programming is certainly a significant part of software engineering: after all, programming is how you generate new software in the first place. If you accept this distinction, it also becomes clear that we might need to delineate between programming tasks (development) and software engineering tasks (development, modification, maintenance). The addition of time adds an important new dimension to programming. Cubes aren’t squares, distance isn’t velocity. Software engineering isn’t programming.

#### COMENTÁRIOS:
No texto acima é comentado que programação é uma parte significante da Engenharia de Software, porém é evidenciado que somente a programção não é Engenharia de Software, assim como cubos não são quadrados e distâncias não é velocidade em si. 

## ATIVIDADE 2 - TRADE-OFFS
#### 3 EXEMPLOS DE TRADE-OFFS:
#### 1 - Desempenho x Custo: Servidores de Alta Performance

Desempenho: Esses servidores são poderosos, com capacidade de processamento e armazenamento significativamente altos. Eles podem lidar com cargas de trabalho intensivas e executar aplicativos complexos de maneira eficiente.

Custo: No entanto, esses servidores de alto desempenho geralmente vêm com um custo mais elevado, tanto em termos de aquisição quanto de operação. Eles consomem mais energia e podem exigir investimentos significativos.

#### 2 - Complexidade do Software x Simplicidade do código: 
Quanto mais complexo do software maior será o detalhamento do software, que implicará no número de linhas digitadas, bem como no "tamanho" do arquivo.
  
Software Complexo: Um exemplo de software com código complexo é o sistema operacional "Linux". O Linux é um sistema operacional de código aberto que é conhecido por sua eficiência, desempenho e escalabilidade. Sua complexidade reside na gestão de recursos, suporte a uma ampla variedade de dispositivos, e na implementação de diversos recursos avançados.

Software com simplicidade no código: Um exemplo de software com código simplificado é o "SQLite". O SQLite é um sistema de gerenciamento de banco de dados relacional leve, rápido e de código aberto. Ele é projetado para ser compacto e fácil de incorporar em aplicativos, sem a necessidade de uma instância de servidor separada.

#### 3 - Software mais seguro e completo x Software com maior portabilidade

Java x Python : Software mais completo e com maior segurança e portabilidade quando comparado ao Python, que por sua vez é mais leve, e mais fácil de implementar quando não se há familiariade. 

#### REQUISITOS NÃO FUNCIONAIS:
Um exemplo de comparação de requisitos não funcionais é a usabilidade do google como site de buscas rápidas quando comparadas a outros sites como bing, yahoo, entre outros, sendo a google uma aplicação direta, que não possue propagandas desnecessárias e de baixissimo tempo de resposta, além de possuir um enorme banco de dados de informações.

## ATIVIDADE 3 - Requisitos não funcionais de usabilidade - Avaliação de 10 Heurísticas
### 1 ACERTO E 1 ERRO DE CADA HEURÍSTICA: "10 Usability Heuristics for User Interface Design".

1: Visibility of system status
  - Acerto: Familiaridade do usuário com o sistema, através das interações previsiveis do sistema, tornando-o mais simples na sua utilização.
    
    ![image](https://github.com/viniciusmangaba/Bertoti/assets/127343200/0907509f-3f06-47fb-b14b-45d35e65fbdb)

  - Erro: Itens ou falta de indicação ao usuário em qual processo ou etapa que ele se encontra.

    ![image](https://github.com/viniciusmangaba/Bertoti/assets/127343200/f8a6d88b-c87b-47a0-a9ac-86c995ea1d61)

2: Match between system and the real world
  - Acerto: Semelhanças de itens do sistema com o mundo real, por exemplo metáforas trazendo maior simplicidade e familiaridade do usuário.

    ![image](https://github.com/viniciusmangaba/Bertoti/assets/127343200/c584a06b-870e-4c05-a77b-24746e000d04)

  - Erro: Pagina não encontrada, ERROR 404.

    ![image](https://github.com/viniciusmangaba/Bertoti/assets/127343200/6468ec39-34a7-4992-a8ea-16ea681f7910)


3: User control and freedom
  - Acerto: O usuário possue total liberdade para navegar e controlar o sistema, colocando as modificações que mais lhe agradam, seja no aspecto visual ou funcional do sistema.

    ![image](https://github.com/viniciusmangaba/Bertoti/assets/127343200/a7a7bd32-938e-4842-8a29-4cdfb0b24c28)

  - Erro: Quando o sistema oferece muitas opções de modificação ou de operação pode acontecer do sistema ficar sobrecarregado e uma vez que não possua um código/ servidor apurado, pode vir a ter travamentos ou lentidôes.

    ![image](https://github.com/viniciusmangaba/Bertoti/assets/127343200/6cca2e03-baa0-4172-a923-724b14b1615c)

4: Consistency and standards
  - Acerto: Apresentar funções padrões que intuitivamente indicam ao usuário o caminho a ser seguido - ex: logout.

    ![image](https://github.com/viniciusmangaba/Bertoti/assets/127343200/f4fb3ee1-c317-43e6-9543-efc0af390b5b)

  - Erro: Apresentar itens, palavras ou expressões que possuam causar dualidade de entendimento ao usuário.

    ![image](https://github.com/viniciusmangaba/Bertoti/assets/127343200/7070dbe5-6b7f-4331-b0e6-116336dbb6b7)

5: Error prevention
  - Acerto: Formatação de informações e dados de entrada para o tratamento facilitado do sistema, prevenindo que o usuário faça erros desnecessários. (No exemplo o sistema insire os caracteres separadores automaticamente).
    ![image](https://github.com/viniciusmangaba/Bertoti/assets/127343200/75bb6dcb-7fe3-403d-ad47-773adbad9a0c)

  - Erro: Permissão que o usuário insira caracteres no sistema que não são reconhecidas pelo sistema, sendo que poderia ser resolvida na criação do código.

    ![image](https://github.com/viniciusmangaba/Bertoti/assets/127343200/e69e6a8e-0db6-4c42-b39b-b7e8677a5e1c)

6: Recognition rather than recall
 - Acerto: Pré definição de itens e opções que facilitam a utilização do sistema, por exemplo o calendário na seleção do dia

  ![image](https://github.com/viniciusmangaba/Bertoti/assets/127343200/5576234c-09a1-484c-ad8a-4c1f0f85e527)

 - Erro: Fazer com que o usúario lembre de dados ou informações que poderiam ser pré definidas pelo sistema. Aqui o CEP poderia ser inserido antes do endereço, e o sistema poderia fazer uma busca automática.
   
  ![image](https://github.com/viniciusmangaba/Bertoti/assets/127343200/95afa45d-6cac-4eaf-a805-e62f304b9843)

7: Flexibility and efficiency of use
  - Acerto: Inserção de atalhos que facilitam a vida de usuários mais experientes, mas que seja "ocultos" à usuários novatos, tornando assim o método mais eficiente para ambos.
    
  ![image](https://github.com/viniciusmangaba/Bertoti/assets/127343200/f246620f-8b5f-4c42-b5d3-a76f9b3edcb9)

  - Erro: Não mostrar os atalhados e modificações para os novos usúarios, o que poderia facilitar a interação com o sistema. O sistema poderia ter um opção de mostrar uma tela de acima.

8: Aesthetic and minimalist design
  - Acerto: Apresentar apenas informações necessárias, com menos informações terá mais acertividade do usuário.

  ![image](https://github.com/viniciusmangaba/Bertoti/assets/127343200/15a4729f-0ece-4ab0-bba2-f6ea111594e7)

  - Erro: Apresentar muitas informações simultaneas ao usuário, tornando a atenção dispersa e não sendo possivel a utilização correta do sistema.

  ![image](https://github.com/viniciusmangaba/Bertoti/assets/127343200/f6364d64-3932-45bc-83dc-812373ed54c6)

9: Help users recognize, diagnose, and recover from errors
  - Acerto: Apresentar informações simples e itens de familiaridade nas mensagens do sistema, tornando-o mais simples a compreensão do usuário.

  ![image](https://github.com/viniciusmangaba/Bertoti/assets/127343200/548d4c61-8d5d-4bfd-b0d0-7fb5523fcdab)

  - Erro: Apresentar mensagens ou informações técnicas ou mesmo sem solução para o usúario, tornando assim impossível a solução do problema.
    
![image](https://github.com/viniciusmangaba/Bertoti/assets/127343200/fdf10e4a-83f2-4ff5-a0d0-c9ed01275773)

10: Help and documentation
  - Acerto: Apresentar ao usuário uma sequência ou manual que o próprio usuário possa realizar a operação de ajuste do erro.
    
    ![image](https://github.com/viniciusmangaba/Bertoti/assets/127343200/c68bdf1b-b2f0-48da-8751-d5f6f022aa2f)

  - Erro: Mesmo que apresente a documentação necessária, ela possua uma linguagem extremamente técnica que seja impossível a compreensão do erro apresentado.

    ![image](https://github.com/viniciusmangaba/Bertoti/assets/127343200/95bf9ab4-2eed-4eb3-807f-de7d6f006a44)

## ATIVIDADE 4 - Diagrama de Caso de Uso (UML) de um sistema simples (Requisitos funcionais).
![Sistema Comparador de Notebooks_Diagrama Caso de Usos](https://github.com/viniciusmangaba/Bertoti/assets/127343200/4c4e3d02-31f8-445f-9e13-df794c63fdbb)

## Diagrama de Clases UML + JAVA (NOTAS DE AULA)

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
  
## Inicie seu diagrama de classes UML fazendo-o JUNTO com o JAVA (NOTAS DE AULA)

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

## ATIVIDADE 5 - Diagrama de Classes UML - Caso escolhido: Consultório Médico.
- 1ª VERSÃO:

![Diagrama de Classes UML_Consultório Médico_2BD_2023 drawio](https://github.com/viniciusmangaba/Bertoti/assets/127343200/4f9b8306-7ac4-41a9-b545-ab05b21e16d2)

- 2ª VERSÃO:

![Diagrama de Classes UML_Consultório Médico_2BD_2023 drawio (1)](https://github.com/viniciusmangaba/Bertoti/assets/127343200/796bb2b1-0c25-48bf-bfb4-300490e301a3)

- 3ª VERSÃO:

![Diagrama de Classes UML_Consultório Médico_2BD_2023](https://github.com/viniciusmangaba/Bertoti/assets/127343200/bbd99a0d-aedd-45eb-bf67-c40fa0c70ed1)

## ATIVIDADE 6 - Implementação Diagrama de Classes UML em Código JAVA
CLASSE CONSULTORIOMEDICO
<details>
  
    package JUnity;
    import JUnity.Consulta;

    import java.util.LinkedList;
    import java.util.List;

    public class ConsultorioMedico {
        private List<Consulta> consultas = new LinkedList<Consulta>();

        public void agendarConsulta(Consulta consulta) {
            consultas.add(consulta);
        }
    
        public List<Consulta> consultarConsultasPorPaciente(String paciente) {
            List<Consulta> consultasEncontradas = new LinkedList<Consulta>();
            for (Consulta consulta : consultas) {
                if (consulta.getPaciente().getNome().equals(paciente)) {
                    consultasEncontradas.add(consulta);
                }
            }
            return consultasEncontradas;
        }
    
        public List<Consulta> consultarConsultasPorMedicoNome(String nome) {
            List<Consulta> consultasEncontradas = new LinkedList<Consulta>();
            for (Consulta consulta : consultas) {
                if (consulta.getMedico().getNome().equals(nome)) {
                    consultasEncontradas.add(consulta);
                }
            }
            return consultasEncontradas;
        }
    
        public List<Consulta> consultarConsultasPorMedicoEspecialidade(String especialidade) {
            List<Consulta> consultasEncontradas = new LinkedList<Consulta>();
            for (Consulta consulta : consultas) {
                if (consulta.getMedico().getEspecialidade().equals(especialidade)) {
                    consultasEncontradas.add(consulta);
                }
            }
            return consultasEncontradas;
        }
    
        public List<Consulta> getConsultas() {
            return consultas;
        }
    
    }
</details>
  
CLASSE MEDICO
<details> 
  
    package JUnity;
    public class Medico {
        private String nome;
        private String especialidade;
        private Integer id;
    
        public Medico(String nome, String especialidade, Integer id) {
            this.nome = nome;
            this.especialidade = especialidade;
            this.id = id;
        }
    
        public void setNome(String nome) {
            this.nome = nome;
        }
    
        public String getNome() {
            return nome;
        }
    
        public void setEspecialidade(String especialidade) {
            this.especialidade = especialidade;
        }
    
        public String getEspecialidade() {
            return especialidade;
        }
    
        public void setId(Integer id) {
            this.id = id;
        }
    
        public Integer getId() {
            return id;
        }
    }
</details>

CLASSE PACIENTE
<details> 
  
    package JUnity;
    public class Paciente {
        private String nome;
        private Integer idade;
        private Integer id;
    
        public Paciente(String nome, Integer idade, Integer id) {
            this.nome = nome;
            this.idade = idade;
            this.id = id;
        }
    
        public void setNome(String nome) {
            this.nome = nome;
        }
    
        public String getNome() {
            return nome;
        }
    
        public void setIdade(Integer idade) {
            this.idade = idade;
        }
    
        public Integer getIdade() {
            return idade;
        }
    
        public void setId(Integer id) {
            this.id = id;
        }
    
        public Integer getId() {
            return id;
        }
    }
</details>

CLASSE CONSULTA
<details> 

    package JUnity;
    public class Consulta {
        private String data;
        private Medico medico;
        private Paciente paciente;
    
        public Consulta(String data, Medico medico, Paciente paciente) {
            this.data = data;
            this.medico = medico;
            this.paciente = paciente;
        }
    
        public void setData(String data) {
            this.data = data;
        }
    
        public String getData() {
            return data;
        }
    
        public void setMedico(Medico medico) {
            this.medico = medico;
        }
    
        public Medico getMedico() {
            return medico;
        }
    
        public void setPaciente(Paciente paciente) {
            this.paciente = paciente;
        }
    
        public Paciente getPaciente() {
            return this.paciente;
        }
    
        public void adicionarPaciente(Paciente pac) {
        }
    }

</details>

## ATIVIDADE 7 - Testes automatizados com técnica de teste
TESTES
<details> 
  
    package JUnity;
    
    import org.junit.jupiter.api.Test;
    import java.util.List;
    import static org.junit.jupiter.api.Assertions.*;
    
    public class TestesConsultorioMedico {
    
        @Test
        public void testarConsultaValidaPorPaciente(){
            ConsultorioMedico cm = new ConsultorioMedico();
            Consulta consulta = new Consulta("15-11-2023", new Medico("Dr. José Roberto", "Pediatra", 1), new Paciente("Lara Prado", 10, 1));
            cm.agendarConsulta(consulta);
    
            List<Consulta> res = cm.consultarConsultasPorPaciente("Lara Prado");
            assertEquals(res.size(), 1);
            assertTrue(res.contains(consulta));
        }
    
        @Test
        public void testarConsultaInvalidaPorPaciente(){
            ConsultorioMedico cm = new ConsultorioMedico();
            Consulta consulta = new Consulta("15-11-2023", new Medico("Dr. José Roberto", "Pediatra", 1), new Paciente("Lara Prado", 10, 1));
            cm.agendarConsulta(consulta);
    
            List<Consulta> res = cm.consultarConsultasPorPaciente("Camila Prado");
            assertEquals(res.size(), 0);
            assertFalse(res.contains(consulta));
        }
    
        @Test
        public void testarConsultaValidaPorMedicoNome(){
            ConsultorioMedico cm = new ConsultorioMedico();
            Consulta consulta = new Consulta("15-11-2023", new Medico("Dr. José Roberto", "Pediatra", 1), new Paciente("Lara Prado", 10, 1));
            cm.agendarConsulta(consulta);
    
            List<Consulta> res = cm.consultarConsultasPorMedicoNome("Dr. José Roberto");
            assertEquals(res.size(), 1);
            assertTrue(res.contains(consulta));
        }
    
        @Test
        public void testarConsultaInvalidaPorPacienteNome(){
            ConsultorioMedico cm = new ConsultorioMedico();
            Consulta consulta = new Consulta("15-11-2023", new Medico("Dr. José Roberto", "Pediatra", 1), new Paciente("Lara Prado", 10, 1));
            cm.agendarConsulta(consulta);
    
            List<Consulta> res = cm.consultarConsultasPorMedicoNome("Dr. Sebastião Oliveira");
            assertEquals(res.size(), 0);
            assertFalse(res.contains(consulta));
        }
    
        @Test
        public void testarConsultaValidaPorEspecialidade(){
            ConsultorioMedico cm = new ConsultorioMedico();
            Consulta consulta = new Consulta("15-11-2023", new Medico("Dr. José Roberto", "Pediatra", 1), new Paciente("Lara Prado", 10, 1));
            cm.agendarConsulta(consulta);
    
            List<Consulta> res = cm.consultarConsultasPorMedicoEspecialidade("Pediatra");
            assertEquals(res.size(), 1);
            assertTrue(res.contains(consulta));
        }
    
        @Test
        public void testarConsultaInvalidaPorEspecialidade(){
            ConsultorioMedico cm = new ConsultorioMedico();
            Consulta consulta = new Consulta("15-11-2023", new Medico("Dr. José Roberto", "Pediatra", 1), new Paciente("Lara Prado", 10, 1));
            cm.agendarConsulta(consulta);
    
            List<Consulta> res = cm.consultarConsultasPorMedicoEspecialidade("Ortopedista");
            assertEquals(res.size(), 0);
            assertFalse(res.contains(consulta));
        }
    
    }

</details>

## Técnica Utilizada: Classe de Equivalência
![image](https://github.com/viniciusmangaba/Bertoti/assets/127343200/e534d6da-750e-463a-8351-3354c564c6ae)

    
