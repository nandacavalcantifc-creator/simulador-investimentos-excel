# Simulador de Investimentos em Fundos Imobiliários (Excel)

Projeto feito no desafio da DIO para aplicar conceitos de investimentos em fundos imobiliários (FIIs). A planilha ajuda o investidor a planejar os aportes mensais, projetar o patrimônio e os dividendos ao longo do tempo e distribuir os investimentos de acordo com o seu perfil.

## Objetivo
Automatizar cálculos financeiros, como juros compostos e dividendos mensais, para que o investidor tenha uma visão clara do retorno esperado e de como dividir a carteira entre os tipos de FII.

## Funcionalidades
- **Configurações:** salário, rendimento mensal da carteira (1,08%) e sugestão de valor para investir
- **Investimento mensal:** calcula o patrimônio acumulado a partir do aporte mensal e do prazo em anos
- **Dividendos mensais:** estima quanto o patrimônio acumulado vai gerar de renda passiva por mês
- **Cenários de longo prazo:** projeta patrimônio e dividendos em 2, 5, 10, 20 e 30 anos
- **Carteira por perfil:** o usuário escolhe o perfil (Conservador, Moderado ou Agressivo) e a planilha sugere o percentual e o valor para cada tipo de FII: Papel, Tijolo, Híbridos, FOFs, Desenvolvimento e Hotelaria
- **Gráfico de pizza:** mostra a distribuição da carteira de acordo com o perfil escolhido

## Ferramentas e conceitos utilizados
- Microsoft Excel
- Função **VF (FV)** para calcular juros compostos com aportes mensais
- Função **PROCV (VLOOKUP)** com chave composta (`PERFIL-TIPO`) para buscar os percentuais em uma tabela auxiliar
- **Intervalos nomeados** (ex.: `aporte`, `taxa_mensal`, `qtd_anos`, `rendimento_carteira`) para deixar as fórmulas mais legíveis
- **Referências mistas e absolutas** (`$D$16`, `$A21`, `D$14`) para replicar as fórmulas nos cenários
- **Validação de dados** com lista suspensa para escolher o perfil do investidor
- **Gráfico de pizza** para visualizar a carteira

## Como usar
1. Baixe o arquivo `Projeto Fernanda Lins.xlsx`
2. Na seção **Configurações**, informe o salário e o rendimento mensal esperado da carteira
3. Em **Investimento mensal**, informe quanto quer investir por mês e por quantos anos
4. Confira o patrimônio acumulado e os dividendos mensais estimados
5. Veja a evolução nos **Cenários** de 2 a 30 anos
6. Escolha o seu **perfil** na lista suspensa e informe o valor mensal a investir. A planilha mostra quanto aplicar em cada tipo de FII

## Visualização
<img width="308" height="277" alt="image" src="https://github.com/user-attachments/assets/ce81be70-0c5c-42b9-81cd-931a160b5e9c" />

## O que aprendi
Com este projeto, aprendi a estruturar cálculos financeiros no Excel, a usar juros compostos para projetar o crescimento do patrimônio e a criar uma tabela auxiliar com PROCV para automatizar a sugestão de carteira por perfil. Também pratiquei documentar um projeto e publicá-lo no GitHub.

Autora
Fernanda Lins – https://www.linkedin.com/in/fernandacavalcantilins/ 
