[![Quality Gate Status](https://sonarcloud.io/api/project_badges/measure?project=blingblingboyy_calculadora1&metric=alert_status)](https://sonarcloud.io/summary/new_code?id=blingblingboyy_calculadora1)
[![Quality gate](https://sonarcloud.io/api/project_badges/quality_gate?project=blingblingboyy_calculadora1)](https://sonarcloud.io/summary/new_code?id=blingblingboyy_calculadora1)
[![SonarCloud](https://sonarcloud.io/images/project_badges/sonarcloud-white.svg)](https://sonarcloud.io/summary/new_code?id=blingblingboyy_calculadora1)

# Calculadora com CI.
Utiliza 3 ambientes:
- dev - Desenvolvimento
- hmg - Homologação
- prd - Produção
- 
Pipeline
- dev - Compilação
- hmg - Compilação, Testes, Análise Código, Cobertura Código
- prd - Empacotamento
- 
<br>
- Utiliza o Apache Maven para a automatização da construção.<br>
- A pasta test contêm os testes unitários do projeto utilizando JUnit 4.<br>
- A cobertura do código é realizada através do JaCoCo.<br>
