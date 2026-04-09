# ***NoShowGuard***

Diariamente, clínicas e hospitais enfretam altos índices de ***no-show (ausência de pacientes)***, gerando transtornos como: perda de receita, aumento de ineficiência e aumento custos operacionais. 

Esse projeto propõe uma solução baseada em dados históricos para **prever a probabilidade de ausência de pacientes antes do dia consulta**, permitindo que ações preventivas possam ser utilizadas por médicos e administradores: como lembretes, contato ativo ou então reagendamentos. Além de gerar insights como quais grupos de pacientes têm maior tendência em cancelar seus agendamentos, permitindo contato personalizado.

## NoShowGuard: Prevendo Cancelamentos em Agendamentos Médicos

## 📌 1. Problema:
Diversas clínicas têm que lidar com altas taxas de cancelamento de agendas, resultando em utilização insuficiente de recursos e perdas financeiras.

## 🎯 2. Objetivo:
Criar um modelo preditivo que possa identificar pacientes com uma alta probabilidade de cancelarem seus agendamentos com 1 dia de antecedência, permitindo que intervenções possam ser realizadas e alinhamento de expectativas possam ser redefinidas.

## 🧠 3. Entendimento de negócio:
- Stakeholders: Médicos, Pacientes, Equipe de marketing e/ou TI da clíncia ou Software.
- Decisão: Tomar acções preventivas (ligações, mensagens, reagendamento).
- Métrica(s) de sucesso: Redução da taxa de **no-show**.
- Custo de erros:
  - **Falso positivo**: Esforço operacional desnecessário.
  - **Falso negativo**: Esforço operacional e perda de receita.
## 🔎 4. Stack Técnica
- **Tipo de algortimo**: Classificação Binária
- **Variável target:** 
  - No Show:
    - 1 - Paciente não compareceu na consulta.
    - 0 - Paciente esteve presente na consulta.
- **Momento previsto para previsão**: 24h antes do antendimento.

## 📚 5. Data Understading (EDA)
 **To add in the future**