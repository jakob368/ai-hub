# What does AI actually cost, and how to stay in control

*Draft blog post for the Microsoft AI hub. English version first, Swedish version below. Tone: thought-leadership, but human. Note: the quote attributed to Rasmus is a suggested placeholder, confirm the wording with him before publishing.*

---

Buying AI has never been easier. Understanding what it actually costs you has never been harder.

In just two years, the price of AI has fallen dramatically; Gartner expects the cost of running a large model to drop by around 90% by 2030. Over those same two years, the average enterprise AI budget has climbed from about $1.2M in 2024 to roughly $7M in 2026. Cheaper per unit, far more expensive overall, at the same time.

And before that becomes a reason to slow down, it shouldn't be. AI is delivering real value, and the companies pulling ahead are using more of it, not less. What sets them apart isn't appetite. It's control.

## The token cost illusion

Price and bill move in opposite directions for a simple reason: usage is growing faster than price is falling.

The first wave of AI was assistants. Someone asks Copilot to summarise an email. The next wave is agents that run whole workflows on their own, and those consume far more. Gartner reckons an agentic task can use 5 to 30 times more tokens than a simple chatbot. One team tweaks a prompt, another adds an always-on monitoring agent, usage climbs, and the falling unit price never reaches the bottom line.

So waiting for prices to drop won't get you more value from AI. Using it deliberately, with control, will.

## Where the cost hides

The bigger problem isn't the size of the bill. It's that much of the cost is hard to even see. As Microsoft moves from flat per-user licences to consumption pricing, the cost scatters:

- **Copilot licences no one uses.** A large share of Microsoft 365 Copilot seats typically go unused. At around €28 a seat per month, that's money paid and never touched.
- **AI billed as capacity in Fabric.** Copilot in Fabric and Power BI is billed as capacity units, not as an "AI" line. So it doesn't arrive as a cost. It arrives as a support ticket: "the BI is slow again."
- **Variable token cost in Azure.** Foundry and Azure OpenAI charge per token. One prompt change can double consumption overnight, and the meters multiply across services and regions.
- **No single dashboard.** Microsoft now meters AI in many places (Copilot Credits, agent-hours, tokens, capacity units), so costs land in different budgets and rarely get reconciled.

The result is an invoice that's hard to read and harder to predict. Finance sees no "AI" cost. IT sees a performance issue. Nobody connects the two.

## Everyone's investing. The winners are in control.

This isn't niche. Gartner puts global generative-AI spend at around €644bn in 2025, up roughly 76% in a year. Yet BCG finds about 60% of companies get no material value from their AI, and McKinsey sees only a small group capturing value at scale.

The pattern is consistent: the technology works, and the value lands with the organisations that run AI deliberately and keep its cost under control. Control isn't the brake. It's what lets the leaders keep saying yes to the next AI project, because they can see what each one costs and what it gives back.

As Rasmus Spendrup, one of our Public Cloud advisors, puts it: *"The problem is rarely that AI is too expensive. It's that no one owns the bill."*

## How to stay in control (and use more AI)

You don't need a huge programme. A few habits go a long way, and each one makes it easier, not harder, to do more with AI:

1. **Make it visible.** Map where AI cost actually lands across Copilot, Fabric, Foundry and Azure OpenAI, so there are no surprises.
2. **Give it an owner.** When someone owns the bill, alerts and right-sizing happen, and new requests get a clear yes or no.
3. **Right-size what you already pay for.** Reclaim unused Copilot licences and put them where they'll be used. Freed budget funds the next idea.
4. **Make the variable predictable.** Use surge protection in Fabric and reserved capacity (PTU) for steady Azure workloads.
5. **Build cost control in, not on.** Budgets, alerts, anomaly detection, a regular review. The same things you already do for the rest of the cloud.

Done well, this isn't penny-pinching. It's what gives you the confidence to scale.

## In short

AI is getting cheaper per unit and more expensive overall, at the same time. No wonder the invoice is confusing. And it isn't your fault that the cost is hard to see, the pricing genuinely shifted under everyone's feet.

The companies that win aren't the most cautious or the most reckless. They're the ones in control: they can see what AI costs, who owns it, and where it's leaking, so they can keep investing where it pays off.

