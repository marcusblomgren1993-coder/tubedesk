# TubeDesk

Ladda ner video från YouTube, SVT Play och SVT:s nyhetsartiklar med en vanlig Mac-app i eget fönster.
Allt som behövs är inbyggt i appen. Inget annat behöver installeras.

**Krav:** Mac med Apple-chip (M1 eller nyare) och macOS 12 eller senare.

## Installera (rekommenderas – inga varningsrutor)

Öppna Terminal (tryck Cmd+Mellanslag, skriv "Terminal" och tryck Enter). Klistra in raden nedan och tryck Enter:

```bash
curl -fsSL https://github.com/marcusblomgren1993-coder/tubedesk/releases/latest/download/install.sh | bash
```

TubeDesk installeras i mappen Program och öppnas av sig själv. Första starten kan ta upp till en halv minut. Nästa gång öppnar du appen från Launchpad.

Samma rad används för att **uppdatera** till en ny version. Den gamla versionen ersätts automatiskt.

## Installera via webbläsaren

1. Ladda ner `TubeDesk.zip` från [senaste versionen](https://github.com/marcusblomgren1993-coder/tubedesk/releases/latest).
2. Dubbelklicka på `TubeDesk.app`. När macOS säger att appen inte kunde verifieras klickar du på **Klar** (inte "Flytta till papperskorgen").
3. Öppna **Systeminställningar → Integritet och säkerhet**, scrolla ner och klicka på **Öppna ändå**. Knappen syns ungefär en timme efter försöket.
4. Bekräfta och skriv ditt Mac-lösenord. Det här behövs bara första gången.

## Använda

- Klistra in en länk och tryck på den röda knappen (eller Cmd+V).
- Filerna hamnar i **Filmer/TubeDesk**. Knappen **Öppna mappen** visar dem i Finder.
- Avsluta genom att stänga fönstret eller trycka Cmd+Q. Pågående nedladdningar avbryts då.
