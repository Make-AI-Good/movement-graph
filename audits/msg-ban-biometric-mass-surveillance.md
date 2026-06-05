---
entity_id: msg-ban-biometric-mass-surveillance
entity_hash: 9dc186b05e0f4f52db0efe033d256ea936f6f458
audit_date: 2026-06-04
pass: 1
status: unverifiable
claims_total: 15
claims_verified: 11
claims_discrepancy: 0
claims_unverifiable: 4
sources_consulted:
  - https://reclaimyourface.eu/
  - https://reclaimyourface.eu/goodbye-eci-hello-ai-act-negotiations/
  - https://edri.org/our-work/reclaim-your-face-biometric-surveillance/
  - https://www.accessnow.org/press-release/reclaim-your-face/
  - https://algorithmwatch.org/en/reclaim-your-face-campaign/
  - https://edri.org/our-work/edri-joins-178-organisations-in-global-call-to-ban-biometric-surveillance/
  - https://algorithmwatch.org/en/eu-artificial-intelligence-act-for-fundamental-rights/
  - https://edri.org/our-work/civil-society-statement-eu-protect-peoples-rights-in-the-ai-act-trilogue-negotiations/
  - https://bigbrotherwatch.org.uk/press-releases/65-parliamentarians-call-for-immediate-stop-to-live-facial-recognition-surveillance/
  - https://en.wikipedia.org/wiki/European_Digital_Rights
---

## Claim 1: "Reclaim our public space. Ban biometric mass surveillance!" (the verbatim slogan)

Source: https://reclaimyourface.eu/
Source content: "Reclaim our public space. Ban biometric mass surveillance!"
Comparison: Body slogan exactly matches the campaign home page.
Decision: verified

## Claim 2: "treats us all as walking barcodes" framing

Source: https://reclaimyourface.eu/
Source content: "This blanket capture of every person's biometric data in public spaces like streets, parks, train stations, shops or sports venues simply for trying to live our lives is biometric mass surveillance. It treats us all as walking barcodes."
Comparison: Body quote matches verbatim.
Decision: verified

## Claim 3: deployment contexts named — streets, parks, train stations, shops, sports venues

Source: https://reclaimyourface.eu/
Source content: "public spaces like streets, parks, train stations, shops or sports venues"
Comparison: Body's enumerated list matches the campaign home page exactly.
Decision: verified

## Claim 4: "October 2020 coalition launch"

Source: https://edri.org/our-work/reclaim-your-face-biometric-surveillance/ and https://en.wikipedia.org/wiki/European_Digital_Rights
Source content: EDRi (primary): "November 2020" coalition launch. Wikipedia: "Launched in October 2020".
Comparison: The two canonical sources disagree on the launch month. The body's "October 2020 coalition launch" matches Wikipedia but contradicts the EDRi primary source. Per source rule, Wikipedia cannot resolve a contradiction alone, and disagreement between canonical sources yields unverifiable. The entity's own `sources[].note` for the EDRi URL acknowledges the ambiguity by writing "October-November 2020", but the body and the `origin:` frontmatter pin the launch to October 2020 alone.
Decision: unverifiable

## Claim 5: scalar:sources[2].note — "the campaign's October-November 2020 launch"

Source: https://edri.org/our-work/reclaim-your-face-biometric-surveillance/
Source content: EDRi page identifies the campaign launch as "November 2020"; Wikipedia identifies it as October 2020.
Comparison: The hedged October-November phrasing in the source note straddles the two canonical-source values; neither side of the disagreement is contradicted by the note. With Wikipedia and EDRi disagreeing, the underlying date itself remains unverifiable; the note's hedge correctly does not pick a winner.
Decision: unverifiable

## Claim 6: ECI signature-collection window opened on 17 February 2021

Source: https://www.accessnow.org/press-release/reclaim-your-face/ and https://en.wikipedia.org/wiki/European_Digital_Rights
Source content: Access Now press release dated February 17, 2021 announcing the ECI launch; Wikipedia: ECI "launched in February 2021".
Comparison: Body's 17 February 2021 opening date matches the Access Now press release date.
Decision: verified

## Claim 7: ECI signature window ran through 1 August 2022

Source: https://reclaimyourface.eu/goodbye-eci-hello-ai-act-negotiations/
Source content: "Today, 1st of August at 23:59, our European Citizens Initiative comes to an end."
Comparison: Body's "1 August 2022" closure date matches the post-mortem (which was published on the closure day).
Decision: verified

## Claim 8: nearly 80,000 verified signatures gathered

