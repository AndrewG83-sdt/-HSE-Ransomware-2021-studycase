# -HSE-Ransomware-2021-studycase
# Attacco Ransomware Conti contro HSE (Irlanda, 2021)

##  Descrizione
Questo repository contiene la mia analisi tecnica dell’attacco ransomware che ha colpito il sistema sanitario irlandese (HSE) nel maggio 2021, condotto dal gruppo Conti.  
Ho ricostruito la timeline, le tecniche utilizzate dagli attaccanti, l’impatto sull’infrastruttura sanitaria e le azioni correttive e preventive necessarie.

##  Contenuto
- `REPORT.md` → Report tecnico completo con sezioni: introduzione, timeline, tecniche (TTP), impatto, lezioni apprese, azioni correttive e preventive, conclusione, fonti.  
- `fonti.txt` → Elenco dei link diretti alle fonti ufficiali e articoli usati per la ricerca.

##  Punti chiave del report
- Accesso iniziale tramite **phishing (Excel malevolo)**.  
- Presenza di **Cobalt Strike e Mimikatz** già settimane prima della cifratura.  
- **Dwell time** lungo: oltre 2 mesi senza rilevamenti efficaci.  
- Impatto enorme: blocco nazionale dei sistemi sanitari, oltre 100 milioni di euro di danni.  
- **Azioni preventive proposte**: EDR/XDR, Zero Trust, patch management continuo, formazione anti-phishing, tabletop exercise.

##  Fonti principali
- [PwC – Independent Post Incident Review](https://www.hse.ie/eng/services/publications/conti-cyber-attack-on-the-hse-full-report.pdf)  
- [Irish Times – Timeline to a Cyberattack](https://www.irishtimes.com/news/crime-and-law/timeline-to-a-cyberattack-the-signs-missed-before-state-s-health-service-crippled-1.4752451)  
- [RTE.ie – Cyberattack on HSE](https://www.rte.ie/news/analysis-and-comment/2021/0523/1223337-cyber-attack-hse/)  
- [TrendMicro – One Year On](https://www.trendmicro.com/en_fi/research/22/e/one-year-on-what-can-we-learn-from-the-hse-ransomware-attack.html)  
- [HC3 – Lessons Learned from the HSE Attack](https://www.hhs.gov/sites/default/files/lessons-learned-hse-attack.pdf)

---

✍ Autore: **Andrea Giovannoni**  
 [LinkedIn](https://www.linkedin.com/in/andrea-giovannoni-253b1b54/)) | [GitHub](https://github.com/AndrewG83-sdt))
