# Cold Case AI 🔎

Et separat, mobiltilpasset prosjekt for kildekritisk historisk analyse av uløste saker. Første forskningsområde er forsvinningen til Jørn Berntzen i Oslo i 2004 og dokumentert kriminalitetshistorisk kontekst 2000–2005.

## Åpne appen
Når GitHub Pages er aktivert: https://oyvind37-cpu.github.io/cold-case-ai/

Appen henter data fra `cases/jorn-berntzen-2004.json`. Den viser kilder, datoer, dokumentasjonsstatus og skiller direkte saksopplysninger fra generell historisk kontekst. Ingen oppføringer etablerer en forbindelse mellom andre kriminelle hendelser og forsvinningen.

## Kildekritikk
- Opplysninger fra journalistikk om journaler og logger er **sekundærformidling av primærmateriale**, ikke egen verifikasjon av originaldokumenter.
- Historisk statistikk er bakgrunnsinformasjon, ikke mistankegrunnlag.
- Oppdateringer skal ha kilde, status og sporbar ID.
- Ingen ansiktsgjenkjenning, identitetssporing eller automatiske anklager.
- Sakens dokumentasjon må kvalitetssikres før slutninger trekkes.

## Mobil
Åpne Pages-nettstedet i Safari og velg Del → Legg til på Hjem-skjerm.

## Publisering
GitHub Actions-filen `.github/workflows/pages.yml` publiserer hele repositoryets rot. Velg **Settings → Pages → Source: GitHub Actions** og kjør arbeidsflyten ved behov.
