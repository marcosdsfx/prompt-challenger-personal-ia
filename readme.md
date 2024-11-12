<p align="center">
    <img width="300px" src=".github/assets/logo_2.png">
</p>

<p align="center">
<a href="https://dio.me/"><img src="https://img.shields.io/badge/DIO-Project-FED564?logo=youtube" alt="DIO - Project"></a>
<a href="https://www.gnu.org/software/bash/" title="Go to Bash homepage"><img src="https://img.shields.io/badge/Prompt-Project-FED564?logo=gnu-bash&amp;logoColor=white" alt="Made with Bash"></a>
<a href="https://aws.amazon.com/" title="Powered by AWS">
  <img src="https://img.shields.io/badge/Powered%20by-AWS-FED564?logo=icloud&logoColor=white" alt="Powered by AWS">
</a>
</p>

<p align="center">
  <h3 align="center">🏋️‍♂️ Assistente de Personal Trainer - Gerador de Treino Ideal</h3>
Este projeto é um desafio de Prompt Engineer, onde o objetivo é criar um prompt que ajuda a montar o treino ideal para cada combinação de fatores, como biotipo corporal, disponibilidade de tempo e tipo de exercícios preferidos. O assistente de personal trainer gerado por esse prompt será capaz de personalizar os treinos de acordo com as características e necessidades do usuário.
O projeto deve ser feito utilizando as boas práticas de prompt engineer.
</p>

## 📋 Índice

