<h1 align="center">STAR CITIZEN ASSISTANT</h1>

---
<div align="center" style="margin-top: 10px; margin-bottom: 10px;">
  <img width="850" height="206" alt="image" src="https://github.com/user-attachments/assets/95a2aeea-7967-4da1-a9b2-2fae7fdba395" />

  <p>Overlay di supporto per Star Citizen, versione 0.3</p>
</div>

---

<h2>LAUNCHER</h2>

<h3>
  <img align="center" width="34" height="35" alt="image" src="https://github.com/user-attachments/assets/8a67d9df-6c59-420c-bc2c-cf27ed309071" />
  IMPOSTAZIONI - TASTO SINISTRO
</h3>

<img width="254" height="186" alt="image" src="https://github.com/user-attachments/assets/7f4da9a3-7abc-4777-b7b3-476c35f685b6" /><br>

<p>
Apre le impostazioni dell'app.<br>
Settare il <b>path</b> alla cartella <code>LIVE</code>, scegliere se si preferisce un layout destro o sinistro, 
e se si desidera registrare gli eventi degli NPC.
</p>

<table>
  <tr>
    <td align="center" width="50%">
      <b>Layout Destro</b><br>
      <img width="260" height="159" alt="image" src="https://github.com/user-attachments/assets/bb337436-bd32-4ca1-a93d-e23e99b073cd" />
    </td>
    <td align="center" width="50%">
      <b>Layout Sinistro</b><br>
      <img width="260" height="157" alt="image" src="https://github.com/user-attachments/assets/a258d0de-b103-49b9-b959-fbb323de955a" />
    </td>
  </tr>
</table>

<br>

<h3>
  <img align="center" width="34" height="35" alt="image" src="https://github.com/user-attachments/assets/8a67d9df-6c59-420c-bc2c-cf27ed309071" /> 
  IMPOSTAZIONI - TASTO DESTRO
</h3>
<p>Trascinare per spostare l'overlay (ad eccezione del feed).</p>

<h3>
  <img width="26" height="30" alt="image" src="https://github.com/user-attachments/assets/5ebf2740-30a5-4e4b-a40f-aebbd7582eaf" />
  <img width="25" height="28" alt="image" src="https://github.com/user-attachments/assets/298bbe5f-7909-4602-8078-fd8d94a9415a" />
  MOSTRA DUMMY DYNAMIC FEED
</h3>
<p>Cliccare (icona verde) per mostrare una versione "dummy" del kill feed, cliccare di nuovo (icona rossa) per nasconderlo</p>

<h4>
  DUMMY FEED
</h4>
<p>
  <img width="30" height="30" alt="image" src="https://github.com/user-attachments/assets/46cef660-ba7c-4201-99db-4d61e26ab3ae" />
  Trascinare tenendo premuto il tasto destro per spostare il feed<br>
  <img width="33" height="32" alt="image" src="https://github.com/user-attachments/assets/5db1fafd-9915-44f8-9246-4bc5e8ea5d83" />
  utilizzare il pulsante al primo avvio e dopo ogni patch per popolare <code>weapon_data.json</code>. Questo file è necessario per 
  le corrispondenze <i>codice_arma → nome_reale_arma</i> del logger.
</p>

<h3>
  <img width="31" height="33" alt="image" src="https://github.com/user-attachments/assets/fd1ca731-8c80-4ea5-a2ff-88d63fd0d8d8" />
  ESCI
</h3>
<p>Cliccare per chiudere l'app.</p>

<h3>
  <img width="29" height="27" alt="image" src="https://github.com/user-attachments/assets/5b0ec6c3-1dc6-4f4b-ad87-485029ec3eba" />
  MENU'
</h3>
<p>Cliccare per aprire o chiudere il menù principale.</p>

<h3>
  <img width="26" height="30" alt="image" src="https://github.com/user-attachments/assets/7c8bc342-2a5e-46e4-ad24-0435db880083" />
  LOCK
</h3>
<p>
Cliccare per abilitare (<b>lucchetto chiuso</b>) o disabilitare (<b>lucchetto aperto</b>) il pass-through del mouse sulle seguenti finestre.<br>
Se abilitato, il click ignora l'overlay <b>ad eccezione del launcher (riquadro blu)</b>.
</p>

