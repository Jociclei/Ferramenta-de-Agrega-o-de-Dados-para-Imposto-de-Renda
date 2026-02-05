# 📚 Tutorial - Agregador de Dados IR

Este tutorial vai guiá-lo passo a passo no uso do Agregador de Dados para Imposto de Renda.

## 📖 Índice

1. [Primeiro Acesso](#primeiro-acesso)
2. [Conhecendo o Dashboard](#conhecendo-o-dashboard)
3. [Preenchendo Rendimentos](#preenchendo-rendimentos)
4. [Registrando Rendimentos Isentos](#registrando-rendimentos-isentos)
5. [Lançando Despesas Dedutíveis](#lançando-despesas-dedutíveis)
6. [Cadastrando Bens e Direitos](#cadastrando-bens-e-direitos)
7. [Informando Dívidas](#informando-dívidas)
8. [Consultando o Resumo](#consultando-o-resumo)
9. [Dicas e Boas Práticas](#dicas-e-boas-práticas)

---

## 1. Primeiro Acesso

### Abrindo o Arquivo

1. Faça o download de `Agregador_IR_2025.xlsx`
2. Abra o arquivo no Excel ou LibreOffice Calc
3. Se aparecer um aviso de segurança, clique em "Habilitar Edição"
4. A planilha abrirá na aba **Dashboard**

### Configuração Inicial

Antes de começar a preencher os dados:

✅ Verifique o ano-base no Dashboard (deve estar correto)
✅ Tenha em mãos todos os seus informes de rendimento
✅ Separe comprovantes de despesas dedutíveis
✅ Organize documentos de bens e dívidas

---

## 2. Conhecendo o Dashboard

O **Dashboard** é sua central de controle. Nele você encontra:

### Navegação Rápida
```
┌─────────────────────────────────────────┐
│ Aba             │ Descrição             │
├─────────────────────────────────────────┤
│ Rendimentos     │ Salários e outros     │
│ Rendimentos     │ Dividendos e PLR      │
│ Isentos         │                       │
│ Despesas        │ Saúde, educação, etc. │
│ Bens e Direitos │ Patrimônio            │
│ Dívidas         │ Financiamentos        │
│ Resumo          │ Consolidação          │
└─────────────────────────────────────────┘
```

### Indicadores Principais

O Dashboard mostra automaticamente:
- 💰 Total de Rendimentos Tributáveis
- 💵 Total de Rendimentos Isentos
- 📝 Total de Despesas Dedutíveis
- 🏠 Total de Bens e Direitos

**Estes valores são atualizados automaticamente conforme você preenche as outras abas!**

---

## 3. Preenchendo Rendimentos

### Quando usar esta aba?
Para registrar salários, pró-labore, aluguéis recebidos e outros rendimentos **tributáveis**.

### Passo a Passo

1. **Clique na aba "Rendimentos"**

2. **Para cada mês, preencha:**
   - **Coluna A (Mês)**: Já está preenchida
   - **Coluna B (Fonte Pagadora)**: Nome da empresa que pagou
   - **Coluna C (CNPJ)**: CNPJ da fonte pagadora
   - **Coluna D (Tipo)**: Clique na seta e escolha:
     - Salário
     - Pró-labore
     - Aluguéis
     - Outros
   - **Coluna E (Valor Bruto)**: Digite o valor recebido
   - **Coluna F (IRRF)**: Digite o imposto retido na fonte

3. **Exemplo prático:**
```
Janeiro | Empresa XYZ Ltda | 12.345.678/0001-90 | Salário | 5.000,00 | 350,00
```

4. **O total anual será calculado automaticamente** na linha 100

### ⚠️ Observações Importantes

- ✅ Use o **Informe de Rendimentos** fornecido pela empresa
- ✅ Digite valores **SEM** pontos ou vírgulas (o Excel formata automaticamente)
- ✅ Para rendimentos de múltiplas fontes no mesmo mês, use linhas separadas
- ❌ **NÃO** edite a linha de totais (linha 100)

---

## 4. Registrando Rendimentos Isentos

### Quando usar esta aba?
Para registrar dividendos, PLR, indenizações e outros rendimentos **não tributáveis**.

### Tipos de Rendimentos Isentos

| Tipo | Exemplo |
|------|---------|
| Dividendos | Lucros distribuídos por empresas |
| PLR | Participação nos Lucros e Resultados |
| Indenizações | Por rescisão de contrato |
| Rendimento Poupança | Juros da caderneta de poupança |
| Lucro na Venda de Imóvel | (se enquadrado como isento) |

### Passo a Passo

1. **Clique na aba "Rendimentos Isentos"**

2. **Para cada rendimento, preencha:**
   - **Coluna A (Tipo)**: Já vem com os tipos principais
   - **Coluna B (Fonte Pagadora)**: Quem pagou
   - **Coluna C (CNPJ)**: CNPJ da fonte
   - **Coluna D (Valor)**: Valor recebido

3. **Exemplo:**
```
Dividendos | ABC S.A. | 98.765.432/0001-10 | 2.500,00
PLR | Empresa XYZ | 12.345.678/0001-90 | 1.800,00
```

---

## 5. Lançando Despesas Dedutíveis

### Estrutura da Aba

A aba está organizada por **cores** para facilitar:

- 🟢 **Verde**: Saúde
- 🔵 **Azul**: Educação
- 🟠 **Laranja**: Previdência Privada
- 🟤 **Marrom**: Dependentes

### 5.1 Despesas com Saúde

**O que pode deduzir:**
- Plano de saúde
- Consultas médicas
- Exames
- Tratamentos odontológicos
- Fisioterapia
- Cirurgias
- Aparelhos ortopédicos

**Como preencher:**
```
Plano de Saúde | Titular | 123.456.789-00 | Mensalidade 2025 | 12.000,00
Consultas | Dr. João | 987.654.321-00 | Cardiologia | 600,00
```

⚠️ **ATENÇÃO**: Não há limite para dedução de saúde!

### 5.2 Despesas com Educação

**O que pode deduzir:**
- Ensino fundamental
- Ensino médio
- Ensino superior
- Pós-graduação (mestrado, doutorado)
- Ensino técnico

**Limite: R$ 3.561,50 por pessoa (2024)**

**Como preencher:**
```
Ensino Superior | Universidade ABC | 11.222.333/0001-44 | Mensalidades | 18.000,00
```

❌ **NÃO pode deduzir:**
- Cursos de idiomas
- Cursos profissionalizantes
- Preparatórios
- Material escolar

### 5.3 Previdência Privada (PGBL)

**Limite:** 12% da renda bruta anual

**Como preencher:**
```
PGBL | Seguradora XYZ | 55.666.777/0001-88 | Contribuições 2025 | 7.200,00
```

### 5.4 Dependentes

**Valor fixo por dependente: R$ 2.275,08 (2024)**

Digite apenas o **número de dependentes**.

---

## 6. Cadastrando Bens e Direitos

### Códigos Principais

| Código | Descrição | Exemplo |
|--------|-----------|---------|
| 11 | Apartamento | Apartamento em SP |
| 12 | Casa | Casa em MG |
| 13 | Terreno | Terreno no litoral |
| 21 | Veículo | Carro Fiat Uno |
| 31 | Conta Corrente | Banco do Brasil |
| 45 | Renda Fixa | CDB banco XYZ |
| 47 | Fundo de Investimento | Fundo multimercado |

### Passo a Passo

1. **Para cada bem, preencha:**
   - **Coluna A (Código)**: Use a tabela acima
   - **Coluna B (Discriminação)**: Descreva o bem
   - **Coluna C (Localização)**: Cidade/Banco/etc
   - **Coluna D**: Valor em 31/12/2024
   - **Coluna E**: Valor em 31/12/2025

2. **Exemplo - Imóvel:**
```
11 | Apartamento 3 quartos | São Paulo-SP | 350.000,00 | 350.000,00
```

3. **Exemplo - Veículo:**
```
21 | Fiat Uno 2020 Placa ABC-1234 | SP | 45.000,00 | 40.000,00
```

4. **Exemplo - Investimento:**
```
45 | CDB Banco XYZ | Banco XYZ | 50.000,00 | 55.000,00
```

### 💡 Dicas Importantes

- Para imóveis: informe endereço completo na discriminação
- Para veículos: informe marca, modelo, ano e placa
- Para investimentos: informe nome da instituição financeira
- Se o bem foi adquirido em 2025, coluna D fica zerada

---

## 7. Informando Dívidas

### Códigos Principais

| Código | Descrição |
|--------|-----------|
| 11 | Financiamento Imobiliário |
| 12 | Financiamento de Veículos |
| 13 | Empréstimo Bancário |
| 14 | Cartão de Crédito |
| 99 | Outras Dívidas |

### Passo a Passo

1. **Para cada dívida, preencha:**
   - **Código e Discriminação**
   - **Credor**: Banco ou instituição
   - **Valor em 31/12/2024**: Saldo devedor
   - **Valor em 31/12/2025**: Saldo devedor

2. **Exemplo:**
```
11 | Financiamento Casa Própria | Caixa Econômica | 280.000,00 | 265.000,00
12 | Financiamento Veículo | Banco ABC | 35.000,00 | 28.000,00
```

---

## 8. Consultando o Resumo

### O que você encontra no Resumo

A aba **Resumo** consolida tudo automaticamente:

1. **Rendimentos**
   - Total de rendimentos tributáveis
   - IRRF retido
   - Rendimentos isentos

2. **Deduções**
   - Total de despesas dedutíveis

3. **Patrimônio**
   - Total de bens e direitos
   - Total de dívidas
   - **Patrimônio líquido** (bens - dívidas)

### Como usar o Resumo

✅ **Confira** se todos os valores estão corretos
✅ **Compare** com o ano anterior
✅ **Use** como base para preencher a declaração
✅ **Imprima** para ter um guia durante o preenchimento

---

## 9. Dicas e Boas Práticas

### 📌 Organização

- ✅ Preencha aba por aba, não pule etapas
- ✅ Guarde todos os comprovantes por 5 anos
- ✅ Faça backup da planilha regularmente
- ✅ Atualize ao longo do ano (não deixe para última hora)

### 🔒 Segurança

- ✅ Não compartilhe a planilha com dados preenchidos
- ✅ Use senha de proteção no arquivo
- ✅ Faça cópias em locais seguros

### ✅ Validação

Antes de usar os dados na declaração:

1. [ ] Todos os campos obrigatórios estão preenchidos?
2. [ ] Os totais do Resumo estão coerentes?
3. [ ] Você tem comprovantes de tudo que lançou?
4. [ ] Os CNPJs estão corretos?
5. [ ] Os valores batem com os informes de rendimento?

### 📞 Quando Procurar um Contador

Procure ajuda profissional se:
- Teve ganho de capital com vendas
- Recebeu rendimentos do exterior
- É empresário ou sócio de empresa
- Tem dúvidas sobre deduções específicas
- Sua situação é complexa

---

## 🆘 Problemas Comuns

### "As fórmulas não estão calculando"

**Solução:**
- Verifique se a edição está habilitada
- Pressione F9 para recalcular
- Confira se não apagou acidentalmente alguma fórmula

### "Os totais estão errados"

**Solução:**
- Verifique se preencheu nas células corretas
- Não use pontos separadores de milhar (digite 5000, não 5.000)
- Verifique se não há linhas em branco no meio dos dados

### "Perdi meus dados"

**Solução:**
- Verifique as versões anteriores do arquivo
- Use Ctrl+Z para desfazer
- Sempre faça backup!

---

## ✉️ Precisa de Ajuda?

- 📖 Leia o [README.md](README.md) completo
- 🐛 Reporte bugs nas [Issues](https://github.com/seu-usuario/agregador-ir/issues)
- 💡 Sugira melhorias

---

**🎉 Parabéns! Você está pronto para usar o Agregador de Dados IR!**

*Lembre-se: Esta é apenas uma ferramenta de organização. Sempre consulte um contador para orientações específicas sobre sua declaração.*
