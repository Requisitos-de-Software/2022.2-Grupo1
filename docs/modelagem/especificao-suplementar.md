# Especificação Suplementar

## 1. Introdução

<p align="justify">O objetivo da Especificação Suplementar é capturar os requisitos do sistema que não são facilmente definidos pela modelagem de casos de uso. De modo que a Especificação Suplementar em conjunto com a modelagem de <a href="https://requisitos-de-software.github.io/2022.2-Grasshopper/modelagem/casos-de-uso/">Casos de Uso</a> define todos os requisitos do sistema.</p>

<p align="justify">Esta Especificação Suplementar se aplica ao aplicativo GrassHoper disponibilizado na Play Store. Ademais, especificação cobre todos os requisitos não funcionais do sistema, como os requisitos de usabilidade, confiabilidade, desempenho e suportabilidade.</p>

## 2. Metodologia

<p align="justify">A descrição dos requisitos foi construída em cima do modelo FURPS+, que diz respeito a um sistema para a classificação de requisitos. (QualidadeBR, 2008)</p>

<p align="justify">Seu acrônimo representa categorias que podem ser usadas na definição de requisitos.</p>

- **F** - _Functionality_ (Funcionalidade): representa todo o aspecto funcional do software, ou seja, seus requisitos (nesse caso já explicitados nos [casos de uso](/casos-de-uso.md)).

- **U** - _Usability_ (Usabilidade): é o atributo que avalia a interface com o usuário, em conformidade com os principíos de usabilidade propostos por Nielsen (PREECE; ROGERS; SHARP; 2005, p. 48-49); "O quão fácil é para o usuário realizar suas demandas via o software?".

- **R** - _Reliability_ (Confiabilidade): refere-se a integridade, conformidade e interoperabilidade do software. Requisitos a serem considerados nessa categoria podem ser do tipo: frequência e gravidade de falha, tempo médio entre falhas, possibilidade de recuperação, etc.

- **P** - _Performance_ (Desempenho): avalia os requisitos de desempenho do software, podendo usar como medida diversos aspectos, entre eles: tempo de resposta, consumo de memória, disponibilidade da aplicação, entre outros.

- **S** - _Supportability_ (Suportabilidade) – os requisitos de suportabilidade agrupam várias características, como: testabilidade, adaptabilidade, manutenibilidade, compatibilidade, escalabilidade, localizabilidade, entre outros.

- **"+"**: este símbolo do acrônimo engloba outros requisitos não-funcionais que devem ser lembrados, como por exemplo:
  - Requisitos de design: muitas vezes chamado de restrição de design; um exemplo: uso de ferramentas de desenvolvimento.
  - Requisitos de implementação: um requisito de implementação especifica ou restringe o código ou a construção de um sistema; ex: padrões obrigatórios ou linguagens de implementação.
  - Requisitos de interface: especifica ou restringe as funcionalidades inerentes a interface do sistema com usuário.
  - Requisitos físicos: especifica uma limitação física pelo hardware utilizado, por exemplo: material, forma, tamanho ou peso.

## 3. Especificação Suplementar

### 3.1 Funcionalidades

<p align="justify"> - Os requisitos funcionais estão definidos através dos Casos de Uso. É possível encontrá-los [AQUI](casos-de-uso.md)</p>

### 3.2 Usabilidade

<span id="usabilidade"></span>

#### Facilidade de uso

<p align="justify">- As operações feitas no sistema são basicamentes simples para os usuários.
- A aplicação deve ser intuitiva e de fácil compreensão e memorização ao ponto de que os usuários não precisem de treinamento para fazer uso do sistema.
- O usuário do GrassHopper é capaz de utilizá-lo através de ações simples, o que torna quase desnecessário o usuário ter um treinamento prévio para a realização da maioria das ações disponíveis.</p>

#### Mensagens de Erro

<p align="justify"> - Caso houver algum erro na operação, o sistema deverá apresentar mensagem informando o problema.</p>

#### Garantia de Disponibilidade

<p align="justify"> - O sistema deve funcionar 24 horas por dia e 7 dias na semana, quando existir o acesso à internet.
Garantia de Segurança do Armazenamento de Dados</p>

### 3.3 Confiabilidade

<span id="confiabilidade"></span>

#### Garantia de segurança mínima no armazenamento de dados:

<p align="justify"> - O GrassHopper segue critérios mínimos para a segurança do armazenamento de dados dos seus usuários.(OBS35)</p>

#### Garantia de atualização de informações pessoais:

