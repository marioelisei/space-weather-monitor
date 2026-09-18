# 🛰️ Space Weather Monitor

Relatório diário automatizado de clima espacial — Solar Cycle 25.

## O que é

Dashboard HTML gerado automaticamente com dados de atividade solar em tempo real, consolidados das seguintes fontes:

- **NOAA SWPC** — Space Weather Prediction Center
- **NASA SDO / SOHO / LASCO**
- **SpaceWeatherLive**
- **EarthSky**
- **ESA SSA**

## O que monitora

- Índice Kp planetário
- Flares solares (classes B, C, M, X)
- CMEs (Ejeções de Massa Coronal) Earth-Directed
- Vento solar e buracos coronais
- Manchas solares e regiões ativas
- Probabilidade de flares M e X
- Fluxo de prótons e elétrons (GOES-19)
- Alertas e tempestades geomagnéticas
- Monitor climático — Brasil · Argentina · Chile

## Níveis de alerta

| Nível | Condição |
|-------|----------|
| 🟢 VERDE | Atividade normal — Kp < 4, sem CME |
| 🟡 AMARELO | Atenção moderada — Flare M, Kp 4–5 |
| 🔴 VERMELHO | Cuidado elevado — Flare X, CME Earth-directed |
| 🟣 ROXO | Extremo — Evento tipo Carrington |

## Atualização

Relatório gerado e publicado automaticamente via tarefa agendada no Claude Cowork.

---
*Gerado por Mario Elisei · Sistema de Vigilância Solar Contínua*
----
