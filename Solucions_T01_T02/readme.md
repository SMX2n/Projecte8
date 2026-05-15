# Tasca 1 – Pla de transformació digital per a TransRàpid S.L.

**Alumne:** [Marc i Martí]  
**Data:** 15/05/2026  
**Client:** TransRàpid S.L. (empresa de transport amb 2 camions i 4 furgonetes)

---

## 1. Anàlisi de l'estat actual (què fan ara i quins problemes tenen)

Ara mateix, TransRàpid S.L. fa servir un **fitxer Excel** per portar tot el negoci: els consums de combustible, les rutes, les factures, els horaris… El problema és que aquest Excel el comparteixen entre tots i es perd informació constantment. A més, l'arxiu s'ha tornat molt lent i de vegades es corromp (es fa malbé). Això fa que els treballadors perdin hores buscant dades i que hi hagi errors.

**Principals mancances:**
- No tenen una base de dades de veritat.
- No controlen qui pot veure o canviar cada dada (seguretat zero).
- Quan un camió és a la carretera, no pot actualitzar l'estat de l'entrega en temps real.
- No fan còpies de seguretat automàtiques; si es perd l'Excel, s'ha perdut tot.

---

## 2. Objectius que volem aconseguir (SMART)

Per solucionar el caos, ens marquem aquests objectius:

1. **Reduir en un 80% les pèrdues d'informació** en 2 mesos, canviant l'Excel per un sistema de gestió de transport (TMS) al núvol.
2. **Que els transportistes puguin actualitzar l'estat de cada lliurament en temps real** des del seu vehicle, en 1 mes.
3. **Fer còpies de seguretat automàtiques cada dia** per no perdre mai les dades.
4. **Estalviar 10 hores a la setmana** que ara es perden buscant dades o corregint errors.

---

## 3. Què proposem per millorar-ho?

Dividirem la solució en **maquinari** (els aparells) i **programari** (els programes).

### 3.1 Maquinari (hardware)

**A l'oficina:**
- Un **NAS** (és com un disc dur connectat a la xarxa) per guardar totes les dades i fer còpies de seguretat. Model recomanat: **Synology DS224+** (uns 400 €).
- Dos ordinadors nous: processador **Intel i5** o **Ryzen 5**, **16 GB de RAM** i disc **SSD de 512 GB**. Així van ràpids i no es pengen. Preu aproximat: 800 € cadascun.

**Als vehicles (6 en total):**
- Una **tableta robusta** per a cada camió i furgoneta. Han de ser resistents a cops, pols i aigua (protecció IP68). Per exemple, la **Cleyver XTREM Tablet MAX 8**. Preu: uns 600 € per unitat.
- Cada tableta ha de tenir una **targeta SIM amb connexió 4G** per anar sempre a internet. Cost: uns 20 €/mes per tableta.

**Total maquinari:**
- NAS: 400 €
- 2 ordinadors: 1.600 €
- 6 tauletes: 3.600 €
- **Total = 5.600 €** (més les SIM: 120 €/mes)

### 3.2 Programari (software) – Comparem dues opcions

| Característica | Opció 1: Programari lliure (Odoo Community) | Opció 2: Programari comercial (SaaS) |
|----------------|---------------------------------------------|--------------------------------------|
| **Preu** | Gratuït (només paguem instal·lació) | Subscripció mensual per usuari |
| **On s'allotja** | Al nostre NAS o en un servidor | Al núvol (no ens hem de preocupar) |
| **Manteniment** | L'ha de fer un tècnic | Ja ho fa l'empresa del programa |
| **Facilitat d'ús** | Mitjana (cal una mica de formació) | Alta (molt intuïtiu) |
| **Exemples** | Odoo Community (mòduls de flota i facturació) | Cargoson, Logistiqo, Odoo Enterprise |

**Quina triar per a TransRàpid?**  
Jo recomanaria l'**Opció 2 (SaaS comercial)** perquè l'empresa és petita i no vol complicacions. Pagant uns 40 € per usuari al mes ja tenen tot: rutes, facturació, estat dels lliuraments en temps real i actualitzacions automàtiques. Així poden dedicar-se a transportar, no a fer de tècnics.

**Cost del programari (Opció 2):**  
8 usuaris (administrador, cap de logística, 6 transportistes) × 40 €/mes = **320 €/mes**. El primer any són uns 3.840 €.

---

## 4. Pressupost total (primer any)

| Concepte | Cost |
|----------|------|
| Maquinari (NAS, 2 PCs, 6 tauletes) | 5.600 € |
| Programari SaaS (12 mesos × 320 €) | 3.840 € |
| Instal·lació i configuració (tècnic, 20 hores a 50 €/h) | 1.000 € |
| Formació als treballadors (10 hores a 40 €/h) | 400 € |
| **TOTAL** | **10.840 €** |

A més, cada mes es paguen 120 € de les targetes SIM dels vehicles.

---

## 5. Seguretat i còpies de seguretat

Per no perdre mai les dades, farem:
- **Còpia automàtica diària** al NAS de l'oficina.
- **Còpia automàtica setmanal** a un núvol (per exemple, Google Drive o Backblaze).
- **Control d'usuaris**: només l'administrador pot esborrar factures; els transportistes només poden veure les seves rutes i marcar entregues.

---

## 6. Conclusió

Amb aquest pla, TransRàpid S.L. deixarà de patir per l'Excel. Tindran un sistema professional, segur i fàcil d'usar. Els transportistes actualitzaran els lliuraments des de la carretera, l'oficina veurà les dades en temps real i tot estarà protegit amb còpies de seguretat. La inversió d'uns 10.000 € es recuperarà en pocs mesos gràcies a l'estalvi de temps i a l'eliminació d'errors.

--- 

*Treball realitzat per [Marc i Martí – SMX 2n*
```
