# 🎲 PG al Volo - Fantastic Depths Character Generator

**Un potente strumento di generazione personaggi per il sistema Fantastic Depths su Foundry VTT**

![image](https://img.shields.io/endpoint?url=https%3A%2F%2Ffoundryshields.com%2Fversion%3Fstyle%3Dplastic%26url%3Dhttps%3A%2F%2Fraw.githubusercontent.com%2FForelius%2Ffantastic-depths%2Frefs%2Fheads%2Fstable%2Fsystem.json)

<br>
<img width="2202" height="747" alt="image" src="https://github.com/user-attachments/assets/aa93a60b-f6cd-45e3-acf3-c40c61b49219" />


<br>
<br>

> [!TIP]
>
> ### 💡 Support
>
> **English:** This macro is free and open source. If you like it, I appreciate any feedback!
>
> **Italiano:** Questa macro e' gratuito e open source. Se ti piace, vorrei un tuo feedback!

<br>


**A simple macro for instant player characters to play on the fly.**
<br>
_Una semplice macro per creare personaggi giocanti al volo._

<br>

## ✨ Caratteristiche Principali

### 🎯 Generazione Intelligente & Veloce
- **Sistema di Livelli Avanzato**: Supporto per livelli fissi, casuali (1-36) o formule dinamiche (es. `2d4+1`, `1d6+2`)
- **Tiro Abilità Flessibile**: 3d6 classico o 4d6 rimuovi il peggiore
- **Allineamento Dinamico**: scegli tra i 3 classici di D&D o casuale

### 🎨 UI Moderna & Interattiva
- Dialog HTML5 responsive con tema scuro ottimizzato
- Tiro statistiche individuali o "Tira Tutte" con un click
- Dropdown equipaggiamento che si aggiorna dinamicamente in base alla classe selezionata

### 🛡️ Sistema Kit di Classe (12 Classi Supportate)
| Classe | Tipo Equipaggiamento |
|--------|---------------------|
| Bardo, Chierico, Druido | Kit arcani/divini |
| Elfo, Nano, Halfling | Strumenti per razze specifiche |
| Guerriero, Paladino, Vendicatore | Armi e Armature pesanti |
| Ladro, Mistico, Mago | Attrezzatura leggera e oggetti magici |

**Ogni kit include:**
- Oggetti fissi (UUID specifici con quantità/dadi)
- Tabelle casuali (armi, armature, oggetti speciali)
- Integrazione con compendi `fade-compendiums`

### 🎭 Generazione Nomi Avanzata
- **Nomi per razza**: Prefissi/suffissi per Elfi, Nani, Halfling e Umani
- Sistema a doppia tabella: Nome + Cognome combinati dinamicamente

### ⚔️ Generazione Automatica Abilità
- **Auto-import**: Abilità esplorazione, tiri salvezza e abilità di classe
- **Classe Speciale - Mistico**: Padronanza base per tutte le armi attivata automaticamente
- **Calcolo XP Bonus %**: Basato sui requisiti primari della classe scelta o casualmente generata

### 🎒 Sistema Equipaggiamento Multi-modalità
1. **💰 Solo Oro**: `(3d6×10)+10%×Lvl` mo per acquisti manuali
2. **🎲 Generico**: Oggetti base esclusi armi/armature
3. **⚔️ Kit Classe**: Equipaggiamento tematico per la classe scelta
4. **❌ Nessuno**: PG "nudo" (Draghi esclusi automaticamente dagli oggetti base)

### 👤 Gestione Personaggio
- **Checkbox Seguace**: Opzione che aiuta a differenziare un PNG da un PG
- **Token Personalizzati**: Immagini classe-specifiche dal game system auto-assegnate
- **Note GM Automagiche**: Padronanza armi, Punti Abilità  precalcolati 

---

## 🛠️ Requisiti

- **Foundry VTT**: v13.351
- **Fantastic Depths**: v1.0.8
- **Fantastic Depths Compendiums**: 1.0.2
- **Italian Translation of Fantastic Depths**: v1.1.0.2
- **Babele** ultima versione
- **Tabelle di questo modulo importate nel tuo mondo** Senza di queste la macro non funziona!
- **Item Piles** v3.2.32 Se si vuole usufruire del Negozio per acquistare l'equipaggiamento

---

## 📝 Utilizzo

1. Importa l'avventura
2. Esegui la macro come GM
3. Compila il form (tutti i campi sono opzionali - casuale per default)
4. Clicca "Crea" → Il personaggio viene generato nella sidebar Actors con:
   - Token configurato
   - Tutti gli oggetti equipaggiati
   - Statistiche calcolate
   - Abilità di classe importate

---

**Versione**: 1.0 GM-only  
**Autore**: FR4NC35C0 (with AI support)
**Licenza**: GNU General Public License v3.0 + Creative Commons Attribution-NonCommercial-NoDerivatives 4.0 International License (CC BY-NC-ND 4.0)

---

*Genera un personaggio completo in meno di 10 secondi. Potenza, flessibilità e stile.*

