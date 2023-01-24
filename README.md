## Hackathon CDIA PUC
Estruturação do funcionamento do hackathon de CDIA da PUC

## O que é um Hackathon?

O Hackathon é um evento que reúne programadores, designers e outros profissionais ligados ao desenvolvimento de software para uma maratona de programação, cujo objetivo é desenvolver um software ou solução tecnológica que atenda a um fim específico.

## Como funciona o Hackathon de CDIA da PUC?

Iremos desenvolver um modelo de machine learning para predizer algum dado, no mesmo estilo de uma competição do Kaggle.

Poderemos ter que resolver um problema de regressão, classificação, etc. Qualquer problema que possamos treinar um modelo e usar um target como métrica de performance

## Diagrama Funcionamento Hackathon

A imagem a seguir mostra como é todo o processo do Hackathom, desde a preparação dos dados feita pelo professor, até a avaliação. Preste atenção na aba **Competidor**, que demonstra as etapas do processo que você precisará atuar.
<br>
<img src="img/Diagrama Hackathon.png" alt="Diagrama Dinâmica Hackathon" />

# Dinâmica do Hackathon

O hackathon é dividido em 3 etapas, vamos comentar cada uma delas e seus recpectivos responsáveis.

#### Prepação (Professor)

O professor vai escolher um dataset mãe para ser tema do nosso hackathon. Ele pode fazer isso de acordo com o conteúdo das aulas que ele estiver ministrando. Pode escolher um dataset para reforçar nos alunos um objetivo de aprendizagem específico

A partir desse dataset o professor vai enviar dois datasets para os alunos, que daremos mais detalhes a seguir

#### Submissão (Aluno)

Os participantes receberão dois datasets, com os seguintes nomes:
- *train_set.csv*: dataset que os alunos deverão usar para treinar seus modelos
- *test_set.csv*: dataset que os alunos usarão para gerar sua submissão (resultado do .predict do modelo treinado)

#### Avaliação (Professor)

Esgotado o prazo final para o envio das submissões, o professor irá juntar todas as submissões e avaliá-las 

| submissao | score |
| -- | -- |
| submissao_fulado.csv | 0.964286 |
| submissao_sicrano.csv | 0.924759 |
| submissao_beltrano.csv | 0.898344 |

- um dataset mãe será dividido em treino e teste

O dataset treino com features e target será enviado aos alunos junto com o dataset de teste, mas esse somente com as features.

Os alunos treinaram o seus modelos no dataset de treino e usarão então seu modelo treinado para predizer os targets do dataset de teste.

Os alunos vão então submeter essa predição para o professor como um arquivo csv junto com o seu caderno.

O professor juntará então todas as submissões e avaliará a performance delas. Será divulgado um ranking final com os vencedores (as predições que melhor performaram). Ao final os cadernos serão compartilhados e os alunos e o professor terão a oportunidade de discutir quais abordagens derão mais certo ou não para a solução do problema.

- precisa avaliar problema de classificação e regressão

- gerar caderno exemplo de participação no hackathon

- alunos submetem atividade e professor ao final avalia todas as submissoes. Os cadernos de todas as pessoas devem ser públicos no final

**Vantagens da dinâmica**:
- alunos aprendem o quaõ importante é fazer um modelo que realmente performa bem em dados nunca antes visto
- os alunos ao verificar quais cadernos performaram melhor podem trocar conhecimento sobre as melhores técnicas e práticas
