# coupery — design

the design source of truth for coupery cryptography corporation.
settled 2026-07-23. visual reference: `brand/board.html`.

## thesis

everything is being read.
cryptography decides what can be.
coupery accelerates cryptography.

ai strips privacy at scale and compounds cryptography at the same rate.
the machines reading everything can also secure it. coupery works the
second edge: products that are private, secure, and usable.

## name

- the company is **coupery**. legal form: coupery cryptography corporation.
- the wordmark is set in capitals. in running text the name is written
  plainly, lowercase, like any other word, with no camel case and no
  styling mid-sentence.
- the full corporate name appears only where the law or a document
  footer requires it, set in geist mono caps, letterspaced.

## color

```css
--black:    #000000;  /* the material */
--white:    #F4F4F4;  /* body text on screen */
--bright:   #FFFFFF;  /* wordmark, emphasis, paper in print */
--gray:     #8A8A8A;  /* secondary text */
--dim:      #757575;  /* metadata, furniture. the floor — see below. */
--hairline: #222222;  /* rules and borders */
--red:      #E5484D;  /* revocation only. see below. */
```

- black and white carry everything.
- contrast floor: all text meets wcag aa (4.5:1). `#757575` is the
  dimmest text allowed on black; `#767676` the lightest on white.
- red exists solely for revocation, compromise, and critical states,
  and it is used rarely so that it stays unmistakable.
- no other color is ever introduced, and there are no gradients.
- screens are black and printed things are white; there is no third mode.

## type

- **instrument sans 600, in capitals,** sets the wordmark and nothing
  else. tracking is -0.015em.
- the wordmark glows white, and nothing else glows:
  `text-shadow: 0 0 6px rgba(255,255,255,.55), 0 0 22px rgba(255,255,255,.35), 0 0 90px rgba(255,255,255,.18)`.
  three layers: a hot core, a halo, a wide wash. the glow is always
  pure white and appears only on the wordmark.
- **geist mono** sets everything that isn't the wordmark.
  - 300 — display, large sizes only
  - 400 — text
  - 500 — headings, emphasis
  - 600 — never used. if a line needs 600, rewrite the line.
- body text is 14px / 1.7. sections are hairline-ruled and follow
  man-page structure (`COUPERY(1)` header/footer furniture where it
  fits the artifact).

## mark

**there is no mark.**

sudo has no logo. the name, set correctly, is the identity.

- nothing is drawn: no icons, no glyphs, no devices.
- the wordmark is the word, with no lockups and no symbols beside it.
- slides carry no logos; the filename is the branding.
- where software forces a square (favicon, avatar): a black square
  bearing the wordmark's C. that is an accommodation.

## voice

- write complete, declarative sentences in lowercase with full stops.
- avoid exclamation points and adjectives you can't prove.
- claims are provable or they aren't made.
- primitives live in specs and code, never in marketing.
- errors state what happened and what to do. nothing hypes, nothing
  apologizes.

## source

- the html source opens with an ascii-art comment, placed at the top of
  the file before the html element. it carries the wordmark in block
  characters, the corporation line, the stanza, the contact address, and
  the modem sign-off (`+++ATH0` / `NO CARRIER`). nothing else.
- the comment uses box-drawing characters only; html comments cannot
  contain a double hyphen.
- the comment speaks in the page's voice. it does not address the
  reader, joke about being found, or recruit.

## documents

- reports and notes are numbered `ccc-YYYY-NNN`.
- printed/pdf artifacts are white with black text; the corporate name
  sets the footer in letterspaced mono caps.

## rejected — do not reintroduce

these were tried or considered and killed. they stay dead:

- color accents of any kind (a copper/verdigris system was rejected
  outright).
- brand storytelling: name etymology, craft metaphors, taglines like
  "secrets, kept."
- clever glyph marks: the y-as-key-exchange, `#`, block cursor,
  monogram hallmarks.
- terminal-cosplay wordmarks: lowercase mono, blinking cursors.
- pronunciation lore ("two syllables", ipa).
- primitive name-dropping (ed25519, secp256k1, frost, sha-256) in any
  marketing surface.
- "design, build, break" style audit-firm positioning. coupery is a
  product company.
- stacked declarative fragments as house rhythm ("the wordmark. nothing
  else, ever."). the voice writes complete sentences.
- unprovable superlatives ("the strongest tools ever"), aphoristic
  kickers ("scarcity is what makes it loud"), and em dashes as rhythm.
- self-referential winks at the reader ("you read the source. so do
  we."), in source comments or anywhere else.
