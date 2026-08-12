<div align="center">

# BOF Studios

**Desktop software that works without an account.**

Three apps. None of them ask you to sign up, none of them phone home, and each
one does the thing it does on your own machine.

</div>

---

### [Parley Agent](https://github.com/BofStudios/parley-agent) · a messenger for AI coworkers

You write who a bot **is** — a name, a face, a personality. The router decides
which model runs it, per message, so a bot you write today keeps working after
the model behind it is retired.

Address a message to one bot or to several. A group thread is a real group: each
participant answers in turn, having read what its colleagues just said. Fifty-two
coworkers ship with it, across seven departments; rename them, retune them, or
start from nothing.

Bring an API key, or point it at a local Ollama and pay nothing at all.

`Tauri` `TypeScript` · macOS · Windows

---

### [Terrafeed](https://github.com/BofStudios/terrafeed) · the world on one map

Twelve live layers — earthquakes, hazards, humanitarian alerts, severe weather,
news from 31 regional desks, military aviation, vessels, satellites, markets —
drawn on a single offline dark map.

Alerting waits for independent sources to agree before it interrupts you: one
outlet repeating itself is not corroboration. The basemap is bundled geometry,
not tiles, so there is no map account and no tile server between you and the
world.

Every layer works with no API key.

`Tauri` `TypeScript` · macOS · Windows · Linux

---

### [Sherlock](https://github.com/BofStudios/sherlock) · face-first OSINT

Recognises faces offline against a built-in Wikipedia/Wikidata index, then
resolves them to verified social accounts. No account, no API key, no credits.

Every match shows its descriptor distance, so you judge the confidence rather
than trusting a label. That is deliberate: an early build called a private
individual a head of state, and the fix was to stop hiding the number.

`Electron` `Next.js` · macOS · Windows

---

<div align="center">

**Everything here is MIT licensed and builds from source.**

The desktop builds are unsigned — a code-signing certificate costs money these
projects do not make. macOS will call an unsigned app "damaged"; it isn't, and
each repo's install guide says exactly what to run. Or build it yourself: the
source is all there, and the same commands CI uses are in every README.

</div>
