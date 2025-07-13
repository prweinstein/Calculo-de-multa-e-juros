# 📊 Calculadora de Multa e Juros

Sistema para cálculo automático de multa e juros em pagamentos em atraso, específico para o **Estado do Rio de Janeiro**.

## 🚀 **Acesso Rápido**

**🌐 [Usar Online](https://prweinstein.github.io/calculadora-supera)** (GitHub Pages)

## ✨ **Funcionalidades**

- ✅ **Cálculo automático** de multa e juros por atraso
- ✅ **Feriados atualizados** via Brasil API (nacionais + RJ)
- ✅ **Regras jurídicas** aplicadas automaticamente
- ✅ **Interface responsiva** e profissional
- ✅ **Validações robustas** de entrada
- ✅ **Tratamento de fins de semana** e feriados
- ✅ **Configurações personalizáveis** de multa e juros

## 🎯 **Regras Implementadas**

### **Regras Jurídicas:**
- **Vencimento em feriado/fim de semana:** Prorrogado para próximo dia útil
- **Pagamento no 1º dia útil:** Sem cobrança de multa/juros (após vencimento em feriado)
- **Pagamento em dia não útil:** Considerado efetivo no próximo dia útil

### **Limites Legais (CDC):**
- **Multa máxima:** 2% (Art. 52 do CDC)
- **Juros máximos:** 1% ao mês (12% ao ano)

### **Feriados Considerados:**
- **Nacionais:** Conforme Brasil API
- **Rio de Janeiro:** São Sebastião, São Jorge, Dia do Professor, Zumbi dos Palmares

## 📱 **Como Usar**

1. **Valor Base:** Digite o valor principal (aceita formatos: 1.000,50 ou 1000,50)
2. **Data Vencimento:** Selecione a data original de vencimento
3. **Data Pagamento:** Selecione quando foi/será pago
4. **Configurações:** Ajuste percentuais se necessário (padrão: 2% multa, 1% juros ao mês)
5. **Calcular:** Clique para obter o resultado detalhado

## 🧮 **Exemplo de Cálculo**

### **Cenário:**
- **Valor:** R$ 200,00
- **Vencimento:** 01/07/2025 (terça-feira)
- **Pagamento:** 13/07/2025 (domingo → próximo dia útil: 14/07)

### **Resultado:**
- **Dias de atraso:** 13 dias úteis
- **Multa (2%):** R$ 4,00
- **Juros (1% ao mês):** R$ 0,87 (13 dias ÷ 30 × 1%)
- **Total:** R$ 204,87

## 🛠️ **Tecnologias**

- **HTML5** + **CSS3** (Tailwind CSS)
- **JavaScript** vanilla (ES6+)
- **Brasil API** para feriados atualizados
- **Responsive Design** para mobile e desktop

## 🌐 **APIs Utilizadas**

- **[Brasil API](https://brasilapi.com.br)** - Feriados nacionais atualizados
- **Fallback local** - Feriados fixos caso API indisponível

## ⚖️ **Aspectos Legais**

Esta calculadora implementa as regras do **Código de Defesa do Consumidor (CDC)** e **Código Civil Brasileiro**.

**⚠️ Importante:** Esta ferramenta é para fins informativos. Consulte sempre um advogado para casos específicos.

## 🤝 **Contribuições**

Contribuições são bem-vindas! Sinta-se livre para:

- 🐛 Reportar bugs
- 💡 Sugerir melhorias
- 🔧 Enviar pull requests
- 📖 Melhorar documentação

## 📧 **Contato**

**Desenvolvido por:** Paulo Weinstein  
**GitHub:** [@prweinstein](https://github.com/prweinstein)

---

### 🌟 **Se este projeto foi útil, deixe uma ⭐ no repositório!**# Calculo-de-multa-e-juros
