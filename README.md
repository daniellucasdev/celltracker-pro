# CellTracker Pro 📡😏

Prank / anti-scam bait: um site que **simula** rastrear a localização de uma pessoa por número de telefone.

**Nada real acontece** — é 100% encenação no navegador:

1. A pessoa digita um número e clica em `INICIAR`.
2. Aparece o modal de termo de responsabilidade ("não nos responsabilizamos por mau uso da plataforma") com `CONFIRMAR`.
3. Uma sequência falsa de "triangulação" roda no terminal (GSM, ERB, GPS, SS7...) com radar e barra de progresso.
4. Ao "encontrar a localização"... toca o áudio do gemido-whatsapp. 😂

## Avisos incluídos

- Banner fixo: ferramenta de **simulação**, usar **apenas em ambientes controlados**.
- Modal de termo antes de iniciar.
- Reveal final explicando que é brincadeira e para não enganar pessoas de boa-fé.
- Rodapé: nenhum dado é coletado/enviado, nenhuma consulta real é feita.

## Rodar localmente

Abra `index.html` ou sirva a pasta:

```bash
python3 -m http.server 8080
```

## Deploy

GitHub Pages: <https://daniellucasdev.github.io/rastreador-prank/>

---
Projeto de entretenimento. Não use para assediar, ameaçar ou enganar pessoas.
