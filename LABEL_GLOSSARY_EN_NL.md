# Heeyoo HR — EN / NL label glossary

The data files keep **structural enum values and key fields as stable English keys** (so app
logic and colour coding stay consistent across both languages). Use this glossary to render the
correct **display label** per language in the UI. Free-text content (names, titles, email and
task text, meeting titles, cities) is already fully translated in each language's files.

## Task priority
High = Hoog | Medium = Middel | Low = Laag
## Task status
Open = Open | Done = Afgerond
## Meeting type
meeting = afspraak | interview = sollicitatiegesprek | 1:1 = 1-op-1 | review = review |
sync = overleg | workshop = workshop | deadline = deadline
## Meeting recurrence
weekly = wekelijks | monthly = maandelijks
## Day of week (key -> NL label)
Mon = ma | Tue = di | Wed = wo | Thu = do | Fri = vr
## Activity types (overview heatmap)
Meeting = Afspraak | Project = Project | Admin = Administratie | Email = E-mail |
Focus = Focus | Break = Pauze
## Work-location mode
Office = Kantoor | Remote = Thuis | Hybrid = Hybride

## CSV column headers (EN -> NL) — already applied in the *_NL.csv files
Master: Employee ID=Medewerker ID, Name=Naam, StartDate=Startdatum, StartYear=Startjaar,
ExitDate=Einddatum, Title=Functie, BusinessUnit=Bedrijfsonderdeel, DepartmentType=Afdeling,
Division=Divisie, EmployeeStatus=Status, IsTerminated=Uit dienst, TerminationType=Type uitstroom,
TerminationReason=Reden uitstroom, Regrettable=Spijtig verloop, EmployeeType=Dienstverband,
EmployeeClassificationType=Contractvorm, PayZone=Salarisschaal, Age=Leeftijd, AgeBand=Leeftijdsgroep,
TenureYears=Dienstjaren, TenureBand=Dienstjarengroep, City=Plaats, Performance Score=Beoordeling,
Current Employee Rating=Huidige score, Engagement Score=Betrokkenheid, Satisfaction Score=Tevredenheid,
Work-Life Balance Score=Werk-privébalans, Training Program Name=Opleiding, Training Type=Opleidingstype,
Training Outcome=Resultaat, Training Duration(Days)=Duur (dagen), Training Cost=Kosten, PhotoFile=Foto

## Overview-page additions (for the Figma example)
### Week days — Voortgang axis (key -> NL label)
Sun=Zo | Mon=Ma | Tue=Di | Wed=Wo | Thu=Do | Fri=Vr | Sat=Za
### Where I work / Waar ik werk (legend)
Office=Kantoor | Remote=Huis | Hybrid=Hybride
### KPI strip
open tasks=open taken | overdue=Over tijd | unread mail=Ongelezen mails | meetings=Afspraken
### Section headers
Progress=Voortgang | Where I work=Waar ik werk | Open tasks=Openstaande taken
### Calendar day nav
Yesterday=Gisteren | Tomorrow=Morgen
