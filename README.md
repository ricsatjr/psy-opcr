<!--
Replacement for the "## Licensing" section of README.md.

Relative links resolve against the repository, so they work on GitHub and
in any clone. They assume the LICENCES -> LICENSES rename has landed; push
that first or the licence links 404.

One TODO is marked at the end.
-->

## Licensing

This repository holds three kinds of material under three kinds of terms.
The split is deliberate: the program carries a copyleft licence, the
interface files carry none at all, and transcribed government material is
not licensed here because nobody holds copyright in it.

| Path | Terms |
|---|---|
| [`opcr_tool.html`](opcr_tool.html) | [`GPL-3.0-or-later`](LICENSES/GPL-3.0-or-later.txt) |
| [`opcr_print.css`](opcr_print.css) | [`GPL-3.0-or-later`](LICENSES/GPL-3.0-or-later.txt) |
| [`opcr_schema.json`](opcr_schema.json), [`mov_schema.json`](mov_schema.json), [`opcr_layout.json`](opcr_layout.json) | [`CC0-1.0`](LICENSES/CC0-1.0.txt) |
| `examples/**` | [`CC0-1.0`](LICENSES/CC0-1.0.txt) |
| [`dost_strategic_plan_2023_2028.json`](dost_strategic_plan_2023_2028.json) | [Work of the Government of the Philippines](LICENSES/LicenseRef-PH-Gov-Work.txt) — see below |
| `*.md` | [`CC-BY-4.0`](LICENSES/CC-BY-4.0.txt) |

Full texts are in [`LICENSES/`](LICENSES). Per-path declarations for files
that cannot carry an inline SPDX header are in [`REUSE.toml`](REUSE.toml),
and `reuse lint` will confirm every file is accounted for.

### The schemas carry no conditions

[`opcr_schema.json`](opcr_schema.json), [`mov_schema.json`](mov_schema.json)
and [`opcr_layout.json`](opcr_layout.json) are released under
[CC0-1.0](LICENSES/CC0-1.0.txt), which is a dedication to the public domain
rather than a licence. **No condition of any kind attaches to data that
conforms to these schemas.** You may build your own tool against them,
change them, embed them in proprietary software, or ignore this repository
entirely. That is the intent: the format is more useful shared than owned.

The copyleft terms on [`opcr_tool.html`](opcr_tool.html) reach that file and
modifications of it. They do not reach your data, your schema variants, or a
separate implementation that happens to read the same keys.

### Embedded schemas inside the tool

[`opcr_tool.html`](opcr_tool.html) is a single self-contained file and may
inline copies of the schemas above as its bootstrap defaults. The file as a
whole is distributed under [GPL-3.0-or-later](LICENSES/GPL-3.0-or-later.txt),
but the inlined schema content remains separately available under
[CC0-1.0](LICENSES/CC0-1.0.txt) from the standalone `.json` files in this
repository. Take it from there if you want it unencumbered.

### Government material

[`dost_strategic_plan_2023_2028.json`](dost_strategic_plan_2023_2028.json) is
a transcription of DOST Administrative Order No. 017, s. 2023. Under Section
176.1 of the Intellectual Property Code of the Philippines
([Republic Act No. 8293](https://www.officialgazette.gov.ph/1997/06/06/republic-act-no-8293/)),
no copyright subsists in any work of the Government of the Philippines, and
no claim is made over it here. See
[`LICENSES/LicenseRef-PH-Gov-Work.txt`](LICENSES/LicenseRef-PH-Gov-Work.txt).

The same applies to the OPCR form itself. This tool reproduces the layout and
wording of an official form; the form is a government work, and the
structural encoding in [`opcr_schema.json`](opcr_schema.json) asserts nothing
over it.

### Provenance

This tool is personal work by the author, developed on the author's own time
and equipment and on the author's own initiative. It is not a deliverable of
any office or position the author holds, and no agency has commissioned,
funded or directed it. It is offered to the Philippine Science High School
System, and to anyone else, under the public terms above.

No real performance data belongs in this repository. Completed OPCR forms
contain institutional ratings, remarks and signatories; `examples/` contains
only synthetic or empty structures.

### Contributing

Contributions are welcome under the terms above. Sign off each commit with
`git commit -s`, certifying the
[Developer Certificate of Origin](https://developercertificate.org/).

The author retains sole copyright in order to keep the option of granting
separate terms to an adopting agency whose procurement or IT policy cannot
accommodate copyleft. By signing off, you agree your contribution may be
offered under such terms as well as under the licences above. If you would
rather it were not, say so in the pull request and it can stay out of any
separate grant.

### Separate terms

If [GPL-3.0](LICENSES/GPL-3.0-or-later.txt) does not fit your situation — an
agency integration, a redistribution that cannot carry copyleft — ask.
Separate permissive terms can be granted for the asking; the public licence
exists to keep the work open, not to obstruct its use.

<!-- TODO: decide whether to publish a contact address in the "Separate
     terms" section, or leave it to GitHub issues. -->