That's where a good partner earns their place. At NetNordic we'd like to be your best companion for Microsoft AI: helping you find the hidden costs, get the right governance in place, and free up budget, so you can use more AI, with confidence. [Learn more about Microsoft Azure Optimization →](https://netnordic.se/kampanj/microsoft-azure-optimization/)

**Sources** (verify each opens before publishing, vendors occasionally move pages):

- [Gartner — Worldwide GenAI spending to reach $644bn in 2025 (+76%)](https://www.gartner.com/en/newsroom/press-releases/2025-03-31-gartner-forecasts-worldwide-genai-spending-to-reach-644-billion-in-2025)
- [Gartner — Inference cost to fall over 90% by 2030](https://www.gartner.com/en/newsroom/press-releases/2026-03-25-gartner-predicts-that-by-2030-performing-inference-on-an-llm-with-1-trillion-parameters-will-cost-genai-providers-over-90-percent-less-than-in-2025)
- [The token cost illusion (per-token down, usage up) — Artefact](https://www.artefact.com/blog/is-ai-really-getting-cheaper-the-token-cost-illusion/) and [enterprise budgets $1.2M→$7M, agents 5–30× tokens — MindStudio](https://www.mindstudio.ai/blog/ai-token-cost-crisis-enterprise)
- [BCG — The widening AI value gap (~60% see no material value)](https://www.bcg.com/publications/2025/are-you-generating-value-from-ai-the-widening-gap)
- [McKinsey — The State of AI](https://www.mckinsey.com/capabilities/quantumblack/our-insights/the-state-of-ai)
- [IDC — Worldwide AI & GenAI spending outlook](https://www.idc.com/resource-center/blog/idcs-worldwide-ai-and-generative-ai-spending-industry-outlook/)
- [~64% of Copilot licences go unused — Peafowl IT](https://peafowlit.com/blog/copilot-licenses-go-unused-and-how-to-fix-adoption/)
- [24% idle cloud capacity (Sweden/EMEA, Insight) — IT-Branschen](https://itbranschen.com/sv/svenska-foretag-slosar-molnkapacitet-ai-insight/)

Figures are indicative industry benchmarks.

---
---

# Svensk version

# Vad kostar AI egentligen, och hur behåller du kontrollen?

Att köpa AI har aldrig varit enklare. Att förstå vad det faktiskt kostar har aldrig varit svårare.

På bara två år har priset på AI fallit dramatiskt; Gartner räknar med att kostnaden för att köra en stor modell sjunker omkring 90 % till 2030. Under samma två år har den genomsnittliga AI-budgeten klättrat från runt 1,2 MUSD 2024 till cirka 7 MUSD 2026. Billigare per enhet, betydligt dyrare totalt, samtidigt.

Och innan det blir ett skäl att bromsa, det borde det inte vara. AI skapar verkligt värde, och de som drar ifrån använder mer av det, inte mindre. Det som skiljer dem åt är inte aptit. Det är kontroll.

## Token-illusionen

Priset och notan rör sig åt olika håll av ett enkelt skäl: användningen växer snabbare än priset faller.

Första vågen av AI var assistenter. Någon ber Copilot sammanfatta ett mejl. Nästa våg är agenter som kör hela arbetsflöden på egen hand, och de drar betydligt mer. Gartner uppskattar att en agent-uppgift kan använda 5 till 30 gånger fler tokens än en enkel chatbot. Ett team justerar en prompt, ett annat lägger till en agent som övervakar dygnet runt, användningen klättrar, och det fallande enhetspriset når aldrig fram till sista raden.

Så att vänta på att priserna ska sjunka ger dig inte mer värde av AI. Att använda det medvetet, med kontroll, gör det.

## Var kostnaden göms

Det större problemet är inte hur stor notan är. Det är att mycket av kostnaden är svår att ens se. När Microsoft går från fasta per-användare-licenser till förbrukningspris sprids kostnaden ut:

- **Copilot-licenser som ingen använder.** En stor andel av Microsoft 365 Copilot-platserna ligger oftast oanvända. Vid runt 28 euro per plats och månad är det pengar man betalar och aldrig rör.
- **AI som debiteras som kapacitet i Fabric.** Copilot i Fabric och Power BI debiteras som kapacitetsenheter, inte som en "AI"-rad. Så den dyker inte upp som en kostnad. Den dyker upp som ett supportärende: "BI:n är seg igen."
- **Rörlig tokenkostnad i Azure.** Foundry och Azure OpenAI tar betalt per token. En enda promptändring kan dubbla förbrukningen över en natt, och mätarna mångfaldigas över tjänster och regioner.
- **Ingen samlad vy.** Microsoft mäter nu AI på många ställen (Copilot Credits, agent-timmar, tokens, kapacitetsenheter), så kostnaderna hamnar i olika budgetar och stäms sällan av.

Resultatet är en faktura som är svår att läsa och ännu svårare att förutse. Ekonomi ser ingen "AI"-kostnad. IT ser ett prestandaproblem. Ingen kopplar ihop de två.

## Alla investerar. Vinnarna har kontroll.

Det här är inget marginellt. Gartner uppskattar de globala utgifterna för generativ AI till omkring 644 mdr euro 2025, upp cirka 76 % på ett år. Ändå konstaterar BCG att ungefär 60 % av företagen inte får något materiellt värde av sin AI, och McKinsey ser bara en liten grupp som fångar värde i skala.

Mönstret är tydligt: tekniken fungerar, och värdet landar hos de organisationer som använder AI medvetet och håller kostnaden under kontroll. Kontroll är inte bromsen. Det är det som låter ledarna fortsätta säga ja till nästa AI-projekt, för att de kan se vad varje initiativ kostar och vad det ger tillbaka.

Som Rasmus Spendrup, en av våra rådgivare inom Public Cloud, brukar säga: *"Problemet är sällan att AI är för dyrt. Det är att ingen äger notan."*

## Så behåller du kontrollen (och använder mer AI)

Du behöver inget jätteprogram. Några vanor räcker långt, och var och en gör det lättare, inte svårare, att göra mer med AI:

1. **Gör den synlig.** Kartlägg var AI-kostnaden faktiskt landar över Copilot, Fabric, Foundry och Azure OpenAI, så slipper du överraskningar.
2. **Ge den en ägare.** När någon äger notan blir det larm och rätt-dimensionering, och nya önskemål får ett tydligt ja eller nej.
3. **Rätt-dimensionera det ni redan betalar för.** Ta tillbaka oanvända Copilot-licenser och lägg dem där de används. Frigjord budget finansierar nästa idé.
4. **Gör det rörliga förutsägbart.** Använd surge protection i Fabric och reserverad kapacitet (PTU) för jämna Azure-arbetslaster.
5. **Bygg in kostnadskontrollen, inte på.** Budgetar, larm, avvikelsedetektering, en regelbunden genomgång. Samma saker ni redan gör för resten av molnet.

Gjort rätt är det här inte att gneta. Det är det som ger er modet att skala.

## Kort sagt

AI blir billigare per enhet och dyrare totalt, samtidigt. Inte konstigt att fakturan förvirrar. Och det är inte ert fel att kostnaden är svår att se, prissättningen ändrades faktiskt under fötterna på alla.

Företagen som vinner är varken de mest försiktiga eller de mest vårdslösa. De är de som har kontroll: de ser vad AI kostar, vem som äger det och var det läcker, så att de kan fortsätta investera där det lönar sig.

Det är där en bra partner gör skillnad. På NetNordic vill vi gärna vara er bästa följeslagare för Microsoft AI: hjälpa er hitta de dolda kostnaderna, få rätt styrning på plats och frigöra budget, så att ni kan använda mer AI, med självförtroende. [Läs mer om Microsoft Azure Optimization →](https://netnordic.se/kampanj/microsoft-azure-optimization/)

**Källor** (kontrollera att varje länk öppnas före publicering, leverantörer flyttar ibland sidor):

- [Gartner — globala GenAI-utgifter når 644 mdr USD 2025 (+76 %)](https://www.gartner.com/en/newsroom/press-releases/2025-03-31-gartner-forecasts-worldwide-genai-spending-to-reach-644-billion-in-2025)
- [Gartner — inferenskostnad faller över 90 % till 2030](https://www.gartner.com/en/newsroom/press-releases/2026-03-25-gartner-predicts-that-by-2030-performing-inference-on-an-llm-with-1-trillion-parameters-will-cost-genai-providers-over-90-percent-less-than-in-2025)
- [Token-illusionen (pris per token ner, användning upp) — Artefact](https://www.artefact.com/blog/is-ai-really-getting-cheaper-the-token-cost-illusion/) och [budgetar 1,2→7 MUSD, agenter 5–30× tokens — MindStudio](https://www.mindstudio.ai/blog/ai-token-cost-crisis-enterprise)
- [BCG — det växande AI-värdegapet (~60 % får inget materiellt värde)](https://www.bcg.com/publications/2025/are-you-generating-value-from-ai-the-widening-gap)
- [McKinsey — The State of AI](https://www.mckinsey.com/capabilities/quantumblack/our-insights/the-state-of-ai)
- [IDC — global prognos för AI- och GenAI-utgifter](https://www.idc.com/resource-center/blog/idcs-worldwide-ai-and-generative-ai-spending-industry-outlook/)
- [~64 % av Copilot-licenserna används aldrig — Peafowl IT](https://peafowlit.com/blog/copilot-licenses-go-unused-and-how-to-fix-adoption/)
- [24 % outnyttjad molnkapacitet (Sverige/EMEA, Insight) — IT-Branschen](https://itbranschen.com/sv/svenska-foretag-slosar-molnkapacitet-ai-insight/)

Siffrorna är indikativa branschvärden.
