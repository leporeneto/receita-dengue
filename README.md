# 💊 Gerador de Receita Médica

Este é um aplicativo web simples e responsivo para geração de receitas médicas personalizadas com base no **peso do paciente**, ideal para uso em pronto atendimento.

### 🚀 Funcionalidades

- Cálculo automático de **volume de hidratação oral** com base no peso informado
- Receita exibida em texto formatado
- Botão para **copiar rapidamente** o conteúdo gerado
- Compatível com dispositivos móveis e desktops
- Pode ser hospedado gratuitamente no **GitHub Pages**

---

### 🧪 Fórmula Utilizada

O cálculo baseia-se no seguinte:

- **Volume Total de Líquidos (LIQTOTAL)** = peso (kg) × 60ml  
- **Sais de Reidratação Oral (#X#)** = 1/3 de LIQTOTAL  
- **Outros Líquidos (#Y#)** = 2/3 de LIQTOTAL  

Os valores são automaticamente arredondados para **1 casa decimal** para facilitar a prescrição.

---

### 📝 Exemplo de Receita

Com base em um paciente de 70 kg, a receita incluirá:

```
5- Sais de reidratação oral
Dissolver 1 envelope em 1 litro de água fervida ou filtrada e consumir 1.4 litros em 24h

ORIENTAÇÕES:
1. Fazer ingesta de líquidos claros [...], ao menos 2.8 litros por dia;
```

---

### 🛠 Como usar

1. Acesse o app em: [https://leporeneto.github.io/receita-medica/](https://leporeneto.github.io/receita-medica/)
2. Digite o peso do paciente em kg
3. Clique em **Gerar Receita**
4. Copie e cole onde desejar

---

### 👨‍⚕️ Desenvolvido por

Armando Neto — Projeto [SOS Saúde Online](https://github.com/leporeneto)
