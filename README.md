# Lovačko streljaštvo SRB – zapisnik (TrapApp-SRB)

Program za takmičenja i trening u lovnom streljaštvu po **Pravilniku o lovnom streljaštvu Lovačkog saveza Srbije (KUP LSS)**:
**trap**, **srndać** (nepokretna meta, sa satom i sirenom), **pokretna meta**, bodovi za plasman (1. = 10 … 10. = 1) i **lovački višeboj**.
Latinica ili **ćirilica** (prekidač „Latinica | Ћирилица“, Ctrl+L).

Za **Windows 10 i 11** i za **Mac** (macOS 14 ili noviji – probna verzija).

> ⚠️ **Probna verzija 0.1.0** – prvo izdanje za Srbiju. Molimo vas da proverite da li pravila i bodovanje odgovaraju praksi i javite greške (u programu: početna strana → „Prijavi grešku u programu“).

## ⬇️ Preuzimanje

**[Preuzmi TrapApp-SRB-win-Setup.exe](https://github.com/daxemann/trapapp-srb-releases/releases/latest/download/TrapApp-SRB-win-Setup.exe)** (uvek najnovija verzija)

Bez instalacije: [TrapApp-SRB-win-Portable.zip](https://github.com/daxemann/trapapp-srb-releases/releases/latest/download/TrapApp-SRB-win-Portable.zip)

Sve verzije i spisak promena: [Releases](https://github.com/daxemann/trapapp-srb-releases/releases)

### 🍎 Mac – probna verzija

| Vaš Mac (jabuka → „O ovom Macu“) | Preuzimanje |
|---|---|
| Čip **Apple M1, M2, M3, M4 …** (skoro svi od 2021.) | **[TrapApp-SRB-0.1.0-mac-applesilicon.zip](https://github.com/daxemann/trapapp-srb-releases/releases/download/mac-0.1.0-test/TrapApp-SRB-0.1.0-mac-applesilicon.zip)** |
| Procesor **Intel** | **[TrapApp-SRB-0.1.0-mac-intel.zip](https://github.com/daxemann/trapapp-srb-releases/releases/download/mac-0.1.0-test/TrapApp-SRB-0.1.0-mac-intel.zip)** |

[Stranica izdanja za Mac](https://github.com/daxemann/trapapp-srb-releases/releases/tag/mac-0.1.0-test)

---

## Instalacija (Windows)

1. Preuzmite datoteku **TrapApp-SRB-win-Setup.exe** (link gore).
2. Pokrenite je dvostrukim klikom.
3. **Pojaviće se plavi prozor Windowsa** (SmartScreen):

   > **Windows je zaštitio vaš računar** *(nem. „Der Computer wurde durch Windows geschützt“)*

   To je **normalno** i ne znači da je program opasan. Windows ovo prikazuje za svaki program koji nije potpisan skupim komercijalnim sertifikatom.

4. Kliknite na link **„Više informacija“** ispod teksta.
5. Dole se pojavi dugme **„Ipak pokreni“** – kliknite ga.
6. Instalacija traje nekoliko sekundi, bez dodatnih pitanja i bez administratorskih prava. Program se zatim sam pokrene.

Program se nalazi u meniju **Start** pod nazivom **„Lovacko streljastvo SRB“**.

> ℹ️ Plavi prozor se pojavljuje **samo jednom**, kod prve instalacije. Ažuriranja ga više ne prikazuju.

Program za Srbiju je **poseban program** – može da radi pored hrvatske verzije (TrapApp) na istom računaru, podaci se ne mešaju.

### Instalacija sa USB fleša

Ako datoteku **TrapApp-SRB-win-Setup.exe** kopirate na USB fleš i pokrenete je sa njega na drugom računaru, plavi prozor se po pravilu ne pojavljuje.

### Instalacija na Macu

1. Preuzmite odgovarajuću **.zip** datoteku (tabela gore) i dvaput kliknite na nju → pojavi se **TrapApp-SRB**.
2. Prevucite **TrapApp-SRB** u fasciklu **Aplikacije / Programi**.
3. **Prvo pokretanje (samo jednom)** – macOS ga blokira jer program nije iz App Storea. To je normalno.

*Slike su sa nemačkog macOS-a – na srpskom ili engleskom dugmad su na istom mestu.*

| | |
|---|---|
| **1.** Dvaput kliknite na TrapApp-SRB → kliknite **„Gotovo“** *(Fertig / Done)* – ne „Premesti u smeće“. | <img src="docs/mac/1-gotovo.png" width="260"> |
| **2.** Jabuka → **Podešavanja sistema → Privatnost i sigurnost** *(Datenschutz & Sicherheit / Privacy & Security)*. | <img src="docs/mac/2-privatnost.png" width="300"> |
| **3.** Dole kod „Sigurnost“: „TrapApp-SRB je blokiran …“ → **„Ipak otvori“** *(Dennoch öffnen / Open Anyway)*. | <img src="docs/mac/3-svejedno-otvori.png" width="420"> |
| **4.** Pitanje „Otvoriti TrapApp-SRB?“ → ponovo **„Ipak otvori“**. | <img src="docs/mac/4-svejedno-otvori.png" width="260"> |
| **5.** Lozinka Maca → **OK**. | <img src="docs/mac/5-lozinka.png" width="260"> |
| **6.** Program se pokrene – od sada normalno dvostrukim klikom. | <img src="docs/mac/6-trapapp.png" width="420"> |

> ℹ️ „Ipak otvori“ važi **samo za TrapApp-SRB** – zaštita Maca za sve ostale programe ostaje uključena. Sa USB fleša se poruka najčešće uopšte ne pojavi.

Ako se pojavi „TrapApp-SRB je oštećen“: otvorite Terminal i upišite
`xattr -cr /Applications/TrapApp-SRB.app` – zatim ponovo pokrenite.

---

## Šta program radi

- **Trap:** broj meta po strelcu podesiv (LSS: najmanje 15), grupe po ekipama, automatska promena mesta posle svake mete, tasteri Pogodak / Promašaj / Nazad
- **Srndać:** 4–10 hitaca (podesivo), vreme 1–10 min po strelcu – **Start/Stop** (razmak), sirena kad istekne vreme, **Sledeći strelac** (Enter), prekobrojni hici −2 boda, vreme u zapisniku
- **Pokretna meta:** 6 hitaca, krugovi 0–10
- **Ekipe:** 4 strelca iz iste LU, boduju se 3 najbolja
- **Plasman:** po disciplini 1. = 10 … 10. = 1 bod; **lovački višeboj** = zbir (samo ko je gađao sve discipline); nerešeno za 1.–3. mesto – raspucavanje po jedna meta / hitac
- **Aktivni sportski strelac:** gađa, ali ne dobija bodove za KUP
- Live monitor (2. ekran/TV), PDF (rezultati, zapisnik), razmena među računarima (USB / mreža), pravilnik LSS u programu, vežba sa izmišljenim strelcima

## Ažuriranja

**Windows:**

- Program kod svakog pokretanja sam proverava da li postoji nova verzija (potreban je internet).
- Ako postoji, na početnoj strani se pojavi narandžasti okvir **„Dostupna je nova verzija …“**.
- Kliknite **„Preuzmi i ažuriraj“** → program preuzme novu verziju i ponovo se pokrene.
- Dok je takmičenje otvoreno, ažuriranje nije moguće (prvo zatvorite takmičenje).

**Mac:** zasad ručno – preuzmite novu .zip datoteku i zamenite TrapApp-SRB u fascikli Aplikacije. Podaci ostaju sačuvani.

## Podaci

Takmičenja se automatski čuvaju u fascikli:

- **Windows:**

```
%LOCALAPPDATA%\LovackoStreljastvoSRB\Takmicenja
```

- **Mac:**

```
~/Library/Application Support/LovackoStreljastvoSRB/Takmicenja
```

Podaci **ostaju sačuvani** kod ažuriranja, deinstalacije i ponovne instalacije.

## Deinstalacija

**Windows:** Podešavanja Windowsa → **Aplikacije** → **„Lovacko streljastvo SRB“** → **Deinstaliraj**.

**Mac:** prevucite **TrapApp-SRB** iz fascikle Aplikacije u Smeće.

---

Autor: Darko Bakić · Pravilnik: Lovački savez Srbije · Hrvatska verzija (HLS): [trapapp-releases](https://github.com/daxemann/trapapp-releases)
