# ⚡ EV Challenge 2026 — Gestão Inteligente de Eletropostos com Energia Solar

> Solução sustentável para recarga de veículos elétricos integrada ao ecossistema GoodWe  
> **FIAP × GoodWe | Sprint 1**

---

## 👥 Equipe

| Nome | RM | Turma |
|------|----|-------|
| _(nome do integrante)_ | RM000000 | _(turma)_ |
| _(nome do integrante)_ | RM000000 | _(turma)_ |
| _(nome do integrante)_ | RM000000 | _(turma)_ |

> Substitua os dados acima com as informações reais da equipe.

---

## 🔍 Problema e Justificativa

A rápida expansão dos veículos elétricos (VEs) impõe desafios significativos para as redes elétricas e para os gestores de infraestrutura de recarga. Os principais problemas identificados são:

- **Picos de demanda** concentrados em horários específicos (início da noite, horário comercial), sobrecarregando a rede elétrica convencional.
- **Ausência de integração com fontes renováveis**, fazendo com que parte da recarga ainda seja suprida por energia de origem fóssil.
- **Falta de monitoramento e precificação em tempo real**, dificultando a gestão eficiente dos eletropostos.
- **Infraestrutura escassa e mal distribuída** no Brasil, limitando o acesso democrático à mobilidade elétrica.

Esses problemas comprometem tanto a viabilidade econômica dos eletropostos quanto os benefícios ambientais esperados com a transição para a mobilidade elétrica — tornando essencial uma solução que una **geração renovável**, **armazenamento inteligente** e **gestão de energia em tempo real**.

---

## 💡 Proposta de Solução

A proposta consiste no desenvolvimento de uma plataforma de **gestão inteligente de eletropostos (Smart Charging)** integrada ao ecossistema GoodWe, capaz de:

- Priorizar a recarga nos momentos de maior geração solar (energia de custo zero ou negativo).
- Utilizar energia armazenada em baterias durante horários de pico tarifário.
- Monitorar em tempo real o consumo, a geração e a pegada de carbono de cada sessão de recarga.
- Operar em modo off-grid durante quedas de energia, garantindo resiliência operacional.
- Gerar relatórios de emissões de CO₂ equivalente (CO₂eq) por sessão de recarga.

### 📊 Impactos Esperados

| Dimensão | Impacto Esperado |
|----------|-----------------|
| 🌿 **Ambiental** | Redução das emissões de CO₂ associadas ao transporte e à geração de energia para recarga de VEs. |
| 💰 **Econômico** | Diminuição dos custos operacionais com uso de energia solar e gestão de picos de demanda. |
| 🤝 **Social** | Democratização do acesso a eletropostos com tarifas mais competitivas e infraestrutura confiável. |
| 🔬 **Tecnológico** | Geração de dados para aprimoramento contínuo da plataforma e integração futura com smart grids. |

---

## 🛠️ Tecnologias Utilizadas

### Ecossistema GoodWe

| Componente | Função no Projeto |
|------------|-------------------|
| **Inversores Híbridos GoodWe** (ex: EH / ET) | Gerenciam simultaneamente solar, bateria, rede elétrica e carregadores de VEs |
| **Baterias Lynx Home (GoodWe)** | Armazenamento de energia excedente para uso noturno ou em emergências |
| **EV Charger GoodWe** | Carregadores de VEs integrados ao sistema de gestão inteligente |
| **SEMS Portal** | Plataforma de monitoramento e gestão em nuvem (tempo real) |

### Níveis de Recarga Suportados

| Nível | Potência | Tempo de Carga | Aplicação |
|-------|----------|----------------|-----------|
| Nível 1 (CA) | até 3,7 kW | 8–20 horas | Residencial |
| Nível 2 (CA) | 7,4 – 22 kW | 2–8 horas | Comercial / Eletroposto |
| Nível 3 (CC) | 50 – 350 kW | 20–60 min | Carga Rápida / Rodovias |

---

## 🌱 Energias Renováveis e Sustentabilidade como Base da Solução

A solução é fundamentada nos **três pilares da sustentabilidade** e nas características das fontes renováveis integradas ao projeto:

### Pilares da Sustentabilidade

- **Ambiental**: uso de energia solar fotovoltaica com baixíssimas emissões de CO₂ ao longo de toda a vida útil (25–30 anos), reduzindo a dependência de fontes fósseis.
- **Social**: tarifas mais acessíveis viabilizadas pela geração local descentralizada, ampliando o acesso à mobilidade elétrica.
- **Econômico**: modelos de operação eficientes que internalizam os custos ambientais e geram valor a longo prazo para operadores e usuários.

### Fontes Renováveis Integradas

| Fonte | Relevância para o Projeto |
|-------|--------------------------|
| ☀️ **Solar Fotovoltaica** | Principal fonte de geração local. Painéis captam radiação → inversor converte CC para CA → energia usada ou armazenada. |
| 🌊 **Hidrelétrica (Matriz Nacional)** | Cerca de 60–65% da geração elétrica brasileira é hidrelétrica, reduzindo a pegada de carbono mesmo na recarga via rede. |
| 🌬️ **Eólica** | Pode complementar eletropostos em regiões com boa incidência de ventos. |

### Três Princípios que Justificam as Escolhas Tecnológicas

1. **Descarbonização** — substituição de fontes fósseis por energia solar na alimentação dos eletropostos.
2. **Eficiência** — inversores GoodWe com rendimento superior a 98%, minimizando perdas na conversão energética.
3. **Resiliência** — sistemas híbridos que garantem operação contínua mesmo em falhas da rede elétrica convencional.

---

## 📖 Glossário

| Termo | Definição |
|-------|-----------|
| **VE / EV** | Veículo Elétrico (Electric Vehicle) |
| **Eletroposto** | Ponto de recarga para veículos elétricos (EVSE) |
| **Inversor Híbrido** | Equipamento que gerencia solar, bateria, rede e cargas simultaneamente |
| **Smart Grid** | Rede elétrica inteligente com comunicação bidirecional entre fornecedores e consumidores |
| **CO₂eq** | CO₂ equivalente — medida padronizada de emissões de gases do efeito estufa |
| **Off-grid** | Operação independente da rede elétrica convencional |
| **SEMS Portal** | Plataforma de monitoramento e gestão da GoodWe baseada em nuvem |
| **Pegada de Carbono** | Total de emissões de GEE causadas por um produto, serviço ou atividade |

---

*EV Challenge 2026 — FIAP × GoodWe | Sprint 1*