<p align="justify"> - O usuário do GrassHopper dever poder alterar os seus dados pessoais caso desejar.</p>

#### Garantia de Disponibilidade

<p align="justify">- O sistema deve funcionar 24 horas por dia e 7 dias na semana, quando existir o acesso à internet.
Garantia de Segurança do Armazenamento de Dados
- A manutenção do sistema deve ocorrer de forma constante, geralmente 1 vez por mês, para fornecer atualizações, correções de bugs, melhorias de usabilidade e novas funcionalidade</p>

#### Proteção de Dados

<p align="justify">- Por lidar com dados sensíveis do usuário, como nome, endereço e cpf, o Correios possui sua política de privacidade própria a fim de explicitar ao usuário como seus dados serão armazenados, tratados e utilizados.(OBS35)
- O aplicativo tem que seguir a Lei Geral de Proteção de Dados (LGPD).(OBS35)</p>

### 3.4 Desempenho

<span id="desempenho"></span>

<p align="justify">- Portanto, durante o desenvolvimento do projeto as necessidades de desempenho devem ser levadas em conta pois o tempo de resposta do sistema deverá ser o mínimo possível.
- Consumo de memória
- É necessário que a aplicação tenha um consumo de memória razóavel para evitar gargalos em dispositivos cujo o sistema operacional não seja atual.
- A aplicação tem que ter um tamanho e um desempenho compativo com dispositivos mais fracos, visto que o GrassHopper é um ferramenta pra estudar programção e deve engloba jovens de diferentes classes sociais.</p>

### 3.5 Suportabilidade

<span id="suportabilidade"></span>

<p align="justify">- O usuário será capaz de utilizar o sistema através do seu smartphone por meio de um aplicativo.
- Não será necessário que nenhum outro software personalizado resida no smartphone além do aplicativo do GrassHopper
- O aplicativo tem compatibilidade com o sistema operacional Android suportando a partir da versão do Android 4.4.</p>

### 3.6 Design

<span id="design"></span>

<p align="justify">- O aplicativo deve seguir uma paleta de cores fixa.(OBS31)
- Os ícones utilizados no aplicativo devem ser coerentes com a funcionalidade que eles representam.(OBS31,OBS33)
- O design do sistema deverá estar de acordo com as normas e boas práticas de desenvolvimento para cada uma das plataformas mobile desejadas, atentando para suas particularidades, ao mesmo tempo em que mantendo a uniformidade das funcionalidades do sistema.
- O design da aplicação deverá estar de acordo com as diretrizes de desenvolvimento do sistema operacional que está sendo desenvolvido. E, a aplicação deve ter detalhes verdes por conta da logo do aplicativo.(OBS31)</p>

### 3.7 Implementação

<p align="justify">- O aplicativo não deve usar mais de 150 MegaBytes de memória interna.</p>

### 3.8 Interface

<span id="interface"></span>

<p align="justify">- A interface dos diferentes componentes devem sequir o mesmo padrão para não confundir o usuário.

- O sistema deve possuir uma interface que exibe graficamente os componentes da aplicação permitindo o seu uso pelo usuário final.
  Interfaces de Hardware

- O sistema deve utilizar tecnologias de linguagens e frameworks pertencentes a um paradigma que favoreça a solução do problema visando eficiência no desenvolvimento e fácil manutenção.</p>

### Interfaces de Comunicação

<p align="justify">- A interface do aplicativo deve simplista e intuitiva para facilitar a utilização. Possuindo poucas opções de interação com o sistema, o usuário pode navegar por todo o sistema em pouco tempo.
- Deve possuir mais opções de idiomas, Português, Espanhol e Inglês(OBS26)</p>

### 3.9 Físico

<span id="fisico"></span>

<p align="justify">- O dispositivo Android deve estar em uma versão 4.4 ou superior.(OBS32)
- Os dispositivos deverão ter acesso a internet para acessar o aplicativo.(OBS32)</p>

## Referências bibliográficas

> Barbosa, S. D. J.; Silva, B. S. da; Silveira, M. S.; Gasparini, I.; Darin, T.; Barbosa, G. D. J. (2021) Interação Humano-Computador e Experiência do usuário. Autopublicação.

## Histórico de versão

| Versão |    Data    |      Descrição       | Autor |     Revisor      |
| :----: | :--------: | :------------------: | :---: | :--------------: |
|  1.0   | 09/12/2022 | Criação do documento | Caio  | Wildemberg Sales |
