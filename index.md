---
title: Zásady ochrany osobních údajů – MeteoMIX
lang: cs
---

# Zásady ochrany osobních údajů – MeteoMIX

*English version below.*

- Platné od: 8. 10. 2026
- Provozovatel aplikace: Roman Macek
- Kontakt: meteomix.app@gmail.com

## Stručně

MeteoMIX nemá uživatelské účty, reklamy ani sledování a provozovatel
nepoužívá žádnou analytiku. Provozovatel
nemá žádný vlastní server: žádná vaše data k němu neputují a nic
o vás neuchovává. Aby aplikace mohla ukázat počasí pro dané místo, posílá jeho
souřadnice veřejným meteorologickým službám uvedeným níže.

## Poloha

Pokud aplikaci povolíte přístup k poloze, zjistí ji přes služby Google Play
(přesně nebo přibližně, podle toho, jaké oprávnění udělíte). Polohu můžete
odepřít; aplikace pak funguje s místy, která si vyhledáte a uložíte ručně.

Souřadnice aktuální polohy i uložených míst aplikace posílá těmto službám, aby
pro dané místo získala data:

| Služba | K čemu | Zásady ochrany soukromí |
|---|---|---|
| MET Norway (api.met.no) | předpověď počasí; souřadnice zaokrouhlené na ~11 m | [met.no/om-oss/personvern](https://www.met.no/om-oss/personvern) |
| Český hydrometeorologický ústav (chmi.cz) | předpověď ALADIN (výstrahy a údaje meteostanic se stahují za celé Česko a vybírají v zařízení) | [chmi.cz – povinně zveřejňované informace](https://www.chmi.cz/o-chmu/povinne-zverejnovane-informace-chmu) |
| Bright Sky (api.brightsky.dev) | předpověď DWD MOSMIX | [brightsky.dev](https://brightsky.dev/) |
| Google (geokodér systému Android) | název místa podle aktuální polohy (např. „Brno-Bohunice") | [policies.google.com/privacy](https://policies.google.com/privacy) |

Pokud zapnete upozornění na výstrahy, aplikace zhruba každých 30 minut na
pozadí stáhne od ČHMÚ celostátní seznam výstrah a s aktuální polohou
a uloženými místy ho porovná přímo v zařízení. Souřadnice ČHMÚ posílá jen
výjimečně, když místo v Česku nejde přiřadit k žádnému správnímu obvodu
(například těsně u hranice). Místa v zahraničí se nekontrolují.

Mapy radaru a výstrah načítají podkladové dlaždice z OpenStreetMap
(tile.openstreetmap.org); server se tak dozví, kterou oblast mapy si
prohlížíte. Zásady: [OSM Foundation – Privacy Policy](https://osmfoundation.org/wiki/Privacy_Policy).

Tyto služby provozují jiné subjekty a s daty zacházejí podle svých vlastních
zásad. Jako každý server vidí také IP adresu vašeho zařízení a označení
aplikace v požadavku.

## Co zůstává jen v zařízení

- **Vyhledávání míst** probíhá v databázi uložené přímo v aplikaci; hledaný
  text se nikam neodesílá.
- **Uložená místa, nedávno hledaná místa a nastavení** jsou uložená jen
  v zařízení. Pokud máte zapnuté zálohování Androidu, mohou být součástí
  šifrované zálohy vašeho účtu Google.
- **Překlad** textů ČHMÚ do angličtiny probíhá v zařízení (Google ML Kit).
  Jazykový model se jednorázově stáhne od Googlu, překládaný text zařízení
  neopouští. Překládá se jen tehdy, když aplikace neběží česky; knihovna ML Kit
  přitom posílá Googlu diagnostické údaje: výrobce a model zařízení, verzi
  Androidu a aplikace, identifikátor instalace, dobu a výsledek překladu
  a zvolenou dvojici jazyků. Google je používá k diagnostice a statistice
  používání ([zásady Googlu](https://policies.google.com/privacy)).
- **Upozornění** se vytvářejí přímo v zařízení.

## Kontakt z aplikace

Tlačítko „Napsat vývojáři / nahlásit chybu" v Nastavení otevře vaši
e-mailovou aplikaci s předvyplněnou zprávou. Pod místem pro váš text jsou
uvedené údaje užitečné pro řešení chyb: verze aplikace, verze Androidu, model
telefonu a jazyk. Zprávu před odesláním vidíte a můžete upravit; odesíláte ji
sami a jen tehdy, když chcete. E-maily slouží jen k odpovědi a řešení
nahlášeného problému.

Provozovatel žádná data neprodává ani nesdílí pro reklamu.

## Vaše možnosti

- Přístup k poloze a k upozorněním můžete kdykoli odebrat v nastavení
  Androidu.
- Všechna data aplikace smažete odinstalací aplikace nebo vymazáním jejích
  dat v nastavení Androidu. U provozovatele žádná data uložená nejsou, takže
  není co mazat jinde.

## Děti

Aplikace není určena přímo dětem a vědomě od nich nesbírá žádné údaje.

## Změny

Případné změny těchto zásad budou zveřejněny na této stránce s novým datem
platnosti. S dotazy se obracejte na meteomix.app@gmail.com.

---

# Privacy Policy – MeteoMIX

- Effective from: 8 October 2026
- App provider: Roman Macek
- Contact: meteomix.app@gmail.com

## In short

MeteoMIX has no user accounts, ads or tracking, and the provider uses no
analytics. The provider runs no
server of their own: none of your data reaches them, and they keep nothing
about you. To show the weather for a place, the app sends that place's
coordinates to the public weather services listed below.

## Location

If you allow location access, the app gets your position through Google Play
services (precise or approximate, depending on the permission you grant). You
can refuse; the app then works with places you search for and save yourself.

The coordinates of your current position and of your saved places are sent to
these services to fetch data for them:

| Service | Used for | Privacy policy |
|---|---|---|
| MET Norway (api.met.no) | weather forecast; coordinates rounded to ~11 m | [met.no/om-oss/personvern](https://www.met.no/om-oss/personvern) |
| Czech Hydrometeorological Institute (chmi.cz) | ALADIN forecast (warnings and station readings are downloaded for all of Czechia and picked on the device) | [chmi.cz – mandatory disclosures](https://www.chmi.cz/o-chmu/povinne-zverejnovane-informace-chmu) |
| Bright Sky (api.brightsky.dev) | DWD MOSMIX forecast | [brightsky.dev](https://brightsky.dev/) |
| Google (Android's geocoder) | the place name for your position, e.g. "Brno-Bohunice" | [policies.google.com/privacy](https://policies.google.com/privacy) |

If you turn on warning notifications, the app downloads ČHMÚ's nationwide
list of warnings in the background, about every 30 minutes, and matches it
against your current position and saved places on the device. Coordinates
are sent to ČHMÚ only in the rare case that a place in Czechia cannot be
matched to any district (right at the border, for example). Places abroad
are not checked.

The radar and warnings maps load their base map tiles from OpenStreetMap
(tile.openstreetmap.org), so that server learns which area of the map you are
looking at. Policy: [OSM Foundation – Privacy Policy](https://osmfoundation.org/wiki/Privacy_Policy).

These services are run by other organisations and handle data under their own
policies. Like any server, they also see your device's IP address and the
app's name in the request.

## What stays on your device

- **Place search** runs against a database built into the app; what you type
  is not sent anywhere.
- **Saved places, recent searches and settings** are stored only on your
  device. If Android backup is on, they may be included in your Google
  account's encrypted backup.
- **Translation** of ČHMÚ's texts into English happens on the device (Google
  ML Kit). The language model is downloaded from Google once; the text being
  translated never leaves the device. Translation runs only when the app is
  not in Czech; while it does, ML Kit sends Google diagnostic data: device
  manufacturer and model, Android and app version, an installation
  identifier, how long translation took and whether it succeeded, and the
  language pair. Google uses it for diagnostics and usage statistics
  ([Google's privacy policy](https://policies.google.com/privacy)).
- **Notifications** are created on the device.

## Contacting the developer

The "Contact the developer / report a bug" button in Settings opens your
e-mail app with a pre-filled message. Below the space for your own text it
lists details that help with fixing bugs: app version, Android version, phone
model and language. You see the message before it is sent and can edit it;
you send it yourself, and only if you choose to. E-mails are used only to
reply and to deal with the problem reported.

The provider does not sell any data or share it for advertising.

## Your choices

- You can revoke location and notification access at any time in Android's
  settings.
- Uninstalling the app, or clearing its data in Android's settings, deletes
  everything it stores. The provider holds no data, so there is nothing to
  delete anywhere else.

## Children

The app is not directed at children and does not knowingly collect data from
them.

## Changes

Any changes to this policy will be published on this page with a new
effective date. Questions: meteomix.app@gmail.com.
