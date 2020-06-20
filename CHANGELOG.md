# Changelog
All notable changes to this project will be documented in this file. All version changes which are not recorded in Github as releases are shown here with the hash of the commit that marks them.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html) adapted to data models, and specifically to Anki notes:
- adding notes increments the patch version
- improving wording (while leaving the content unmodified) increments the patch version
- adding note types increments the minor version
- modifying note types (any of their properties, such as fields, css, etc.) increments the major version
- substantially modifying the content of notes, ie. substantially changing what people will have already learned, increments the major version
- making minor changes to the content of notes (such as moving an answer from "Very likely yes" to "yes") increments the minor version.

## [Unreleased]

## [4.0.0] - 2020-06-20
### Changed
- minor readability improvements
- the note types are updated to support another background for another tag

## [3.2.0] - 2020-05-18
### Changed
- updated information about pets being at risk of infection, as we now have more conclusive evidence that it's definitely possible, and has happened. Nevertheless, it's still not clear how easily this happens
- abbreviated "University of California" to "UC" to shorten the context for a few questions
- removed the timer while reviewing, as a default setting
- minor changes to the definition of sepsis, to simplify and clarify it
- removed viruses as a common way to cause pneumonia, keeping bacteria as most frequent cause

### Added
- definitions of presymptomatic transmission, infectivity
- question about infectivity peaking before or after symptom onset
- question about number of days after symptom onset when infectiousness may start to decline significantly
- question about how long the virus remained on stainless steel (separated from a question that previously contained both plastic and stainless steel)


## [3.1.0] - 2020-04-29
### Changed
- design change: placed the context below the prompt and encased it in a dotted border.
- design change: faded out the background so it doesn't interfere with the text legibility.

## [3.0.0] - 2020-04-29
### Added
- more questions about sources of information inaccuracy
- definitions of flattening the curve, contact tracing, dyspnea, sepsis, plasma, convalescence

### Changed
- the question about masks was replaced by a question about fomites.
- updated some sources
- reworded some notes for clarity

## [2.2.0] - 2020-03-30
### Added
- CONTRIBUTORS file
- Disclaimer section in README.md

### Changed
- the definition of tuberculosis to include the name of the bacteria causing it
- made it clear that it's not yet certain that the tuberculosis and measles vaccines do indeed boost the immune system in general

## [2.1.0] - 2020-03-29
### Changed
- changed the answer for the note about asymptomatic transmission to "yes", where it used to be "very likely yes"
- changed an answer to 'possibly' (where it used to be 'no evidence so far') regarding human-to-animal transmission

## [2.0.1] - 2020-03-29 - 015665c740570dc66b0a7cafc88c0a51400fe7ca
### Added
- a javascript file containing the code for showing the background only for cards tagged with 'covid-19'
- this CHANGELOG.md file
- separate css files with the css code in both note types

### Changed
- #16 now there's a bacteria-themed background for the Cloze deletion note types as well
- showing the source information in the same way between the two note types
- tagged all the cards with 'covid-19'
- improved the text on some notes for legibility and clarity
- "future-proofed" a question by adding the current month on it, in case in the future it changes

### Fixed
- #16 #19 using javascript, now we're only showing the background for notes tagged with "covid-19"

## [2.0.0] - 2020-03-27 - 3728288221f1af65c001e828bf7ad6c29e98af67
### Added
- new questions related to the challenges of estimating the spread and case fatality rate; defining incubation period.
- CONTRIBUTING.md file, containing v2.0 of the Contributor Covenant

### Changed
- broke up questions about the challenges of estimating accurately the spread and case fatality rate of COVID-19 into separate questions, as their answers were too long.
- improved wording for some notes
- removed from README.md the information about contributions (and moved it to CONTRIBUTING.md)

## [1.2.0] - 2020-03-27 - e1df476dd4b69a2a033ac945ac485d23d62c439e
### Added
- a new note type, "Cloze with Source"
- a background for the cards which can provide context on what they're about when the question doesn't suffice
- new guidelines for contribution
- notes about tuberculosis and measles and their vaccines, which may prove helpful with COVID-19; about anosmia and hyposmia as symptoms.

### Changed
- improved wording for some notes

## [1.1.0] - 2020-03-20 - 1c4f1339a235399f516f22c50e6eb442e8308712
### Added
- notes on comorbidities; transmission rates in relation to humidity and temperature; mortality in relation to gender; time to recover; more about coronaviruses in general; why official numbers don't reflect reality; asymptomatic transmission
- a photo of SARS-CoV-2 to illustrate the solar corona that they seemingly resemble

### Changed
- added another symptom to the list of common symptoms
- improved README.md

## [1.0.1] - 2020-03-18 - 7e261826b886bc522a65a0b8872871ea1e224915
### Added
- notes about stability of SARS-CoV-2 on different surfaces and related concepts such as Fomite, Aerosol; more about SARS-CoV and the differences to SARS-CoV-2 (and the illnesses they cause); same about MERS-CoV; about coronaviruses in general; about viruses in general.

### Changed
- improved the display of Source fields
- changed to original sources (rather than Wikipedia) for some of the notes
- improved legibility and clarity of some notes

## [1.0.0] - 2020-03-17 - c4b4f112baa03f7d7943f3f4aa78965e18d3e3f9
### Added
- notes about case fatality rate, how age affects the mortality rate in the case of COVID-19

### Changed
- made notes more legible and clear, also providing context

### Removed
- The "Front -> Back Source Context" note type. It has been merged with "Front <-> Back Source Context", which remains


## [0.0.2] - 2020-03-17 - 45b1bc8ec3c559091e64956c7348c821f3bd0018
### Added
- more information about deck objectives, about how to contribute and how to install
- notes about circulating myths

## [0.0.1] - 2020-03-16 - 3bb50593f892e18abda4cd5cafe8824163da8417
### Added
- a license file
- a README.md description
- the first notes around COVID, COVID-19, SARS, SARS-CoV-1, symptoms, consequences, incubation period, usage of masks and sanitizers, Pneumonia, the first infection with SARS-CoV-2, time the virus remains in the body after infection, how recovered patients can help those struggling with the infection
