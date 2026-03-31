# 4.3 Website / Webshop

### 4.3.1 Kurzbeschreibung des Prozesses

Die Website / Webshop umfasst den öffentlich zugänglichen Webshop sowie die zugehörige Hosting‑Infrastruktur (Webserver, Datenbank, DNS). Sie dient der Präsentation des Sortiments, der Bestellabwicklung und der Kundeninteraktion.

### 4.3.2 Ablauf (vereinfacht)

1. Nutzer rufen Website / Webshop auf (DNS → Hosting → Webserver).
2. Lade Produktkatalog, Bilder, Preise.
3. Interaktion: Warenkorb, Login, Checkout.
4. Dynamische Inhalte aus Datenbank (Produkte, Bestellstatus).

### 4.3.3 Risiken & Bewertung

<div class="joplin-table-wrapper"><table data-table-width="760" data-layout="default" data-local-id="a85b141b5d45" class="confluenceTable"><colgroup><col style="width: 68.0px;"><col style="width: 347.0px;"><col style="width: 160.0px;"><col style="width: 181.0px;"></colgroup><tbody><tr data-local-id="bf1d6077525f"><th data-local-id="5c42995bb54b" class="confluenceTh"><p local-id="124f70e09da4">Risiko-ID</p></th><th data-local-id="c45208bc4ea3" class="confluenceTh"><p local-id="fa01f301dc81">Beschreibung</p></th><th data-local-id="42a2173b64ed" class="confluenceTh"><p local-id="bb85f2d046d0">Wahrscheinlichkeit (1–5)</p></th><th data-local-id="826c6a42b06d" class="confluenceTh"><p local-id="19c2c69b841f">Auswirkungsschwere (1–5)</p></th></tr><tr data-local-id="45bf928c0527"><td data-local-id="ec71de7922a3" class="confluenceTd"><p local-id="f6d53ae14a8b">R8</p></td><td data-local-id="44aa527da5bb" class="confluenceTd"><p local-id="c2654432c6f6">DDoS‑Attacke auf Webshop</p><div id="expander-1232406447" class="expand-container conf-macro output-block" data-hasbody="true" data-macro-name="expand" data-macro-id="68e4361c-2652-4939-9828-17d472ecffe5" data-local-id="7f1f32ecb96b"><div id="expander-control-1232406447" class="expand-control"><span class="expand-control-icon icon">&nbsp;</span><span class="expand-control-text">Ursache/Auswirkung/best. Maßnahmen</span></div><div id="expander-content-1232406447" class="expand-content expand-hidden"><ul local-id="81416b8b-505a-4573-b9ef-31f2610e88e3"><li local-id="27dedc67-fdd0-4672-845d-310c132ddebc"><p local-id="086abe49a335"><strong>Ursache:</strong> Angriffe von Bots oder Konkurrenz, fehlende DDoS‑Schutzmaßnahmen.</p></li><li local-id="8621c352-75d1-47f5-b635-936173213e48"><p local-id="251ad46e8c30"><strong>Auswirkung:</strong> Webshop nicht erreichbar, Umsatzverlust, Panik bei Kunden.</p></li><li local-id="c7366bfe-705c-4616-9e1e-a979dae37a9c"><p local-id="88e4aa9bfd41"><strong>Bestehende Maßnahmen:</strong> Cloudflare oder Hoster mit DDoS‑Mitigation, Rate‑Limiting.</p></li></ul></div></div></td><td data-local-id="f8eaf3a54a38" class="confluenceTd"><p local-id="0fa43c781ecd">3</p></td><td data-local-id="b481873056a8" class="confluenceTd"><p local-id="e9807cebcd81">5</p></td></tr><tr data-local-id="b31d5ac91e1f"><td data-local-id="e3482a46f007" class="confluenceTd"><p local-id="e942359b4d96">R9</p></td><td data-local-id="a7ac3636f3f5" class="confluenceTd"><p local-id="09189d236ba4">Website‑Defacement (Vandalismus)</p><div id="expander-808385055" class="expand-container conf-macro output-block" data-hasbody="true" data-macro-name="expand" data-macro-id="ff01ff19-47f8-483b-8fe2-90b4e60ce60c" data-local-id="1418377b9beb"><div id="expander-control-808385055" class="expand-control"><span class="expand-control-icon icon">&nbsp;</span><span class="expand-control-text">Ursache/Auswirkung/best. Maßnahmen</span></div><div id="expander-content-808385055" class="expand-content expand-hidden"><ul local-id="396357a2-99cb-4e4a-919d-457ff9f9b04f"><li local-id="038ab57c-46b6-47bf-b0e5-4822989a7072"><p local-id="163623ab324f"><strong>Ursache:</strong> Schwachstellen im CMS, unsichere Admin‑Accounts, fehlende Patches.</p></li><li local-id="e0d3de88-4d2d-4840-93cf-23176f60dfff"><p local-id="99172bbeb625"><strong>Auswirkung:</strong> Vertrauensverlust, Image‑Schaden, rechtliche Risiken.</p></li><li local-id="db39d625-908b-4338-953e-0c5eda11a83e"><p local-id="5652b2442c15"><strong>Bestehende Maßnahmen:</strong> Regelmäßige Updates, WAF (Web Application Firewall), File‑Integrity‑Monitoring.</p></li></ul></div></div></td><td data-local-id="de84266fcfa5" class="confluenceTd"><p local-id="a03282d047c0">2</p></td><td data-local-id="335b3fe8569a" class="confluenceTd"><p local-id="3c752cb8c7d3">5</p></td></tr><tr data-local-id="416683367fba"><td data-local-id="e1ef28488229" class="confluenceTd"><p local-id="28107552843d">R10</p></td><td data-local-id="0d0ed8d84bd8" class="confluenceTd"><p local-id="029483200b0b">SSL/TLS‑Zertifikat abgelaufen</p><div id="expander-1347356700" class="expand-container conf-macro output-block" data-hasbody="true" data-macro-name="expand" data-macro-id="a363f13b-469a-4c2b-9184-e5cd4a7c0e42" data-local-id="8c363695a3e2"><div id="expander-control-1347356700" class="expand-control"><span class="expand-control-icon icon">&nbsp;</span><span class="expand-control-text">Ursache/Auswirkung/best. Maßnahmen</span></div><div id="expander-content-1347356700" class="expand-content expand-hidden"><ul local-id="4f816aaf-516a-4c13-ab55-fb692d4ebc94"><li local-id="44b4b198-4251-49a3-bb30-de3a1bba6ee6"><p local-id="7c6bebdaacf2"><strong>Ursache:</strong> Vergessen der automatischen Erneuerung, manuelle Fehler.</p></li><li local-id="aea030e9-9f3d-4179-8c63-088a078d1820"><p local-id="05866efe1a15"><strong>Auswirkung:</strong> Browser warnen vor unsicherer Verbindung, Kundenabwanderung.</p></li><li local-id="5e4bd522-7703-4ff8-9aac-1081dd4e9b1f"><p local-id="b74ed3634fac"><strong>Bestehende Maßnahmen:</strong> Automatische Zertifikats‑Erneuerung (Let's Encrypt), Monitoring.</p></li></ul></div></div></td><td data-local-id="6661586d526e" class="confluenceTd"><p local-id="e8a34c09f3d0">1</p></td><td data-local-id="eeccb0d2544b" class="confluenceTd"><p local-id="53b69eaf1dbd">4</p></td></tr></tbody></table></div>

### 4.3.4 Visualisierte Risikomatrix

```mermaid
flowchart LR
    classDef axis fill:#f0f0f0,stroke:#000,color:#000;
    classDef low fill:#d0f0d0,stroke:#000,color:#000;
    classDef medium fill:#fff0c0,stroke:#000,color:#000;
    classDef high fill:#f06060,stroke:#000,color:#000;

    %% Y-Achse (Wahrscheinlichkeit)
    Y3["Hoch"]:::axis
    Y2["Mittel"]:::axis
    Y1["Niedrig"]:::axis

    %% X-Achse (Auswirkung)
    H0["Eintrittswahrscheinlichkeit (Y) / Auswirkung (X)"]:::axis
    H0 --- X1["Gering"]:::axis --- X2["Mittel"]:::axis --- X3["Hoch"]:::axis

    %% Zeile Niedrig (Wahrscheinlichkeit niedrig)
    Y1 --- R11["R10"]:::medium --- R12["R9"]:::medium --- R13[" "]:::medium

    %% Zeile Mittel (Wahrscheinlichkeit mittel)
    Y2 --- R21[" "]:::low --- R22[" "]:::medium --- R23["R8"]:::high

    %% Zeile Hoch (Wahrscheinlichkeit hoch)
    Y3 --- R31[" "]:::medium --- R32[" "]:::high --- R33[" "]:::high
```