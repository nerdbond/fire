<br/>
<br/>
<br/>
<br/>
<br/>
<br/>
<br/>

<p align='center'>
  <img src='https://github.com/termsurf/fire/blob/make/view/fire.gif?raw=true' height='256'>
</p>

<h3 align='center'>fire</h3>
<p align='center'>
  Recent Events of Public Importance
</p>

<br/>
<br/>
<br/>

## Hello

This is a public collection of recent events of public importance, so you can get a better sense of what's happening in the world without the excess stuff, and see it en masse.

These are displayed on [`fire.beat.surf`](https://fire.beat.surf) for now.

## Data Files

The files will be YAML files of the base data, so it can be captured in raw form. The files go into folder structures which is how the URL structure will be for the data on [`fire.beat.surf`](https://fire.beat.surf). The `link` property is relative to this folder path. This way sub collections can be built out of the raw data on the website.

### Event Files

Most of these fields are optional for events.

```yaml
- text: An event description
  link: /an-event
  date: Jan 1, 1970 - Jan 11, 1971
  view:
    - img.jpg
  cite:
    - https://example.source.com
  site:
    - A location
  term:
    - keyword
```

### Person Files

Most of these fields are optional.

```yaml
- text: A person description
  name: Person Name
  link: /a-person
  rise:
    date: Jan 1, 1970 # birthdate
    site: Birth location
  fall:
    date: Dec 31, 2010 # death date
    site: Death location
  view:
    - img.jpg
  cite:
    - https://example.source.com
  site:
    - A location
  term:
    - keyword
```

### Place Files

Most of these fields are optional.

```yaml
- text: A place description
  name: Place name
  link: /a-place
  rise:
    date: Jan 1, 1970 # birthdate
    site: Birth location
  fall:
    date: Dec 31, 2010 # death date
    site: Death location
  view:
    - img.jpg
  cite:
    - https://example.source.com
  site:
    - A location
  term:
    - keyword
```

## Content

### Positive Categories

- **protests** (peaceful protests and demonstrations)
- **love**
- **sharing**
- **open-mindedness**
- **education**
- **values**
- **awareness**
- **factchecking**

### Negative Categories

- **violence** (not extreme gory violence, but enough to get the picture
  across)
  - police-violence
  - individual-violence
  - group-violence
- **hate**
  - racism
  - anti-woman
  - anti-lgtbq+
  - anti-refugee
  - anti-immigrant
  - anti-man
- **lying**
  - political-lying
- **bias** (taking too hard of a stance without taking into account a
  full perspective)
  - us-anti-conservative-bias
  - us-anti-liberal-bias
  - discrimination (not necessarily hate, but an implicit bias
    undercutting someone)
  - bigotry
- **ignorance**
  - climate-change-denial
- **corruption**
  - cronyism
- **awareness**
  - climate-change
  - species-extinction
  - deforestation
  - pollution
- **misinformation** (stuff intending to deceive)
  - propaganda

### Decisions / Change

This section is decisions we as a society make to try and find peace and balance, or other less glorious reasons for making decisions.

## Contribute

If you have something recent, or have dug up something important in the past, please [open an issue or PR](https://github.com/termsurf/fire/issues) with a link to the content so we can add it to the collection. For a more detailed guide on one particular approach to contributing sort of like a journalist, see the [contributing guide](https://github.com/termsurf/fire/blob/make/contributing.md).

This is not a news site, but a place to aggregate important media so we can become more aware of how the world is functioning with today's complexities and problems.

## Other Resources

- [GeorgeFloyd Protest - police brutality videos on Twitter (Spreadsheet)](https://docs.google.com/spreadsheets/u/1/d/1YmZeSxpz52qT-10tkCjWOwOGkQqle7Wd1P7ZM1wMW0E/htmlview?pru=AAABcql6DI8#)
- [/t/hate_speech](https://www.reddit.com/t/hate_speech/)

## License

<p xmlns:dct="http://purl.org/dc/terms/" xmlns:vcard="http://www.w3.org/2001/vcard-rdf/3.0#">
  <a rel="license"
     href="http://creativecommons.org/publicdomain/zero/1.0/">
    <img src="http://i.creativecommons.org/p/zero/1.0/88x31.png" style="border-style: none;" alt="CC0" />
  </a>
  <br />
  <br />
  To the extent possible under law,
  <a rel="dct:publisher"
     href="https://github.com/termsurf">
    <span property="dct:title">TermSurf</span></a>
  has waived all copyright and related or neighboring rights to
  <span property="dct:title">fire</span>.
This work is published from the
<span property="vcard:Country" datatype="dct:ISO3166"
      content="US" about="https://github.com/termsurf">
  United States</span>.
</p>

## TermSurf

This is being organized by the folks at [TermSurf](https://term.surf), a California-based project for helping humanity master information and computation. Find us on [Twitter](https://twitter.com/_termsurf), [LinkedIn](https://www.linkedin.com/company/termsurf), and [Facebook](https://www.facebook.com/termsurf). Check out our other [GitHub projects](https://github.com/termsurf) as well!
