# 📋 ARSAL – Fichas de Inspeção de Saneamento

> Sistema digital para preenchimento, controle e geração de relatórios PDF das fichas de fiscalização operacional de saneamento do Estado de Alagoas.

**Gerência de Fiscalização Operacional de Saneamento – GEFSAN / ARSAL**

---

## ✨ Funcionalidades

- **14 fichas de inspeção** cobrindo abastecimento de água, esgoto e área comercial
- **Exportação em PDF** com cabeçalho institucional, logos, conformidade e rodapé ARSAL
- **Salvamento automático** via LocalStorage — sem perda ao fechar o navegador
- **Resultado de conformidade** com contagem de SIM / NÃO / N.A. e barra visual
- **Funciona offline** — arquivo único, sem servidor ou banco de dados
- **Responsivo** para tablets e desktops usados em campo

---

## 📁 Estrutura de arquivos

```
sua-pasta/
├── index.html        ← aplicação completa
├── README.md
└── img/
    ├── arsal.png     ← logo ARSAL
    └── gov.png       ← logo Governo de Alagoas
```

---

## 🚀 Como usar

1. **Baixe os arquivos** — `index.html`, `arsal.png` e `gov.png`
2. **Organize a pasta** — crie uma pasta `img/` no mesmo diretório do `index.html` e coloque as duas imagens dentro dela
3. **Abra no navegador** — dê dois cliques em `index.html`, nenhuma instalação necessária
4. **Selecione a ficha** — escolha o tipo de inspeção e preencha os campos
5. **Exporte o PDF** — clique em **Gerar Relatório** e depois **Exportar PDF**

---

## 📂 Fichas disponíveis

### 💧 Abastecimento de Água
| Ficha | Descrição |
|-------|-----------|
| Manancial – Captação | Sinalização, outorga, perímetro de proteção, controle de vazões |
| Manancial – Poços | Infraestrutura, proteção sanitária, instalações elétricas |
| Adutoras | Manutenção, macromedição, vazamentos e perdas |
| Estação Elevatória (EE) | Operação, manutenção, eficiência energética e segurança |
| ETA – Tratamento de Água | Coagulação, filtração, casa de química, laboratório |
| Reservatório | Conservação, limpeza, desinfecção e controle de perdas |
| Redes de Distribuição | Cadastro, pressões, continuidade e qualidade da água |
| Pressão Manométrica | Registro de medições: logradouro, hora, coordenadas |

### 🟣 Esgotamento Sanitário
| Ficha | Descrição |
|-------|-----------|
| Elevatória de Esgoto (EEE) | Infraestrutura, operação e manutenção |
| Emissário | Licença ambiental, outorga, controle de efluentes |
| ETE – Tratamento de Esgoto | Fases preliminar, primária, secundária, manejo de lodo |
| Redes de Esgotamento | Pontos críticos, manutenção preventiva, transbordamentos |

### 🟢 Comercial / Operacional
| Ficha | Descrição |
|-------|-----------|
| Inspeção Comercial/Operacional | Escritório, atendimento, almoxarifado, serviço de campo |
| Acompanhamento Comercial/Operacional | Versão de acompanhamento sistemático |

---

## ⚠️ Observações

> **Modo privado / incógnito:** o salvamento automático usa o LocalStorage do navegador. Em abas privadas, os dados são apagados ao fechar a janela. Exporte o PDF antes de encerrar a sessão.

---

## 🏛️ Sobre

**ARSAL – Agência Reguladora de Serviços Públicos do Estado de Alagoas**  
Rua Eng. Roberto Gonçalves Menezes, nº 149 – Centro, Maceió/AL · CEP 57.020-680  
Telefone: +55 (82) 3315-2500 · Ouvidoria: 0800 284-0429 · [www.arsal.al.gov.br](https://www.arsal.al.gov.br)