Source: https://reclaimyourface.eu/goodbye-eci-hello-ai-act-negotiations/
Source content: "we gathered almost 80 thousand signatures without using any targeted social media advertisement"
Comparison: Body's "nearly 80,000 verified signatures" matches the campaign post-mortem's "almost 80 thousand".
Decision: verified

## Claim 9: ECI window extended through 1 August 2022 from an original 16 February 2022 deadline due to COVID-19

Source: https://reclaimyourface.eu/goodbye-eci-hello-ai-act-negotiations/
Source content: The post-mortem confirms the 1 August 2022 close date but contains no mention of the original 16 February 2022 deadline or a COVID-19 extension.
Comparison: The specific "16 February 2022 original deadline" and the "COVID-19 extension" reason are not present in the cited source, and no other canonical source consulted carries them. The entity's `sources[1].note` attributes these specifics to the RYF post-mortem, but the source as fetched does not contain them.
Decision: unverifiable

## Claim 10: ECI registered on 7 January 2021

Source: https://reclaimyourface.eu/goodbye-eci-hello-ai-act-negotiations/ and https://edri.org/our-work/reclaim-your-face-biometric-surveillance/
Source content: RYF post-mortem: "We started the ECI in January 2021". EDRi: registration in January 2021 region (campaign-launch material referencing the ECI process). Neither cited canonical source pins the specific 7 January registration date.
Comparison: "January 2021" is broadly attested, but the specific 7 January registration date is not present in the canonical sources consulted. Treated as Wikipedia-alone-insufficient territory (public-record fact, definitional Wikipedia-alone class) — but Wikipedia does not provide the specific date either.
Decision: unverifiable

## Claim 11: campaign credited with putting "ban" and "remote biometric identification" into the April 2021 AI Act proposal

Source: https://reclaimyourface.eu/goodbye-eci-hello-ai-act-negotiations/
Source content: "In April 2021, when the law was proposed, we managed to include in the draft a mention of a ban."
Comparison: The body's specific claim is framed as the campaign's own credit-claim ("is credited by the coalition with putting…"); the post-mortem makes that credit-claim explicitly for "ban". The "remote biometric identification" half of the credit-claim is the substantive demand the campaign carried, so the campaign's self-attribution covers it. The credit-claim itself is verified at the level the body asserts (the campaign's claim, not an independent causal verification).
Decision: verified

## Claim 12: 16 June 2021 Access Now-led global call signed at launch by 175+ organisations (later cited as 178) across 55 countries

Source: https://edri.org/our-work/edri-joins-178-organisations-in-global-call-to-ban-biometric-surveillance/
Source content: Date June 16, 2021; "over 175 organisations" in body, "178 organisations" in headline; "55 countries".
Comparison: All three numeric and date claims match exactly.
Decision: verified

## Claim 13: international call co-led by Access Now, EDRi, Amnesty International, Human Rights Watch, Internet Freedom Foundation (India), IDEC (Brazil)

Source: https://edri.org/our-work/edri-joins-178-organisations-in-global-call-to-ban-biometric-surveillance/
Source content: Co-leading orgs listed: Access Now, Amnesty International, Human Rights Watch, Internet Freedom Foundation (India), Instituto Brasileiro de Defesa do Consumidor / IDEC (Brazil). EDRi as signatory and announcement publisher.
Comparison: Body list matches the EDRi page's named co-leads.
Decision: verified

## Claim 14: 6 October 2023 UK joint statement — 65 parliamentarians, 31 organisations, verbatim demand "UK police and private companies to immediately stop using live facial recognition for public surveillance"

Source: https://bigbrotherwatch.org.uk/press-releases/65-parliamentarians-call-for-immediate-stop-to-live-facial-recognition-surveillance/
Source content: October 6, 2023; 65 parliamentarians (38 MPs and 27 Peers); 31 rights, race-equality, and technology groups; verbatim quote "We call on UK police and private companies to immediately stop using live facial recognition for public surveillance."
Comparison: Date, both counts, and the verbatim demand language all match the BBW press release.
Decision: verified

## Claim 15: 30 November 2021 "An EU Artificial Intelligence Act for Fundamental Rights" statement — 115 organisations and seven prohibitions including remote biometric identification in publicly accessible spaces

Source: https://algorithmwatch.org/en/eu-artificial-intelligence-act-for-fundamental-rights/
Source content: Date November 30, 2021; "115 civil society organisations"; seven prohibitions listed verbatim: "social scoring systems; remote biometric identification in publicly accessible spaces (by all actors); emotion recognition systems; discriminatory biometric categorisation; AI physiognomy; systems used to predict future criminal activity; systems to profile and risk-assess in a migration context."
Comparison: Date, signatory count, and the seven-prohibition enumeration all match.
Decision: verified