---

<h2>MENU' PRINCIPALE</h2>

<h3>
  <img width="28" height="31" alt="image" src="https://github.com/user-attachments/assets/d57007bd-4621-407e-984e-78fa9e2b8415" />
  <img width="27" height="28" alt="image" src="https://github.com/user-attachments/assets/1d627de8-53df-4033-8a69-d8c2bde4868b" />
  VISUALIZZA LOGGER
</h3>

<p>
  Cliccare per abilitare/disabilitare la visualizzazione del feed. Anche se non visualizzato continuerà a loggare.
  <ul>
    <li>Verde -> abilitato</li>
    <li>Rosso -> disabilitato</li>
  </ul>
</p>
<img width="535" height="214" alt="image" src="https://github.com/user-attachments/assets/8f0d42d0-18c4-4baa-ae8b-58d711fcfaab" />
<br>

<h3>
  <img width="37" height="32" alt="image" src="https://github.com/user-attachments/assets/1479f3d4-ba4b-46c6-9c04-aabea9e55c25" />
  INCONTRI
</h3>

<p>
Selezionare un log (memorizzati in cartella <code>Logs</code>) per visualizzarlo; di default viene aperto quello odierno.
</p>

<img width="428" height="267" alt="image" src="https://github.com/user-attachments/assets/a872c4aa-1820-49ff-8c2c-85224c5c0862" /><br>
<p>
Per ogni entry, il nome del giocatore rappresenta un link che porta al suo profilo sul sito ufficiale.
</p>

<h3>
  <img width="38" height="32" alt="image" src="https://github.com/user-attachments/assets/24cdd4be-4152-4231-accf-ccfc9515bddc" />
  TIMER
</h3>

<p>
Apre la schermata col timer in tempo reale per apertura/chiusura degli executive hangars.
</p>
<img width="426" height="404" alt="image" src="https://github.com/user-attachments/assets/a0d834ed-f574-4718-b6fd-38ba5b862475" />

<h3>
  <img width="29" height="29" alt="image" src="https://github.com/user-attachments/assets/f96a4530-a7b0-4bb9-8ed1-b9afbdc110ad" />
  SESSION INFO
</h3>

<p>
  Apre la schermata con le informazioni sull'attuale sessione. Nell'elenco delle sessioni recenti quelle in verde sono la stessa di quella attuale.<br>
  Il tasto <img width="30" height="32" alt="image" src="https://github.com/user-attachments/assets/d7021b3b-1220-436b-9909-ee16a59df891" /> permette di
  copiare negli appunti l'ID dello shard.<br>
  Gli orari sono calcolati in base all'orario locale della macchina.
</p>
<img width="427" height="347" alt="image" src="https://github.com/user-attachments/assets/73a68c03-a65a-4bd4-883d-b1e7983002af" />

<h3>
  <img width="30" height="33" alt="image" src="https://github.com/user-attachments/assets/39d6214d-c0ab-49de-94a6-28b2bd8c625b" />
  ITEM FINDER
</h3>

<p>
  Apre una schermata con barra di ricerca per cercare luogo d'acquisto e prezzo di armi, armature e componenti
  <img width="903" height="587" alt="image" src="https://github.com/user-attachments/assets/019e10bf-a1e7-43bf-a957-96ac145fd046" /><br>
  N.B.1 Vengono inseriti in lista SOLO gli oggetti acquistabili<br>
  N.B.2 Per funzionare necessita di un Bearer Token dal sito di UEXCorp:
  <ul>
    <li>crea un account/logga</li>
    <li>in basso a sinistra clicca su API</li>
    <li>aggiungi una nuova app</li>
    <li>in fondo ci sarà il token da copiare in "config.json" tra le virgolette della voce "uexAPI"</li>
    <li>per ogni utente sono concessi un massimo di 100 operazioni al giorno: cercare gli elementi e selezionarne uno costano 2 per esempio</li>
  </ul>
</p>

<p align="center"><i>Guida realizzata per VN's SC Assistant Overlay ©</i></p>
