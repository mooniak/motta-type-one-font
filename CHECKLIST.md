# Motta Type One: shipping checklist

Status on 18 November 2026, after the move to the Mooniak pipeline (`dev` branch).
Maturity: **beta**, the font works for real text, but a few forms are still undrawn.
Tick items as they're done; keep this file current with each release.

## 1. Repository and pipeline

- [x] Repo `mooniak/motta-type-one-font`, public, from the Mooniak project template
- [x] Template synced to the latest (`mnik template-sync motta-type-one-font`)
- [x] `dev` branch is the working and default branch; `main` is release-only
- [x] `sources/config.yaml` builds static TTF + OTF + WOFF2 from the Glyphs package
- [x] Builds locally with `make build` and with `mnik build`
- [x] Full CI sequence passes locally: build, stamp, test, proof, manifest, pages
- [x] GitHub Actions build green on `dev`
- [x] GitHub Pages serves the proof site at https://src.mooniak.com/motta-type-one-font/
- [x] README badges (build, QA pass rate, release, licence) resolve
- [ ] First `canary` pre-release published by CI (happens on the first push to `dev`; check the Releases page)

## 2. Source

- [x] Converted from the 2020 FontForge UFO to `sources/MottaTypeOne.glyphspackage`
      (original UFO kept in git history, commit `6c9ec0e`)
- [x] Glyph names follow LankaGlyphset (`documentation/rename-map.tsv`)
- [x] Feature code builds (fixed a missing lookup and three misspelled glyph names)
- [x] FontForge GDEF removed; GDEF comes from glyph categories
- [x] Spacing vowel signs, anusvara, visarga, ya-sign are Mark/Spacing (keep their advance)
- [x] Nonspacing marks (i/ii/u/uu signs, virama) have zero advance
- [ ] Open the package in Glyphs 3 once and save it, so Glyphs writes its own formatting
      (it was written by a script); then rebuild and compare (`git diff` should be cosmetic)

## 3. Metadata

- [x] Family name `Motta Type One`, style Regular
- [x] Copyright `Copyright 2020 The Motta Type One Project Authors (https://github.com/mooniak/motta-type-one-font)`
- [x] Designer Damith Welikala, manufacturer mooniak, vendor ID `MNIK`
- [x] SIL OFL 1.1 licence + URL in the font; `OFL.txt` header matches
- [x] `fontpackage.json`: free tier, OFL-1.1, maturity beta; `mnik fp check` clean
- [x] `AUTHORS.txt`, `CONTRIBUTORS.txt`, `documentation/ARTICLE.en_us.html`
- [ ] Designer to confirm the description, credits and the year (2020)
- [ ] Add the designer's email/URL to `fontpackage.json` `designers` if they want it shown

## 4. Drawing (designer)

Glyphs that exist in the source but are **empty**. They are set to not export and the rules
that use them are commented out (`# DISABLED: output not drawn yet`). Draw them, set them to
export, and re-enable the rules in the feature code.

- [ ] `repha-sinh`, repaya (ර්‍ + consonant), rule in `sin_reph` / `rphf`. Highest priority:
      common in real text (ධර්ම, කර්ම); today it falls back to ර් + consonant
- [ ] `ghR-sinh` (gha + rakar + virama), `jh-sinh` (jha + virama), `ng-sinh` (nga + virama),
      rules in the virama lookups; today they fall back to letter + separate virama
- [ ] The 25 `ss01` touching da-forms (`daa._c-sinh` … `nyaae._c-sinh`). Once drawn, also
      re-enable the `ss01` feature (it's disabled in Font Info → Features) and give it a name

Other drawing items:

- [ ] Review the generated `dottedCircle` (geometric placeholder sized to the weight)
- [ ] Clean up the joins in `ddhIi-sinh`, `phIi-sinh`, `tThIi-sinh`, `thIi-sinh`, `tthIi-sinh`:
      retracted FontForge handles leave a zero-area contour after overlap removal
      (fontspector `outline_direction`)
- [ ] Look at fontspector's outline warnings (jaggy segments, colinear vectors, semi-vertical
      lines, overlapping segments) and fix the ones that are real
- [ ] Decide on `rasign-sinh` and `isign-sinh.alt3`: drawn but nothing uses them. Delete, or add rules
- [ ] Optional: candrabindu U+0D81 and Sinhala Lith digits U+0DE6–0DEF
- [ ] Optional: Latin. The font has no Latin letters, so it can't render its own name and fails
      the Google Fonts Latin coverage checks. Needed only for a Google Fonts submission

## 5. OpenType

- [x] akhn, vatu (rakar, yansaya), pstf, abvs, blws, psts all compile and shape
- [x] Added rules for seven drawn but unreachable conjuncts: fRI, fRIi, nDRI, nDRIi, ssRI,
      ssRIi, ndRa
- [x] `ss02` disabled: it was an exact copy of the rakar lookup, so it did nothing
- [x] Kerning built from the kerning data (one pair) into `dist`
- [ ] Mark positioning: there is no `mark`/`abvm`/`blwm`. The vowel signs are drawn in place and work
      on most consonants; check stacked and wide consonants in the proofs, and add anchors where
      a sign collides or floats
- [ ] Kerning: only one pair. Kern the common Sinhala pairs for display sizes
- [ ] Shaping review in the proof site's sections (conjuncts, rakar/yansaya, signs combinations)

## 6. QA (Fontspector, Google Fonts profile)

Latest local run: 4 FAIL, 16 WARN, 95 PASS (pass rate 79%). Was 14 FAIL before the port.

- [x] Vertical metrics: hhea = typo = win = 900/−300, `USE_TYPO_METRICS`, covers the bounding box
- [x] No-break space, dotted circle, name ID 9, copyright, licence
- [ ] Accepted for now (shared by the other Sinhala-only Mooniak fonts): `glyph_coverage`,
      `glyphsets/shape_languages`, `render_own_name` (all need Latin), and the GF
      repository-layout check
- [ ] Remaining WARNs to review: missing ₹ U+20B9, U+2028/2029 separators, no STAT/meta table
      (static font), the outline warnings above

## 7. Release

- [ ] Designer sign-off on the proofs at https://src.mooniak.com/motta-type-one-font/
- [ ] Tag a preview for testers: `v1.001-dev.1` on `dev`
- [ ] Bump the source version to 1.001 (`versionMinor = 1`) before the release
- [ ] Merge `dev` into `main` (no squash) and tag `v1.001` on `main`
- [ ] Set `maturity` to `stable` in `fontpackage.json` once section 4's repaya item is done
- [ ] Add display images to `fontpackage.json` `directory.display_images`