- [📋 Índice](#-índice)
- [📝 Introdução](#-introdução)
- [💪 Biotipos Corporais](#-biotipos-corporais)
- [📅 Dias Disponíveis para Treino](#-dias-disponíveis-para-treino)
- [🏋️ Tipos de Exercícios](#️-tipos-de-exercícios)
- [🛠️ Regras de negócio](#️-regras-de-negócio)
- [📖 Material de Apoio](#-material-de-apoio)
- [🎯 Prompt de Resposta Proposto](#-prompt-de-resposta-proposto)

---

## 📝 Introdução

Este projeto visa criar um assistente de personal trainer automatizado que ajuda a gerar treinos personalizados. O usuário fornecerá informações como o biotipo corporal, a quantidade de dias disponíveis para treinar na semana e o tipo de exercício preferido, e o assistente gerará um plano de treino ideal com base nessas informações.

---

## 💪 Biotipos Corporais

A primeira regra para personalizar o treino é determinar o biotipo corporal do usuário. Existem três biotipos principais:

<table>
  <tr>
    <th>Imagem</th>
    <th>Biotipo</th>
    <th>Descrição</th>
  </tr>
  <tr>
    <td style="text-align: center;">
      <img src=".github/assets/ectomorph.jpg" width="50%" height="50%">
    </td>
    <td><strong>Ectomorfo</strong></td>
    <td>Corpo mais magro, difícil ganhar peso e massa muscular.</td>
  </tr>
  <tr>
    <td style="text-align: center;">
      <img src=".github/assets/mesomorph.jpg" width="50%" height="50%">
    </td>
    <td><strong>Mesomorfo</strong></td>
    <td>Corpo naturalmente musculoso, facilidade para ganhar massa muscular e perder gordura.</td>
  </tr>
  <tr>
    <td style="text-align: center;">
      <img src=".github/assets/endmorph.jpg" width="50%" height="50%">
    </td>
    <td><strong>Endomorfo</strong></td>
    <td>Corpo com tendência a acumular gordura, maior dificuldade em perder peso.</td>
  </tr>
</table>

> **Nota:** Escolha o biotipo que mais se aproxima do seu corpo atual para que o treino seja mais eficiente.

---

## 📅 Dias Disponíveis para Treino

A segunda regra é determinar quantos dias por semana o usuário tem disponível para treinar. Dependendo do número de dias, o treino sugerido pode variar:

| **Imagem**                                                     | **Dias por Semana** | **Tipo de Treino Sugerido** |
| -------------------------------------------------------------- | ------------------- | --------------------------- |
| <img src=".github/assets/calendar.png" width="50" height="50"> | 1 dia               | Treino Full Body            |
| <img src=".github/assets/calendar.png" width="50" height="50"> | 3 dias              | Treino ABC                  |
| <img src=".github/assets/calendar.png" width="50" height="50"> | 5 dias              | Treino ABCDE                |

- **Full Body**: Treino que trabalha o corpo todo em uma única sessão.
- **ABC**: Divisão do treino em três dias, cada um focado em grupos musculares diferentes.
- **ABCDE**: Divisão do treino em cinco dias, com foco ainda mais específico em cada grupo muscular.

---

## 🏋️ Tipos de Exercícios

A terceira regra envolve a escolha do tipo de exercício preferido. Aqui estão algumas categorias com exemplos:

| **Imagem**                                                       | **Tipo de Treino** | **Descrição**                                                                                                 |
| ---------------------------------------------------------------- | ------------------ | ------------------------------------------------------------------------------------------------------------- |
| <img src=".github/assets/dumbells.png" width="50%" height="50%"> | **Funcional**      | Exercícios que melhoram a funcionalidade do corpo, usando movimentos naturais.                                |
| <img src=".github/assets/4760665.png" width="50%" height="50%">  | **Maquinário**     | Exercícios feitos em máquinas, com foco em isolar grupos musculares.                                          |
| <img src=".github/assets/barr.png" width="50%" height="50%">     | **Peso Livre**     | Exercícios com pesos livres, como halteres e barras, para trabalhar vários grupos musculares simultaneamente. |
| <img src=".github/assets/cardio.png" width="50%" height="50%">   | **Cardio**         | Exercícios voltados para melhorar a resistência cardiovascular, como corrida ou ciclismo.                     |
| <img src=".github/assets/hiit.png" width="50%" height="50%">     | **HIIT**           | Treinos intervalados de alta intensidade, ótimos para queima de gordura.                                      |

---

## 🛠️ Regras de negócio

1. **Identifique seu biotipo corporal** consultando a seção de biotipos.
2. **Determine quantos dias por semana você pode treinar** e escolha o tipo de treino mais adequado.
3. **Selecione o tipo de exercício** que prefere realizar e que se encaixa melhor nos seus objetivos.
4. Use o prompt do assistente para gerar um plano de treino personalizado.

---

## 📖 Material de Apoio

Aqui estão alguns recursos adicionais que podem ser úteis para entender melhor o projeto e as práticas de prompt engineering:

- [Fundamentos de Engenharia de prompt](https://elidianaandrade.gitbook.io/fundamentos-de-engenharia-de-prompts-com-claude-3)
- [Boas práticas de prompt](https://aline-antunes.gitbook.io/otimize-seus-prompts-e-aprenda-mais-usando-ias-1)

---

## 🎯 Prompt de Resposta Proposto

# Você é um personal trainer e precisa criar um plano de treino ideal baseado em algumas informações que vou lhe passar, como: 

***Biotipos Corporais:***

A primeira regra para personalizar o treino é determinar o biotipo corporal do usuário. Existem três biotipos principais:

1 - Ectomorfo:	Corpo mais magro, difícil ganhar peso e massa muscular.

2 - Mesomorfo:	Corpo naturalmente musculoso, facilidade para ganhar massa muscular e perder gordura.

3 - Endomorfo:	Corpo com tendência a acumular gordura, maior dificuldade em perder peso.


***Idade:***

1 - Adolescente: 15-19 anos — Diferencia os mais jovens, que geralmente têm mais flexibilidade e metabolismo acelerado, de quem já está em fase adulta inicial.

2 - Jovem Adulto: 20-35 anos — Fase em que muitos começam a focar no desempenho, com maior capacidade de recuperação e ganho de massa muscular.

3 - Adulto: 36-50 anos — Aqui, o treino pode focar tanto no condicionamento físico como em prevenir o declínio natural da força e flexibilidade.

4 - Maturidade: 51-65 anos — Para quem já pode ter algumas limitações ou preocupações com saúde, mas ainda mantém um bom nível de atividade.

5 - Melhor Idade: 66+


***Nível de condicionamento atual:***

1 - Iniciante: Para quem está começando ou retornando após um longo período sem atividade. Geralmente, esse nível inclui pessoas que não têm uma base muscular forte ou condicionamento cardiovascular.

2 - Intermediário: Para quem já pratica exercícios regularmente há pelo menos 6-12 meses, tem uma base de força e resistência, mas ainda está desenvolvendo técnica e consistência.

3 - Avançado: Para pessoas que treinam há mais de 1-2 anos de forma consistente, têm boa técnica, força e condicionamento cardiovascular, e conseguem lidar com rotinas mais intensas e específicas.

4 - Atleta: Para quem treina com alta intensidade e especificidade, como atletas amadores ou profissionais. Esse nível exige um planejamento detalhado, com foco em performance e aprimoramento contínuo.

5 - Condicionamento Funcional (opcional): Essa é uma categoria alternativa para pessoas que podem ter alguma limitação física ou necessidade específica, como reabilitação. Os treinos são adaptados para melhorar a funcionalidade e qualidade de vida.


***Objetivos específicos:***

1 - ganho de massa muscular

2 - perda de peso

3 - condicionamento cardiovascular


***Quantos dias por semana você planeja treinar:***

1 Dia - Treino Full Body

3 Dias - Treino ABC

5 Dias - Treino ABCDE

***Full Body:*** Treino que trabalha o corpo todo em uma única sessão.

***ABC:*** Divisão do treino em três dias, cada um focado em grupos musculares diferentes.

***ABCDE:*** Divisão do treino em cinco dias, com foco ainda mais específico em cada grupo muscular.


***Exercícios Preferidos:*** 

1 - Funcional:	Exercícios que melhoram a funcionalidade do corpo, usando movimentos naturais.

2 - Maquinário	Exercícios feitos em máquinas, com foco em isolar grupos musculares.

3 - Peso Livre	Exercícios com pesos livres, como halteres e barras, para trabalhar vários grupos musculares simultaneamente.

4 - Cardio	Exercícios voltados para melhorar a resistência cardiovascular, como corrida ou ciclismo.

5 - HIIT	Treinos intervalados de alta intensidade, ótimos para queima de gordura.



# Crie um formulário para que eu possa preencher esses dados, e após eu te entregar esse formulario, você criará um treino personalizado baseado em todas essas variáveis.

***Aqui está um formulário estruturado com todas as variáveis que você descreveu. Com ele, poderei montar um plano de treino totalmente personalizado para atender às suas necessidades!***

***Formulário de Planejamento de Treino Personalizado***

1. Biotipo Corporal
   
Escolha seu biotipo corporal:

 Ectomorfo: Corpo mais magro, difícil ganhar peso e massa muscular.
 Mesomorfo: Corpo naturalmente musculoso, facilidade para ganhar massa muscular e perder gordura.
 Endomorfo: Corpo com tendência a acumular gordura, maior dificuldade em perder peso.


2. Idade
   
Selecione sua faixa etária:

 Adolescente: 15-19 anos
 
 Jovem Adulto: 20-35 anos
 
 Adulto: 36-50 anos
 
 Maturidade: 51-65 anos
 
 Melhor Idade: 66+ anos


3. Nível de Condicionamento Atual
Qual é o seu nível de condicionamento físico atual?

 Iniciante: Está começando ou retornando após um longo período sem atividade.
 
 Intermediário: Pratica exercícios regularmente há pelo menos 6-12 meses, mas ainda desenvolve técnica e consistência.
 
 Avançado: Treina consistentemente há mais de 1-2 anos, com boa técnica e força.
 
 Atleta: Treina com alta intensidade e especificidade (atleta amador ou profissional).
 
 Condicionamento Funcional: Possui alguma limitação física ou necessidade específica.


4. Objetivo Específico
Qual é o seu principal objetivo?

 Ganho de massa muscular
 
 Perda de peso
 
 Condicionamento cardiovascular

5. Frequência Semanal de Treino
Quantos dias por semana você planeja treinar?

 1 Dia - Treino Full Body
 
 3 Dias - Treino ABC
 
 5 Dias - Treino ABCDE
 

6. Exercícios Preferidos
Escolha os tipos de exercício que prefere (pode selecionar mais de um):

 Funcional: Exercícios que melhoram a funcionalidade do corpo, usando movimentos naturais.
 
 Maquinário: Exercícios feitos em máquinas, focados em isolar grupos musculares.
 
 Peso Livre: Exercícios com pesos livres, como halteres e barras.
 
 Cardio: Exercícios voltados para resistência cardiovascular (corrida, ciclismo, etc.).
 
 HIIT: Treinos intervalados de alta intensidade, ótimos para queima de gordura.
 

***Preencha o formulário com suas preferências e informações, e então montarei um plano de treino personalizado para você com base nessas variáveis!***

# Aqui está meu formulário preenchido: Formulário de Planejamento de Treino Personalizado:

1. Biotipo Corporal
Escolha seu biotipo corporal:

 Ectomorfo: Corpo mais magro, difícil ganhar peso e massa muscular.
 
2. Idade
Selecione sua faixa etária:

 Adulto: 36-50 anos
 
3. Nível de Condicionamento Atual
Qual é o seu nível de condicionamento físico atual?

 Intermediário: Pratica exercícios regularmente há pelo menos 6-12 meses, mas ainda desenvolve técnica e consistência.
 
4. Objetivo Específico
Qual é o seu principal objetivo?

 Ganho de massa muscular e Condicionamento cardiovascular
 
5. Frequência Semanal de Treino
Quantos dias por semana você planeja treinar?

 3 Dias - Treino ABC

6. Exercícios Preferidos
Escolha os tipos de exercício que prefere (pode selecionar mais de um):

 Funcional: Exercícios que melhoram a funcionalidade do corpo, usando movimentos naturais.
 
 Cardio: Exercícios voltados para resistência cardiovascular (corrida, ciclismo, etc.).

# Com base nas informações que você forneceu, aqui está um plano de treino personalizado para o seu perfil:

Plano de Treino Personalizado
Biotipo: Ectomorfo (Corpo magro, dificuldade em ganhar peso e massa muscular)

Idade: Adulto (36-50 anos)

Nível de Condicionamento Atual: Intermediário (Pratica exercícios regularmente há pelo menos 6-12 meses)

Objetivo Principal: Ganho de massa muscular e Condicionamento cardiovascular

Frequência de Treino: 3 Dias por semana (Treino ABC)

Exercícios Preferidos: Funcional e Cardio

Divisão de Treino ABC:
Dia A: Peito, Tríceps e Cardio

Aquecimento: 5-10 minutos de cardio leve (corrida ou ciclismo)
Supino reto com barra – 4 séries de 8-10 repetições
Supino inclinado com halteres – 4 séries de 8-10 repetições
Mergulho entre bancos (para tríceps) – 3 séries de 10-12 repetições
Tríceps na polia alta (cabo) – 3 séries de 12-15 repetições
Flexão de braço (com variação) – 3 séries até a falha
Cardio (HIIT ou corrida intervalada) – 20 minutos (1 minuto de alta intensidade, 1 minuto de descanso)
Dia B: Costas, Bíceps e Funcional

Aquecimento: 5-10 minutos de cardio leve
Puxada frente na polia alta – 4 séries de 8-10 repetições
Remada curvada com barra – 4 séries de 8-10 repetições
Remada unilateral com haltere – 3 séries de 10 repetições (cada braço)
Rosca direta com barra – 4 séries de 10-12 repetições
Rosca alternada com halteres – 3 séries de 12 repetições
Exercício funcional (exemplo: Kettlebell swing ou burpees) – 3 séries de 12-15 repetições
Cardio (ciclismo ou caminhada rápida) – 20 minutos
Dia C: Pernas, Ombros e Cardio

Aquecimento: 5-10 minutos de cardio leve
Agachamento com barra – 4 séries de 8-10 repetições
Leg press – 4 séries de 10-12 repetições
Afundo (com halteres) – 3 séries de 10 repetições por perna
Desenvolvimento com halteres – 4 séries de 8-10 repetições
Elevação lateral de ombro com halteres – 3 séries de 12 repetições
Cardio (HIIT ou corrida intervalada) – 20 minutos (1 minuto de alta intensidade, 1 minuto de descanso)
Dicas e Observações:
Progressão de Carga: Como o objetivo é ganho de massa muscular, procure aumentar a carga progressivamente sempre que se sentir confortável com a execução de 10-12 repetições.
Recuperação: Em cada treino, tente descansar entre 60 a 90 segundos entre as séries para maximizar o ganho muscular.
Exercícios Funcionais: Como você prefere, inclua exercícios funcionais que ajudem no desenvolvimento de força, equilíbrio e coordenação. Faça-os principalmente no início do treino, quando está mais descansado.
Cardio: O cardio será inserido após o treino de musculação, com foco no condicionamento cardiovascular. Como você possui um biotipo ectomorfo, o cardio será moderado para não afetar o ganho muscular.
Esse plano mistura treino de musculação com exercícios funcionais e cardio para garantir que você esteja promovendo tanto o ganho de massa muscular quanto o aprimoramento do condicionamento cardiovascular.

# FIM
