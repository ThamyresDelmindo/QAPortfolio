# 🧮 Testes Manuais - Calculadora Online  

## 📌 Objetivo  
Testar funcionalidades básicas e de memória da [calculadora em calculator.net](https://www.calculator.net/), identificando bugs e documentando evidências para portfólio de QA.  

## 🎯 O Que Aprendi  
- ✅ **Criação de casos de teste** com cenários válidos e inválidos.  
- 🐞 **Identificação e documentação de bugs** (ex: funções de memória MR/MC).  
- 📱 **Testes de usabilidade** (botões, display, responsividade).  
- 📂 **Gestão de evidências** (prints, gravações, organização em pastas).  

## 📊 Resultados  
- **15 casos de teste** executados.  
- **4 bugs críticos** encontrados (principalmente em funções de memória).  
- **100% de cobertura** nas operações básicas.  
- **Taxa de falha**: 26.6% (4/15 testes falharam).  
- **Tempo de execução**: 1h30.  

## 🐞 Bugs Críticos Encontrados
| ID Bug  | Descrição                       | Gravidade |
|---------|-------------------------------- |-----------|
| CT-017  | MR insere vírgula no display    |  Média    |
| CT-018  | Botão MC não limpa memória      |  Alta     |

## 🛠️ Ferramentas Utilizadas  
| Ferramenta        | Uso                              |  
|-------------------|----------------------------------|  
| Excel             | Documentação de casos de teste   |  
| Gravador de Passos| Captura de tela e gravações      |  
| GitHub            | Versionamento e portfólio        |  

## 📂 Estrutura do Projeto  
- **Calculator-Test/**  
  - 📄 [Casos de Teste](/Test-Cases/Calculator-Tests.xlsx)  
  - 📄 [Relatório de Bugs](/Bug-Reports/Bug-Calculator.md)  
  - 📁 [Evidencias](/Evidence/)  

## 💡 Insights e Lições Aprendidas  
- 🔄 **40% dos bugs** em funções de memória (MR/MC).  
- ⚠️ **Edge cases** são críticos (divisão por zero).  
- 📌 **Documentação clara** é essencial para reproduzir bugs.  

## 🎥 Demonstração do Bug MR/MC  
![GIF mostrando o bug dos botões MR/MC](evidencias/CT-018-FunçãoMC-GravadordePassos.gif)  
*Botões MR/MC não funcionam conforme o esperado - veja a alternância sem ação.*  

## 🚀 Como Reproduzir  
1. Acesse [calculator.net](https://www.calculator.net/).  
2. Siga os [casos de teste](/Test-Cases/).  

## 🔎 Tags  
`#QA` `#TestesManuais` `#CasosDeTeste` `#BugReport` `#PortfólioQA`  
