---
title: Type Collection
navcat: Workflows
tags: cataloging
last_modified_at: 2021-03-15
---

This documentation was created for the LACMIP Type Collection Renovation & Digitization project funded by the Institute of Museum & Library Services [(IMLS Award # MA-10-19-0223-19)](https://www.imls.gov/grants/awarded/ma-10-19-0223-19-0).

# Introduction

## What is a "type"?

Type specimens, or "types", are the physical, name-bearing vouchers for new species, genera, etc. They are therefore retained in a specially designated "type collection" so researchers can reexamine them from time to time to assess their taxonomic validity. Therefore, types are some museum's most intellectually valuable specimens and must be handled with extreme care. 

Before accessing any specimens in the type collection, please review the following:
- **Always ask for help when moving specimen trays**. They may be much heavier than they appear. 
- **Open drawers slowly and cautiously.** Be aware that these cabinets _do not_ have drawer stoppers. In other words, if you pull to hard, the drawer may fall out. As a precaution, always pull out the drawer immediately below the one you wish to access about halfway; it will act as an emergency "stopper" should you pull out the upper tray too far.
- **Immediately alert the Collections Manager if specimens are damaged or disassociated from their labels.**
- Work with one specimen lot (box) at a time.
- Never move specimens or labels between boxes, or reorganize the boxes within their drawers unless directed to do so.
- All type specimens must be returned to their appropriate drawer(s)/cabinet(s) at the end of your shift.
- No food or drink (except water) is allowed in the type room, and please keep water away from specimens and equipment at all times.
- Please do not invite visitors into the type collections without consent from the Collections Manager or Curator.
- Always ask questions whenever you are unsure what to do!

## What is "taxonomy"?

In the biological sense, taxonomy refers to the classification of organisms. While you will not be entering or editing specimen identifications or taxonomy, taxonomic classificiation forms the foundation upon which the type collection was built and is organized. Please familiarize yourself with the basic concepts of taxonomy and binomial nomenclature by reviewing [this article] and the following video.
{% include video id="12XO8vYqBsA" provider="youtube" %}

## "QC" vs. Cataloging

Most of the specimens in the type collection are cataloged, meaning they already have a catalog number (or *Cat. No.*). The catalog number is a unique, human-readable identifier for a specimen lot that can be cited when the specimen is referenced in published research. 

Instead of cataloging, you will be updating--or "QC'ing" (quality controlling)--existing catalog records with missing information.

Before QC'ing any catalog records for specimens in type collection, please review our comprehensive documentation for the [Catalogue module]({{ site.baseurl }}/documentation/catalogue/), as well as all steps below outlined below.

As a point of diambiguation, true "cataloging" refers to the creation of _new_ catalog records and is only needed when new type specimens are received from researchers. Interns and volunteers will rarely catalog specimens in the type collection, and this should only be accomplished with guidance from the Collections Manager. LACMIP maintains a separate workflow for [cataloging](({{ site.baseurl }}/documentation/cataloging/).

# Type Collection QC Workflow

-> How does one go about selecting a specimen lot to QC?
-> How to log in to EMu

## Search for the specimen

{% include figure image_path="/assets/images/catalogue_typesearch.png" alt="screenshot of the Invert. Paleo. tab's search form in the Catalogue module" caption="Screenshot of the *Invert. Paleo.* tab's search form in the Catalogue module." %}

You will search for specimens by their LACMIP type number. These numbers are always labelled on specimens in bright red, yellow, and blue paint (not white paint and not stickers). If you are unsure whether a number is a type number, consult the Collections Manager.
{% include figure image_path="/assets/images/catalogue_LACMIPtypeno.png" alt="example LACMIP Type No." caption="LACMIP type numbers are indicated by bright red, yellow, or blue paint. Red = holotypes, syntypes, lectotypes; Yellow = paratypes, paralectotypes; Blue = hypotypes (figured or unfigured specimens)." %}

 *Step* | *On the search form...*
   --- | ---
   1 | In *LACMIP Type No.*, enter the type number 
   2 | Select the binoculars icon to execute the query.
   
## Assess the catalog record

Below is the first window encountered when loading EMu's Catalogue module, where the majority of EMu work will be done. The `Search` window can be used to query our database for specific type specimens. 

![img](https://lh4.googleusercontent.com/nnflmKe-uRHZwvXgwHMEhzC7PzI9QuRVRY56pZqIC-TXa1SBc8ktAOntqjJ7hEtsLowrEK7PmYkBGM5e68MriuEdGB2XprlwIKtK6aLRNYi_7H4ZtNAar4_PkMtX3JGschzUJMXJ)

1. `LACMIP Type No.` : enter the **type number** (not locality number!) for type specimens. 
2. `Search button` : click this button to execute the query. 

If no records are returned or if the returned records do not match the type number and/or locality number on the type specimen or included labels, contact Daniel for guidance. 

### Invert Paleo tab

The `Invert Paleo` tab (displayed at the bottom of the application window) is where the majority of information regarding the type specimen will need to be entered. 

A complete overview of the fields in the Invert Paleo tab exists on the LACMIP EMu Handbook under the [Catalogue](https://lacmip.github.io/emu/documentation/catalogue/) page. Below are the fields that will be primairly used for cataloging type records. 

![img](https://lh3.googleusercontent.com/LQm0HIFdBc9yLsEKgP2f7N9UaPoYJ-q5BKHOFDec4wJz5Pn0svO_U9Tiy8mJaDBsH1EhzUZgYfSTYh2xPOPMxuwZMxlMA6QtWevQnfjgwSsGkzfCzpDgj8FXG_Nyyftny3HJk-KS)

1. `Locality` : locality numbers are the first part of LACMIP's catalogue numbers (see here for a more detailed explanation of LACMIP's specimen IDs) and refer to the specific collection event and location (locality) where specimens were collected. While these numbers are almost always correct on any given type number, it is best to **always** double check. 
   - Make sure to verify that locality numbners are correct on **both** the EMu catalogue record and the type specimen.
   - Ensure that the location associated with the locality record matches any references to collection locations on labels associated with a type specimen.
   
2. `Lot count` : refers to the number of actual objects or individual specimens with the same type number. This will often be immediately apparent (one clam fossil will equate to  *Lot Count: 1*) but in cases when it is not (such as a chunk or colonial fossil fragments), please ask for guidance. 

3. `Disposition` : a dropdown menu with options to note the physical state of a specimen lot. For the vast majority of specimens where you have the actual specimen in front of you, you will choose "in collection". Options include: 

   - `being processed` : for specimens being incorporated into the collection (e.g. a new donation)
   - `discarded` : for specimens permanently removed from the collection
   - `in collection` : for specimens phusically locatable
   - `missing` : for specimens whose wherabouts are unknown
   - `on loan` : for specimens out on loan (refer to [transactions page](https://lacmip.github.io/emu/documentation/transactions/))
   - `unknown` : for specimens that haven't been physically located, but are known to exist.

4. `Alternative numbers` : the "legacy" numbers assigned by another institution or collector. 
   - 4a.  `Inst. Code` : code given to legacy institution. (See here to know how to choose the proper institution code). **Always click the lookup list button** when entering an Inst Code to validate your entry. If you are trying to add a new institution code, please ask for assistance. 
   - 4b.  `Inst. Number` : this number can either refer to a number assigned by an institution (such as UCLA) or a collector (such as Pierce). In the case of a collector, the number should be formatted as capitalized name and number (e.g. 'PIERCE 32a'). 
   
5. `Type Status` : dropdown of kinds of type specimens.
   
    - *Figured* is synonymous with *hypotype*. Always choose hypotype.
  
6. `Collection` : should always be 'TYPE'.
7. `Project` : should always be 'IMLS'.
8. `Original Nature` : dropdown of kind of fossil present. Most will be 'body fossil'. 
   - This is highly dependent on which higher taxanomy is being catalogued. 
   - Multiple values are possible per record (e.g. if a lot includes both a body fossil as well as the cast associated with it.)
   - Refer to the 'Original Nature' section of the [Catalogue](https://lacmip.github.io/emu/documentation/catalogue/) page of the EMu Handbook for a full list of options. 
9. `Anatomy` : lookup lists with options for what part of the animal was fossilized.  
   
   - Do not use body fossil as shown in the example above. 
   - Most mollusks will be just 'shell(s)'.
10. `IP Publications` :  table to attach bibliography records that correspond to a citation. 
    - It is extremely important that we have accurate cirtations for type specimens. 
    - If a new bibliography needs to be attached, follow the [Bibliography](#bibliography) workflow. 
11. `Pages, Fig. & Type` : data about where a specimen waas described in the cited paper. 
    - `Pages` : format with only the page number. Do not enter `p.`, `pg.`, ect. 
    - `Fig` : Enter the plate and/or figure number(s) seperated by a colon. See following examples: 
      + Specimen not figured: `unfigured`
      + Only plate: `pl. 3`
      + Only figure: `fig. 1`
      + Figure with range: `fig. 1A-B`
      + Multiple figures: `fig. 1, 3, 5-7`
      + Plate and only one figure: `pl. 3: fig. 15`
      + Plate and range of figures: `pl. 3: fig 9-15`
      + Plate and sequence of figures listed: `pl. 3: fig. 7, 12, 24`
      + Multiple plates: `pl. 3: fig. 7, 12, 24; pl.4: fig.8`
    - `Type`: open text field for kind of type 
      + Capitalize first letter
### Identification (1) tab
Below is an example of when the taxon of a specimen in known and needs to be entered. This only needs to be done if the genus nad species listed on a type specimen's record is not already entered in the `Identification List` nested table. 

If attempting to add a taxon to a catalog record, please ask for guidance.

A complete overview of the fields in the [Identification (1) tab](https://lacmip.github.io/emu/documentation/catalogue/#identification-1-tab) exists on the LACMIP EMu Handbook under the Catalogue page. Below are the fields that will be primairly used for cataloging type records. 

![img](https://lh6.googleusercontent.com/Zj6wDB0ph_2twEn60XdpzgmXW9Cura8lZfiNF_qElfNGgeisZIwrM1zcEzebOrewdLHg7xcmOunvI3SKP4CMde0Oi5S7wL-rjr3l4wtTacL3aEfVS7vawcGHLQS5rbFdYGBulYhi)

1. `Taxon` : attached record from the Taxonomy module that is currently selected from `Identification List`. 
    - If known, type the genus and species into and box and search for the taxon by clicking the blue button.
    - If the correct taxon is not available add the following text to the `Comments` open text box:
    > originally identified as [taxon]; taxonomy for this name does not exist in EMu (yet)
    >
2. `Identified By` : lookup list of full name(s) of person(s) who made this identification. 
    - Should only be filled out if label or publication explicitly states who identified (not collected) specimen. 
    - Generally formatted as `[first initial]. [surname]` though occasionally as `[first name] [surname]`. 
    - `Date Identified` : should only be filled out if date for identification is provided. Can be as granular as a day or a year. 
    - `Identification List` : tabel displaying the different taxa associated with a specimen
      + `Filed As` and `Currently Accepted` are radio buttons that take special meaning for type records. If attaching a new taxonomy, please consult collection manager for guidance. 
      + `*` : Clicking this button will add a new row in the nested table so more taxon records can be added. 

### Location tab

Locations for each specimen are recorded in EMu based on which cabinet and drawer they reside in. 

![screenshot of the location tab in the catalogue module](https://lacmip.github.io/emu/assets/images/catalogue_location.png)

1. `Current`  : type in `Cabinet [#] Drawer [#]` of the cabinet, drawer pair and press 'Tab' or the blue arrow to populate the field. 
   - If nothing populated, ask Daniel for help.
2. `Authorized By:` : type in `Daniel Markbreiter` and the blue arrow/tab.
3. `Moved By` : enter your full name and the blue arrow/tab.
4. `Inventoried  : enter your full name and the blue arrow/tab.

### Condition tab

![img](https://lh6.googleusercontent.com/9X6hV6Bu6yNbNpZbhlw3UIqKtoMqmTv7_7ldYMCIMctmYVf8HDAWDf9BSiOMD5xv2Q_1d7lBQDYPluJF_KbcljgANzJ98n-7gtW9qH_PpW6pUpnLqQTutWKAkWQS6hyn1O8xb5kP)

This tab is intended for specimens that will require special attention by the volunteers who rehouse the type specimens. 

1. `Condition Status` : choose 'The object is fragile and requires treatment' if specimen is oversized and will require a special mount.

## Bibliography

Using the Bibliography module is typically only required when a catalogue record needs an additional entry to the `Publication` nested table. The easiest way to enter the Bibliography module to accomplish this is by clicking the plus sign button to the very right of the table. 

This IMLS bibliography workflow was adapted from the [Bibliography](https://lacmip.github.io/emu/documentation/bibliography/) page of the LACMIP EMu Handbook. Please consult this reference for an expanded explanation of the module. 

### Creating a bibliography record

This tab is where the bulk of the bibliographic information will need to be recorded. Please refer to the [Bibliography](https://lacmip.github.io/emu/documentation/bibliography/) page of the LACMIP EMu Handbook for a detailed list of fields and their definitions. 

**Below is list of required fields:**

If journal article: 

- `Title`
- `Journal`

If book: 

- `Book Title`

For all publication types: 

- `Author`
- `Pages` 
- `Year`

**Below is a list of required fields, if information is available**:

- `Year Letter`
- `Volume`
- `Publ. No.`
- `Series`
- `Editor`
- `DOI`

### Attaching a bibliography record

After a record is completed, click the `Attach to record` button (see below) in the top right of the application window in the tool bar. 

![image-20210314132842902](/Users/macbook/Library/Application Support/typora-user-images/image-20210314132842902.png)

Once attached, the bibliography record should show as an entry in the `Publication` table. 

### Adding PDFs to Google Drive

If a PDF of the publication is available for download, please include it in the [Type Publications](https://drive.google.com/drive/folders/1Ej6RF7llwTXr4qvrzZv9XuWY222T1Ahy?usp=sharing) directory of the `IMLS` Google Drive. If you do not have access to the linked Google Drive directory, please ask for access. 

#### Formatting PDF filenames

It is imperative that PDF filenames conform to the convention applied to the other PDF files in the `Type Publications` directory. These PDFs will eventually be uploaded as multimedia attachments to their associated EMu record. Incorrect formatting can cause errors when they are uploaded. 

**Single author**
```
[Surname], [First initial]. [Middle initial]. ([Year]) [Title]
```
**Two authors**
```
[Surname], [First initial]. [Middle initial]. & [Surname], [First initial]. [Middle initial]. ([Year]) [Title]
```
**Three to four authors**
```
[Last name], [First initial]. [Middle initial]., [Last name], [First initial]. [Middle initial] and [Last name], [First initial]. [Middle initial]. ([Year]) [Title]
```
**Five or more authors**
```
[Last name], [First initial]. [Middle initial]., et al ([Year]) [Title]
```
**Example**:
> Valentich-Scott, P., Powell, C., L., Lorenson, T. D. & Edwards, B. E. (2014) A new genus and species of Thyasiridae (Mollusca, Bivalvia) from deep-water, Beaufort Sea, northern Alaska.pdf

## Appendix

### Institutional Numbers

Institutional numbers are the old identifiers used by previous institutions/collections. They are added in the `Identification` tab in the `Invert Paleo` tab. 

There are both institutional locality and catalogue numbers. **Only catalogue numbers are added to the Indentification tab**. To verify that you have the correct number is by opening the locality record attached to the catalog record (clicking the blue button next to the `Locality` field). If you see your number under the `Institution Number` nested table, you have a locality number. 

#### Frequently encountered institution numbers

| Institution Code | Locality sticker color | Catalogue sticker               |
| ---------------- | ---------------------- | ------------------------------- |
| UCLA             | Green                  | White rectangular handwritten sticker |
| CIT              | Gold                   | -                               |
| CSUN             | Red                    | -                               |
| USGS             | -                      | On label                        |
| SDSU             | Red (painted)          | -                             |
| Collector Number | Unique | Unique |

##### UCLA

<ins>Institution catalogue number</ins>: The institution catalogue number will be written on a **white rectangular** label glued onto the specimen. 

<ins>Institution locality number</ins>: found on a circular **green** sticker on specimen. 

<img src="https://lh6.googleusercontent.com/-5BBn2wceTEZzl_aDvQa2pmIL6Ak27rn41O2ZNIoYJMrlbx5PQ1R7FjQEGzgH8qM9TWkCicd9p3BuwoNqpORuB8q7IWpnejfHdgSnfcenVtpKr_2AOwYdmzdJq7qBdruqdawK5xK" width="400"/> <img src="https://lh6.googleusercontent.com/3OBzjamYzWe22sbhoSnQuEgI8vPXsoYusZIvIyV1B69YC6XJKF_AOMDwFTRiVgyk3Bo9xPT29fAOC-kQKG6IMkETYf7r2aGSXGDFJvIFkgfoN7UVdwTbJSGPXa1FGGnQo4cyOaLQ" alt="photo of specimen label with UCLA locality number" width="200"/>



##### CIT

<ins>Institution catalogue number</ins>: typically CIT specimens do not have an associated CIT catalogue number. 

<ins>Institution locality number</ins>: found on a circular **gold** sticker on specimen. 

<img src="https://lh4.googleusercontent.com/e1-bZp2MdcMll3pBBELgRSyfRMc-r8amGX3AXZ0IH3fyIgFz1abz0AAgnXmJKDtWZJj3CSH5sclnZmXL4xxsvrAowKKEBl1T-LltMpvXenCheW2kTu62ck3xiGhKIYWvln-k_k9P" width="300"/>

##### CSUN

<ins>Institution catalogue number</ins>: typically CSUN specimens do not have an associated CSUN catalogue number. 

<ins>Institution locality number</ins>: found on a circular **gold** sticker on specimen. 

### Type color codes

Type specimens in the collection will either have painted numbers or typed labels with font colors correspondig to the kind of type specimen it is. Below is reference to the three colors of type numbers in the collection.

| Type             | Color  |
| ---------------- | ------ |
| Holotype/Syntype | Red    |
| Paratype         | Yellow |
| Hypotype/Figured | Blue   |

### Finding publications

Addind publications to a type catalogue record is the most critical part of cataloging for the IMLS project. When searching or publications it can be useful to check the resources listed below. They are listed in the order of general purpose to more specific. 

1. [Google Scholar](https://scholar.google.com/)

2. [IMLS Type Publications folder](https://drive.google.com/drive/folders/1Ej6RF7llwTXr4qvrzZv9XuWY222T1Ahy?usp=sharing)

3. [Biodiversity Heritage Library](https://www.biodiversitylibrary.org/)

4. [PBDB](https://paleobiodb.org/#/)