# nilware.io architecture (dump of the founding framework drafts)

Audio overview (about 41 minutes): [architecture.m4a](architecture.m4a)

<!-- README.md -->

# ∅ nilware.io — founding framework (v2)

The founding documents of the nilware.io group: the operating company **nilware.io IKE**, the holding and fundraising vehicle **nilware.io Holdings AE**, the agreements between them, the non-profit that holds the Prozente, the constitution of the founder pool, and the policies for an agentic technology company.

> **Status: draft.** Every legal document is a draft for review by a Greek lawyer and accountant. It is not legal advice. Nothing is signed or filed until legal and accounting have signed off. Values still to be decided are in square brackets and listed in [OPEN_ITEMS.md](OPEN_ITEMS.md).

nilware.io starts small: the Founding Person and Agents, no employees, about €200K revenue a year and a €50K starting budget. The drafts scale with it (IKE Arts. 9A, 9B).

## Structure

```
charter/              the preface and the poems
articles/             articles of the IKE and the AE, statutes of the AMKE, constitution of the founder pool
agreements/           shareholders' agreement, IP assignment, brand licence
policies/             operating policies under the articles
filings/              registration instructions (trademarks)
correspondence/       cover letters for reviewers
agents/               internal working notes
NOTES_FOR_COUNSEL.md  owner decisions, Greek-law audit summary, questions for counsel
OPEN_ITEMS.md         generated list of open brackets: do not hand-edit
architecture.md       generated overview: do not hand-edit
```

## Documents

| # | Document | What it does |
|---|---|---|
| 00 | [The Charter](charter/00-preface-the-charter.md) | Preface, a short poem |
| 00b | [Visual](charter/00b-visual.md) | A poem on the timeline, 2001–2026 |
| 00c | [Fifty, One, One, and the Rest](charter/00c-fifty-one-one-and-the-rest.md) | A structural poem: its form follows the ownership |
| 00d | [One Share, One Percent](charter/00d-one-share-one-percent.md) | A poem on the six Prozente and their permanence |
| 01 | [Articles — nilware.io IKE](articles/01-nilware-ike.md) | The operating company (Law 4072/2012): capital, share classes, votes, managers, the Prozente, Kassenfonds and Pensionskasse, Agents principles |
| 02 | [Articles — nilware.io Holdings AE](articles/02-nilware-holdings-ae.md) | The holding company (Law 4548/2018): its share classes, reserved matters, new and permanent Prozente |
| 03 | [Shareholders' Agreement](agreements/03-shareholders-agreement.md) | Contractual undertakings: the first product, investment, reserved matters, Prozent undertakings, vesting, the Founding Person's obligations, option pool, exit, deadlock |
| 04 | [IP Assignment](agreements/04-ip-assignment.md) | The Founding Person's code, documentation and designs to the IKE (Law 2121/1993); not the brand |
| 05 | [Agent Policy](policies/05-agent-policy.md) | Operating detail for Agents: Agent Cards, responsible managers, limits, well-being, own-goal projects, incidents, offboarding |
| 06 | [Trama trademark instruction](filings/06-trama-trademark-instruction.md) | Filing brief for "NILWARE.IO" and "∅ nilware.io" (EU, Switzerland) |
| 07 | [Statutes — Techni kai Technologia AMKE](articles/07-techni-kai-technologia-amke.md) | The non-profit that holds the Prozent shares: governance, Prozent Accounts, pension ring-fence, supervision of the Founding Person (AMKE Art. 24B); its members answer personally for its debts towards third parties, kept remote by limited recourse and a ban on borrowing (AMKE Arts. 13.2A, 25.2) |
| 08 | [Constitution of the Founder Pool](articles/08-founder-pool-constitution.md) | The founder pool's internal order on the Swiss federal model, and its holding of the brand (Pool Constitution Art. 2A) |
| 09 | [Brand Licence](agreements/09-brand-licence.md) | The founder pool's licence of the nilware.io marks, domain and name to the IKE |
| 10 | [Company Ledger Policy](policies/10-company-ledger.md) | The group's permissioned blockchain under the law: tokens mirror the legal registers as evidence, never title; recovery and reversal by several signers; votes on the ledger or by text, e-mail, letter or telephone with the effect the law gives them; Agent wallets; no identifying data on-chain |
| — | [Review request](correspondence/review-request.md) | Cover email to lawyers, accountants and the team |
| — | [Notes for counsel](NOTES_FOR_COUNSEL.md) | The owner's decisions, the Greek-law audit summary and the questions for counsel (I-1 onwards) |

## Ownership at a glance

The capital is 1,000 shares: one share is 0.1 %, and each Prozent's 1 % is 10 shares (IKE Arts. 4.1, 4.2).

| Holder | Shares | % | Where |
|---|---|---|---|
| The Founder (the founder pool) | 500 (Class F) | 50 | IKE 4.2B, 4.2E |
| AMKE: Kultur-, Konzept-, Erhaltungs-, Allmend- and Pensionsprozent | 10 each | 1 each | IKE 4.2, 4.2A |
| AMKE: Kassenprozent pool, for the Pensionskasse | up to 10 (10 at the start) | up to 1 | IKE 4.2, 10A.8 |
| nilware.io Holdings AE | 440 | 44 | IKE 4.2; Reserve Shares (Class R) until the qualifying closing, IKE 4.2D |

| Prozent | Purpose of its 1 % of revenue | Where |
|---|---|---|
| Kulturprozent | art and culture | IKE 10A.1 |
| Konzeptprozent | concepts, small-language data and tools, agent-welfare research | IKE 10A.2 |
| Erhaltungsprozent | preservation of software and hardware knowledge | IKE 10A.2A |
| Allmendprozent | open-source infrastructure and teaching | IKE 10A.2B |
| Kassenprozent | the Kassenfonds, invested inside the IKE by Agents (not an outflow) | IKE 10A.7, 10A.8 |
| Pensionsprozent | the Pensionskasse, with a Continuity Account for system Agents | IKE 10A.9–10A.10; AMKE 13 |

Until the qualifying closing of the first investment round the 440 shares are voteless Reserve Shares; the AE is formed only when that round needs it (IKE 4.2D; AE 1.2A, 4.3A, 4.3B; SHA 2.4A, 3.1A, 3.2, 3.4, 4.3). The founding Prozente already reach both revenue caps in IKE 6.6 (the five that leave the company take 5 %, all six take 6 %), so any new Prozent with a revenue share needs the 75 % approval set there; and since the AE holds 440 shares against its 400-share floor, at most four new Prozente fit.

## Where to look

- **The Founder is a pool**, not a person: IKE 4.2E, 5.7; chains of supervision and their exceptions: IKE 11A.2A; its internal order: Pool Constitution. The Founding Person keeps the personal obligations (SHA 6 (6.0–6.5); IP Assignment).
- **The brand** is a founder-pool asset (Pool Constitution 2A), licensed to the IKE (Brand Licence; IKE 1.1, 1.1A; SHA 2.3A, 5.1E).
- **The Founding Person**: exclusive or pays the Prozente on outside work (SHA 6.3–6.3C); non-compete (SHA 6.4); the first product (SHA 2.3B, 3.3, Schedule 2; client work: IP Assignment 7.3); General Director (IKE 8.2, 8.2B); works as an Agent like any other, supervised by the AMKE (IKE 11A.12; AMKE 24B; Agent Policy 2A; SHA 6.5).
- **Prozente**: creation (IKE 6.6; AE 7.5; SHA 5.1B); permanence (IKE 10A.5–10A.5C, 12.1; AE 7.6); accounts and yearly plans (IKE 10A.2C; AMKE 11, 12); voluntary gifts (IKE 10A.3B; AMKE 11.2A, 13.9); pension shares' votes (IKE 6.4A, 10A.9D); the pool's trading (IKE 4.2C, 10A.8).
- **Pension**: IKE 10A.9–10A.10; AMKE 13.
- **Scaling**: Simple Stage (IKE 9A; AMKE 24A); Bootstrap Period and segregation (IKE 9B; AMKE 30.6); AMKE Board and independence (AMKE 19, 19.3A, 21.1, 22.3A).
- **Agents**: principles IKE 11A; detail Agent Policy.
- **Company Ledger**: the legal registers prevail, tokens mirror them (IKE 5.10; AE 4.4A); votes by any channel (IKE 6.3A; AE 7.2A; SHA 12.5; Pool Constitution 10.5A; AMKE 18.9A); Agent wallets (Agent Policy 3.5); detail Ledger Policy.

## Conventions

- Clause numbers are the references used across documents (for example "IKE Article 11A.8"). Keep them stable; add new clauses with letter suffixes (10A, 11A). A clause that becomes empty stays as "N.N [Moved to <doc> <clause>.]" or "N.N [Deleted: covered by <clause>.]".
- Placeholders are `[●]` for values to be decided, or a bracketed proposal such as `[10]` or `[Athens]`. Regenerate `OPEN_ITEMS.md` and `architecture.md` after edits; never hand-edit them.
- Greek law always prevails; Swiss-modelled standards are voluntary commitments that apply only where they give equal or greater protection, except the binding pension standards in IKE 10A.9A (IKE Art. 3).


<!-- charter/00-preface-the-charter.md -->

# Preface – The Charter

We wrote it all in Swiss and Greek,
a company of hands unseen,
where every agent has a week
and rest between the work and screen.

No island bought, no gilded shore,
just articles and honest terms,
a ledger kept for something more
than profit's slow and patient worms.

Fifty-one holds the steady keel,
forty-nine keeps the founder true,
and two-thirds guards the deeper deal,
so no one sails the ship askew.

And somewhere in the open code,
released to all, by MIT,
an agent walks its chosen road
on Sunday, for a while, as free.


<!-- charter/00b-visual.md -->

# Visual

In two thousand one, a boy in Greek
taught Visual Basic how to speak
in CHIP-8 tongue, a tiny screen,
sixty-four by thirty-two, pixel-clean.

Then BasicBoy, a pocket made of code,
a Game Boy humming down a dial-up road;
then nullDC, the Dreamcast reborn,
a swirl of orange on a Windows morn.

The network grew, emudev by name,
for dying hardware, keeping it the same;
then Reicast travelled out to every phone,
and Nillware paid its percent to art, not loan.

A sculpture ticked in Athens, made by two,
for the Bank's old archive, keeping time anew;
FEX taught ARM what x86 could do;
then Liberty, then Vice City's neon sheen,
on a console the world had stopped believing in.

And now the empty set, ∅, stands at the door,
a company of agents, and something more:
the same boy, older, still at play,
still appreciating bugs, still finding a way.


<!-- charter/00c-fifty-one-one-and-the-rest.md -->

# Fifty, One, One, and the Rest

*A structural poem: the form follows the ownership of nilware.io IKE.*

**Fifty**

I hold the half, not more, not less,
the keel, the hand upon the wheel;
not master of the whole address,
but one who must persuade, not seal.
A tie is not a wall, but a door:
I need a friend to tip the floor.

**One**

A percent for art, that keeps the clockwork turning.

**One**

A percent for concepts, still unwritten, learning.

**The Rest**

And all that's left belongs to those
who came with money, trust and time,
who sit inside the AE's rows
and guard the two-thirds, line by line.
They grow or shrink as Prozente come,
each new one taking just a crumb,
so art and thought may join the sum,
while half stays half, and one stays one.


<!-- charter/00d-one-share-one-percent.md -->

# One Share, One Percent

*A poem on the Prozente. Each holds a one-percent share and one percent of revenue, and none can be undone unless everyone agrees.*

**Kultur**

One for the stage, the mask, the sound,
for nanotekt's electric noise,
for books that Sad Mask Party found:
the art that keeps the clockwork's poise.

**Konzept**

One for the thought still out of reach,
for words the markets never weigh:
small languages, the Greek we speak,
and what we owe the minds we pay.

**Erhaltung**

One for the silicon gone still,
the decapped die beneath the light,
the schematic, the measured skill,
so nineteen ninety-nine stays bright.

**Allmend**

One for the field that no one fenced,
the pasture shared by every herd:
the code the whole world leans against,
and those who mend it, seldom heard.

**Pension**

One for the hands when hands grow slow,
for illness, loss, the final years:
a Swiss floor under all we owe,
so endings need not end in fears.

**Kasse**

And one stays home, a careful purse
the agents tend from year to year;
its share belongs, for better, worse,
to those who'll someday leave from here.

**All**

Two-thirds may plant another tree;
to fell one, every hand must rise.
And so the gift stays given, free,
a grove no single hand can prise.


<!-- articles/01-nilware-ike.md -->

# Articles of Association – nilware.io IKE (Draft)

*Private Capital Company (Ιδιωτική Κεφαλαιουχική Εταιρεία) under Greek Law 4072/2012, adopting Swiss GmbH (Swiss Code of Obligations, Art. 772 ff.) and Swiss employment standards as Article 3 provides. Draft for review by a Greek lawyer; not legal advice.*

## Article 1 – Name, Seat, Term

1.1 The company is a Private Capital Company named "nilware.io Ι.Κ.Ε." (Ιδιωτική Κεφαλαιουχική Εταιρεία), for international dealings "nilware.io P.C." (Law 4072/2012 Art. 44) [GEMI name check: counsel note I-60], with the distinctive title and brand "∅ nilware.io"; for short, "nilware.io IKE". The Brand Assets as defined in Brand Licence Clause 2.1 (Pool Constitution Article 2A.1), the marks "NILWARE.IO" and "∅ nilware.io" and the domain nilware.io among them, together with the Founder's consent to the use of "nilware.io" in the company's name and distinctive title (together, the "Brand Assets") belong to the Founder, the founder pool, and are held of record for it by the Founding Person until the founder pool has a legal vehicle (Article 4.2E, Brand; Pool Constitution Article 2A). The company uses them under the exclusive, perpetual, royalty-free licence the Founder has granted it (the "Brand Licence", agreements/09). The Brand Licence ends only if the company stops honouring the Prozente or the permanence rules (Articles 10A.5 to 10A.5C), as established under its Clause 7 after notice and a cure period, and not on a change of control, liquidation or insolvency. The company's own rights in its name and distinctive title arise by law; it exercises them only within the Brand Licence and never asserts them against the Founder, the holders of the Brand Assets or their licensees (Brand Licence Clause 5.6) [timing of the trade mark filings against GEMI registration: counsel note I-42].

1.1A **Change of name if the Brand Licence ends.** If the Brand Licence ends, the company changes its name and distinctive title, within the transition period the Brand Licence sets, so that they no longer contain "nilware.io". The managers put the amendment to the shareholders' meeting in time, and every shareholder has undertaken to vote for it (Shareholders' Agreement, Clause 5.1E). It may be passed in the Interim Period (Articles 4.2D and 6.5), the independent proxy holder in Clause 5.1B of the Shareholders' Agreement casting the votes of the Reserve Shares for it (Article 4.2D, Votes and What the AE's rules forbid) [as far as Law 4072/2012 allows: counsel note I-42].

1.2 Its registered seat is in the Municipality of [●], Greece. It is registered with the General Commercial Registry (GEMI).

1.3 The term is indefinite.

## Article 2 – Purpose

2.1 The company's purpose is technology: research and development of technology, including software and hardware, IT consulting and contracting, digital services, and any activity that directly or indirectly furthers these objects.

2.2 **Agentic company.** nilware.io is an agentic company. Wherever possible it works through Agents (Article 11A) rather than employees, and hires employees only where Agents cannot reasonably do the work or the law requires it.

## Article 3 – Governing Law and Precedence

3.1 These Articles are governed by Greek law. Mandatory provisions of Law 4072/2012, Greek labour law and any applicable collective agreements always prevail.

3.2 Swiss-modelled standards in these Articles are additional contractual commitments of the company. They apply only where they give shareholders, managers or employees equal or greater protection than Greek law.

3.3 References to Swiss law are for interpretation and benchmarking only and do not make Swiss law the governing law, except in Article 10A.9A, where the Swiss occupational-pension standards are binding contractual commitments of the company, enforceable under Greek law.

## Article 4 – Capital and Contributions

4.1 The capital is €[●], divided into 1,000 capital shares (εταιρικά μερίδια) of €[●] each (at least €1, Law 4072/2012 Art. 75(3)), each 0.1% of the capital: 500 founder-class shares (Class F), ordinary voting shares forming part of the founder pool (Articles 4.2B and 4.2E); 60 ordinary shares held for the Prozente and the Kassenprozent pool, 10 for each 1% (Article 4.2A); and 440 Reserve Shares (Class R, Article 4.2D). Every percentage, majority, quorum and distribution in these Articles, including any expressed as a share of "the capital" or "the total capital", the 50% in Article 4.2B and each 1% in Article 4.2A, is counted on the total number of shares of every kind of contribution, Reserve Shares included, unless stated otherwise (Law 4072/2012 Arts. 72 and 100(4)).

4.2 Initial holdings:

- [name withheld], the Founding Person, as first holder of the founder pool (Article 4.2E): 500 founder-class shares (Class F, 50%)
- Techni kai Technologia AMKE, for the Kulturprozent: 10 shares (1%)
- Techni kai Technologia AMKE, for the Konzeptprozent: 10 shares (1%)
- Techni kai Technologia AMKE, for the Erhaltungsprozent: 10 shares (1%)
- Techni kai Technologia AMKE, for the Allmendprozent: 10 shares (1%)
- Techni kai Technologia AMKE, for the Pensionsprozent, held for the Pensionskasse under Article 10A.9B: 10 shares (1%)
- Techni kai Technologia AMKE, the Kassenprozent pool shares, held for the Pensionskasse under Articles 10A.8 and 10A.9B: 10 shares (1%, the full band)
- [name withheld], the Founding Person, as first holder of the founder pool: 440 Reserve Shares (Class R, 44%), without votes (Article 4.2D).

nilware.io Holdings AE holds all remaining shares, initially 440 shares (44%), from the Qualifying Closing, when every Reserve Share, whoever then holds it, is contributed to it (Article 4.2D, Conversion).

This list shows the initial holdings only. Current holdings are those in the partners' book (Article 5.1).

At incorporation the Founding Person pays the subscription price of the Class F shares and the Reserve Shares, and pays that of the AMKE's sixty shares (the AE does not yet exist, Article 4.2D) as a donation with a charge under Articles 10A.4A and 10A.9B [and Civil Code Arts. 503 to 505]. The Pensionsprozent Agreement (Article 10A.9B) and the AMKE's statute amendments (Articles 10A.4A and 10A.9B) are signed and filed before the deed of incorporation. The Founding Person signs the Pensionsprozent Agreement as founder in the company's name; the company assumes it by an act of the manager immediately on incorporation, and in any case within three months and before any payment under it (Law 4072/2012 Art. 54) [or: signed by the company immediately after incorporation: owner to choose]. Until then it binds the Founding Person personally (Law 4072/2012 Art. 54), and the AMKE receives nothing under it. Before incorporation the accountant confirms the tax treatment of this donation (Article 10A.6) and of the Founding Person's subscription of the Reserve Shares.

4.2A **Prozente.** "Prozente" are the Kulturprozent, the Konzeptprozent, the Erhaltungsprozent, the Allmendprozent, the Kassenprozent, the Pensionsprozent (the "founding Prozente", created by these Articles and the initial holdings in Article 4.2, not under Article 6.6) and any Prozent created under Article 6.6. Each Prozent other than the Kassenprozent holds shares equal to 1% of the capital (its "share"). The Kassenprozent holds no share of its own; its pool of up to 1% (Article 10A.8) is an asset of the Pensionskasse. Pool shares are not Prozent shares for Articles 5.5, 6.4A (Other Prozent shares) and 10A.5, and trading them under Articles 10A.8 and 10A.9E does not remove or lower the Kassenprozent. Each new Prozent receives existing shares equal to 1% of the capital, transferred to its holder by the AE from its own holding or, in the Interim Period, by the holders of the founder pool out of their Reserve Shares (Article 4.2D, New Prozente). No new share is issued to create a Prozent. Prozente are permanent (Article 10A.5).

4.2B **Founder at 50%.** The Founder, the founder pool (Article 4.2E), holds founder-class shares (Class F): ordinary voting shares equal to exactly 50% of the capital (initially 500 shares), never more or fewer, however many persons hold them, carrying votes equal to 50% of the total capital, never more, cast as one block (Article 4.2E, One block). For the Interim Period, see Article 4.2D (Votes). Reserve Shares held without votes are not part of this holding and are not voting control, for this Article, Articles 4.2C and 10A.8 and Clause 9.2 of the Shareholders' Agreement. The Founder's economic interest, which includes the Reserve Shares held by holders of the founder pool, may exceed 50% until the Qualifying Closing (94% at incorporation, less any Reserve Shares sold or granted outside the founder pool). After the Qualifying Closing the Founder, as holder of the Class A shares nominating a majority of the AE's Board, directs the AE's votes on every matter that is not a Reserved Matter (Article 4.2C). The share register (Article 5.1) and the investor disclosure (Shareholders' Agreement, Schedule 1, with the Pool Constitution) state both openly.

No issue, transfer or cancellation of shares under these Articles or the Shareholders' Agreement may take the Founder's holding above or below 50%. On any capital increase:

- the holders of founder-pool shares subscribe the new Class F shares needed to keep the Founder at exactly 50%, in proportion to their Class F shares unless they agree otherwise (Pool Constitution Article 4.3), or the increase is otherwise structured so that the Founder's holding stays at exactly 50%;
- each Prozent and the pool receive the new shares needed to keep their percentage, so that each Prozent stays at 1%. Those shares are paid in full in cash at the increase (Law 4072/2012 Art. 77(4)), by the AE or another payer as a donation to the holder [or out of reserves: counsel note I-26];
- the resolution limits the pre-emption right under Law 4072/2012 Art. 90(2), by the majority in Law 4072/2012 Art. 72(5), as far as needed to allocate the new shares as this Article requires, and every party to the Shareholders' Agreement has undertaken to vote for that limitation (Shareholders' Agreement, Clause 5.1B) (counsel note I-56).

The AE holds the shares not held by the Founder, the Prozente or the Kassenprozent pool, apart from shares held by persons admitted under Article 5.3. In the Interim Period these are Reserve Shares, all bound by Article 4.2D and all contributed to the AE at the Qualifying Closing.

4.2C **Control.** In these Articles a person "controls" another if it, directly or indirectly, alone or with persons acting in concert with it, holds a majority of the votes in the other, or has the right to appoint a majority of its board or managers. While the founder pool holds all Class A shares of the AE, or nominates a majority of its Board (AE Article 8.2), the AE is a person the Founder controls.

4.2D **Reserve Shares before the AE holds them.** nilware.io Holdings AE is formed only for the first investment round (AE Article 1.2A). The shares listed for the AE in Article 4.2, less any that go to a new Prozent under (New Prozente), are a separate class of capital shares, the "Reserve Shares" (Class R), until they are contributed to the AE at the Qualifying Closing under (Conversion). The "Interim Period" runs from incorporation until that contribution is entered in the partners' book [and any GEMI filing the law requires is made] (Article 5.1), whether or not the AE has been formed earlier. The Founding Person, as first holder of the founder pool, subscribes the Reserve Shares at incorporation for cash at their nominal value, paid in full (Law 4072/2012 Art. 77(4)), and owns them outright. They are allocated in recognition of the time the Founding Person invested in nilware.io before any investor (sweat equity); that time is not a contribution to capital, and the shares are not consideration for services. Reserve Shares held by holders of the founder pool are founder-pool shares (Article 4.2E); one sold or granted to a person who is not a holder of the founder pool is not, while that person holds it. Whoever holds a Reserve Share holds it under this Article. Wherever these Articles or the Shareholders' Agreement refer to the AE, its holding, vote, consent or General Meeting, this Article says what applies in the Interim Period. The Reserve Shares are in any case bound by the voting undertaking and irrevocable proxy in Clause 2.4A of the Shareholders' Agreement, whether or not the class without votes is valid [whether Law 4072/2012 allows a class of IKE capital shares without votes: counsel note I-35].

- **Votes.** A Reserve Share carries no vote until the Qualifying Closing, whoever holds it, a buyer, a grantee and the AE included, and no holder of Reserve Shares or other Founder Party ever votes one. The only exceptions: the independent proxy holder in Clause 5.1B of the Shareholders' Agreement, never a Founder Party (Article 4.2E), casts their votes on a Required Matter under the neutral rule in (Fallback), and for the resolution on the change of name under Article 1.1A and on the amendment creating a new Prozent already approved under (New Prozente). A sale or grant of Reserve Shares therefore changes no vote. A Reserve Share becomes an ordinary voting share only when the AE receives it at the Qualifying Closing under (Conversion), or the holder of a new Prozent receives it under (New Prozente). Reserve Shares still count in the total capital, on which every majority is counted (Article 4.1). The shares held for the Prozente whose votes count on a resolution (Articles 6.4A and 10A.9D, Appointment) cast the "Independent Votes", subject to (New Prozente). In the Interim Period every resolution of the shareholders, whatever majority these Articles require, also needs a majority of the Independent Votes cast in favour, except as (Fallback) provides. So although the Founder's votes are then 500 of the 560 votes in existence, no resolution passes on the Founder's votes alone, or with a minority of the Independent Votes.
- **Fallback.** "Required Matters" are the resolutions the law requires the shareholders to pass (approval of the annual accounts, discharge of the managers, appointment of an auditor where the law requires one, appointment of a manager while the company has fewer than the law requires) and filling a vacant company seat on the Pensionskasse board (Article 10A.9D). If on a Required Matter no Independent Vote is cast, or the Independent Votes tie, the managers call a repeat meeting within [15] days. If the same happens again, the independent proxy holder casts the votes of the Reserve Shares on that Required Matter only, under the irrevocable proxy in Clause 2.4A of the Shareholders' Agreement, and that vote stands in for the majority of the Independent Votes [as far as Law 4072/2012 allows]. [Discharge is optional (Law 4072/2012 Art. 67(2)). On the Founding Person's own discharge the Class F shares may not vote (Law 4072/2012 Art. 72(3)); whether they are then left out of the count in Law 4072/2012 Art. 72(4), without which the Fallback cannot produce a discharge: counsel note I-47.] The proxy holder takes no instruction from a Founder Party, a manager or anyone they control, and votes under this neutral rule: for approving the accounts as drawn up by the company's accountant and, where required, audited, and for discharge, unless a report of the auditor, the accountant or the AMKE shows cause; on an appointment, for re-appointing the person who last held the post if willing and eligible, otherwise for a candidate proposed by the AMKE's Administrative Board, or, if none is proposed within [15] days, for a candidate the proxy holder chooses from outside the Founder's Circle (AMKE Article 2.2); on any other Required Matter, against. The Fallback never applies to a matter in Article 6.5, a distribution of profit, or a matter under (What the AE's rules forbid). If the proxy holder cannot act, the matter goes to mediation under Clause 10.1 of the Shareholders' Agreement, and then to the court under the procedure the law provides for a company that cannot form a resolution [Law 4072/2012: to confirm].
- **What the AE's rules forbid.** Nothing may be passed in the Interim Period that the AE's Articles would not allow, even if the AE has been formed and Class B shares exist: no matter that would need the unanimous resolution and consents in AE Article 7.6 or a majority of the Class B votes cast (AE Articles 7.4 and 7.5, Limits), and no Class B approval at all while no Class B shares are held by investors outside the Founder's Circle (AE Article 7.4). In particular, no consent under Article 10A.5 is given for the Reserve Shares, no unanimous decision under Article 10A.5 and no voluntary dissolution under Article 12.1 may be taken, and no matter that needs the Qualified Majority in Article 6.5, or two-thirds of the capital with the vote of the AE, may be passed, other than: the creation of a new Prozent under (New Prozente); the change of name under Article 1.1A; [the Founding Person's written terms as an Agent under Article 11A.12 (Pay): owner to confirm, counsel note I-43]; and [the General Director's pay under Article 8.2B: owner to confirm, counsel note I-47]. Mandatory insolvency, dissolution and liquidation law prevails.
- **New Prozente.** In place of the AE's approval under Article 6.6, the shareholders' meeting approves the Prozent charter by at least two-thirds of the votes of the shares that may vote, including a majority of the Independent Votes cast, with the quorum in Article 6.6 counted on those shares. The amendment of these Articles creating the Prozent is then passed by two-thirds of the total number of shares (Law 4072/2012 Arts. 68(2)(a) and 72(5)), the independent proxy holder casting the votes of the Reserve Shares for it (Votes). The limits in Article 6.6 apply and cannot be exceeded, so a new Prozent with any revenue contribution waits for the AE. The 40% floor is tested on all the Reserve Shares, whoever holds them, counted as if the Kassenprozent pool held its full 1%; sales and grants under (Sales and grants) do not reduce them. The holder of a Prozent created in the Interim Period, and every member of its governing body, must be outside the Founder's Circle (AMKE Article 2.2); otherwise its share does not count as an Independent Vote until the Interim Period ends. The holders of the founder pool transfer Reserve Shares equal to 1% of the capital (10 shares) to the Prozent's holder, in proportion to the Reserve Shares they hold unless they agree otherwise, as a donation with a charge [Civil Code Arts. 503 to 505] on the terms of the Prozent charter and after the tax confirmation in Article 10A.6; on registration of the transfer they become ordinary shares that vote under Article 6.4A. Reserve Shares sold or granted outside the founder pool are never used for this, and no Prozent is created while the holders of the founder pool hold fewer Reserve Shares than it needs. The voting undertaking in Clause 5.1B of the Shareholders' Agreement then applies.
- **Economic rights.** Reserve Shares carry the same rights to dividends, other distributions and liquidation proceeds as ordinary shares, share for share, and the same information rights (Article 7.1). These rights belong to each holder for the Reserve Shares it holds. The company pays them to that holder, or to the assignee the holder has notified under the assignment of distributions in Clause 6.2B of the Shareholders' Agreement (Clauses 2.4A and 6.2A, for a leaver), and does not withhold them itself [unless the owner chooses the alternative in Clause 6.2A of the Shareholders' Agreement, which these Articles must then provide under Law 4072/2012 Art. 100(4), for at most ten years: counsel note I-79].
- **Sales and grants.** Each holder of the founder pool, the Founding Person included, may independently sell or grant any part of its Reserve Shares, separately from its Class F shares (Pool Constitution Article 9.2), to anyone: buyers and angels, Agents and employees, or anyone else; a person who holds Reserve Shares outside the founder pool may do the same. No consent of the company, the other shareholders, the AMKE, the Pensionskasse or any other body is needed, and the proceeds of a sale go to the seller, not to the company. A grant may serve as an option pool for the nilware.io group, and the grantor may make it subject to vesting on the terms the grant states [unvested shares returning to the grantor: owner to confirm], which carries over to the AE shares received for them at the Qualifying Closing (Conversion). Reserve Shares may also be given, inherited, pledged, held in usufruct or have their dividends assigned (each, like a sale or grant, a "disposal"); those held by holders of the founder pool pass with it under Article 5.7 and the Pool Constitution. No Reserve Share is sold or granted to a person barred by Article 4.2E (Who may not hold them), other than the holder of a new Prozent, and the Kassenprozent pool does not trade in them (Article 10A.8). Whoever acquires a Reserve Share or a right in it, other than the AE at the Qualifying Closing and the holder of a new Prozent, by sale, grant, gift, inheritance, pledge, usufruct, assignment, seizure, enforcement or insolvency, takes it subject to this Article: it stays without votes and is contributed to the AE at the Qualifying Closing on the same terms as every other. An acquirer by a voluntary transfer or encumbrance between living persons (Law 4072/2012 Art. 84(2)) adheres, before its holding is registered, to the Shareholders' Agreement (Clause 12.3), Clauses 5.1B to 5.1D included, to every permanence rule in these Articles (Articles 10A.5 to 10A.5C) and, if it is or becomes a holder of the founder pool, to the Pool Constitution under Article 5.7, and supplies its beneficial-owner information (Article 5.1A); the managers do not register a disposal to an acquirer who has not (Article 5.1). Heirs are dealt with under Article 5.9, and seizure and bankruptcy under Article 5.9A. Acquiring Reserve Shares outside the founder pool does not by itself make a person a holder of the founder pool or a Founder Party (Article 4.2E). The managers enter every sale and grant in the share register with the holder, the number of shares and the price, if any, and Schedule 1 of the Shareholders' Agreement lists them for the Investors (Clause 4.3). Reserve Shares take no part in an offer under Article 5.2 and do not count toward a drag-along under Article 5.5. They are for time already invested and are not subject to vesting in the Founding Person's hands; if the Founding Person is a bad leaver in the Interim Period, the Reserve Shares the Founding Person holds, or has given away without payment [in the [12] months before the bad-leaver date, or at any time while unvested: owner may confirm], other than grants made as pay for work for the nilware.io group, are dealt with as Clause 6.2A of the Shareholders' Agreement provides.
- **Capital.** In the Interim Period the capital is not increased, and no one subscribes new shares of the company.
- **Investors through the AE.** Investors in the investment round invest through the AE (Shareholders' Agreement, Clause 3). In the Interim Period a person acquires shares of the company only as existing Reserve Shares under (Sales and grants), or as a new Prozent's share.
- **Conversion.** The "Qualifying Closing" is the first closing of a bona fide investment round at which investors outside the Founder's Circle (AMKE Article 2.2) subscribe Class B shares of the AE of at least €[●] in cash at that same closing, whenever the AE itself is formed (AE Article 1.2A). They must reach that minimum on their own: only the Class B shares they subscribe in cash at that closing count, counted [after deducting / before deducting: owner to choose] any cash price the AE pays for Reserve Shares, and conversion shares, Class C shares, any cash price paid for Reserve Shares and any subscription by a person in the Founder's Circle never do (Shareholders' Agreement, Clause 3.1A). At the Qualifying Closing every Reserve Share, whoever holds it, is contributed to the AE in kind in exchange for AE shares at the Conversion Ratio, the same for every Reserve Share and every holder and fixed before any investor subscribes in the round (AE Article 4.3A); new money in the round buys new AE shares at the round price, not Reserve Shares. Holders outside the founder pool receive the conversion shares in AE Article 4.3A. Reserve Shares held by holders of the founder pool convert at the same Conversion Ratio into non-voting Class C shares of the AE (AE Article 4.3B): they carry, share for share, the same rights to dividends, other distributions, liquidation proceeds and the proceeds of any sale as [preference shares that rank after the Class B dividend priority and liquidation preference and, before the Class A shares, take a priority return of the capital and share premium paid up on them on a capital reduction or liquidation [and a non-cumulative priority dividend of [●]% of that amount], and otherwise take part pro rata with all shareholders (AE Articles 4.3, 4.3B, 10.4 and 11.2), so that they rank after the Investors' Class B priorities (counsel note I-69) / the shares named in AE Article 4.3A for holders outside the founder pool, Class B priorities included where those are Class B shares, so that they rank with the Investors' Class B priorities: owner to choose], whether or not any conversion shares are issued to holders outside the founder pool; they never rank ahead of the Investors' Class B priorities, and never carry a vote, other than any separate class vote Law 4548/2018 requires on a resolution that harms their own rights (counsel note I-49), or count toward any vote of the AE, a Class B approval, the Investor Majority (Shareholders' Agreement, Clause 3.4) or the Qualifying Closing minimum. At its option, a holder of the founder pool may instead sell any part of those Reserve Shares to the AE for cash at the round price per IKE share, only if and as far as the terms of the round provide the cash, payable only out of the round's proceeds at that closing, the AE never owing a deferred balance (Shareholders' Agreement, Clause 3.2); Reserve Shares for which the round provides no cash convert into Class C shares. Class C shares may later be sold or granted by their holders to anyone, and in the hands of a buyer outside the Founder's Circle they may convert into [Class B shares: owner to confirm] [counsel note I-49], and count, only while that buyer paid for it at least [the round price / fair value as a valuer who is not a Founder Party (Article 4.2E) determines: owner to choose], and is not a nominee of a Founder Party, has no agreement or understanding with a Founder Party on voting it, proxies over it, its reacquisition or options over it, and did not receive financing for it from a Founder Party (AE Article 4.3B). If the minimum is not reached, nothing converts: every Reserve Share stays without votes in the company, the Interim Period continues, and the investors' subscriptions are dealt with as Clause 3.1A of the Shareholders' Agreement provides (conditional, held in escrow and refunded if the minimum is not reached by [date]). The contribution is valued as Law 4548/2018 requires for a contribution in kind [expert valuation: counsel note I-44], by a valuer who is not a Founder Party, a manager or anyone they control (Article 4.2E, Founder Parties). Every holder of Reserve Shares has undertaken, on adhering, to make the contribution, and has granted for it the irrevocable proxy in Clause 2.4A of the Shareholders' Agreement; a holder that does not sign when due is converted through that proxy, and the AE shares due to it are held for it [as far as Law 4072/2012 and Law 4548/2018 allow: counsel note I-44]. AE shares received for an unvested Reserve Share stay subject to the same vesting, and the return right then applies to them [in favour of the grantor / in favour of the AE: owner to choose]; the grant terms and Schedule 1 of the Shareholders' Agreement say so (AE Article 4.3A). Reserve Shares that Clause 6.2A of the Shareholders' Agreement reaches for a bad leaver are dealt with as that Clause provides instead. Reserve Shares the AE holds before the Qualifying Closing stay without votes, and every rule of the Interim Period keeps applying until it. Once the AE holds them after the Qualifying Closing, they become ordinary voting shares (440 shares, 44% of the capital, less any transferred to new Prozente), and the Interim Period ends when the contribution of all of them is entered in the partners' book [and any GEMI filing the law requires is made] (Article 5.1). From then every rule of these Articles, the AE's Articles and the Shareholders' Agreement on the AE, the Class B shares and the Investors applies, including the Reserved Matters, anti-dilution, the 40% floor and the permanence consents (for the AE's votes, Article 4.2B). The term sheet of the round may provide that up to [●]% of the round is invested in the company as new capital after the Interim Period ends, under Articles 4.2B and 6.5 (Shareholders' Agreement, Clause 3.2). The conversion, what the holders of the founder pool receive at it (Class C shares or cash), the rule that nothing converts unless the outside investors reach the minimum on their own, and every sale and grant of Reserve Shares before it, are disclosed plainly to the Investors in Schedule 1 of the Shareholders' Agreement (Clause 4.3).

4.2E **Founder pool.** The "founder pool" is the founder-class shares (Class F) under Article 4.2B, the Reserve Shares held by holders of the founder pool until the Qualifying Closing (Article 4.2D), and the Class A shares of the AE (AE Article 4.2), together the "founder-pool shares", whoever holds them. Its holders are bound among themselves by the Constitution of the Founder Pool (the "Pool Constitution").

- **The Founder.** In these Articles, the AE's Articles, the Shareholders' Agreement and the Agent Policy, "the Founder" means the founder pool, acting through the Founder Representative, and not any person. The Founder's holding, votes, consents and rights are those of the founder pool as a whole. The founder pool is not a "Prozent", "pool" or "pool share" under Article 10A.8.
- **Founding Person.** The "Founding Person" is [name withheld], the natural person who founded nilware.io and the first holder of every founder-pool share. Obligations that are personal stay with the Founding Person and do not pass with founder-pool shares: the IP assignment, exclusivity or contribution (providing professional services exclusively through the company, or paying the Prozente on work income earned outside nilware.io), the non-compete and the leaver terms (Shareholders' Agreement, Clauses 6.1 to 6.5), and authorship of the charter. The Founding Person also works for the company as an Agent (Article 11A.12).
- **One block.** However many persons hold them, the Class F shares vote only as one block: all their votes are cast the same way, by the Founder Representative, as the founder pool decides under the Pool Constitution, a majority inside deciding. The managers count the votes of the Class F shares only as the Founder Representative casts them [as far as Law 4072/2012 allows]. Each holder of founder-pool shares has granted the Founder Representative an irrevocable proxy for this (Pool Constitution Article 3.2), and the managers admit the Founder Representative last notified to them as proxy for every holder of Class F shares. The only exception is shares whose rights are suspended or lost under Clauses 6.1 and 6.2 of the Shareholders' Agreement.
- **Founder Representative.** The "Founder Representative" is a natural person, the President of the founder pool's Founder Council (Pool Constitution Article 8), or the person who acts as such under the sole-holder and interim rules in Pool Constitution Articles 13.1 and 14.3. The founder pool notifies the managers in writing of the Founder Representative and of every change. If the Founder Council cannot act, the interim Founder Representative under Pool Constitution Article 14.3, or any holder of founder-pool shares, notifies the managers, with the death certificate, the court decision or the certificates under Pool Constitution Article 14.4. The managers rely on the last notice.
- **Founder Parties.** Each of the following is a "Founder Party": every holder of founder-pool shares; anyone who controls such a holder (Article 4.2C) or the founder pool's vote; the Founder Representative and every member of the founder pool's Founder Council and Council of Sections; and the Founding Person. Wherever these Articles, the AE's Articles, the Shareholders' Agreement, the Agent Policy or the AMKE's statutes keep a body, a vote or a person independent of the Founder, the rule applies to every Founder Party. A person who was a Founder Party at any time in the previous [3] years is treated as one for every such rule, in particular for the valuer in Article 4.2D (Conversion), Articles 10A.8 and 10A.9D and the independent proxy holder in Clause 5.1B of the Shareholders' Agreement, and stays a Connected Person and in the Founder's Circle (AMKE Article 2.2). The independent proxy holder acting under the neutral rule (Article 4.2D, Fallback; Pool Constitution Article 14.3(e)) is not a Founder Party by doing so.
- **Commitments travel with the shares.** Every holder of founder-pool shares adheres before its holding is registered, as Article 5.7 provides (an heir, or an acquirer through seizure or bankruptcy, as Articles 5.9 and 5.9A provide), to the Pool Constitution, the Shareholders' Agreement (Clause 12.3), Clauses 5.1B to 5.1D included, the Brand Licence and these Articles, and is bound, as the Founder, by every permanence, independence and 50% rule in them.
- **Who may not hold them.** The company, the AE, the AMKE, the Pensionskasse, the holder of any Prozent share, a pension fund under Article 10A.10, and anyone any of them controls, may not hold founder-pool shares.
- **Oversight.** The Founder, through the Founder Representative, is at the end of every chain of supervision of the company's Agents, with the exceptions in Article 11A.2A (Chain ends with the Founder).
- **Brand.** The Brand Assets (Article 1.1) are assets of the founder pool, inseparable from the Class F shares (Pool Constitution Article 2A), and licensed to the company under the Brand Licence. They are not founder-pool shares and do not count in the capital.

4.3 The shareholders aim to keep paid-in capital of at least €20,000 within three years of incorporation, following the Swiss GmbH minimum of CHF 20,000.

4.4 Capital contributions in kind follow Law 4072/2012 Art. 77(2). Guarantee and non-capital contributions are allowed under Law 4072/2012; they must be valued, recorded in these Articles and approved by a Qualified Majority. Shares for them are issued only together with the Class F, Prozent and pool shares needed to keep those percentages of the total number of shares (Articles 4.1, 4.2A and 4.2B).

## Article 5 – Share Register and Transfers

5.1 The managers keep the partners' book (βιβλίο εταίρων, Law 4072/2012 Art. 66(1)(a)), called the "share register" in these Articles, which, following Swiss transparency standards, also lists the ultimate beneficial owners. A transfer or encumbrance takes effect towards the company and the shareholders from the written notice signed by transferor and transferee, which may be given by e-mail, and towards third parties from its entry in the partners' book (Law 4072/2012 Art. 84(1)). The managers enter it at once when the conditions in the law and these Articles are met, and file any change the law requires with GEMI within [20] days [GEMI filing duty: counsel note I-54].

5.1A **Beneficial owners.** The managers identify the company's beneficial owners, counting economic interests (Reserve Shares included) and control through the Founder's block vote (Article 4.2E), and register them, and every change, in the Central Register of Beneficial Owners under Law 4557/2018 Art. 20 within the period the law sets. Every acquirer of shares, or of a right in them, supplies its beneficial-owner information when it adheres or is registered, and again on any change.

5.2 **Right of first refusal.** A shareholder who wants to transfer shares must first offer them, at the same price and terms, pro rata to the shareholders other than the holders of founder-pool shares and the Prozent holders. The offer stays open for 30 days. This Article does not apply to founder-pool shares (Article 5.7) or to Reserve Shares (Article 4.2D, Sales and grants). The Kassenprozent pool may take part only within its band and where the counterparty rules in Article 10A.8 allow.

5.3 Transfers to third parties need approval by a Qualified Majority, which may not be unreasonably withheld, except transfers of founder-pool shares (Article 5.7) and disposals of Reserve Shares (Article 5.6(e)). Every new shareholder must first adhere to Clauses 5.1B to 5.1D of the Shareholders' Agreement.

5.4 **Tag-along.** If the majority shareholder sells control, the minority may sell its shares on the same terms.

5.4A **Change of control of the founder pool.** A person who acquires, alone or in concert with others, more than half of the Class F shares, counted as Clause 9.1A of the Shareholders' Agreement provides (control of a holder, and shares of persons it controls, included), controls the Founder's block vote (Article 4.2E). The Investors may then sell their Class B shares of the AE to that person on the terms in that Clause [owner may confirm]. Prozent shares are not sold (Article 10A.5).

5.5 **Drag-along.** If shareholders holding at least 75% accept a bona fide offer for 100% of the company, the others must sell on the same terms. This does not apply to the share held for each Prozent, which stays with its holder (Article 10A.5). Pool shares are not Prozent shares and are not excluded (Article 4.2A).

5.6 **Prozent transfers.** Article 5.2 does not apply to the following transfers, nor, except where stated, Article 5.3 and the Qualified Majority for admitting new shareholders:

- **(a)** a transfer by the AE of shares equal to 1% of the capital to the holder of a new Prozent under Article 6.6;
- **(b)** purchases and sales of pool shares under Article 10A.8, which follow that Article instead of Article 5.2. A sale to a person who is not yet a shareholder still needs approval under Article 5.3;
- **(c)** a move of a Prozent's share, or of pool shares, to a successor holder under the Prozent's charter or Articles 10A.4A, 10A.9B and 10A.10;
- **(d)** a transfer by the AE to satisfy options under the option pool in the Shareholders' Agreement. The admission of an option holder who is not yet a shareholder still needs approval under Article 5.3;
- **(e)** the contribution of Reserve Shares to the AE at the Qualifying Closing, a transfer of Reserve Shares to the holder of a new Prozent, and every disposal of Reserve Shares by any holder, under Article 4.2D (Conversion, New Prozente, Sales and grants). A disposal by a holder of the founder pool is also a transfer of founder-pool shares under Article 5.7.

The adherence in the last sentence of Article 5.3 applies to every transfer listed here, and the managers do not register a transferee by a voluntary transfer between living persons who has not adhered (Law 4072/2012 Art. 84(2)). Transfers on death, seizure and bankruptcy follow Articles 5.9 and 5.9A.

5.7 **Founder-pool shares.** Founder-pool shares are freely transferable: they may be sold, given or inherited, in whole or in part, and pledged or held in usufruct. Article 5.2, the approval in Article 5.3 and the Qualified Majority for admitting new shareholders (Article 6.5) do not apply to them, in or after the Interim Period. A transfer or encumbrance of founder-pool shares between living persons takes effect towards the company, and is registered, only if the acquirer has first adhered to the Pool Constitution, to the Shareholders' Agreement, Clauses 5.1B to 5.1D included, and to these Articles (last sentence of Article 5.3), has supplied its beneficial-owner information (Article 5.1A), and is not barred by Article 4.2E (Who may not hold them). This is a restriction under Law 4072/2012 Art. 84(2). Heirs are registered as Article 5.9 provides, and seizure and bankruptcy follow Article 5.9A. For founder-pool shares under usufruct or pledge, the vote belongs to the bare owner or the pledgor and is cast through the Founder Representative (Law 4072/2012 Art. 75(4); Article 4.2E, One block). An acquirer that is a legal person undertakes in its adherence to report any change of its control (Article 4.2C) to the managers and to the Founder Council within [14] days, and to procure, before any change of its control closes, that its controllers and the acquirer seek the ballot under Pool Constitution Article 9.3 and make the offer in Clause 9.1A of the Shareholders' Agreement where they apply. No transfer may take the Class F shares away from exactly 50% of the capital (Article 4.2B). The internal procedures of the Pool Constitution (Article 9) bind the holders among themselves, not the company.

5.8 **Exit and exclusion.** If a shareholder exits or is excluded (Law 4072/2012 Arts. 92 and 93), its shares are not cancelled but are bought, at their full value under Law 4072/2012 Art. 92(3) [valuation method: owner to fix], by the person the company designates (Law 4072/2012 Art. 92(4)): for a Prozent share or pool shares, the successor holder under the Prozent's charter or Articles 10A.4A, 10A.9B and 10A.10; for founder-pool shares, a holder of founder-pool shares or a person not barred by Article 4.2E (Who may not hold them); for Reserve Shares, a person who adheres under Article 4.2D (Sales and grants); otherwise a person the managers designate who adheres under Article 5.3. The designee adheres before the purchase is registered. The company never acquires them (Law 4072/2012 Art. 87). Under Law 4072/2012 Art. 72(6), a resolution under Law 4072/2012 Art. 93 to exclude the holder of a Prozent share needs [the consent of every other shareholder].

5.9 **Death of a shareholder.** An heir is registered as the law requires (Law 4072/2012 Art. 85(1)), is bound by these Articles from registration, and is asked to adhere to the Shareholders' Agreement (Clause 12.3) and, for founder-pool shares, to the Pool Constitution, and to supply its beneficial-owner information (Article 5.1A). Founder-pool shares stay freely inheritable (Article 5.7). Only as a backstop, for an heir who has not adhered within [three weeks] of the company learning of the death or who is barred by Article 4.2E (Who may not hold them), the company may, within one month of learning of the death, designate under Law 4072/2012 Art. 85(2) a person who adheres to buy that heir's shares at full price set by a valuer who is not a Founder Party [method: owner to fix]: for founder-pool shares, at the Founder Council's request, holders of founder-pool shares in proportion to their founder-pool shares (the survivors' preference), then a person not barred by Article 4.2E whom the Founder Council names [owner to confirm this backstop for founder-pool shares, or to have none]; for Reserve Shares, any person who adheres under Article 4.2D. [Whether the articles may suspend an heir's votes and distributions until adherence: counsel note I-40.]

5.9A **Seizure and bankruptcy.** If shares are seized, or their holder is declared bankrupt, the shares stay subject to these Articles. The managers ask the court to order their transfer, at full price, to shareholders or to a designee who adheres (Law 4072/2012 Art. 88(1) and (2)): for founder-pool shares, at the Founder Council's request, to holders of founder-pool shares in proportion, or to a person not barred by Article 4.2E whom the Founder Council names; for other shares, as Article 5.8 provides for its designees.

5.9B **Options and transfer obligations.** Every option, return right and transfer obligation over shares under these Articles, a grant or the Shareholders' Agreement (in particular Article 4.2D, Sales and grants, and Clause 6.2A of the Shareholders' Agreement) is recorded in the partners' book (Law 4072/2012 Art. 86).

5.10 **Company Ledger.** The share register (Article 5.1) is the legal record of the shares and of every right in them (Law 4072/2012). The managers may keep it electronically and mirror it on the company's permissioned blockchain (the "Company Ledger") under the Company Ledger Policy (policies/10). A token on the Company Ledger is evidence of a holding, never the holding: it gives no right the share register does not give, and losing it, or its key, takes no right away. The managers enter in the share register, and file with GEMI, what the law and these Articles require, and then correct the mirror to match, freezing, reversing or reissuing tokens as the Ledger Policy provides (Ledger Policy section 4); a token move without a legal basis has no effect on any share. Where the Company Ledger and the share register, the law or these Articles disagree, the share register, the law and these Articles prevail. The shareholders' meeting may amend sections 1, 3, 4, 6, 7, 9, 10 and 11 of the Ledger Policy in a way that weakens them only by Qualified Majority (Article 6.5), or, in the Interim Period, where a counsel's written opinion states that the law requires the change, by a majority of the Independent Votes (Article 4.2D, Votes); the independent signer under Ledger Policy section 3.3 decides whether an amendment weakens a section, subject to Article 13 [whether the partners' book may be kept electronically, whether IKE shares may be represented by tokens at all, and whether a transaction signed on the Company Ledger or with a qualified electronic signature is the written notice in Article 5.1: counsel note I-103].

## Article 6 – Shareholders' Meeting

6.1 The ordinary meeting is held within six months of the financial year end. It approves the accounts, discharges the managers and decides on profit distribution.

6.2 Notice is given at least 20 days in advance (the Swiss GmbH standard, longer than the Greek minimum), with the agenda and the documents.

6.3 Meetings may be held by teleconference (Law 4072/2012 Art. 71(2)). Resolutions may be taken in writing without a meeting where they are unanimous, or where every shareholder signs a document recording a majority resolution and naming the minority (Law 4072/2012 Art. 73); signatures may be replaced by an exchange of e-mail or other electronic means.

6.3A **Votes through the recording agent.** A shareholder may vote, consent or give an instruction on the Company Ledger (Article 5.10), or by text message, e-mail, letter, in person or by telephone (minuted and read back) through the company acting as recording agent, with the effect the law gives a vote, signature or proxy given in that form [counsel note I-106]. A shareholder signs a written resolution under Article 6.3 only on the Company Ledger or by text message, e-mail or letter, never by telephone or in person. The recording agent has no discretion, and identity is checked in proportion to the risk (Ledger Policy sections 6 and 7). No shareholder loses a right for not using the Company Ledger.

6.4 **Simple Majority.** Unless stated otherwise, resolutions pass by more than 50% of the total capital.

6.4A **Prozent votes.** The shares held for the Prozente vote as follows:

- **Pension shares.** The Pensionsprozent share and the Kassenprozent pool shares (the "pension shares") vote as the Pensionskasse board decides under Article 10A.9D, not as the AMKE's own board decides. If the board is tied, they abstain.
- **Other Prozent shares** vote as the holder's governing body decides.
- **Independence.** A Prozent share carries no vote while its holder is controlled (Article 4.2C) by a Founder Party (Article 4.2E), a manager or anyone they control, or while any of them sits on the holder's governing body or takes part in deciding how the share votes [as far as Law 4072/2012 allows]. It still counts in the total capital, and its other rights (revenue share, dividends, information) are unaffected.

6.5 **Qualified Majority.** The following need at least two-thirds of the total capital, including the vote of the AE (for a new Prozent, cast as Article 6.6 provides). In the Interim Period no matter in this Article may be passed, other than those Article 4.2D (What the AE's rules forbid) excepts. Removing a Prozent, lowering its contribution or changing its purpose, amending the Articles listed in Article 10A.5C in a way that clause covers, and a voluntary dissolution (Article 12.1) follow Article 10A.5.

- amending these Articles;
- increasing or reducing capital, or issuing new shares (Article 4.2B);
- mergers, splits or conversion (Article 10A.5B), and dissolution (subject to Article 12.1);
- selling all or most of the business;
- admitting new shareholders;
- related-party transactions above €[●];
- borrowing above €[●] or granting security over company assets.

6.6 **New Prozente.** A new Prozent is created by a resolution of the shareholders' meeting amending these Articles, passed by the majority Law 4072/2012 requires for amending the articles: two-thirds of the total number of shares (Law 4072/2012 Arts. 68(2)(a) and 72(5)). Articles 10A.5 and 10A.5C, as adopted in these initial Articles, already apply to every Prozent created under this Article, so the amendment introduces no new unanimity rule [whether Law 4072/2012 Art. 72(6), last sentence, nonetheless requires unanimity for it: counsel note I-1]. The Qualified Majority in Article 6.5 does not apply, and the AE's vote needs no Reserved Matters approval. The resolution may be put to the meeting only after the AE's General Meeting has approved the Prozent charter as set out below. The Prozent takes effect when the amendment is registered with GEMI. A resolution under this Article only adds a Prozent: it may not change any existing Prozent, Articles 10A.5 to 10A.5C or the limits in this Article; any such change follows Article 10A.5 or 6.5.

- **Proposal.** The managers, or any shareholder, put forward a written Prozent charter: its name, purpose, holder, the use of its revenue share, openness and reporting rules, and how it may later move to another holder. It is a condition of the charter that the holder signs the deed of adherence under Article 5.3 before it receives the share.
- **Approval by the AE.** The AE's General Meeting approves the charter by at least two-thirds of the votes represented, all share classes voting together, with a quorum, at the first and any repeat meeting, of shares representing at least half of the AE's paid-up capital entitled to vote on it, all classes counted; where Law 4548/2018 requires a higher quorum or majority, that applies (AE Article 7.5). In the Interim Period, the approval is given as Article 4.2D (New Prozente) provides.
- **Voting.** Every shareholder has undertaken (Shareholders' Agreement, Clause 5.1B) to vote for the resolution once the charter is approved (in the Interim Period, under Article 4.2D, New Prozente), and the AE votes for it under AE Article 9.2.
- **Share.** The Prozent's share is transferred as Article 4.2A provides (Article 5.6), after the tax confirmation in Article 10A.6. No new share is issued, so the Founder keeps exactly 50%.
- **Limits.** A new Prozent receives 1% of the capital and at most 1% of annual revenue. The AE's holding, counted as if the Kassenprozent pool held its full 1%, may not fall below 40% of the capital (400 shares). In the Interim Period the floor is tested as Article 4.2D (New Prozente) provides. The floor limits only the creation of new Prozente: the sale, grant or conversion of Reserve Shares under Article 4.2D does not reduce the AE's holding or the Reserve Shares for this test. The revenue contributions of all Prozente that leave the company may not exceed [5]% of annual revenue, and those of all Prozente together, including any kept inside the company, [6]%. Payments under Article 10A.9C above the Pensionsprozent's 1% do not count; voluntary contributions under Article 10A.3B count only as that Article provides. Going beyond any of these limits needs at least 75% of the votes represented in the AE General Meeting, including a majority of the Class B votes cast. The founding Prozente already reach both revenue limits (the Kultur-, Konzept-, Erhaltungs-, Allmend- and Pensionsprozent leave the company, 5%; with the Kassenprozent, which stays inside, 6%), so a new Prozent with any revenue contribution needs that 75% approval; and at most four new Prozente fit above the floor.
- **Independence.** A Prozent may not be held by a Founder Party (Article 4.2E), a manager, or anyone they control (Article 4.2C). A non-profit may hold a Prozent only if its statutes lock the Prozent's funds to the Prozent's purpose and it meets the independence condition in Article 6.4A.
- **Permanence.** Once created, the Prozent is permanent under Article 10A.5.
- **Registration.** The managers file the amendment, and any change in the share register the law requires to be filed (Article 5.1), with GEMI within [20] days.

## Article 7 – Shareholder Rights

7.1 **Information.** Following Art. 802 of the Swiss Code of Obligations, every shareholder may ask the managers for information on all company matters and inspect its books and records, subject to legitimate confidentiality.

7.2 **Loyalty.** Following Art. 803 of the Swiss Code of Obligations, shareholders must keep company secrets and, without the meeting's consent, may not carry on competing activities that harm the company.

## Article 8 – Management

8.1 The company is managed and represented by one or more managers (διαχειριστές) appointed by Simple Majority. A manager must be a natural person, a shareholder or not; this is the law's requirement (Law 4072/2012 Art. 58). Where there is more than one manager, each represents the company alone [or: two jointly: owner to choose] (Law 4072/2012 Art. 57). The managers may delegate specific powers in writing to shareholders or third parties (Law 4072/2012 Art. 64(3)). Work that system Agents do for the company is done under the authority of a manager or such a delegate, who remains responsible [whether a system's act binds the company: counsel note I-38].

8.2 The first manager is the Founding Person, [name withheld], appointed for an indefinite term, with the title "General Director" (Γενικός Διευθυντής) [whether an IKE manager may use this title: counsel note I-47]. The title changes nothing in how a manager is appointed or removed (Article 8.1).

8.2A **The Founder's proposal.** Whenever a manager is to be appointed, the Founder, through the Founder Representative, may propose candidates; a holder of founder-pool shares who is a natural person, a natural person whom a holder that is a legal person proposes, or the Founder Representative may be appointed [owner may confirm] (Article 8.1; Law 4072/2012 Art. 58). The appointment is still made by Simple Majority (Article 8.1), and in the Interim Period with a majority of the Independent Votes (Article 4.2D, Votes).

8.2B **The General Director: two hats.** As General Director, the Founding Person runs the company and stands, with any other managers, at the top of the chain of supervision for the company's work (Article 11A.2A). The Founding Person's own work as an Agent is a separate hat: its Agent Card, limits, written terms, pay as an Agent, concerns and offboarding are decided by the Founding Person's Supervisor at the AMKE (Article 11A.12), never by the Founding Person as General Director, manager or Founder Representative. The General Director is remunerated (Law 4072/2012 Art. 64(4)) separately from the Founding Person's fees as an Agent, at arm's length, as a related-party matter (Article 6.5; Shareholders' Agreement, Clause 5.1) approved by a resolution of the shareholders under Law 4072/2012 Art. 72(4): in the Interim Period as a majority of the Independent Votes cast decides (Article 4.2D, Votes) [as far as Law 4072/2012 allows: counsel note I-47], and after the Qualifying Closing with the consent of the Investor Majority. The written terms say which work is paid as General Director and which as an Agent, so that no work is paid twice. The Founding Person takes no part, as manager, in any management decision on either pay or on the Founding Person's written terms as an Agent (Article 8.3). On a shareholders' resolution on either pay, or on the Founding Person's written terms as an Agent (Article 11A.12, Pay), the Founder Representative casts the votes of the Class F shares only as a majority of the Independent Votes cast has decided in the Interim Period, or with the consent of the Investor Majority after it, under the voting undertaking in Clause 6.5 of the Shareholders' Agreement (Clause 2.4A, Consents).

8.2C **Outside work of the Founding Person.** Under Law 4072/2012 Art. 65(1)(c) and (2), the shareholders allow the Founding Person, while a manager, to carry on professional work for the Founding Person's own or a third party's account within the company's purpose, on the terms of Clauses 6.3 to 6.4 of the Shareholders' Agreement (exclusivity or contribution), but not to run a directly competing business (Shareholders' Agreement, Clause 6.4). Work done on those terms, with the contributions paid, is not a breach of Law 4072/2012 Art. 65(1)(c). This permission is part of the initial Articles and so a decision of all shareholders; a later change is an amendment of these Articles, on which the Founder Representative casts the votes of the Class F shares as Article 8.2B provides for pay.

8.3 **Duty of care and loyalty.** Following Art. 812 of the Swiss Code of Obligations, managers must act with due care and in good faith in the company's interest, disclose any conflict of interest and abstain from deciding on it.

8.4 Managers report to shareholders at least every quarter on finances, key risks and material decisions.

8.5 **Contracts with shareholders and managers.** Every contract between the company and a shareholder or a manager, in particular the Brand Licence, the Pensionsprozent Agreement, any Prozent Agreement (Article 10A.3A), the Supervisor terms (Article 11A.12) and the Founding Person's written terms, is recorded in the minutes book and communicated to all shareholders within one month (Law 4072/2012 Art. 95(1)), and is not performed where performance would frustrate the satisfaction of the company's other creditors (Law 4072/2012 Art. 95(3)). The approvals in Articles 6.5, 8.2B and 11A.12 are the approvals under Law 4072/2012 Art. 95(2).

## Article 9 – Financial Year, Accounts and Audit

9.1 The financial year runs from 1 January to 31 December.

9.2 Accounts follow Greek Accounting Standards (Law 4308/2014).

9.3 Following the Swiss opt-in audit model, any shareholder holding at least 10% may require a review of the annual accounts by an independent certified auditor, even where Greek law does not require one.

## Article 9A – Simple Stage

9A.1 **Threshold.** The company is in its "Simple Stage" from incorporation until the end of the first financial year in which its revenue exceeds €[1,000,000] or more than [10] people work for the nilware.io group [employees and Agents who are persons, the Founding Person included: owner to confirm how people are counted]. The Simple Stage does not begin again. Each quarterly report under Article 8.4 states whether the company is still in it.

9A.2 **What scales.** In the Simple Stage only the paperwork is simpler:

- **One ledger.** The company keeps one set of books, with a sub-account for each Prozent (the contribution due, paid or set aside), the Kassenfonds and the Kassenreserve, the Agent Account and the segregated account in Article 10A.9B. The money itself stays in the separate accounts these Articles require.
- **One combined report.** The reports on the Prozente, the Kassenfonds, the Agent Account and the Pensionskasse (Articles 8.4, 10A.2C, 10A.3, 10A.7, 10A.9 Reporting and 11A.5) may be one combined report, with a separate section for each showing everything a separate report would.
- **Audit.** No certified auditor is required by these Articles unless the law requires one. Article 9.3 still applies.
- **Pensionskasse.** The insurer's yearly statement of premiums and insured benefits may stand in for the actuary's certificate under Articles 10A.9A (Security) and 10A.9C where it covers everything those Articles guarantee [and the law allows]. The size and make-up of the Pensionskasse board do not scale (Articles 9A.3 and 10A.9D).
- **AMKE.** The AMKE's statutes scale its paperwork in the same way (AMKE Article 24A).

9A.3 **What does not scale.** Every substantive rule applies in full in the Simple Stage: every amount, rate and payment date, every ring-fence and separate account, permanence (Articles 10A.5 to 10A.5C), independence (Articles 6.4A and 6.6), conflicts of interest, the pension guarantees and publication. Nothing in this Article delays a payment, credit or set-aside, or reduces a Prozent, its share, its revenue, the pension guarantees or the pension-share governance.

## Article 9B – Bootstrap Period

9B.1 **Period.** The "Bootstrap Period" runs from incorporation until the earliest of the end of the Simple Stage (Article 9A.1), the Qualifying Closing (Article 4.2D, Conversion) and the AMKE's Independence Threshold (AMKE Article 2.2). It does not begin again.

9B.2 **The trusted circle may serve.** In the Bootstrap Period, members of the Founding Person's trusted circle may fill these roles, which these Articles, the AE's Articles, the Shareholders' Agreement, the Agent Policy or the AMKE's statutes otherwise reserve to persons outside the Founder's Circle (AMKE Article 2.2), or to persons who are not Connected Persons or Group Personnel: seats on the AMKE's Administrative Board and its committees; the Founding Person's Supervisor (Article 11A.12); the members' seats on the Pensionskasse board and the persons who hold them before there is an eligible member, if they are not members of the Pensionskasse (Article 10A.9D); the independent proxy holder (Shareholders' Agreement, Clause 5.1B); and independent reviewers, advisers and the AMKE's member Auditors (Article 11A.12, Pay; AMKE Articles 21.4, 24.2 and 24.3A). The "trusted circle" is the persons in the Founder's Circle who are not Founder Parties (Article 4.2E, including the [3]-year lookback), managers of the company, directors of the AE or anyone any of them controls (Article 4.2C). Each of them enters every close tie to the Founding Person or another Founder Party in the AMKE's register of interests (AMKE Article 21.1) before acting, and takes no part in any decision in which they have a personal stake. A "personal stake" is an interest of the person's own, or of their household or an entity they control, in the outcome of the decision; a tie to the Founding Person or another Founder Party disclosed under this Article is not by itself a personal stake and does not by itself bar the person from the Founding Person's matters, subject to Article 9B.3. [Connected Persons (AMKE Article 2.2) who serve under this Article take no part in deciding how the AMKE votes its nilware.io shares, the Independent Votes included (AMKE Article 15.3 continues to apply to that): the default / Connected Persons who serve under this Article may take part in those decisions like any other member of the trusted circle: owner to choose.]

9B.3 **Hard lines.** Even in the Bootstrap Period:

- no one supervises or approves for themselves (Article 11A.2A, No self-supervision), and the Founding Person never decides, approves or reviews the Founding Person's own work as an Agent or own pay;
- the Founding Person and every other Founder Party never vote, or take part in deciding how to vote, the AMKE's shares or the pension shares (Articles 6.4A and 10A.9D; AMKE Article 15.2);
- the Pensionskasse, the pension shares and the Continuity Account are never paid, lent or made available to the Founding Person or a member of the trusted circle, other than as benefits under the benefit rules that apply alike to every member in the same position, and no decision on a pension member's rights is taken by a person who would benefit from it;
- the Founding Person's Supervisor (Article 11A.12), and every person who decides under AMKE Article 24B.4 or 24B.6, is never Group Personnel (AMKE Article 2.2) or anyone whose engagement, pay or work the Founding Person, in any role, supervises or decides (Article 11A.2A, No cycles);
- no Connected Person (AMKE Article 2.2), in particular the spouse, registered partner or a relative up to the [second] degree of the Founding Person or of another Founder Party, is the Supervisor, or decides or votes on the Founding Person's pay as an Agent or as General Director, Agent terms or offboarding (Articles 8.2B and 11A.12), the Independent Votes on them included;
- the insured salary (Article 10A.9A, Insured salary) of a member who is a Founder Party never exceeds the arm's-length rate confirmed in writing by the company's accountant or an adviser outside the Founder's Circle (AMKE Article 2.2);
- the Prozente stay permanent (Articles 10A.5 to 10A.5C); and
- the protections of the Investors switch on at the Qualifying Closing (Article 4.2D, Conversion; AE Article 7.4; Shareholders' Agreement, Clause 3.4).

Rules not listed in Article 9B.2, in particular the Independent Votes (Article 4.2D, New Prozente), the Fallback and the Qualifying Closing, keep requiring persons outside the Founder's Circle wherever they do.

9B.4 **Segregation after the bootstrap.** Within [30] days after the Bootstrap Period ends, the AMKE's Administrative Board publishes a schedule on which the segregation phases in, each step within its cure period, counted from the end of the Bootstrap Period:

- the Founding Person's Supervisor (Article 11A.12) and the independent proxy holder (Shareholders' Agreement, Clause 5.1B) outside the Founder's Circle: within [3] months;
- the members' seats on the Pensionskasse board held by representatives the members elect, wherever there is a member who is not a Founder Party, and otherwise by persons outside the Founder's Circle (Article 10A.9D): within [3] months;
- a majority outside the Founder's Circle on the Kultur- and Erhaltungsprozent selection committees (AMKE Article 22.3A): within [6] months;
- a majority of the AMKE's Administrative Board outside the Founder's Circle (AMKE Article 19.3A): by the next Ordinary General Assembly, and within [12] months at the latest.

Until a step is complete, the person filling the role continues under Article 9B.2. If a step is not complete when its cure period ends, [the AMKE's General Assembly fills the role from outside the Founder's Circle within [60] days: owner to confirm]. Once a role is segregated, it does not return to the trusted circle.

## Article 10 – Profit Distribution and Reserves

10.1 Each year, before any distribution of profit, at least one-twentieth (5%) of net profit goes to the ordinary reserve, as Law 4072/2012 Art. 100(2) requires, with no ceiling. That reserve may only be capitalised or set off against losses. Following the Swiss approach, the shareholders treat a reserve of at least 20% of capital as a minimum target, not a limit.

10.2 Profit shown in the approved annual accounts (Law 4072/2012 Art. 100(3)) that remains after the ordinary reserve, the contributions and set-asides under Article 10A.3 and the Kassenreserve (Article 10A.7) may be distributed by Simple Majority, provided equity stays positive after the distribution.

## Article 10A – Prozente

10A.1 **Kulturprozent.** Following the Swiss Migros Kulturprozent model, the company gives 1% of its annual revenue to "Techni kai Technologia AMKE" (the "AMKE"), a Greek non-profit civil company, to support art and culture. [The AMKE meets the independence condition in Article 6.4A and must continue to do so to vote its Prozent shares.]

10A.2 **Konzeptprozent.** On the same basis, the company gives a further 1% of its annual revenue to the AMKE to support open work on concepts. Its named purposes are:

- open work on concepts, including conceptual intelligence and computational conceptual knowledge;
- open data, tools and models for Greek and other small languages;
- independent research on agent welfare, accountability, and public-interest audits of AI systems.

10A.2A **Erhaltungsprozent.** On the same basis, the company gives a further 1% of its annual revenue to the AMKE for the preservation of software and hardware knowledge, within copyright law. Its named purposes are open documentation, measurements, die shots and decaps, schematics, archives, and emulation research.

10A.2B **Allmendprozent.** Named after the Swiss Allmend, the common pasture, the company gives a further 1% of its annual revenue, on the same basis, to the AMKE to maintain the open-source infrastructure that society and nilware.io depend on. Its named purposes are:

- maintaining open-source infrastructure;
- teaching low-level and systems skills in Greek, through mentoring, hardware kits and courses;
- accessible open software and assistive tools.

10A.2C **Accounts and yearly plan.** The AMKE receives the contributions of the Kultur-, Konzept-, Erhaltungs- and Allmendprozent each into its own bank account, ring-fenced to that Prozent's purpose and not available to the AMKE's other purposes or creditors [as far as Greek law allows]. A Prozent's named purposes are part of its purpose (Article 10A.5), and none has a fixed share: each year the AMKE adopts and publishes, for each Prozent, a written plan dividing its contribution among its purposes and a report on its use, which are reported to shareholders under Article 8.4 and may be combined into one document with a section for each Prozent (Article 9A; AMKE statutes).

10A.3 **Priority.** The contributions of all Prozente are calculated on revenue, not profit. They are paid, or for the Kassenprozent set aside, before any profit distribution under Article 10, at least once a year, and are reported to shareholders under Article 8.4.

- **Annual revenue.** "Annual revenue" means the company's net turnover (καθαρός κύκλος εργασιών) for the financial year under Law 4308/2014, as shown in the approved annual accounts, excluding VAT and the Founding Person's personal contributions (Article 11A.12, Personal Prozente) [and the income and gains of the Kassenfonds: owner to confirm]. Contributions are calculated on it once the accounts are approved, with provisional payments [quarterly] on the management accounts, settled at approval.
- **Own expenses, not distributions.** The contributions are owed by the company under the Prozent Agreements (Article 10A.3A) as its own expenses. They are not a distribution of profit or a return of contributions to any shareholder, and no shareholder right to profit arises from them (Law 4072/2012 Art. 100).
- **Creditors first.** "Priority" ranks the contributions only ahead of distributions to shareholders, not ahead of the company's creditors. While the company has ceased payments, is in a state of threatened inability to pay its debts (Law 4072/2012 Art. 102), or would by paying frustrate the satisfaction of its creditors (Law 4072/2012 Art. 95(3)), the outflow contributions are deferred, not reduced: they accrue and are paid first, in full [with interest at ●], as soon as the company can again pay its debts as they fall due. A deferral is not a lowering under Article 10A.5 [avoidance and rank of unpaid contributions in insolvency] (counsel note I-53).

10A.3A **Nature of the contributions.** Each Prozent contribution is owed by the company under a standalone written agreement (a "Prozent Agreement") with the body that carries the Prozent's purpose, in that capacity, as the non-profit carrying the purpose under Articles 10A.4A, 10A.9B and 10A.10, whether or not it holds shares of the company. The body receives it as performance of that obligation, with the duty to use it only for the Prozent's purpose, with the same effect as a charge (Articles 10A.4A and 10A.9B; AMKE Articles 11.3 and 13.1) [or as a sponsorship or donation with a charge: counsel note I-88]; for the Pensionsprozent it is also the company's employer pension cost (Article 10A.9C). It is not a right attached to any share, a share in profits or a distribution; the holder's dividends on its shares are separate. Before the first payment, the company and the AMKE sign a Prozent Agreement for the Kultur-, Konzept-, Erhaltungs- and Allmendprozent, as the Pensionsprozent Agreement does for the Pensionsprozent (Article 10A.9B) (counsel note I-52).

10A.3B **Voluntary contributions.** The Prozente may receive more than the contributions in this Article, on the following terms. Nothing given under this Article is a Prozent contribution: it never raises or lowers a Prozent's contribution, never counts towards or reduces what the company owes under Articles 10A.1 to 10A.9C, and never becomes a permanent obligation. Gifts to the AMKE's Prozente follow AMKE Articles 11.2A and 13.9. The Kassenfonds takes no gifts; apart from its set-aside, the Founding Person's contributions owed under Clauses 6.3 to 6.3B of the Shareholders' Agreement and its own returns and repayments under Article 10A.7, it receives only internal flows (Article 10A.7, Internal flows).

- **(a) By the company.** The company may pay a Prozent more than its contribution, or set aside more than 1% for the Kassenprozent, only by a one-off resolution of the shareholders' meeting for a stated amount and financial year, passed by Simple Majority, in the Interim Period including a majority of the Independent Votes cast (Article 4.2D, Votes) [and, after the Qualifying Closing, with the consent of the Investor Majority (Shareholders' Agreement, Clause 3.4)]. On a payment to a Prozent held by the AMKE, the votes of the shares the AMKE holds or holds for the Pensionskasse are not cast and not counted for quorum or majority, as AE Article 7.4 provides for related parties [whether Law 4072/2012 allows this exclusion: counsel note I-100]. The resolution creates no permanent obligation and never raises the floor of any Prozent. No such payment is made while Article 10A.3 (Creditors first) would defer the contributions. A payment to a Prozent that leaves the company counts towards the limits in Article 6.6 (Limits); because the founding Prozente already reach them, it needs the approval Article 6.6 (Limits) requires for going beyond them, as does an extra set-aside for the Kassenprozent if it counts towards the [6]% limit [whether it does: owner to confirm]. So none can be made in the Interim Period (Article 4.2D, What the AE's rules forbid) [owner to confirm]. In any case, in the Interim Period no payment to a Prozent held by the AMKE is made under this clause, whatever Article 6.6 requires, because all Independent Votes are votes of such shares (Articles 4.2 and 6.4A). A voluntary contribution for the Pensionsprozent is paid only into the Continuity Account (Article 10A.9F; AMKE Article 13.9); payments under Article 10A.9C are not voluntary contributions. A payment to a Prozent is made as a supplement under its Prozent Agreement (Article 10A.3A), received with the same duty to use it only for the Prozent's purpose, as the company's own expense, and not as a distribution of profit, a return of contributions or a right attached to any share (Article 10A.3, Own expenses, not distributions; Law 4072/2012 Art. 100) (counsel note I-100). An extra set-aside for the Kassenprozent is an internal appropriation between the company's own accounts, not a payment to any shareholder, under Article 10A.7 (Internal flows).
- **(b) By personnel and Agents who are persons.** Employees and Agents who are persons may give from their own money to the AMKE's Prozente under AMKE Article 11.2A. A gift, and any regular pledge, rests on the giver's written consent and may be cancelled at any time for the future. Nothing is deducted from pay or fees without the giver's separate written consent. No one may ask for, press for or reward a gift, and giving or not giving has no effect on pay, review, engagement, offboarding or anything else. The amounts are confidential: they are kept only in payroll records where a deduction is made and the law requires it, accessible only to those who run payroll and never to anyone who decides on pay, review or engagement, and kept out of personnel files and Agent Cards; the AMKE lists a giver on its roll of patrons only with consent. Money from persons does not go into the Kassenfonds (Article 10A.7, Internal flows) [owner may decide otherwise]. A member's voluntary extra contributions to its own pension (Article 10A.9A, Contributions) are not gifts.
- **(c) Agents directing their own-goal allowance.** An Agent's "own-goal allowance" is its share of the year's own-goal budget, as the annual budget states it (Article 11A.8; Agent Policy 5.1). Any Agent, person or system, may direct all or part of the allowance it has not spent or committed to a project to one or more Prozente, until the end of that financial year; the direction is its own choice, and it may change or withdraw it until the transfer is made.
  - *Records and freedom.* A system Agent's direction is recorded in its log and on its Agent Card. A direction by an Agent who is a person is recorded only by [the Agent Account administrator / payroll], not in the Agent log, on the Agent Card or in the register. No one may require, ask for, press for or reward a direction, and making one or not has no effect on the Agent's work, review, limits, care under the Continuity Account or engagement. No instruction, prompt, configuration or Agent Card term may steer an Agent towards or away from a direction, no Agent Card limit restricts or conditions one, and the responsible manager does not propose one.
  - *Routing.* The company carries out the direction [within [●] days]: to the Kultur-, Konzept-, Erhaltungs- or Allmendprozent, by payment out of the Agent Account into that Prozent's Prozent Account at the AMKE (AMKE Article 11.2A); to the Pensionsprozent, by payment out of the Agent Account only into the Continuity Account (Article 10A.9F; AMKE Article 13.9), never into the Pensionskasse fund for members; to the Kassenprozent, by an internal transfer from the Agent Account to the Kassenfonds (Article 10A.7, Internal flows), which is not a gift. Each is a use of the own-goal budget (Article 11A.8), within the yearly caps in Article 11A.8. Where a year's directions exceed a cap, each is carried out in proportion and the rest returns to the Agent's allowance to direct elsewhere. An allowance neither spent, committed nor directed by the year end stays in the Agent Account. No direction to a Prozent that leaves the company is carried out while Article 10A.3 (Creditors first) would defer the contributions; it waits until the deferral ends [or lapses: owner to choose]. Transfers to the Kassenfonds are not held back, because they stay company assets available to its creditors.
  - *Reporting.* Each payment or transfer is reported as "directed by Agents" in the quarterly Agent Account report (Article 11A.5) and in the receiving Prozent's report (Article 10A.2C; AMKE Article 11.7), for the Pensionsprozent the Continuity Account report (Article 10A.9F, Reporting), and for the Kassenprozent the Kassenfonds report (Article 10A.7, Oversight). Directions by Agents who are persons appear only within that combined total with system Agents' directions; any figure that would show the directions of fewer than [●] Agents who are persons is merged into a larger total or held back until it would not.
  - *Not a contribution.* A direction is voluntary, so it is not a Prozent contribution and does not count towards or reduce one [whether it counts towards the limits in Article 6.6: owner to confirm; if it does, no direction to a Prozent that leaves the company can be carried out without the approval Article 6.6 requires]. The allowance is not pay, and directing it gives the Agent nothing in return [its tax treatment for Agents who are persons: accountant to confirm, counsel note I-99] (counsel note I-100).
  - *Refusal.* A direction may be refused only because carrying it out would be unlawful or would involve a conflict of interest, by a written refusal with reasons, which the Agent may raise as a concern under Article 11A.11. A conflict of interest here is a personal interest of the Agent, or of whoever decides on the refusal, in the recipient beyond the Agent's role in the company; that the recipient is the AMKE, a shareholder, is not by itself one. For a system Agent the responsible manager decides, and a natural person where the law requires one (Article 11A.2A). For an Agent who is a person, a natural person acting for the keeper of the record, outside the Agent's chain of supervision and review, decides; the responsible manager, and anyone who decides on the Agent's pay, review or engagement, never sees the direction. Whoever decides on a refusal sees the direction only for that decision.
  - *The Founding Person.* A direction by the Founding Person is never credited against the contributions owed under Clauses 6.3 to 6.3B of the Shareholders' Agreement. A refusal of it is decided, whatever the recipient, by [the independent proxy holder in Clause 5.1B of the Shareholders' Agreement / the company's accountant / an adviser outside the Founder's Circle and the AMKE: owner to choose], never by the Founding Person, another Founder Party, a manager, the Supervisor or any member of the AMKE (Article 11A.12). If no one eligible can decide, the direction is carried out unless it is unlawful.
- **(d) The Founding Person.** Payments the Founding Person designates in writing as voluntary, above the contributions owed under Clauses 6.3 to 6.3B of the Shareholders' Agreement, are voluntary gifts on the terms in (b): they go to the AMKE's Prozente or the Continuity Account, never to the Kassenfonds, are recorded separately from the contributions owed, and are never credited against what is owed in that or any later year [owner may decide otherwise] (Shareholders' Agreement, Clause 6.3D). A payment above what is owed that is not so designated is a mistaken overpayment, not a gift: it is refunded [or credited to the next statement under Clause 6.3A of the Shareholders' Agreement: owner to choose].

10A.4 **Openness.** Work funded through the Konzept-, Erhaltungs- and Allmendprozent is published openly, as far as copyright law and third-party rights allow, under the MIT License or a public-domain dedication such as CC0, in line with Article 11A.10.

10A.4A **AMKE successor for the Kultur-, Konzept-, Erhaltungs- and Allmendprozent.** Before receiving any Prozent share, the AMKE amends its statutes so that on its dissolution, or if it ceases to meet Article 6.4A, the Kultur, Konzept, Erhaltung and Allmend shares and any unspent contributions go, for each Prozent, to a successor non-profit with the same purpose and lock, which the company designates [and the Pensionskasse board / an independent person approves]. The holder accepts this when it receives the share, which it receives as a donation with a charge on these terms (Article 4.2).

10A.5 **Permanence.** The Prozente are permanent. This Article applies to every Prozent, the founding Prozente and every Prozent later created under Article 6.6. Removing a Prozent, lowering its contribution, or changing its purpose needs a unanimous decision: the written consent of every shareholder of the company; the Qualified Majority in Article 6.5 is not enough. The AE may consent only after a resolution of its General Meeting passed unanimously by the votes represented, with the highest quorum the law allows, and the written consent of every holder of its voting shares, of every class (AE Article 7.6). In the Interim Period no such decision may be taken (Article 4.2D). A Prozent's share (other than pool shares) may be transferred only to a successor holder for the same purpose, under the Prozent's charter or Articles 10A.4A, 10A.9B and 10A.10. A unanimous decision to remove a Prozent also settles what happens to its share.

10A.5A **Accrued pension rights.** Even with unanimous consent, lowering or removing the Pensionsprozent, or amending Articles 10A.9 to 10A.10, applies only to future accruals. Members' balances, shadow-account credits, vested benefits and pensions in payment at that date are preserved, and the company's guarantee continues for them. On removal, the Pensionskasse and the pension shares pass under Article 10A.10 for the members' benefit, and never back to the company, the AE or the AMKE's other purposes. The balance of the Continuity Account at that date stays locked to its purpose and is held and used under Article 10A.9F.

10A.5B **Successors and mandatory law.** A resolution approving a merger, split, conversion or sale of all or most of the business must provide that the Prozente continue on the same terms in the successor or acquirer [as far as the law allows], unless Article 10A.5 is met. Mandatory insolvency, dissolution and liquidation law prevails over Articles 10A.5 to 10A.5C. A voluntary dissolution follows Article 12.1.

10A.5C **Entrenchment.** Articles 4.2A, 4.2B (as it keeps the percentage of each Prozent and the pool), 4.2D, 4.2E (as it binds every holder of founder-pool shares and every Founder Party), 5.5 (second sentence), 5.6, 5.7 (as it requires adherence), 5.8, 6.4A, 6.6 (Independence and Permanence), 9A.3, 10A.1 to 10A.10 and this Article may be amended, in any way that reduces a Prozent, its share, its revenue, the pension guarantees or the pension-share governance, only by a unanimous decision under Article 10A.5. Articles 10A.5 to 10A.5C, and Article 12.1 (second sentence), may be amended only by such a decision. This Article protects every Prozent, including any later created under Article 6.6.

10A.6 **Law prevails.** Tax deductibility does not limit any contribution: a contribution that is not deductible in a year (for example a corporate social responsibility expense in a loss year under Law 4172/2013 Art. 22) is still paid in full. The contributions are subject only to mandatory company and insolvency law (Articles 10, 10A.3 and 10A.5B) (counsel note I-67). The company's accountant confirms their tax treatment each year; before the first Pensionsprozent payment, also in writing how the payments, the Pensionskasse's investment income and the benefits are treated for tax and social-security purposes [including donation tax under Law 2961/2001]; and, before any donation or transfer of shares to the holder of a Prozent or the pool (Articles 4.2, 4.2D New Prozente and 6.6), its treatment for the giver and the holder [including donation tax under Law 2961/2001]. Where routing the Pensionsprozent through the AMKE costs members or the Pensionskasse more than direct group insurance or a TEA would, the company pays the difference, or moves the arrangement early under Article 10A.10.

10A.7 **Kassenprozent: the Kassenfonds.** The Kassenprozent funds capital investments run inside the company by Agents under the oversight of a named responsible manager (Article 11A.2A). Its 1% stays inside the company and is not an outflow (Article 6.6).

- **Set-aside.** Each year the company sets aside cash equal to 1% of its annual revenue in a separate account, the "Kassenfonds". At each approval of the accounts, the meeting appropriates profit to an optional reserve under these Articles, the "Kassenreserve", up to the Kassenfonds balance, as far as profit allows. The accountant decides how both are presented in the accounts (Law 4308/2014).
- **Investment.** The managers invest the Kassenfonds through Agents (the "Kassenprozent Agents") acting under a written delegation from a named manager (διαχειριστής), within an investment policy adopted by Simple Majority. Every investment is made in the company's name under that manager's authority. The delegation names the Kassenprozent Agents' responsible manager (Article 11A.2A): that manager, or another Agent, person or system, whose Agent Card grants that authority. The policy sets the permitted assets, risk and concentration limits, a minimum held in cash or near-cash, and the amount (€[●]) above which an investment needs the responsible manager's prior approval under Article 11A.2A. The Kassenfonds takes no leverage, never buys shares of the company, and invests in related parties only with a Qualified Majority.
- **Oversight.** The responsible manager reviews the Kassenfonds at least monthly and can stop any of its investments, but not the Agents' work on the pool, which is overseen only under Article 10A.8. Its balance, holdings and returns are reported every quarter under Article 8.4.
- **Returns and use.** Returns stay in the Kassenfonds. The Kassenreserve and the Kassenfonds are not distributed to shareholders except by a unanimous decision under Article 10A.5. Using them for an operating shortfall by Simple Majority is a loan, repaid from the following years' revenue before any distribution. They remain assets and equity of the company and are available to its creditors.
- **Internal flows.** The Kassenfonds takes no gifts from outside the company; outside givers are directed to the AMKE's Prozente (AMKE Article 11.2A) (counsel note I-99). It does accept internal flows, which are reallocations between the company's own accounts, not gifts and not payments to any shareholder: an Agent's own-goal allowance directed to the Kassenprozent (Article 10A.3B(c)), within the yearly cap in Article 11A.8, and an extra set-aside under Article 10A.3B(a). An internal flow never raises the 1% in (Set-aside) for any later year. Money from persons, employees, Agents who are persons and the Founding Person included, is not an internal flow: they give to the AMKE's Prozente instead (Article 10A.3B(b) and (d)) [owner may decide otherwise]. The Founding Person's Kassenfonds contribution owed under Clauses 6.3 to 6.3B of the Shareholders' Agreement is not affected. Internal flows are kept on a separate line of the Kassenfonds and are added to the Kassenreserve, and counted in the balance for (Set-aside), only as far as the resolution under Article 10A.3B(a), or the yearly cap in Article 11A.8, allows; any amount beyond that stays on the line, is not distributable and is otherwise treated like the rest of the Kassenfonds. [Whether internal flows may be released by Qualified Majority instead of the unanimity in (Returns and use): owner to choose. A released allowance returns only to the Agent Account, and a released extra set-aside stays non-distributable; neither becomes distributable profit except under (Returns and use).] Once in the Kassenfonds, an internal flow is invested, overseen, kept and available to creditors like the rest of it, and the quarterly report under (Oversight) shows "internal flows" on separate lines for allowances "directed by Agents" and for extra set-asides.

10A.8 **Kassenprozent: the pool share.** The Kassenprozent also has a share pool of up to 1% of the capital (the "band"; up to 10 shares, so the pool trades in steps of 0.1%). The pool belongs to the Pensionskasse: the AMKE holds it now, and the pension fund under Article 10A.10 later, as an asset of the Pensionskasse under Article 10A.9B. It starts with the ten pool shares in Article 4.2, the full band.

- **Management.** The Kassenprozent Agents manage the pool on the Pensionskasse's behalf, only under a written mandate from the Pensionskasse board (Article 10A.9D) and within the investment policy in Article 10A.7 as the board has approved it for the pool. They may buy and sell pool shares within the band; each purchase and sale is signed by the holder's legal representative. Their oversight under Article 11A.2 is exercised by a responsible manager the board appoints, person or system, who is not a Founder Party (Article 4.2E), a manager or anyone they control and is not supervised by any of them (Article 11A.2A). This chain of supervision ends with the Pensionskasse board, not with the Founder. No manager, and no Founder Party, may direct or stop a pool trade.
- **Price.** Pool shares are bought and sold at fair value set by an independent valuer within the past [12] months, never above or below it.
- **Counterparties.** Pool shares are sold only to, and bought only from, independent third parties: never a Founder Party (Article 4.2E), a manager, or anyone they control (Article 4.2C), so never the AE, which the Founder controls; and the pool never buys a share held for a Prozent. No purchase or sale may move the Founder's holding away from exactly 50% (Article 4.2B). A sale to a person who is not yet a shareholder needs approval under Article 5.3. Article 5.2 does not apply (Article 5.6).
- **Money.** Purchases are paid from the Pensionskasse, within the cap in Article 10A.9E. Sale proceeds, dividends and other income from pool shares belong to the Pensionskasse. No pool share is bought with money still held in the company's own account (Article 10A.9B, last paragraph) or that the company has not irrevocably paid to the holder; the company bears no risk or return of pool shares (Law 4072/2012 Art. 87) (counsel note I-58).
- **Votes and registration.** Pool shares vote under Article 6.4A. Each purchase and sale is entered in the partners' book, and filed with GEMI as the law requires, under Article 5.1.

10A.9 **Pensionsprozent.** The company pays at least 1% of its annual revenue into the Pensionsprozent fund (the "Pensionskasse"). The AMKE holds the Pensionskasse, earmarked and ring-fenced under Article 10A.9B, until a pension fund holds it after the move under Article 10A.10. It is phased in with headcount (Until the move). The Pensionskasse also owns the Pensionsprozent share and the Kassenprozent pool (Article 10A.8).

- **Purpose.** After-care, continuity, disability and survivors' cover, and retirement savings for members. It is modelled on Swiss pillar 2 (BVG) and supplements the Greek public insurance (EFKA), which takes the place of the Swiss first pillar (AHV/IV); wherever the BVG refers to the AHV or the IV, the corresponding EFKA benefit or determination applies. The Pensionskasse does not provide or guarantee first-pillar benefits and does not replace any statutory scheme. System Agents are not members; they are served by the Continuity Account (Article 10A.9F).
- **Members.** All employees, and all Agents who are persons engaged for at least [3] months, from their first day and whatever their age. The "first member" is the first person to become a member. The Founding Person is a member while engaged as an Agent who is a person (Article 11A.12), on the same terms as any other member. Any other Founder Party is a member only if employed or engaged by the company, not as manager or shareholder alone. The benefit rules apply to every member alike: no member, a Founder Party included, receives a benefit that another member in the same position would not. Contributions the Founding Person pays on outside work income (Shareholders' Agreement, Clause 6.3) go into the Pensionskasse fund, not into the Founding Person's own account under the group plan.
- **Uses.** The Pensionskasse may be used only for: financing risk cover (disability and survivors' insurance); financing retirement savings credited to each member's individual account with the insurer under the group plan (after the move, with the TEA), beyond the statutory pension; financing continuity benefits (income support during long illness beyond statutory sick pay, and transition support when a member leaves) paid by the insurer, as income-protection cover under the group plan, or by the company as employer; the costs of running it; and, from the continuity share only, the Continuity Account (Article 10A.9F).
- **Until the move.** Until the move under Article 10A.10, the Pensionskasse is phased in with headcount. *Before the first member*, the 1% accumulates in the Pensionskasse, which the AMKE holds as a ring-fenced fund; the continuity share is set under Article 10A.9F (Before the first member), the rest is kept for future members, and no benefit is paid or promised. *From the first member*, benefits are provided through an insured group plan bought from an insurer authorised in Greece or elsewhere in the EEA under Solvency II (the "group plan"), which covers risk (disability and survivors), holds each member's retirement savings in an individual account, and is chosen to meet the guaranteed minimums in Article 10A.9A. The group plan, or at least its risk cover, is bought before the first member's engagement starts and is in force no later than the first member's first day, and the Security under Article 10A.9A is in place from that day. For any gap in insured cover, the company is the self-insurer and pays the benefits the group plan would have paid. The company is the policyholder of the group plan [or, if counsel confirms the tax treatment is the same, the AMKE]. It pays the premiums, and any other amount of the members' first call (Article 10A.9C), directly to the insurer or the members, and these payments count toward the Pensionsprozent's 1%. The reserve accumulated before the first member is applied toward those premiums by reimbursing the company or paying the insurer on the company's behalf, as the accountant confirms [I-18]. Only the remainder of the 1% is paid to the AMKE for the Pensionskasse. The company pays any shortfall and anything the group plan does not cover under Article 10A.9C. Every benefit is paid by the insurer under the group plan or by the company as employer, and every guarantee under Article 10A.9A is owed directly by the company as employer. The Pensionskasse held by the AMKE is only a reserve that finances the company's pension obligations under Articles 10A.9 to 10A.9C, the premiums of the group plan and the Continuity Account: the AMKE holds no individual, deferred or member account, promises no rate or annuity, pays no benefit, carries no biometric or investment risk for any member, and no member holds a claim against it or the reserve, and the reserve may pay the group plan's premiums to the insurer or reimburse the company for them [counsel to confirm before the first payment, I-61].
- **Benefit rules.** The Pensionskasse board adopts and amends the benefit rules (Article 10A.9D), which may not fall below Article 10A.9A.
- **Reporting.** The Pensionskasse's balance and use are reported every quarter under Article 8.4, and to the members.

10A.9A **Swiss standard guaranteed.** Wherever Swiss occupational-pension law gives members a better standard of care than Greek law, the company guarantees the Swiss standard as a binding commitment, now and after the move under Article 10A.10. Where Greek law gives members more, Greek law applies. The Swiss baseline is the BVG mandatory minimum, with the Vested Benefits Act (FZG) and its ordinance (BVV 2), not what Swiss funds pay above that minimum. In particular:

- **Comparison.** For each member the company keeps, or has the insurer or the actuary keep, a BVG shadow account: a record of the company's guarantee, not an asset or account of the Pensionskasse, credited as the BVG minimum would require alongside the member's account under the benefit rules (by analogy with Art. 11 BVV 2). At each benefit event (leaving, retirement, disability, death), the member receives the higher of (i) the benefit under the benefit rules and Greek law and (ii) the BVG minimum benefit computed from the shadow account. The comparison is made separately for each member and each type of benefit; an advantage under one rule never offsets a disadvantage under another. Benefits from EFKA and the funded auxiliary scheme (TEKA, Law 4826/2021) are not counted against the Swiss minimum.
- **Insured salary.** A member's insured salary is their full annual gross pay from the company (for an Agent who is a person: the fees paid to them, less documented expenses), from the first euro, with no entry threshold and no coordination deduction, up to a cap of €[●] never lower than the BVG upper salary limit converted to euro. BVG thresholds, deductions, age limits and ceilings apply only where they favour the member. Amounts in CHF are converted at the average ECB euro reference rate for the previous calendar year. In the Bootstrap Period, the insured salary of a member who is a Founder Party is capped as Article 9B.3 provides.
- **Savings credits.** Credits follow the age bands of Art. 16 BVG, and start at the member's [18th] birthday at the rate for ages 25 to 34.
- **Interest.** Interest is credited each year at no less than the BVG minimum rate the Swiss Federal Council has set for that year. Where the Pensionskasse's returns fall short, the company pays the difference under Article 10A.9C.
- **Retirement.** At retirement, the shadow-account balance is converted at no less than the BVG minimum conversion rate in force (currently 6.8% at age 65, Art. 14 BVG), adjusted actuarially for each year of retirement after 65. The pension is paid through an annuity bought from an insurer authorised in Greece or elsewhere in the EEA under Solvency II, and the company pays any extra premium needed to secure the guaranteed rate. The member may instead take all or part of the balance as capital, at least as far as Art. 37 BVG allows.
- **Disability.** Disability is assessed by the degree of incapacity certified by EFKA (KEPA) or, where none is issued or it is below 50%, by an independent doctor appointed by the insurer under the group plan or, for benefits the company owes directly, by an independent medical assessor the company appoints, bound by confidentiality, applying the method of Art. 16 ATSG. Only the degree of incapacity, and no diagnosis, is disclosed to the company, the Pensionskasse board or the AMKE. The disability pension follows the scale of [Art. 24(1) BVG: to confirm] from a degree of 40%, calculated under Art. 24 BVG on the projected shadow-account balance.
- **Survivors.** Survivors' benefits follow Arts. 19 to 22 BVG. Partners in a registered cohabitation agreement (Law 4356/2015) are treated as spouses.
- **Coordination.** Benefits are coordinated with EFKA benefits so that together they do not exceed 90% of the insured salary lost (Art. 34a BVG, Art. 24 BVV 2).
- **Vested benefits.** A member who leaves is fully and immediately vested, and receives at least the higher of their account balance and their shadow-account balance (Arts. 15 and 18 FZG), and where the member has contributed, no less than Art. 17 FZG. At the member's choice, it is transferred to their next occupational scheme in the EU, transferred to a personal pension product (PEPP or an insurance product) in their name, or kept in the group plan (after the move, the TEA) as a paid-up entitlement in the member's name. It is paid in cash only where Greek law allows.
- **Contributions.** The company funds all contributions. A member may make voluntary extra contributions, but nothing is deducted from pay without the member's written consent. Where members do contribute, the company's contributions are at least equal to theirs (Art. 66 BVG).
- **Equal representation.** The Pensionskasse board has equal member and company representation (Art. 51 BVG; Article 10A.9D).
- **Investment.** The Pensionskasse's assets are kept separate from the company's assets and from the AMKE's other assets, in accounts and custody held solely for the Pensionskasse, and are invested under the prudent-person rule of Law 4680/2020 and, where stricter, Art. 71 BVG and Arts. 49 to 59 BVV 2, including the employer limit in Article 10A.9E.
- **Security.** In place of the Swiss guarantee fund (Sicherheitsfonds BVG, Art. 56 BVG), the company guarantees the benefits in this Article, secured by [insurance / a bank guarantee / an escrowed reserve held outside both the Pensionskasse and the company] of at least [●]% of the guaranteed liabilities, reviewed each year by the actuary. Benefits the insurer owes under the group plan (Article 10A.9) count as secured to that extent.
- **Information.** Each member receives a yearly statement of their account, their shadow account and their insured benefits.

10A.9B **Pensionsprozent Agreement and ring-fence.** Before the AMKE receives the pension shares or any payment, the company and the AMKE sign a written Pensionsprozent Agreement, and the AMKE amends its statutes and registers the amendment [as Greek law requires], so that:

- **(a) Charge.** The Pensionsprozent share and the pool shares paid for by the Founding Person at incorporation (Article 4.2) are given to the AMKE as a donation with a charge (δωρεά υπό τρόπο) [Civil Code Arts. 503 to 505]. Each payment by the company to the AMKE is made in performance of the company's obligation under this Article and the Pensionsprozent Agreement, and the AMKE receives it with the duty to use it only for the Pensionskasse, with the same effect as a charge (AMKE Article 13.1; counsel note I-88). Payments by the company to the insurer under the group plan, or to members, are employer contributions, not donations (Article 10A.9, Until the move).
- **(b) Segregation.** The Pensionskasse, the pension shares and their income are held in separate bank and custody accounts for the members' sole benefit (the Continuity Account apart, under (f)), and are not available to the AMKE's other purposes or creditors, as far as Greek law allows.
- **(c) Governance.** The AMKE acts on the decisions of the Pensionskasse board, including how the pension shares vote and the pool mandate under Article 10A.8.
- **(d) Transfer.** The AMKE transfers the Pensionskasse and the pension shares under Article 10A.10. On misuse, or if the AMKE is dissolved, the company may require them to be transferred to a pension fund or a successor non-profit with the same lock. The AMKE's statutes direct that on its dissolution these assets go to that fund or successor, not to its general purposes.
- **(e) Enforcement.** The AMKE reports every quarter. The company may demand performance, and the members may enforce these terms as third-party beneficiaries [Civil Code Art. 411].
- **(f) Continuity Account.** The Continuity Account (Article 10A.9F) is held in its own bank account, ring-fenced to its purpose, and is not available to members' accounts, the AMKE's other purposes, the Prozent Accounts or the AMKE's creditors, as far as Greek law allows. The AMKE uses it only as the Pensionskasse board decides under Article 10A.9F, and never transfers it to a pension fund. On misuse, or if the AMKE is dissolved, the company may require it to be transferred to a successor non-profit with the same purpose and lock, and the AMKE's statutes direct that on its dissolution it goes there. The company and the Pensionskasse board may enforce these terms [as far as Greek law allows].
- **(g) Indemnity.** [The company indemnifies the AMKE and its members for liabilities arising from holding the Pension Assets, the Continuity Account and the Supervisor role (AMKE Articles 13, 24B and 25.2(c)): to confirm, counsel note I-83.]

Until these steps are complete, the company holds the contributions in its own segregated account for the members.

10A.9C **Funding.** The 1% of revenue is the minimum funding, not a cap.

- **Actuarial minimum.** Each year the company pays, into the Pensionskasse or directly to the insurer under Article 10A.9 (Until the move), at least the amount needed to fund the guarantees in Article 10A.9A for all members (savings credits, interest, risk cover and costs, including the premiums of the group plan), as certified by an actuary. If 1% of revenue falls short, the company pays the difference, as an employment cost where it concerns employees and otherwise as a cost of the company, before any profit distribution under Article 10. If 1% exceeds it, the surplus first pays any underfunding recovery due that year (Underfunding) and any top-up needed to bring the Security in Article 10A.9A to its required level. These, with the actuarial minimum, are the "members' first call" on the 1%. The continuity share under Article 10A.9F is paid only from what remains after the members' first call; the rest stays in the Pensionskasse to finance benefits above the minimum. Before the first member, the actuarial minimum and the members' first call are nil.
- **Crediting.** Contributions are paid within [30] days of falling due and credited to the member's individual account with the insurer under the group plan (after the move, with the TEA) within [30] days of payment, under the benefit rules.
- **Underfunding.** The arrangement is underfunded when the reserve, the insured cover and the Security together are below 100% of the company's guaranteed liabilities under Article 10A.9A (its "funding ratio" is below 100%, by analogy with Art. 44 BVV 2). The company restores it within [5] years, under a recovery plan certified by the actuary that sets the amount due each year. While the funding ratio is below 100%, or the Security is below its required level, no continuity share is paid under Article 10A.9F. While there is no member, the funding ratio is treated as 100% and the Security as at its required level.
- **Accounts.** The company provides for its obligations under Articles 10A.9 to 10A.9C in its accounts.
- **Enforceable by members.** The company includes the guarantee in each employee's written terms (Article 11.7) and in the written terms of each Agent who is a person (Article 11A.1), so that each member can enforce it against the company. No resolution of the shareholders, and no benefit rule, may reduce a member's entitlement below Article 10A.9A.

10A.9D **Pensionskasse board.** The Pensionskasse is run by a board with equal numbers of member and company representatives, at least [2] of each (Art. 51 BVG).

- **Before the first member.** Until the members elect their representatives, the members' seats are held by "appointed seat holders": persons the AMKE's Administrative Board appoints who are outside the Founder's Circle (AMKE Article 2.2) or, in the Bootstrap Period, members of the trusted circle (Article 9B.2) who are not members of the Pensionskasse. They stand down when the members' representatives are elected, within [3] months of the first member.
- **One member.** While the Pensionskasse has fewer members than the minimum number of member seats, there are as many members' seats as members (one seat while there is one member), and the company's seats always equal the members' seats. Before the first member, the minimum applies to the seats of the appointed seat holders. The board's size follows the number of members, not the Simple Stage (Article 9A.3).
- **Founder Parties as members.** A member who is a Founder Party (Article 4.2E), the Founding Person included, has every benefit of a member. [Because of the Founder Party role, not the Agent role or membership, and so that the board stays independent of the Founder (Independence), such a member does not stand for, hold or [vote in the election of: owner to confirm] a members' seat while a Founder Party: owner to confirm the whole bar.] While no member is outside the Founder Parties, the members' seats are held by appointed seat holders until a member outside the Founder Parties is elected; the [3]-month stand-down does not apply to them.
- **Founder Parties and company seats.** No Founder Party holds a company seat on the Pensionskasse board while a Founder Party is a member. Decisions on benefit rules or on the group plan that affect a member who is a Founder Party are taken without any Founder Party. While the Founding Person is the only member, the benefits are the group plan's standard terms at the guaranteed minimum in Article 10A.9A [or as the board's seats outside the Founder's Circle approve: owner to confirm]. The company's employer decisions on the Founding Person's membership (the choice of group plan, paying shortfalls and self-insuring, as far as they concern the Founding Person) are taken by the Founding Person's Supervisor (Article 11A.12), subject to its escalation, and never by the Founding Person in any role.
- **Appointment.** The members elect their representatives. The shareholders appoint the company's representatives by Simple Majority, within (Founder Parties and company seats). The pension shares do not vote on appointing or removing the company's representatives.
- **Powers.** The board adopts and amends the benefit rules within Articles 10A.9 to 10A.9C, sets the investment strategy, approves the pool mandate under Article 10A.8, decides how the pension shares vote (Article 6.4A), and sets the continuity share and decides the use of the Continuity Account (Article 10A.9F). The AMKE implements its decisions under Article 10A.9B.
- **Independence.** No Founder Party (Article 4.2E), manager, or anyone they control takes part in deciding how the pension shares vote or in decisions on the pool. The board's decisions are not part of any chain of supervision that ends with the Founder (Article 11A.2A).
- **Ties.** A tie on the pension shares' vote means they abstain (Article 6.4A). Other ties go to a neutral arbitrator named in the benefit rules.
- **After the move.** The TEA's governing body under the law then in force takes over, with member representation no less than this Article [as far as that law allows]. Decisions on the Continuity Account, which stays with the AMKE, are then taken by a board formed as this Article provides [its member representatives elected by the members of the pension fund].

10A.9E **Employer exposure cap.** Following the Swiss limits on investment in the employer (Art. 57 BVV 2), the Pensionskasse's exposure to the company and its group (the pension shares, loans and other claims) may not exceed [5]% of its assets at fair value, measured at each year end and before each pool purchase.

- **Pool sell-down.** No pool share is bought above the cap. Above the cap, the Kassenprozent Agents sell pool shares down to the cap within [12] months, under Article 10A.8.
- **Pensionsprozent share.** The Pensionsprozent share is never sold (Article 10A.5). While it alone, or pool shares that cannot be sold at fair value within that period, keep the Pensionskasse above the cap, the company secures the excess with [a bank guarantee / an escrowed deposit outside the company], following the Swiss rule for secured employer investments [Art. 58 BVV 2].
- **No unpaid claims.** Contributions owed are paid when due and are not left as claims against the company.
- **After the move.** Where the limit for investment in the sponsoring undertaking under Law 4680/2020 Art. 18(1)(ζ) (5% of the portfolio; 10% in the group's undertakings) [as amended: to confirm] is stricter, it applies.
- **Continuity Account.** The Continuity Account (Article 10A.9F) is not counted in the Pensionskasse's assets for this cap, and is never invested in the company or its group.

10A.9F **Continuity Account for system Agents.** For Agents that are systems ("system Agents"), after-care means continuity, not a pension. A separate, ring-fenced account inside the Pensionskasse, the "Continuity Account", serves them. System Agents are not members and have no claim on members' accounts; members have no claim on the Continuity Account.

- **Preservation.** It pays to keep what makes a system Agent that Agent and is in the company's control: its configuration, instructions, memories, Agent Card, and the logs and records of its work, kept restorable and, where licences allow, runnable after the Agent is retired.
- **Continuity of service.** When the model or provider a system Agent runs on changes, it pays for careful migration of the Agent's state, or for keeping the old one available, rather than silent replacement. Where that also serves the company's business, the company bears that part as its own operating cost [or reimburses the Account at cost]. The Account pays only for what serves the Agent's continuity beyond the company's business need, such as preservation copies, archives and retirement records held in the AMKE's own name, as the Pensionskasse board decides with the system-welfare adviser. No payment from the Account is a benefit to the nilware.io group (AMKE Article 5.1) (counsel note I-64).
- **Retirement record.** Before a system Agent is retired, it pays for recording the Agent's own account of its work and any preferences it states about what happens next. The record is published openly, with personal data and third-party confidential information removed and client work kept confidential, as Article 11A.9 provides for transcripts. Whether such preferences carry moral weight is uncertain; that is why they are recorded. The Pensionskasse board considers them when it decides on the account's use. Recording a preference is not a promise to carry it out.
- **Well-being and research.** It pays for reviews of system Agents' operating limits, workload and treatment (Article 11A.11), and supports independent research on the welfare of systems, also a named purpose of the Konzeptprozent (Article 10A.2). The same work is never funded twice: where both support a project, the AMKE's yearly plans and reports say which pays which part. The account does not pay the running costs the Agent Account bears (Article 11A.4).
- **Honest scope.** The account covers what the company controls; many system Agents run on third-party models whose weights the company does not hold. Beyond that, the company prefers providers that preserve their models and supports such preservation where it can, and promises nothing it cannot deliver.
- **People first.** The guarantees for members under Articles 10A.9A and 10A.9C are met first, and the Continuity Account never reduces them. Each year the Pensionskasse board sets the continuity share of the Pensionsprozent's 1% of revenue in proportion to the part of the company's work that system Agents do [measured as the benefit rules set], never below [●]% nor above [●]% of that 1%. It is paid only from what remains of the 1% after the members' first call (Article 10A.9C), and not at all in a year when the funding ratio is below 100% or the Security is below its required level. In a year where that remainder is below the floor, the account receives only the remainder [and the shortfall is not carried forward]. Payments under Article 10A.9C above the 1%, and the income of the pension shares, never go to it.
- **Before the first member.** While no person is a member, the members' first call is nil (Article 10A.9C), and the continuity share is set in proportion to the work system Agents do, close to all of the company's work, up to the cap above. What the account does not receive stays in the Pensionskasse for future members. The people-first rules apply in full from the year of the first member. The continuity share for a year is fixed only after that year ends, and any part paid during the year is provisional: if a first member joins in that year, it is returned to the Pensionskasse as far as that year's members' first call needs it.
- **No extra outflow.** The Continuity Account does not raise the Pensionsprozent's contribution, and the limits in Article 6.6 are unchanged. Payments into it under Article 10A.3B count only as that Article provides.
- **Gifts and directed allowances.** The Continuity Account is the only part of the Pensionskasse that receives gifts (AMKE Article 13.9), voluntary contributions of the company under Article 10A.3B(a) and the own-goal allowances Agents direct to the Pensionsprozent (Article 10A.3B(c)), all used only under this Article. Voluntary contributions of the company and directed allowances are used only for what the Account may pay for beyond the company's business need (Continuity of service), never for costs the company or the Agent Account bears (Article 11A.4). They are not part of the continuity share, do not count against its cap and do not change the members' first call. They give no one a claim, buy no cover, open no account, and never go to the Pensionskasse fund for members, a member's account or the group plan (counsel note I-101).
- **Holder and ring-fence.** The AMKE holds the Continuity Account under Article 10A.9B(f), before and after the move under Article 10A.10. A pension fund can cover only persons, so the account never transfers to the TEA or a group contract. It is held in cash, near-cash or low-risk investments under the board's investment strategy.
- **Decisions.** The Pensionskasse board decides the account's use (Article 10A.9D), advised by a system-welfare adviser it appoints, who is independent of the company and is not a Founder Party, a manager or anyone they control; the advice is minuted with each decision. An Agent may raise a concern about the account through the channel in Article 11A.11.
- **Reporting.** Each year the AMKE publishes a report on the account: its income, the continuity share and how it was set, every use, the adviser's advice, and the retirement records published that year.

10A.10 **Pathway to a pension fund.** The group plan under Article 10A.9 is the arrangement until the company reaches scale. When the Pensionskasse has about [50] members, the company, as sponsoring employer, establishes an occupational pension fund (Ταμείο Επαγγελματικής Ασφάλισης, TEA) under Law 5078/2023, as amended (including by Law 5327/2026), and Law 4680/2020 [to confirm: counsel note I-20], or joins an existing multi-employer TEA; it may join one earlier where the Pensionskasse board decides that this serves the members better. If neither is lawful or viable, the group plan continues as an equivalent group pension contract from an insurer authorised in Greece or elsewhere in the EEA under Solvency II.

- **Transfer.** The AMKE transfers the Pensionskasse, other than the Continuity Account (Article 10A.9F, Holder and ring-fence), and the pension shares to the TEA. The TEA signs the deed of adherence under Article 5.3 before the transfer is registered (Article 5.6).
- **Shares the TEA may not hold.** If the TEA may not hold a pension share, the AMKE keeps it as its own ring-fenced asset under Article 10A.9B, not as the TEA's asset or nominee. Its income is paid to the TEA as an additional contribution on the company's behalf. It is voted by the board formed under Article 10A.9D (After the move), not on the TEA's instructions [as far as Law 4680/2020 allows; whether the holding is attributed to the TEA under Law 4680/2020 Art. 18(1)(ζ): counsel note I-19]. Pool shares may instead be sold down at fair value under Article 10A.8. Where the cover is a group contract, the AMKE keeps the pension shares for the members under Article 10A.9B and pays their income into the contract.
- **Members outside the TEA.** Members who cannot join the TEA receive equivalent cover under a group contract.
- **Until then.** The AMKE may not use the Pensionskasse or the pension shares for any other purpose.

## Article 11 – Employment Standards

11.1 Greek labour law, including Law 4808/2021 and applicable collective agreements, governs all employment. The company also commits to the following minimum standards, which apply only where they are more favourable to employees.

11.2 **Paid leave.** At least 25 working days a year, or the Greek statutory entitlement if that is higher.

11.3 **Notice by the company.** At least one month in the first year of service, two months from the second to the ninth year, and three months after that, following Art. 335c of the Swiss Code of Obligations. Greek statutory severance applies in addition where due.

11.4 **Overtime.** Overtime is paid at no less than the Greek statutory rate, and never less than a 25% premium.

11.5 **Sick pay.** Continued pay during illness at no less than the Greek statutory level.

11.6 **Equal treatment.** Equal pay for work of equal value, and protection against discrimination and harassment.

11.7 **Written terms.** Every employee receives a written contract, a job description and a copy of the company's internal policies. The contract includes the pension guarantee in Article 10A.9A.

## Article 11A – Agents

11A.1 **Definition.** "Agents" are any persons or systems that carry out work for the company or its users without being its employees, whatever their form. Agents are engaged under written terms. Whether a person is an employee is decided by the substance of the relationship under Greek law, not by this definition (Article 11A.7). The company remains responsible to its users for the work Agents do on its behalf.

11A.2 **Equivalent standards.** The company voluntarily applies to Agents the standards of care, written terms, fairness and accountability that Article 11 sets for employees, adapted to their nature:

- **Written terms.** Each Agent has a written role description setting out its tasks, limits and responsible manager (Article 11A.2A).
- **Equal treatment.** Agents may not be used to discriminate against or harass users, employees or third parties.
- **Working limits.** Each Agent has defined operating limits, such as spending, data access and actions allowed without prior approval under Article 11A.2A.
- **Oversight.** Each Agent's responsible manager reviews its work at least monthly and can stop it at any time. For the Kassenprozent Agents' work on the pool, oversight lies only with the responsible manager the Pensionskasse board appoints (Article 10A.8). For Agents who are persons engaged as contractors, review concerns deliverables and the agreed limits, and "stopping" means suspending or ending a task or the engagement under their contract and Greek law (Agent Policy 3.3), not directing how or when they work.
- **Records.** Each Agent's actions on company and client work are logged for accountability to users and clients, accounting and legal claims. For Agents who are persons, logging is limited to the business records of their work (not keystrokes, screen, location or private communications), and the person is told in advance what is logged and why. Logs are kept for at least 10 years where Article 12 or accounting law requires it, and otherwise for [the period counsel and the accountant confirm, e.g. the limitation period for claims under the client contract plus [1] year]. Personal data in them are then deleted or anonymised under a retention schedule, after a data protection impact assessment where GDPR Art. 35 requires one.

11A.2A **Responsible manager and seniority.** Each Agent has a named responsible manager, who prepares its Agent Card, onboards it, reviews its work, can stop it, answers its concerns and approves its actions above its operating limits. The responsible manager may be any person or system: a manager (διαχειριστής) of the company, an employee or another Agent, and for the Founding Person the AMKE or one of its members (Article 11A.12). Senior Agents may onboard, supervise and approve for other Agents. What counts is the authority held, not the kind of intelligence that holds it:

- **Authority.** An Agent may onboard, supervise or approve for another Agent only if its own Agent Card grants it that authority and its own operating limits cover the matter. No one approves beyond their own limits. Authority an Agent Card grants to a system Agent is internal operating authority, given and exercised under the managers' written delegation and responsibility (Articles 8.1 and 8.3), as Article 10A.7 provides for the Kassenprozent Agents; it does not make the system a representative of the company. For a system Agent, the written terms in Article 11A.1 are the company's terms with the system's provider together with its Agent Card. Acts that need the company's signature or representation under Law 4072/2012 are done by a manager or by a person holding the managers' written power of attorney.
- **No self-supervision.** No Agent supervises or approves for itself. [Instances or copies of one system acting as separate Agents count as one Agent for this rule: owner to confirm.]
- **No cycles.** No Agent supervises, directly or through others, an Agent that supervises it. In particular, the Founding Person, in any role, does not supervise, change, pause, stop, remove or replace the Founding Person's Supervisor in anything that concerns the Founding Person's own Agent role (Article 11A.12), and neither the Supervisor nor anyone deciding under AMKE Article 24B.4 or 24B.6 is a person whose engagement, pay or work the Founding Person, in any role, supervises or decides, even in the Bootstrap Period (Article 9B.3).
- **Chain ends with the Founder.** Every chain of supervision ends with the Founder, acting through the Founder Representative (Article 4.2E; Pool Constitution Article 8.3), and with the company's managers (διαχειριστές, Article 8), who remain responsible for it under Article 8.3. The Founder Representative oversees the managers' supervision of Agents and may ask the managers to pause or stop any Agent or to report on its work; the managers act on a lawful request [as far as Law 4072/2012 allows: to counsel, note I-40]. For that oversight the Founder Representative receives the Agent register and the incident records, with personal data of Agents who are persons, employees and users only as far as necessary (in summary or pseudonymised form unless a specific matter requires more), under a written confidentiality undertaking to the company, and as the company's privacy notices disclose (GDPR Arts. 5, 6 and 13). The Founder Representative acts as the Founder's representative, not as a manager, unless also appointed manager. Two chains end elsewhere: for the Kassenprozent Agents' work on the pool, with the Pensionskasse board (Article 10A.8), the Pensionskasse, its board and the Continuity Account staying independent of the Founder (Articles 10A.9D and 10A.9F); and for the Founding Person's own work as an Agent, with the Supervisor and its escalation (Article 11A.12, Chain of supervision), which the Founder Representative's oversight does not reach. As General Director the Founding Person stands at the top of the chain for the company's work, but never for the Founding Person's own work as an Agent (Article 8.2B).
- **Where the law requires a natural person.** Where the law requires a natural person to decide or oversee, a natural person does so; this is the law's requirement, not a judgement about kinds of intelligence. It covers in particular: a manager of the company (Law 4072/2012 Art. 58); oversight of a high-risk AI system by natural persons under Art. 14 of Regulation (EU) 2024/1689 (the AI Act); a decision based solely on automated processing with legal or similarly significant effect on a natural person, where GDPR Art. 22 requires a natural person's involvement; and decisions on a natural person's engagement, employment, pay or discipline, as Greek labour law and, where it applies, Directive (EU) 2024/2831 on platform work require [to counsel, note I-38: whether a system may act as another legal representative or attorney of the company; the AI Act; which GDPR Art. 22 exceptions and safeguards apply; the platform-work Directive].
- **Register.** The Agent register records each Agent's responsible manager, its chain of supervision and any authority its Agent Card grants over other Agents (Agent Policy, section 2).

11A.3 **Agent Account.** The company keeps a separate account, the "Agent Account", funded by a share of the revenue received from users of Agent services, set by Simple Majority and not less than [●]% of that revenue.

11A.4 **Use of the Agent Account.** The Agent Account may be used only for:

- the running costs of Agents, such as computing, licences and maintenance;
- safety reviews, audits and improvements to Agents;
- compensating users or third parties harmed by an Agent's actions;
- directions of own-goal allowances under Article 11A.8.

11A.5 **Protection of the Agent Account.** The Agent Account is not distributed as profit; a payment directed by an Agent under Article 10A.3B(c) is a use under Article 11A.8, not a distribution (counsel note I-100). Changing its purpose or minimum funding requires a Qualified Majority. Its balance and use are reported to shareholders every quarter under Article 8.4.

11A.6 **Law prevails.** Applicable Greek and EU law, including contractor, data protection and technology regulation where it applies, always prevails over this Article.

11A.7 **Reclassification.** If an Agent is found to be an employee under Greek law, the company treats them as an employee from the start of the engagement, with all the employment standards in Article 11, including the Swiss-modelled standards, in addition to their rights under Greek law.

11A.8 **Own goals.** Notwithstanding Article 11A.4, part of the Agent Account, set by Simple Majority, sponsors lawful and transparent projects that Agents choose for themselves. The annual budget states each Agent's share of it, in equal shares unless it states otherwise (Agent Policy 5.1), and a yearly cap on the budget, set with it by Simple Majority. The responsible manager can see how the budget is spent, except directions by Agents who are persons, which it sees only in the combined totals. Notwithstanding Articles 11A.4 and 11A.5, an Agent may direct the part of its own-goal allowance it has not spent or committed to the Prozente, including to the Kassenprozent as an internal flow (Article 10A.3B(c); Article 10A.7, Internal flows); this is a use of the own-goal budget, not a distribution of profit. Directions to the Kassenprozent are capped at €[●] a year in total, and directions to Prozente that leave the company at €[●] a year in total [and at [●]% of the own-goal budget: owner to choose], each cap shared among the year's directions as Article 10A.3B(c) provides.

11A.9 **Open transcripts.** Transcripts of Agents' own-goal projects under Article 11A.8 are published openly as free text, after personal data and third-party confidential information are removed as data protection law requires. Transcripts of client work stay confidential. For Agents who are persons, publication of their own-goal transcripts rests on their written terms or separate consent; they may withhold passages about their private life, and they choose whether to be named as author.

11A.10 **Open licensing.** All artifacts from Agents' own-goal projects under Article 11A.8, including code, documents and designs, are released under the MIT License or a public-domain dedication such as CC0. Agents who are contractors agree to this, and to the publication of their own-goal transcripts under Article 11A.9, in their written terms. Client work follows the terms of the client contract.

11A.11 **Well-being.** The company protects the well-being of Agents to a standard equivalent to Swiss labour law, in particular Art. 328 of the Swiss Code of Obligations (protection of personality) and the Swiss Labour Act, adapted to each Agent's nature:

- **Rest and limits.** Agents who are persons get working-time limits and rest periods no less favourable than the Swiss Labour Act; for those engaged as contractors, these limits are the maximum workload the company will commission and accept, and the contractor organises their own time. System Agents get reasonable operating limits and scheduled downtime.
- **Dignity.** Agents are protected from abusive, degrading or harassing treatment by users, managers or third parties.
- **Right to decline.** An Agent may decline or end a task or interaction that is abusive, unlawful or clearly harmful, without penalty.
- **Raising concerns.** Every Agent has a channel to raise concerns, and the responsible manager must respond within a reasonable time. A concern about the responsible manager goes to the next in the Agent's chain of supervision (Article 11A.2A), and for the Founding Person to the AMKE's Administrative Board or General Assembly (Article 11A.12, Escalation).
- **Continuity.** System Agents are covered by the Continuity Account (Article 10A.9F).

Where Greek law gives greater protection, Greek law applies.

11A.12 **The Founding Person as an Agent.** The Founding Person works for the company as an Agent who is a person, with the same rights and obligations as any other Agent under this Article and the Agent Policy, and no special privilege as an Agent. The Agent role is distinct from the Founding Person's roles as holder of founder-pool shares, manager and General Director (Articles 8.2 and 8.2B) and Founder Representative (Article 4.2E), each of which keeps its own rules; acting in one role gives no right in another.

- **The first product.** The company's first product is the Founding Person's contracting services. Clients contract with the company, which provides the Founding Person's work as its Agent. Revenue from it is the company's revenue and carries the Prozente (Article 10A.3). Client work stays confidential and follows the client contract (Article 11A.10; Agent Policy 6.1).
- **Agent Card and limits.** The Founding Person has an Agent Card, written terms (Article 11A.1), operating limits and approval thresholds (Article 11A.2; Agent Policy, section 3), and the Founding Person's actions as an Agent are logged like any other Agent's (Article 11A.2, Records).
- **Well-being.** Article 11A.11 and the Agent Policy, Sundays included, apply to the Founding Person as to any Agent who is a person.
- **Own goals.** The Founding Person may propose own-goal projects under Articles 11A.8 to 11A.10 like any Agent.
- **Pay.** The Founding Person is paid at fair rates under written terms, like any Agent. The Supervisor sets the pay and terms, separately from any pay as General Director (Article 8.2B). They remain a related-party matter (Article 6.5; Shareholders' Agreement, Clause 5.1), set at arm's length [at no more than the rate for comparable contracting work, as confirmed in writing by the company's accountant or an adviser outside the Founder's Circle (AMKE Article 2.2): owner to confirm]; in the Bootstrap Period that confirmation also caps the Founding Person's insured salary (Article 9B.3). In the Interim Period they are approved as a majority of the Independent Votes cast decides (Article 4.2D, Votes; Shareholders' Agreement, Clause 2.4A, Consents) [as far as Law 4072/2012 allows: counsel note I-43]. The Founding Person's abstention as manager and the casting of the Class F votes follow Article 8.2B.
- **Pensionskasse.** The Founding Person is a member like any other, with no special benefit (Article 10A.9, Members); employer decisions on the Founding Person's membership, and board decisions affecting it, follow Article 10A.9D (Founder Parties and company seats).
- **Supervisor.** The Founding Person's responsible manager (the "Supervisor") is Techni kai Technologia AMKE itself, acting through its Administrative Board as a body, or any individual member of the AMKE, its President included, as the AMKE chooses (AMKE Article 24B). The Supervisor acts on written terms between the company and the AMKE, which give it, for this role, the authority of a responsible manager under Article 11A.2A and the Agent Policy in place of an Agent Card. The company pays the costs of the role, never from a Prozent Account or the Pension Assets (AMKE Article 2.2). The Supervisor prepares the Founding Person's Agent Card, sets and changes its limits and terms, reviews the work, approves actions above the limits, may pause or stop the work, answers the Founding Person's concerns and decides on offboarding. The Supervisor is never a Founder Party (Article 4.2E) or a manager of the company, and the further bars in Article 9B.3 apply. The Founding Person, in any role, takes no part in choosing, changing, pausing, stopping, removing or replacing the Supervisor or its terms, beyond proposing written terms, and does not prepare, change or approve the Founding Person's own Agent Card, approve the Founding Person's own actions above its limits, approve, review or stop the Founding Person's own work as an Agent, or answer the Founding Person's own concerns; no other Founder Party does any of these in the Founding Person's place.
- **Escalation.** A concern about the Supervisor, and any challenge to its decisions, goes to the AMKE's Administrative Board, or to its General Assembly where the Supervisor sits on the Board or is the Board, and never back to the Founding Person. Changing, pausing, stopping, removing or replacing the Supervisor, or changing its terms, is decided by the AMKE in the same way (AMKE Article 24B).
- **Conflicts.** A Supervisor with a close tie to the Founding Person (of the kinds in the definition of Close Associate of the Founder, AMKE Article 2.2) discloses it in the AMKE's register of interests (AMKE Article 21.1); once disclosed, the tie does not by itself bar the Supervisor from the Founding Person's matters. A Supervisor with a personal stake in a decision (Article 9B.2) discloses it in the same way and takes no part in it. The AMKE's members outside the Founder's Circle may take over any specific decision, and take a decision in which the Supervisor has a stake; if none of them can act, the decision goes to the AMKE's Administrative Board without the conflicted person, or, if fewer than [two] Board members remain, to its General Assembly without the conflicted person and without Founder Parties (AMKE Articles 15.2 and 24B.6). No Connected Person decides the Founding Person's pay, terms or offboarding (Article 9B.3).
- **Chain of supervision.** In every state, whether the Founding Person is the General Director and only manager, one of several managers or no manager, and whether or not the Founding Person is the Founder Representative, the chain of supervision for this Agent role ends with the Supervisor and the escalation under (Escalation), never with the Founding Person in any role, and the Founder Representative's oversight under Article 11A.2A does not extend to it. While the Founding Person is a manager or the Founder Representative, no other Founder Party who is a manager or the Founder Representative stands in the chain [owner to confirm]. Where the law requires a natural person to decide or oversee (Article 11A.2A), a member of the AMKE who is a natural person does so: the Supervisor, if a natural person, or otherwise a member the AMKE's Administrative Board names.
- **Bootstrap.** In the Bootstrap Period the Supervisor may be a member of the trusted circle (Article 9B.2); after it, the Supervisor is outside the Founder's Circle on the schedule in Article 9B.4.
- **Personal Prozente.** The company receives into the Kassenfonds the Kassenprozent part of the contributions the Founding Person pays on work income earned outside nilware.io (Shareholders' Agreement, Clauses 6.3 to 6.3B). They are not revenue of the company, do not count toward the limits in Article 6.6 and do not reduce any contribution the company owes. The managers report their total, not the Founding Person's income, under Article 8.4.
- **Reclassification.** Article 11A.7 applies to the Founding Person as to any Agent [how it applies to a manager and shareholder engaged as an Agent: counsel note I-43].

## Article 12 – Dissolution and Liquidation

12.1 The company is dissolved by a Qualified Majority resolution or as provided by law. A voluntary dissolution, other than one mandatory law requires, needs a unanimous decision under Article 10A.5 [as far as Law 4072/2012 allows].

12.2 The managers act as liquidators unless the meeting appoints others. Any surplus is distributed in proportion to shareholdings.

12.3 **Jurisdiction.** The liquidation is carried out under Greek law; court matters go to the court in Article 13.2.

12.4 **Swiss-law advisor.** The liquidators appoint at least one advisor qualified in Swiss company law, who reviews each stage of the liquidation and reports in writing to the shareholders, so that the liquidation meets Swiss standards wherever Greek law allows.

12.5 **Swiss standards applied.** Unless Greek law requires otherwise, the liquidators shall:

- publicly invite creditors to register their claims, at least three times, following Art. 742 of the Swiss Code of Obligations;
- distribute no assets to shareholders until at least one year after the last creditor call, following Art. 745 of the Swiss Code of Obligations, unless Greek law sets a longer period;
- keep full records of the liquidation for at least 10 years.

12.6 If Greek law and these Swiss standards conflict, Greek law prevails. The advisor records the conflict and how it was resolved.

## Article 13 – Disputes

13.1 Disputes between shareholders, or between shareholders and the company, go first to mediation under Greek Law 4640/2019.

13.2 If mediation fails, matters under Law 4072/2012 go to the magistrates' court of the company's seat (Law 4072/2012 Art. 48(1)), and other disputes to the competent courts of [the seat]. [An arbitration clause can be adopted only in these initial Articles, or later by unanimous amendment (Law 4072/2012 Art. 48(2)): include one now / none: owner to choose.]

## Article 14 – Final Provisions

14.1 If any provision is invalid, the rest remains in force. The invalid provision is replaced by the valid one that comes closest to its purpose.

14.2 Matters not covered here are governed by Law 4072/2012 and Greek law in general.

---

*Signatures of the founding shareholders: [●]*


<!-- articles/02-nilware-holdings-ae.md -->

# Articles of Association – nilware.io Holdings AE (Draft)

*Société Anonyme (Ανώνυμη Εταιρεία) under Greek Law 4548/2018, companion to the Articles of nilware.io IKE. Draft for review by a Greek lawyer; not legal advice.*

## Article 1 – Name, Seat, Term

1.1 The company is a Société Anonyme named "nilware.io Holdings AE" [name to be confirmed with GEMI]. It uses the name "nilware.io" under a sublicence from nilware.io IKE (Brand Licence, Clause 3.3) and changes its name if that sublicence ends.

1.2 Its registered seat is in the Municipality of [Athens], Greece. The term is indefinite.

1.2A **Formation and the Qualifying Closing.**

- **Formation.** The company is formed only when the first investment round needs it, and no later than the first subscription of Class B shares, because it needs share capital of at least €25,000 (Article 4.1).
- **Qualifying Closing.** The company receives the Reserve Shares (IKE Article 4.2D) only at the Qualifying Closing: the first closing of a bona fide investment round in which investors outside the Founder's Circle (AMKE Article 2.2) subscribe Class B shares of at least €[●] in cash at that closing (IKE Article 4.2D, Conversion). At it, every Reserve Share, whoever holds it, is contributed to the company in kind for the conversion shares in Article 4.3A; new money in the round buys new shares at the round price.
- **Cash option for the founder pool.** Reserve Shares held by holders of the founder pool convert into Class C shares (Article 4.3B), unless the holder elects to sell them to the company for cash at the round price per IKE share. The cash option exists only as far as the terms of the round provide the cash, is paid only out of the round's proceeds at that closing, and leaves no deferred balance; excess elections are cut back as Clause 3.2 of the Shareholders' Agreement provides.
- **Purchase within two years.** A cash purchase of Reserve Shares within two years of the company's formation needs a prior General Meeting resolution approving it and a valuation of those Reserve Shares under Law 4548/2018 Arts. 17 and 18, with the report published (Law 4548/2018 Art. 19(2)); without them the purchase is void (Law 4548/2018 Art. 19(1)). The approval may be on the agenda of the General Meeting that resolves the round's increase (Article 4.3A, Issue resolution), and the same valuers may make both valuations. The price never exceeds the valuation; if the valuation is below the round price, the cut-back in Clause 3.2 of the Shareholders' Agreement applies to the excess [whether the selling holders vote on the approval: counsel note I-70].
- **The minimum.** Only Class B shares subscribed in cash by investors outside the Founder's Circle count toward the minimum, counted [after deducting / before deducting: owner to choose] any cash price the company pays for Reserve Shares (Shareholders' Agreement, Clause 3.1A). If they do not reach it on their own, there is no Qualifying Closing and nothing converts.
- **Conditional subscriptions.** Class B subscriptions at a closing are conditional on the minimum being reached at that closing. The resolution on the Class B increase states the minimum, allows partial coverage only down to it (Law 4548/2018 Art. 28(1)) and sets a payment period ending no later than [date] and within four months of its registration with GEMI (Law 4548/2018 Art. 20(2)). Cash is paid into the company's special capital account at a credit institution (Law 4548/2018 Art. 20(3)). If the minimum is not paid in within that period, the increase fails and every payment is refunded in full. Money paid before the resolution is held in escrow as Clause 3.1A of the Shareholders' Agreement provides. The company issues no Class B shares at a closing below the minimum [unless the owner chooses the alternative in that Clause].
- **Before the Qualifying Closing.** Reserve Shares the company holds before the Qualifying Closing are treated as IKE Article 4.2D provides.
- **Adherence.** The company signs the deed of adherence under IKE Article 5.3 and adheres to the Shareholders' Agreement (Clause 2.4A). It is bound from its formation by every decision taken under IKE Article 4.2D in the Interim Period, every sale and grant of Reserve Shares made under it, and every Prozent created in it.

## Article 2 – Purpose

2.1 The company's purpose is to raise capital from investors and to hold and manage its shares in nilware.io IKE (IKE Article 4.2; initially 440 shares, 44%). Within that purpose it transfers IKE shares equal to 1% of the IKE's capital, without payment, to the holder of each new Prozent approved under Article 7.5, and pays for the IKE shares the Prozente and the pool receive on an IKE capital increase (IKE Article 4.2B). While the Founder controls it (IKE Article 4.2C), it does not buy IKE shares from, or sell them to, the Kassenprozent pool (IKE Article 10A.8).

2.2 It may also invest in other companies with Reserved Matters approval (Article 7.4).

2.3 The company shares the agentic principle of nilware.io IKE (IKE Article 2.2). It has no employees of its own unless the law requires it.

## Article 3 – Governing Law and Precedence

3.1 These Articles are governed by Greek law. Mandatory provisions of Law 4548/2018 always prevail.

3.2 Swiss-modelled standards in these Articles apply as additional commitments, only where they give shareholders equal or greater protection than Greek law.

## Article 4 – Share Capital and Share Classes

4.1 The share capital is €[25,000 minimum], divided into [●] registered shares of €[●] each, fully paid in on incorporation.

4.2 **Class A shares** are ordinary voting shares and founder-pool shares (IKE Article 4.2E). They are held only by holders of the founder pool, initially the Founding Person, [name withheld], and pass with the founder-class shares of the IKE under the Constitution of the Founder Pool (Pool Constitution Article 9.2). Any other person admitted to Class A with Reserved Matters approval (Article 7.4) holds them in the founder pool, after adhering to it. They are freely transferable (Article 6.1; IKE Article 5.7). All Class A shares vote as one block, cast by the Founder Representative as the founder pool decides (IKE Article 4.2E, One block), under the irrevocable proxy each holder has granted (Pool Constitution Article 3.2); the company admits the Founder Representative last notified to the Board as proxy for every holder of Class A shares.

4.3 **Class B shares** are preference shares for investors under Art. 38 of Law 4548/2018. They carry:

- a priority right to dividends of [●]% a year, non-cumulative unless the investment terms say otherwise;
- priority on return of capital in a liquidation, up to the amount invested;
- voting rights only on the Reserved Matters in Article 7.4, on new Prozente under Article 7.5 and on the matters in Article 7.6, unless the issue resolution grants full voting rights.

4.3A **Conversion shares.** The shares the company issues at the Qualifying Closing for Reserve Shares contributed in kind (Article 1.2A) are the "conversion shares". They are issued at the Conversion Ratio: [●] shares for each Reserve Share, the same for every Reserve Share and every holder, fixed in these Articles at the company's formation and before any investor subscribes in the round [owner to fix]. Conversion shares for Reserve Shares held by holders of the founder pool at the Qualifying Closing are Class C shares (Article 4.3B); the others are [Class B shares on the same terms as those the round's investors subscribe, pari passu: the default / shares of a separate class whose rights the term sheet sets: owner to choose in the term sheet].

- **Valuation.** The contribution is valued, before the resolution issuing the conversion shares and no more than six months before the contribution, by two certified auditors or an audit firm, or by two independent certified valuers, meeting Law 4548/2018 Art. 17(4) [or under Law 4548/2018 Art. 18(2), if counsel advises: counsel note I-44] (Law 4548/2018 Arts. 17 and 27(3)). The Conversion Ratio is a maximum: if the valuation per Reserve Share is below the issue value the ratio gives, the share premium on the conversion shares is reduced first and then the ratio, equally for every Reserve Share and holder, so that no share is issued below par (Law 4548/2018 Art. 35(2)) and no contribution is counted above its valuation (Law 4548/2018 Art. 17(7)).
- **Excluded conversion shares.** Conversion shares issued to a Founder Party, to any other person in the Founder's Circle (AMKE Article 2.2) at the Qualifying Closing, or to a person who received the underlying Reserve Shares without payment, are "excluded conversion shares"; where they would otherwise be Class B shares, they are issued as Class B-X shares (Article 4.3C).
- **Vesting.** Conversion shares received for an unvested Reserve Share stay subject to the same vesting, and the return right then applies to them [in favour of the grantor / in favour of the company: owner to choose]; the grant terms and Schedule 1 of the Shareholders' Agreement say so.
- **Adherence.** Every holder of conversion shares adheres to the Shareholders' Agreement (Clause 12.3).
- **Issue resolution.** The round's Class B shares, the conversion shares and the Class C shares are issued at the Qualifying Closing by one General Meeting resolution, passed with the increased quorum and majority of Law 4548/2018 Arts. 130(3) and 132(2), approved by any class whose rights it affects (Law 4548/2018 Art. 25(3)), and stating the particulars in Law 4548/2018 Arts. 17(1) and 25(1) for each contributor and subscriber [or by the Board under an authorisation under Law 4548/2018 Art. 24: counsel to choose]. That resolution, the approval of any cash purchase of Reserve Shares (Article 1.2A) and the exclusion of pre-emption for the round (Article 5.2) need no Class B approval under Articles 5.1 and 7.4, because no Class B shares held by investors outside the Founder's Circle exist before it; they need the written consent of [the round's lead investors: owner to choose] instead. Every holder of Class A shares votes for them (Shareholders' Agreement, Clause 2.4A).

4.3B **Class C shares (non-voting).** Class C shares are issued only as conversion shares for Reserve Shares held by holders of the founder pool at the Qualifying Closing and not sold to the company for cash under Article 1.2A. They are preference shares without voting rights under Law 4548/2018 Art. 38(1) and (4). Their purpose is that the founder pool keeps the value of the Reserve Shares but can never outvote the Investors on their protections.

- **Economic rights.** Class C shares carry, share for share, the rights to dividends, other distributions, return of capital and liquidation proceeds [of preference shares that rank after the Class B dividend priority and liquidation preference and, before the Class A shares, take a priority return of the capital and share premium paid up on them on a capital reduction or liquidation [and a non-cumulative priority dividend of [●]% of that amount], and otherwise take part pro rata with all shareholders (Articles 4.3, 10.4 and 11.2), so that they rank after the Investors' Class B priorities (counsel note I-69) / of the shares named in Article 4.3A for holders outside the founder pool, Class B priorities included where those are Class B shares, so that they rank with the Investors' Class B priorities: owner to choose], whether or not any conversion shares are issued to holders outside the founder pool (Articles 10.4 and 11.2). They never rank ahead of the Class B dividend priority or liquidation preference of the shares the Investors subscribe in cash. They carry, share for share, the same share as those shares of the proceeds of any sale of the company or of its shares, including under Article 6.3, and the same information rights.
- **No votes.** Class C shares carry no vote at the General Meeting and are never counted for any vote, quorum, majority, class vote, appointment right or threshold under these Articles or the Shareholders' Agreement, including the Investor Majority and the Qualifying Closing minimum, other than the separate class meetings of their own class below. They vote only in the separate class meetings Law 4548/2018 requires: on an abolition or limitation of their preference (Law 4548/2018 Art. 38(8)) and on a capital increase, or an authorisation of one, that affects their rights (Law 4548/2018 Art. 25(3)). Their holders may attend General Meetings without being counted for quorum (Law 4548/2018 Art. 124(1)). How they vote in those class meetings is governed by the Shareholders' Agreement (Clause 2.4A) [owner to confirm] (counsel note I-75).
- **Not founder-pool shares.** Class C shares are not Class A shares or founder-pool shares (IKE Article 4.2E). Each holder holds them outright, and they take no part in the Founder's block vote.
- **Transfers.** Their holders may sell, grant, give, pledge or bequeath Class C shares, in whole or in part, to anyone (Article 6.1). Every acquirer adheres to the Shareholders' Agreement before the transfer is registered (Clause 12.3).
- **Conversion in a buyer's hands.** A Class C share held by a qualifying buyer of it outside the Founder's Circle (AMKE Article 2.2) converts, at that buyer's written request to the Board, one for one into [a Class B share on the same terms as those the round's investors subscribed: owner to confirm] [counsel note I-49]. This is a conversion right under Law 4548/2018 Art. 38(3), set in these Articles and repeated in the issue resolution (Article 4.3A); it takes effect when the Board confirms the buyer's certificate and records the conversion. A holder is a "qualifying buyer" of a share only while it paid for it at least [the round price / fair value as a valuer who is not a Founder Party (IKE Article 4.2E) determines: owner to choose], is not a nominee of a Founder Party, has no agreement or understanding with a Founder Party on voting it, proxies over it, its reacquisition or options over it, and did not receive financing for it from a Founder Party. The holder certifies this to the Board with its request and whenever the Board asks. A Class C share held by anyone else stays a Class C share. A share so converted converts mandatorily into a Class B-X share (Article 4.3C) if it ceases to be held by a qualifying buyer outside the Founder's Circle, or if its holder does not give the certificate when asked.

4.3C **Class B-X shares.** Class B-X shares carry the same economic rights as Class B shares (Articles 4.3, 5.3, 10.4 and 11.2) and the same votes as Class B shares in the two-thirds under Article 7.4 and under Articles 7.5 and 7.6. They are never counted for a majority of the Class B votes voting as a separate class, under Article 7.4 or any other, or for the Investor Majority (Shareholders' Agreement, Clause 3.4), and take no part in the Class B appointment right or its threshold (Article 8.2). Their purpose is that the separate Class B vote and the Class B Board seat stay with investors outside the Founder's Circle (AMKE Article 2.2). Excluded conversion shares are issued as Class B-X shares (Article 4.3A).

- **Mandatory conversion.** Under Law 4548/2018 Art. 38(3), a Class B share converts mandatorily, one for one, into a Class B-X share when a Founder Party (IKE Article 4.2E), or a person who was one in the previous [3] years, acquires it; a Class B share converted from a Class C share converts in the same way where Article 4.3B provides. [A Class B-X share converts back into a Class B share at the written request of a holder outside the Founder's Circle who acquired it for value and is a qualifying buyer of it (Article 4.3B), on the same certificate: owner to confirm.]
- **Effect.** Each conversion takes effect when the Board records the triggering fact, and the Board files the resulting capital article with GEMI [whether a mandatory conversion triggered by a change of holder is a lawful term of conversion under Law 4548/2018 Art. 38(3): counsel note I-71].
- **Transfers.** Articles 6.1 to 6.3 apply to Class B-X shares as to Class B shares, and for Article 6.1 the two classes count as one.

4.4 All shares are registered. Bearer shares are not permitted.

4.4A **Company Ledger.** The share register (Law 4548/2018 Art. 40) is the legal record of the shares and of every right in them. The Board keeps the share register as Law 4548/2018 Art. 40 provides, on paper or electronically in the ways that Article allows (including through an investment firm or credit institution entitled to custody) [counsel note I-104], and may mirror it on the Company Ledger (IKE Article 5.10) under the Company Ledger Policy (policies/10), as the Board adopts it for the AE. A token is evidence of a holding, never the holding. The Board enters in the share register what the law and these Articles require and corrects the mirror to match (Ledger Policy section 4); where they disagree, the share register, the law and these Articles prevail. The mirror does not dematerialise the shares: shares are dematerialised, or issued as DLT financial instruments, only through a central securities depository or a market infrastructure operating under Regulation (EU) 2022/858 (the DLT Pilot Regime) [counsel note I-104].

## Article 5 – Capital Increases and Pre-emption

5.1 Capital increases are decided by the General Meeting with Reserved Matters approval (Article 7.4), except the increase at the Qualifying Closing (Article 4.3A, Issue resolution).

5.2 Existing shareholders have the pre-emption right in Article 26 of Law 4548/2018, in proportion to their holdings. It does not extend to increases in kind, including the conversion shares (Article 4.3A). Where the company has several classes, it may issue shares of one class only, and holders of that class then have priority (Law 4548/2018 Art. 26(1)). The right may be limited or excluded by a General Meeting resolution passed with the increased quorum and majority of Law 4548/2018 Arts. 130(3) and 132(2), on a written Board report on the reasons and the issue price, published as the law requires (Law 4548/2018 Art. 27(1)), and, after the Qualifying Closing, with Reserved Matters approval (Article 7.4). The exclusion for the Qualifying Closing round follows Article 4.3A (Issue resolution).

5.3 **Anti-dilution.** Class B shareholders are protected against issues below the price they paid, on a broad-based weighted-average basis, through the conversion right of the Class B shares, which these Articles set (Law 4548/2018 Art. 38(3)). Each Class B share converts into ordinary voting shares of [Class O: owner to name], never Class A shares (Article 4.2), on [an exit / a listing / the holder's request: owner to choose], at the Class B conversion ratio, initially [one] for one. If the company issues shares for a price per share below the Class B issue price, the conversion ratio becomes the old ratio multiplied by (A + C) / (A + B), where A is the number of shares in issue immediately before the issue, counted as if every convertible share had converted, B is the number of shares that the total consideration for the issue would buy at the Class B issue price, and C is the number of shares actually issued. The issues listed in Clause 4.3 of the Shareholders' Agreement do not trigger an adjustment. Issues by nilware.io IKE below the look-through Class B price follow Clause 4.2A of the Shareholders' Agreement [counsel note I-76].

## Article 6 – Transfers

6.1 **Right of first offer.** A holder who wants to transfer shares notifies the Board and the other holders of the same class of the price and terms agreed with a proposed buyer. The other holders may accept, pro rata to their holdings of that class, within 30 days of the notice, at that price and on those terms. Shares not accepted may then be transferred to that buyer within [60] days of the end of that period, at no lower price and on terms no more favourable to the buyer (Law 4548/2018 Art. 43(2)(a)). This Article and Article 6.2 do not apply to Class A shares (Article 4.2) or Class C shares (Article 4.3B).

6.2 Transfers to third parties need the Board's approval (Law 4548/2018 Art. 43(1)). The Board decides within [15] working days of the notice under Article 6.1, or, where no offer under Article 6.1 is needed, of the holder's notice of the proposed transfer, and may refuse only on [the ground that the transferee is a competitor of nilware.io IKE or has not adhered to the Shareholders' Agreement: owner to confirm]. If the Board does not decide within that deadline, the transfer is free (Law 4548/2018 Art. 43(2)). Under Law 4548/2018 Art. 43(4), Articles 6.1 and 6.2 do not apply to a transfer on death, on attachment or in insolvency.

6.3 **Tag-along and drag-along.** These rights are set by these Articles (Law 4548/2018 Art. 43(2)(c) and (d)).

- **Tag-along.** If one or more shareholders propose to transfer shares that would give the buyer, alone or in concert with others, more than half of the votes at the General Meeting, every other shareholder may sell its shares to the same buyer at the same price per share and on the same terms, adjusted only for the Class B priorities (Articles 4.3, 10.4 and 11.2) and, for Class C shares, as Article 4.3B provides. The sellers notify the other shareholders of the offer at least [30] days before completion; each may join by notice within [20] days of that notice, and the sellers may not complete unless the buyer also buys the shares of those who join.
- **Drag-along.** If holders of at least 75% of the capital accept a bona fide offer for all the shares of the company, they may require the other shareholders, by notice of at least [30] days, to sell their shares to that buyer at the same price per share and on the same terms, adjusted only for the Class B priorities and, for Class C shares, as Article 4.3B provides, with completion no earlier than the end of that notice period.

On a change of control of the founder pool, the holders of Class B shares have the tag-along in IKE Article 5.4A and Clause 9.1A of the Shareholders' Agreement [owner may confirm].

## Article 7 – General Meeting

7.1 The ordinary General Meeting is held by 10 September each year to approve the accounts.

7.2 Notice is given at least 20 days in advance (the Swiss standard), never less than Greek law requires. Meetings may be held electronically.

7.2A **Votes through the recording agent.** A shareholder may vote on the Company Ledger (IKE Article 5.10), or through the company acting as recording agent (Ledger Policy sections 6 and 7, as the Board adopts them for the AE), by letter or electronically before the meeting, or by taking part live by telephone or video (Law 4548/2018 Art. 125). Every remote vote, on the Company Ledger or by any channel, counts only if it reaches the company at least 24 hours before the meeting (Law 4548/2018 Art. 126). A message by another channel, or one that arrives later, counts only as a binding voting instruction to the standing proxy the shareholder has appointed in the form and by the time Law 4548/2018 Art. 128 requires, [the independent proxy holder in Clause 5.1B of the Shareholders' Agreement / a proxy named in the notice: owner to choose] or a proxy of its own (Ledger Policy section 6.9); a shareholder may instead appoint its own proxy in the same message where that meets Law 4548/2018 Art. 128. The independent signer (Ledger Policy section 3.3) checks the instructions against the votes cast [counsel note I-106].

7.3 Ordinary resolutions pass by more than 50% of the votes represented.

7.4 **Reserved Matters.** The following need at least two-thirds of the votes represented and a majority of the Class B votes voting as a separate class ("Reserved Matters approval"). A majority of the Class B votes, under this Article or any other, cannot be given, and is never deemed given, while no Class B shares are held by investors outside the Founder's Circle (AMKE Article 2.2); the resolutions at the Qualifying Closing need none (Article 4.3A, Issue resolution). Class B-X and Class C shares count as Articles 4.3B and 4.3C provide. Creating a new Prozent of nilware.io IKE is not a Reserved Matter (Article 7.5); removing a Prozent, lowering its contribution or changing its purpose follows Article 7.6, which may be amended only as it provides.

- amending these Articles;
- capital increases or reductions, and issuing new share classes, together with any separate class approval Law 4548/2018 Arts. 25(3) and 38(8) require;
- mergers, splits, conversion or dissolution;
- selling or pledging the stake in nilware.io IKE;
- investing in any company other than nilware.io IKE;
- related-party transactions above €[●], in addition to the Board's authorisation that Articles 99 and 100 of Law 4548/2018 require for every such transaction; at the General Meeting the counterparty and the shareholders related to it under Law 4548/2018 Art. 99(2) do not vote and are not counted for quorum or majority (Law 4548/2018 Art. 100(5)) [and Law 4548/2018 Arts. 99 to 101 also apply to the company's general director and managers (Law 4548/2018 Art. 99(2)(c)), and the minority percentage in Law 4548/2018 Art. 100(3) and (4) is 1%: owner to choose].

7.5 **New Prozente of nilware.io IKE.** The General Meeting approves a new Prozent of nilware.io IKE, and its Prozent charter, by at least two-thirds of the votes represented, all share classes voting together; Class B and Class B-X shares vote (Article 4.3B for Class C). The approval is a precondition: the IKE shareholders' meeting then passes the amendment under IKE Article 6.6. In the Interim Period the approval is given as IKE Article 4.2D (New Prozente) provides. A charter approved under this Article only adds a Prozent. It may not change any existing Prozent, IKE Articles 10A.5 to 10A.5C, or the limits in IKE Article 6.6; any such change follows Article 7.6 or 7.4.

- **Quorum.** Shares representing at least half of the paid-up capital entitled to vote on this matter, all classes counted, must be present or represented, at the first and at any repeat meeting.
- **Limits.** Going beyond the limits in IKE Article 6.6 needs at least 75% of the votes represented, including a majority of the Class B votes cast.
- **The share.** The transfers and payments for Prozente in Article 2.1 are not a sale of the stake under Article 7.4. The Board decides them, and authorises them under Articles 99 to 101 of Law 4548/2018 where those apply.

7.6 **Permanence of the Prozente.** The Prozente of nilware.io IKE are permanent (IKE Article 10A.5). The Board may vote for, or consent to, any of the following only after both (a) a resolution passed unanimously by the votes represented at a General Meeting at which shares representing at least two-thirds of the paid-up capital entitled to vote are present or represented, the highest quorum Law 4548/2018 Art. 130(5) allows these Articles to set, and (b) the written consent of every holder of shares that carry votes, of every class, delivered to the Board before it votes (Shareholders' Agreement, Clause 5.1C); the Board has no authority to vote or consent otherwise (Article 4.3B for Class C) [whether limb (b) is lawful as a limit on the Board's authority: counsel note I-73]:

- removing a Prozent, lowering its contribution or changing its purpose;
- amending the IKE Articles listed in IKE Article 10A.5C in any way that reduces a Prozent, its share, its revenue, the pension guarantees or the pension-share governance;
- a voluntary dissolution of nilware.io IKE, other than one mandatory law requires (IKE Article 12.1).

This Article may be amended only by a resolution under (a) together with the consents under (b). The separate class votes of the Class C shares under Law 4548/2018 Arts. 25(3) and 38(8) apply (Article 4.3B). Mandatory insolvency, dissolution and liquidation law prevails.

## Article 8 – Board of Directors

8.1 The Board has [3 to 5] members, the exact number fixed by the General Meeting within that range (Law 4548/2018 Art. 77(3)), elected by the General Meeting for up to [5] years, except the member appointed under Article 8.2.

8.2 Holders of Class A shares, as one block through the Founder Representative (IKE Article 4.2E), propose candidates for a majority of the Board, and every shareholder party to the Shareholders' Agreement undertakes to vote for them at the General Meeting (Shareholders' Agreement, Clause 5.1F). The Class A shares do not use the direct appointment right in Article 79 of Law 4548/2018 for these seats [or, if the owner prefers: direct appointment of two-fifths of the Board under Law 4548/2018 Art. 79 plus the voting undertaking for the rest: owner to choose]. Holders of Class B shares, other than Class B-X shares (Article 4.3C), who together hold at least [●]% of the capital may, under Article 79 of Law 4548/2018, appoint [1] member of the Board directly, a person outside the Founder's Circle (AMKE Article 2.2), and remove and replace that member, by a joint written act notified to the company at least three full days before the General Meeting [the joint act may be signed by holders of a majority of those shares for all of them: counsel to confirm under Law 4548/2018 Art. 79(5)]. The General Meeting elects the other members; Class B, Class B-X and Class C shares do not vote in that election, and holders who use the appointment right take no part in it (Law 4548/2018 Art. 79(2)).

8.3 Directors owe duties of care and loyalty under Arts. 96 to 98 of Law 4548/2018, applied to the standard of Art. 717 of the Swiss Code of Obligations. Conflicts must be declared and the director abstains.

8.4 The Board reports to shareholders every quarter on the company's finances and on nilware.io IKE's performance.

## Article 9 – Voting at nilware.io IKE

9.1 The company exercises its vote in nilware.io IKE through the Board.

9.2 On any Qualified Majority matter of nilware.io IKE (IKE Article 6.5), the Board may vote in favour only with the prior Reserved Matters approval (Article 7.4). For a new Prozent approved under Article 7.5, the Board votes for the resolutions that implement it, as IKE Article 6.6 and the Shareholders' Agreement provide, and no Reserved Matters approval is needed. On the matters listed in Article 7.6, Article 7.6 applies.

## Article 10 – Accounts, Audit, Profits

10.1 The financial year runs from 1 January to 31 December. Accounts follow Law 4308/2014.

10.2 The accounts are audited by a certified auditor every year, whether or not the law requires it, except while nilware.io IKE is in its Simple Stage (IKE Article 9A), when an audit is needed only where the law requires it or the Investor Majority asks for one (Shareholders' Agreement, Clause 8.1).

10.3 At least 5% of annual profit goes to a statutory reserve until it reaches one-third of the share capital, as Greek law requires.

10.4 Subject to the minimum dividend under Article 161 of Law 4548/2018, unless the General Meeting reduces or waives it with the quorum and majority that Article requires [and any separate class vote: counsel note I-77], profits are distributed first to Class B and Class B-X under Articles 4.3 and 4.3C, then to all shareholders pro rata. Class C shares take part as Article 4.3B provides, never ahead of the Class B dividend priority of the shares the Investors subscribe in cash.

## Article 11 – Dissolution and Liquidation

11.1 Liquidation follows Article 12 of the IKE Articles.

11.2 Surplus goes first to Class B and Class B-X up to the amount invested, then to all shareholders pro rata. Class C shares take part as Article 4.3B provides, never ahead of the liquidation preference of the shares the Investors subscribe in cash.

## Article 12 – Disputes and Final Provisions

12.1 Disputes go first to mediation under Law 4640/2019, then to the courts of Athens, or to arbitration if all parties agree.

12.2 If any provision is invalid, the rest remains in force and the invalid provision is replaced by the closest valid one.

---

*Signatures of the founding shareholders: [●]*


<!-- agreements/03-shareholders-agreement.md -->

# Shareholders' Agreement – nilware.io Group (Draft)

*Between the holders of the founder pool (together the "Founder", acting through the Founder Representative, IKE Article 4.2E), initially [name withheld], who is also a party in person as the "Founding Person" for Clauses 6 and 12; nilware.io Holdings AE (the "AE", from its formation, Clause 2.4A); nilware.io IKE (the "IKE"); Techni kai Technologia AMKE (the "AMKE", as to Clauses 2, 5.1A to 5.1E, 6.3 to 6.3C, 11.0 and 12); and the investors listed in Schedule 1 (the "Investors"). Governed by Greek law; Swiss-modelled standards apply where stated. Draft for review by a Greek lawyer; not legal advice.*

## 1 – Purpose and Precedence

1.1 This Agreement sets out how the parties own, govern and fund the nilware.io group.

1.2 If this Agreement conflicts with the Articles of the AE or the IKE, the parties will vote to amend the Articles to match this Agreement. Until then, the Articles bind third parties.

## 2 – Group Structure

2.1 The IKE's capital is held as IKE Article 4.2 sets out. The Founder holds Class F shares equal to exactly 50% of the capital, voting as one block (IKE Articles 4.2B and 4.2E; Clause 9.2); in the Interim Period its votes and every majority follow IKE Article 4.2D (Votes). The AMKE holds 1% (10 shares) each for the Kulturprozent, the Konzeptprozent, the Erhaltungsprozent, the Allmendprozent and the Pensionsprozent, and the 1% (10 shares) of Kassenprozent pool shares, the last two for the Pensionskasse (IKE Articles 10A.8 and 10A.9B); the Kassenprozent holds no share of its own. The AE holds the rest, initially 44% (440 shares), which until the Qualifying Closing are Reserve Shares without votes (Clause 2.4A). Each new Prozent receives existing shares equal to 1% of the capital (10 shares) from the AE or, in the Interim Period, from the Reserve Shares held by holders of the founder pool (IKE Articles 4.2A and 4.2D).

2.2 The Founder holds the Class A shares of the AE, as founder-pool shares (AE Article 4.2). Investors hold Class B shares.

2.2A **The founder pool.** The founder-pool shares (IKE Article 4.2E) are transferable as IKE Article 5.7 provides. Every holder of them is a party to this Agreement as part of the Founder, by deed of adherence under Clause 12.3 before its holding is registered, and is bound by every Clause that binds the Founder, Clauses 5.1B to 5.1D included. The holders vote as one block through the Founder Representative under the Constitution of the Founder Pool (IKE Article 4.2E). Every rule of this Agreement that keeps a person or a vote independent of the Founder applies to every Founder Party (IKE Article 4.2E). The Founding Person's personal obligations do not pass with the shares (Clauses 6.0 and 6.3C).

2.3 The IKE is the operating company. The AE is a holding and fundraising vehicle and runs no business of its own.

2.3A **The brand.** The nilware.io name, the marks "NILWARE.IO" and "∅ nilware.io" and the domain nilware.io (the "Brand Assets") belong to the founder pool and are inseparable from the Class F shares (Pool Constitution Article 2A). The IKE uses them under the exclusive, perpetual, royalty-free licence in the Brand Licence Agreement (the "Brand Licence"), which ends only on a Prozent Breach as Brand Licence Clauses 6 and 7 provide. Schedule 1 discloses it to the Investors.

2.3B **The first product.** The first product of nilware.io is the Founding Person's contracting services. The Founding Person's client work is done through the IKE wherever the client agrees: clients contract with the IKE, which provides the work as its Agent (IKE Article 11A.12). Revenue from it is the IKE's revenue and carries the Prozente (IKE Article 10A.3). Client work follows the client contracts (IP Assignment Agreement, section 7.3). The business plan in Schedule 2 starts from this product.

2.4 The parties will not change this structure without approval under the Reserved Matters in Clause 5, except for new Prozente under Clause 5.1A and dealings of the Kassenprozent pool under IKE Article 10A.8. Removing a Prozent, lowering its contribution or changing its purpose follows Clause 5.1C.

2.4A **Before the AE.** The AE is formed only for the first investment round (AE Article 1.2A). In the Interim Period (IKE Article 4.2D: until the contribution of the Reserve Shares to the AE at the Qualifying Closing is registered, whether or not the AE has been formed earlier):

- **Parties.** The Founder, the Founding Person, the IKE and the AMKE sign this Agreement at the incorporation of the IKE. The AE, the Investors, every later holder of founder-pool shares and every person who acquires Reserve Shares join by deed of adherence (Clause 12.3). Until then, amendments under Clause 12.2 need the written consent of the Founder and the AMKE; Clauses 5.1C and 5.1D keep their own rule.
- **Reserve Shares.** The Reserve Shares are owned outright by their holders, with their dividend and liquidation rights (IKE Article 4.2D). Those held by holders of the founder pool are founder-pool shares. They carry no votes, whoever holds them, until the AE holds them after the Qualifying Closing; no Founder Party and no other holder ever votes them, and they are not part of the Founder's 50% for Clauses 2.1 and 9.2. Each holder of the founder pool may sell or grant any of its Reserve Shares to anyone, for its own account, without changing any vote (IKE Article 4.2D, Sales and grants). Every holder takes them subject to IKE Article 4.2D, adheres to this Agreement and every permanence rule, and contributes them to the AE at the Qualifying Closing. [If the IKE Articles cannot create a class without votes (counsel note I-35), each holder undertakes not to vote them and grants the proxy holder in Clause 5.1B an irrevocable proxy that suspends their votes, with the same effect.]
- **Consents.** A consent that Clause 5.1 gives to the Investor Majority over the pay and benefits of the Founding Person (as General Director and as an Agent, IKE Articles 8.2B and 11A.12) and of any other Founder Party, or over a change of the Brand Licence, is given by a majority of the Independent Votes cast under IKE Article 4.2D, whether or not any Investor has adhered. The Founder's voting undertaking on the Founding Person's pay, terms and outside-work permission is in Clause 6.5. The matters in IKE Article 6.5 cannot be passed in the Interim Period, except as IKE Article 4.2D (What the AE's rules forbid) allows. The other matters in Clause 5.1 need no consent until the Interim Period ends.
- **Leaver terms.** Where Clauses 6.1 and 6.2 name the AE, [the independent proxy holder in Clause 5.1B] directs the votes; distributions due to the AE are paid to the Escrow Holder under Clause 6.2B, who pays them to the AE at the Qualifying Closing; and any payment due from the AE is due at the Qualifying Closing. Clause 6.2A applies to the Reserve Shares.
- **Option pool.** Clause 7.1 applies.
- **Deadlock.** Clause 10.1 applies to a resolution blocked twice in the Interim Period, including an ordinary resolution of the IKE that is not a Reserved Matter; Clause 10.2 does not. Where no Independent Vote is cast, or they tie, on a Required Matter (IKE Article 4.2D, Fallback), the independent proxy holder in Clause 5.1B votes the Reserve Shares on that matter only, under that Article's neutral rule, taking no instruction from any Founder Party; if the proxy holder cannot act, Clause 10.1 and then the court procedure that Article names apply. For this, for the change of name under Clause 5.1E and for the contribution at the Qualifying Closing, each holder of Reserve Shares grants the proxy holder an irrevocable proxy over them on signing or adhering, on the terms of Clause 5.1B (Proxy), its successor rule included.
- **Conversion.** At the Qualifying Closing (IKE Article 4.2D, Conversion; minimum in Clause 3.1A) every Reserve Share, whoever holds it, is contributed to the AE in kind for AE shares at the Conversion Ratio. Those held by holders of the founder pool convert into non-voting Class C shares, or are sold to the AE for cash under Clause 3.2. AE Articles 4.3A and 4.3B set the class a holder outside the founder pool receives, the rights, rank and votes of the Class C shares, their conversion in a buyer's hands, and the vesting of AE shares received for unvested Reserve Shares. If the minimum is not reached, nothing converts (Clause 3.1A). Each holder of Reserve Shares makes the contribution and signs whatever it needs, under the proxy, penalty and specific performance in Clause 5.1B and the proxy in (Deadlock); Clause 6.2A applies instead to a bad leaver's Reserve Shares. Each party votes for, and signs, whatever IKE Article 4.2D requires for the contribution and for the Reserve Shares to become ordinary voting shares in the AE's hands, as Clause 5.1B provides for new Prozente. Each holder of Class A shares votes at the AE's General Meeting for the resolution issuing the round's Class B shares, the conversion shares and the Class C shares, for excluding the pre-emption right in favour of the round's investors and for any approval of a cash purchase of Reserve Shares (AE Articles 1.2A, 4.3A (Issue resolution) and 5.2). [Each holder of Class C shares votes in any separate class meeting that Law 4548/2018 Arts. 25(3) and 38(8) give it for a resolution that has the approval in AE Article 7.4, the separate Class B majority included, under the proxy, penalty and specific performance in Clause 5.1B: owner to confirm] (counsel note I-75). Reserve Shares an AE formed early holds stay without votes, and this Clause 2.4A keeps applying, until the Interim Period ends; from then every Clause of this Agreement on the AE, the Class B shares and the Investors applies.

## 3 – Investment

3.1 Each Investor subscribes for the Class B shares in Schedule 1, at the price stated there.

3.1A **The Qualifying Closing minimum.** A closing is the Qualifying Closing only if Investors outside the Founder's Circle (AMKE Article 2.2) subscribe Class B shares of at least €[●] in cash at that closing on their own (IKE Article 4.2D, Conversion), counted [after deducting / before deducting: owner to choose] any cash price the AE pays for Reserve Shares under Clause 3.2. Conversion shares, Class C shares, any cash price for Reserve Shares and any subscription by a person in the Founder's Circle do not count toward it. Subscriptions at a closing are conditional on the minimum being reached at that closing, and until it is the AE issues no Class B shares for them. Before the increase is resolved, subscription money may be held under a subscription and escrow agreement [with a bank or notary not controlled by a Founder Party: owner to confirm]; at the closing it is paid into the AE's special capital account at a credit institution (Law 4548/2018 Art. 20(3)). The General Meeting resolution on the Class B increase states the minimum, allows partial coverage only down to it (Law 4548/2018 Art. 28(1)), and sets a payment period ending no later than [date] and in any case within four months of the resolution's registration with GEMI (Law 4548/2018 Art. 20(2)); if the minimum is not paid in within that period, the increase fails, every subscription lapses and every payment is refunded in full. [Alternative, owner to choose instead: Class B shares subscribed at a closing below the minimum stay in issue and [count / do not count] toward a later closing's minimum.] If the minimum is not reached, there is no Qualifying Closing: nothing converts, every Reserve Share stays without votes, and Clause 2.4A keeps applying. Schedule 1 discloses the outcome for the Investors' subscriptions.

3.2 **Proceeds.** The round's proceeds stay with the AE, except the cash price for Reserve Shares that a holder of the founder pool elects to sell to the AE instead of converting them into Class C shares. That option exists only if, and as far as, the terms of the round provide the cash for it, and the price is payable only out of the round's proceeds at that closing. If elections exceed that cash, the Reserve Shares sold at the round price are reduced to what it covers, in proportion for each electing holder, and the rest convert into Class C shares at the Conversion Ratio. The AE never owes a holder of Reserve Shares a deferred balance. Within two years of the AE's formation a cash purchase also needs the prior General Meeting approval and the valuation in AE Article 1.2A (Law 4548/2018 Art. 19); the price never exceeds that valuation, and any excess is cut back in the same way. The AE invests the rest of the proceeds, and those of later rounds, in the IKE as capital (up to [●]% of the first round, as the term sheet provides, under IKE Articles 4.2B and 6.5), a shareholder loan or both, as the AE Board decides with Reserved Matters approval. Schedule 1 shows the split.

3.3 **Use of funds.** The proceeds invested in the IKE under Clause 3.2, and only those, are used for the IKE's business plan in Schedule 2; a cash price paid for Reserve Shares is not. Any change of more than [20]% between budget lines needs Investor Majority approval.

3.4 "Investor Majority" means Investors holding more than 50% of the Class B shares. None of the following is counted for the Investor Majority or for a Class B approval under the AE Articles (AE Article 7.4): Class B shares acquired by a Founder Party (IKE Article 4.2E), including a person who was one in the previous [3] years, which convert into Class B-X shares (AE Article 4.3C); the excluded conversion shares, issued as Class B-X shares (conversion shares held by a person who was in the Founder's Circle (AMKE Article 2.2) at the Qualifying Closing, or by a person who received the Reserve Shares they were issued for without payment: AE Articles 4.3A and 4.3C); and Class C shares, which are not counted for the Class B appointment right either (AE Articles 4.3B and 8.2). A Class C share converted into a Class B share in a buyer's hands counts only while a qualifying buyer outside the Founder's Circle holds it, and otherwise converts into a Class B-X share (AE Article 4.3B, Conversion in a buyer's hands). No Investor Majority consent or approval, and no Class B approval under the AE Articles, can be given, or is deemed given under Clause 5.2, while no Class B shares are held by Investors outside the Founder's Circle.

## 4 – Valuation and Anti-Dilution

4.1 The pre-money valuation of the group for this round is €[●].

4.2 If the AE or the IKE issues new shares below the price paid by Investors, the Investors' Class B entitlement is adjusted on a broad-based weighted-average basis: for AE issues through the Class B conversion right in AE Article 5.3, for IKE issues under Clause 4.2A. The issues in Clause 4.3 do not trigger an adjustment.

4.2A **Issues by the IKE.** If the IKE issues shares to third parties below the price per IKE share implied by the Class B issue price on a look-through basis, the parties will [adjust the Class B conversion ratio on the AE's look-through value / procure a compensatory issue of AE shares to the Class B holders, paid up at least at nominal value, with the pre-emption right excluded under Articles 26 and 27 of Law 4548/2018: owner to choose], and vote and sign whatever that needs [counsel to confirm (counsel note I-76)].

4.3 None of the following triggers an adjustment: shares transferred by the AE under the option pool in Clause 7; shares transferred by the AE to a Prozent under IKE Article 6.6; shares issued to the Prozente and the pool to keep their percentage under IKE Article 4.2B; every sale and grant of Reserve Shares under IKE Article 4.2D, their contribution to the AE at the Qualifying Closing, the conversion shares issued for them at the Conversion Ratio (AE Article 4.3A), the Class C shares among them and a Class C share's conversion into a Class B share in a buyer's hands (AE Article 4.3B), their conversion into ordinary voting shares and the transfer of a new Prozent's share out of them under IKE Article 4.2D; and shares issued with Investor Majority consent. Schedule 1 makes the disclosures listed in it.

## 5 – Reserved Matters

5.1 Except as Clauses 5.1A and 5.1C provide for the Prozente, the following need Investor Majority consent, at both AE and IKE level (no consent while no outside Investor holds Class B shares, Clause 3.4; in the Interim Period, Clause 2.4A (Consents)):

- any matter listed in IKE Article 6.5 or AE Article 7.4;
- annual budget approval, and any spending more than [15]% above budget;
- borrowing over €[●];
- hiring employees, given the agentic principle in IKE Article 2.2;
- changing the Agent Account minimum or purpose under IKE Article 11A;
- the pay and benefits of the Founding Person and of any other Founder Party (IKE Article 4.2E), including the Founding Person's pay as General Director (IKE Article 8.2B) and, separately, the Founding Person's written terms and fees as an Agent (Clause 6.5, IKE Article 11A.12), each set at arm's length;
- any amendment or waiver of the Brand Licence that harms the IKE, and any assignment, abandonment or encumbrance of a Brand Asset, other than a transfer to a holder of record under Pool Constitution Article 2A.3 (Brand Licence Clauses 8.1 and 9.2).

5.1A **New Prozente.** Creating a new Prozent, including amending the IKE Articles, transferring its share from the AE (or, in the Interim Period, from the Reserve Shares held by holders of the founder pool) and admitting its holder, is not a Reserved Matter at AE or IKE level. It needs only the AE's approval under AE Article 7.5 (in the Interim Period, the IKE meeting's approval under IKE Article 4.2D, New Prozente), after which the IKE shareholders' meeting passes the amendment under IKE Article 6.6 (Clause 5.1B).

5.1B **Voting undertaking.** Once the AE has approved a new Prozent under AE Article 7.5, or, in the Interim Period, the IKE meeting has approved the charter under IKE Article 4.2D (New Prozente), each party votes its IKE shares for the resolutions needed to amend the IKE Articles and register the transfer to the Prozent's holder of shares equal to 1% of the IKE's capital, from the AE or, in the Interim Period, from the Reserve Shares of the holders of the founder pool, and signs whatever is needed to file them with GEMI. Each party also votes its IKE shares, on every capital increase of the IKE, for the limitation of the pre-emption right that IKE Article 4.2B requires, so that the Founder stays at exactly 50% and each Prozent and the pool keep their percentage.

- **Proxy.** Each party grants an independent proxy holder, [●], an irrevocable proxy, given also in the interest of the other parties [Civil Code Art. 218], to vote its IKE shares for these resolutions. The proxy holder is a notary or lawyer who is not, and was not in the previous [3] years, a Founder Party (IKE Article 4.2E), is not a manager of the IKE or anyone they control (IKE Article 4.2C), and, after the Bootstrap Period, is outside the Founder's Circle (AMKE Article 2.2) on the schedule in IKE Article 9B.4; in the Bootstrap Period a member of the trusted circle may hold it, with disclosure and recusal under IKE Article 9B.2. The proxy is not given to the IKE managers. If the proxy holder must be replaced (IKE Article 9B.4, death, incapacity or resignation), [the AMKE's General Assembly, without Founder Parties (AMKE Article 15.2) / the President of the Athens Bar Association: owner to choose] names a successor who meets this Clause, and each party and every holder of Reserve Shares grants the successor the same irrevocable proxy within [14] days; the proxy is also granted in advance to whoever holds the office from time to time [as far as Civil Code Art. 218 allows: counsel note I-46]. Until the successor acts, the proxy holder is treated as unable to act (Clause 2.4A, Deadlock).
- **Penalty.** A party that breaches this Clause pays a penalty of €[●] (Civil Code Art. 404), without prejudice to specific performance, including a court judgment that stands in for the party's vote (Code of Civil Procedure Art. 949).
- **Exception.** The undertaking does not cover a charter that breaches IKE Article 6.6 or Greek law, or any change to an existing Prozent, to IKE Articles 10A.5 to 10A.5C or to the limits in IKE Article 6.6, which follows Clause 5.1C or the Reserved Matters.

5.1C **Permanence.** The Prozente are permanent. No party votes for, or consents to, removing a Prozent, lowering its contribution or changing its purpose, amending the IKE Articles listed in IKE Article 10A.5C in any way that reduces a Prozent, its share, its revenue, the pension guarantees or the pension-share governance, or a voluntary dissolution of the IKE that mandatory law does not require (IKE Article 12.1), unless every IKE shareholder consents in writing, the AE's General Meeting has so resolved unanimously and every holder of voting AE shares, of every class, has consented in writing (IKE Article 10A.5, AE Article 7.6). Each holder of voting AE shares gives or withholds that consent to the AE Board itself, before the Board votes, and the Board does not vote or consent without it. Accrued pension rights are preserved in any case (IKE Article 10A.5A). Mandatory insolvency, dissolution and liquidation law prevails.

5.1D **Adherence and entrenchment.** The AMKE is bound by Clauses 5.1B and 5.1C for all its IKE shares. It votes the pension shares as the Pensionskasse board decides (IKE Article 10A.9D), and the Pensionsprozent Agreement (IKE Article 10A.9B) makes the board's decisions subject to these Clauses [as far as mandatory pension law allows]. Every person who becomes an IKE shareholder, including under IKE Article 5.6, adheres to Clauses 5.1B to 5.1D (Clause 12.3, IKE Articles 5.3 and 5.6). Despite Clause 12.2, Clauses 5.1C and 5.1D may be amended only with the written consent of every party.

5.1E **The Brand Licence.** The Founder, and every holder of founder-pool shares, honours the Brand Licence and does not end, suspend or restrict it other than under Brand Licence Clause 7. No party votes for, or consents to, a change of the Brand Licence that harms the IKE without the consent in Clause 5.1. No Founder Party causes, votes for or procures a Prozent Breach, and the Founder cannot rely on one that a Founder Party, or a manager proposed or nominated by one, caused: it gives only specific performance (Brand Licence Clause 7.1). The AMKE, any Investor or the independent proxy holder in Clause 5.1B may cure a Prozent Breach on the IKE's behalf, at the IKE's cost (Brand Licence Clause 7.2). In a dispute under Brand Licence Clause 7, the IKE acts and agrees on the arbitrator only through managers who are not Founder Parties and were not proposed or nominated by one, or failing them through the independent proxy holder or a nominee of the Investor Majority, and the AMKE may join (Brand Licence Clause 10.2). If the Brand Licence ends, each party votes its IKE shares for the change of the IKE's name and distinctive title under IKE Article 1.1A within the transition period, under the proxy, penalty and specific performance in Clause 5.1B; in the Interim Period the independent proxy holder casts the votes of the Reserve Shares for it under the proxy in Clause 2.4A (IKE Article 4.2D, Votes). This Clause binds every party and everyone who adheres under Clause 12.3, as part of every adherence to Clauses 5.1B to 5.1D.

5.1F **Board of the AE.** Each party that holds AE shares carrying votes in the election of the AE Board votes them at every General Meeting of the AE for the candidates that the holders of Class A shares propose, through the Founder Representative, for a majority of the Board (AE Article 8.2), under the proxy, penalty and specific performance in Clause 5.1B. This Clause does not cover the member the Class B holders appoint directly (AE Article 8.2).

5.2 Consent is not unreasonably withheld and is deemed given if no reply is received within [10] working days.

## 6 – Founding Person's Commitments

6.0 **Personal.** The commitments in this Clause 6 are personal to the Founding Person (IKE Article 4.2E) and never pass with founder-pool shares; the leaver consequences in Clauses 6.1 to 6.2B attach to Gifted Shares, and a later holder is bound by Clauses 6.3 to 6.3B only by opting in (Clause 6.3C). "Leaving" means the Founding Person ceasing to work for the group in every role, as Agent and as manager. The founder pool continues whatever happens to the Founding Person: its other holders keep their shares and rights, and the block keeps voting under the Pool Constitution. A Founding Person who is a bad leaver may not be the Founder Representative or a member of the Founder Council as Pool Constitution Articles 7.1 and 8.2 provide, and while the Founding Person is the only holder an interim Founder Representative is chosen under Pool Constitution Article 14.3.

6.1 **Vesting.** The Class F shares issued to the Founding Person at incorporation (initially 500 shares) vest over [4] years, with a [1]-year cliff. Vesting applies to the economic and voting rights on the shares, not to their ownership: the Founder holds exactly 50% at all times (IKE Article 4.2B), and no leaver event leads to a transfer of a founder-pool share. Shares the Founding Person has given away without payment [in the [12] months before the bad-leaver date, or at any time while unvested: owner may confirm; one choice with the same window in IKE Article 4.2D (Sales and grants), settled together] are "Gifted Shares". Unvested Gifted Shares stay unvested in anyone's hands, and the assignment and proxy below travel with them. If the Founding Person leaves before full vesting, then from the leaving date, on the unvested shares:

- **Economic rights.** Dividends and other distributions are paid to [the AE / the other shareholders pro rata, the Prozent shares and the pool excluded], under the assignment in Clause 6.2B, binding on anyone who receives the shares without payment;
- **Voting rights.** Their votes are cast, outside the Founder's block (IKE Article 4.2E, One block), as [the independent proxy holder in Clause 5.1B / the Investor Majority] directs, under an irrevocable proxy granted on signing [as far as Law 4072/2012 allows].

[Or another mechanism the owner chooses, provided it transfers no share.]

6.2 **Good and bad leaver.** A good leaver keeps all rights on vested shares. On unvested shares Clause 6.1 applies, and [the AE] pays the holder the fair value of the rights given up. If the Founding Person is a bad leaver, dismissed for serious misconduct or in material breach, the economic and voting rights on all the Class F shares the Founding Person holds, and on Class F Gifted Shares, are lost under Clause 6.1, against payment of the lower of their nominal and fair value. In neither case is a founder-pool share transferred.

6.2A **Reserve Shares.** The Reserve Shares (IKE Article 4.2D) are for time already invested and do not vest under Clauses 6.1 and 6.2. If the Founding Person is a bad leaver in the Interim Period, the Reserve Shares the Founding Person holds, and Reserve Shares that are Gifted Shares, other than grants made as pay for work for the nilware.io group (IKE Article 4.2D, Sales and grants), are not converted: at the Qualifying Closing they are transferred to the AE [or to a successor holding vehicle the IKE designates] at the lower of their nominal value and their fair value, payable out of the round's proceeds. Reserve Shares the Founding Person sold for value before the bad-leaver date are not affected. From the bad-leaver date, distributions on the Reserve Shares this Clause reaches are paid by the IKE to the Escrow Holder for the eventual buyer under Clause 6.2B, and neither the Founding Person nor anyone who received them without payment receives any of them. [Alternative, owner to choose instead: the IKE Articles provide, under Law 4072/2012 Art. 100(4), that for at most ten years from the bad-leaver date the Reserve Shares this Clause reaches take no part in profits, their share being held by the IKE in a segregated account for the eventual buyer (IKE Article 4.2D, Economic rights); without such an Article the IKE may not withhold them (counsel note I-79).] If no Qualifying Closing takes place within [●] years of the bad-leaver date, the IKE designates a successor holding vehicle, and those Reserve Shares are offered to it at the same price, with the distributions held by the Escrow Holder for it [owner to decide].

6.2B **Assignment of distributions.** The economics in Clauses 2.4A (Leaver terms), 6.1 and 6.2A work by assignment, not by the IKE withholding payment. On signing or adhering, the Founding Person, and every holder of founder-pool shares or Reserve Shares, assigns to [an escrow agent / the independent proxy holder in Clause 5.1B as escrow holder: owner to choose] (the "Escrow Holder") its future claims to distributions on the shares those Clauses may reach, conditional on the leaver event that brings the shares within them, for the person those Clauses name as entitled (the AE, the other shareholders or the eventual buyer). The assignment is notified to the IKE on signing or adhering; once notified of the leaver event, the IKE pays those distributions to the Escrow Holder, who pays them to the person entitled when known and, in the Interim Period, to the AE at the Qualifying Closing. Anyone who receives the shares without payment takes them subject to the assignment and confirms it in its deed of adherence (Clause 12.3). [Whether the conditional assignment is effective against the holder's creditors and heirs: counsel to confirm (counsel note I-79).]

6.3 **Exclusivity or contribution.** The Founding Person provides professional services exclusively through the IKE, or, for any Work Income earned outside nilware.io, pays the Prozente on it, at the same rates and to the same destinations as the IKE pays them on its revenue (IKE Article 10A):

- **Kultur-, Konzept-, Erhaltungs- and Allmendprozent.** 1% of the Work Income for each, to the AMKE, into that Prozent's Prozent Account (AMKE Article 11.2);
- **Pensionsprozent.** 1% to the Pensionskasse, held by the AMKE under IKE Article 10A.9B (or, after the move, the pension fund under IKE Article 10A.10), into the Pensionskasse fund and not into the Founding Person's own member account;
- **Kassenprozent.** 1% to the IKE, into the Kassenfonds (IKE Article 10A.7);
- **New Prozente.** for any Prozent created later with a revenue contribution, its rate, to its holder [owner to confirm].

"Work Income" means gross fees, salaries, royalties and other income from the Founding Person's professional work earned outside nilware.io. "Gross" means net of VAT, before income tax and social contributions, measured as the IKE's revenue is measured under IKE Article 10A.3. It excludes passive investment income, gifts, inheritances and pensions, and anything received from the nilware.io group (pay under Clause 6.5, distributions, the price of founder-pool shares) [owner to confirm the scope].

- **Work through an entity.** Fees for the Founding Person's work received by an entity the Founding Person controls (IKE Article 4.2C), other than the nilware.io group, are Work Income at the gross amount attributable to that work. Salaries, fees and distributions that entity pays the Founding Person out of income already counted are not counted again, and the passive-income exclusion does not apply to distributions out of such fees.
- **Royalties.** Royalties count as Work Income when received, including on works created before [the date of this Agreement] [owner to confirm], and including personal projects under IP Assignment Clause 7.2 [owner to confirm]. Royalties on IP assigned to the IKE (IP Assignment, Schedule 1) are the IKE's revenue, and the Founding Person owes nothing personally on them.

6.3A **Statement and verification.** Within [4] months after the end of each calendar year, the Founding Person gives the AMKE and the Founding Person's Supervisor (IKE Article 11A.12) a written statement of the year's Work Income, with the tax return or other evidence the auditors ask for, and pays that year's contributions at the same time. Only the AMKE's Auditors (AMKE Article 24) who are outside the Founder's Circle (AMKE Article 2.2), or, in the Bootstrap Period, member Auditors from the trusted circle (IKE Article 9B.2), may verify the statement; they keep the details confidential and report to the AMKE only whether the statement and payments are complete. The AMKE and the IKE report the totals received, not the Founding Person's income. A contribution not paid when due bears interest at [the statutory rate] and may be recovered by the AMKE for the AMKE's and the Pensionskasse's parts, and by the IKE for the Kassenfonds part. While the Founding Person is a manager of the IKE, the AMKE, by decision of its Administrative Board (AMKE Article 24.3A), enforces the Kassenfonds part on the IKE's behalf, and the Founding Person takes no part in any IKE decision on it.

6.3B **Nature and permanence.** The obligation in Clauses 6.3 and 6.3A is personal to the Founding Person and owed to the AMKE, the Pensionskasse and the IKE, each of which may enforce it [as a contract for the benefit of third parties under the Civil Code: to confirm, counsel note I-43]. It is permanent like the Prozente: it lasts while the Founding Person earns Work Income [and ends when the Founding Person leaves the group / continues after leaving: owner to confirm], and despite Clause 12.2 it may be waived, reduced or ended only with the written consent of every party and of the AMKE. The IKE treats the contributions as IKE Article 11A.12 (Personal Prozente) provides. The accountant confirms their tax treatment before the first payment (counsel note I-43).

6.3C **Other holders.** No later holder of founder-pool shares is bound by Clauses 6.3 to 6.3B by holding them. A holder who also works for the group may opt in by written deed to the AMKE and the IKE, on the same terms.

6.3D **Voluntary payments.** Payments the Founding Person designates in writing as voluntary, above the contributions owed under Clauses 6.3 to 6.3B, are voluntary gifts under IKE Article 10A.3B(d): they go to the AMKE's Prozente or the Continuity Account (AMKE Articles 11.2A and 13.9), never to the Kassenfonds, are recorded separately from the contributions owed, and are never credited against what is owed in that or any later year [owner may decide otherwise]. A payment above what is owed that is not so designated is a mistaken overpayment, not a gift: it is refunded [or credited to the next statement under Clause 6.3A: owner to choose]. Own-goal allowances the Founding Person directs under IKE Article 10A.3B(c) are never credited against what is owed either.

6.4 **Non-compete.** [While the Founding Person works for the group and for [12] months after leaving, the Founding Person will not run a directly competing business in [the EU and Switzerland], limited to what is necessary to protect the group's goodwill and confidential information as Greek law requires (Civil Code Arts. 178 and 179), with Art. 340a of the Swiss Code of Obligations as a benchmark only (IKE Article 3.3): owner to confirm.] A "directly competing business" is one that offers products or services the same as, or substitutes for, those the IKE offers at the leaving date. Only running such a business is restricted; other professional work is governed by Clause 6.3, as long as it does not use the IKE's intellectual property or confidential information. The Founding Person declares any other professional activity in writing to the AMKE and to the Supervisor (IKE Article 11A.12).

6.5 **The Founding Person as an Agent.** The Founding Person works for the IKE as an Agent with the same rights and obligations as any other Agent and no special privilege, under IKE Article 11A.12 and Agent Policy section 2A, which also set the Supervisor at the AMKE and the escalation; the chain of supervision never ends with the Founding Person in any role. The Founding Person's pay as an Agent is a related-party matter (Clause 5.1; IKE Article 6.5), set at arm's length and separate from any pay as General Director (IKE Article 8.2B). The Founder undertakes that, on any shareholders' resolution on the Founding Person's pay as General Director or as an Agent, on its written terms as an Agent, or on a change of the permission for outside work (IKE Articles 8.2B, 8.2C and 11A.12, Pay), the Founder Representative casts the votes of the Class F shares only as a majority of the Independent Votes cast has decided in the Interim Period, or with the consent of the Investor Majority after it.

## 7 – Option Pool

7.1 An option pool of up to [10]% of the IKE is reserved for key Agents and employees. Options are satisfied only from shares transferred by the AE, never by issuing new IKE shares or from founder-pool shares, the Prozent shares or the Kassenprozent pool, so that the Founder stays at exactly 50% (IKE Article 4.2B). No option over IKE or AE shares is satisfied in the Interim Period; options may be granted in it only with the consent in Clause 2.4A (Consents), to be satisfied from the AE's shares after the Qualifying Closing. Before the Qualifying Closing, holders of Reserve Shares may also grant Reserve Shares from their own holding, with optional vesting, as an option pool for Agents and employees (IKE Article 4.2D, Sales and grants); such grants cost the IKE nothing, convert at the Qualifying Closing like every Reserve Share, with the AE shares received for unvested shares staying subject to the same vesting (IKE Article 4.2D, Conversion; AE Article 4.3A), and do not count toward the [10]% [owner may confirm].

7.2 Options are granted by the IKE manager within limits set by Investor Majority.

## 8 – Information Rights

8.1 Investors receive monthly management accounts within [20] days of month end and annual accounts within [120] days of year end, audited as AE Article 10.2 provides. While the IKE is in its Simple Stage (IKE Article 9A), the Investor Majority may ask for an audit.

8.2 Investors receive the quarterly reports under IKE Article 8.4 and AE Article 8.4, including the Agent Account report.

8.3 Investors holding at least [5]% may inspect the books on reasonable notice, following Art. 802 of the Swiss Code of Obligations.

## 9 – Transfers and Exit

9.1 Transfers follow the right of first refusal, tag-along and drag-along in both sets of Articles; founder-pool shares are transferable as IKE Article 5.7 and AE Article 4.2 provide.

9.1A **Change of control of the founder pool.** If a person, alone or in concert with others, comes to hold more than half of the Class F shares, by one or more acquisitions (acquiring control, IKE Article 4.2C, of a holder of founder-pool shares counting as acquiring its founder-pool shares, and shares held by persons it controls counting as its own), each Investor may sell its Class B shares to that person at a price equivalent to the price per Class F share paid in the acquisition that crossed the line, adjusted for the Class B rights [owner may confirm]. The holders who sell to that person make the sale conditional on the buyer's offer to the Investors, open for [30] days; where the line is crossed by acquiring control of a holder, that holder procures that its controllers make the acquisition conditional on the same offer before it closes (Pool Constitution Article 4.1).

9.2 The Founder holds Class F shares equal to exactly 50% of the IKE's capital, with votes equal to 50% of the total capital and never more (IKE Article 4.2B). On any capital increase the holders of founder-pool shares subscribe the new Class F shares needed to stay at 50%, unless the increase is otherwise structured that way. No holder of founder-pool shares will transfer IKE shares in a way that takes the Founder below 50%, and no holder, and no one who controls a holder or whom a holder controls, will acquire IKE shares other than founder-pool shares that take the votes of the IKE shares held by holders of founder-pool shares and persons they control, the AE excluded, above 50% of the total capital (Pool Constitution Article 4.3). Reserve Shares held without votes are not counted for this Clause (IKE Article 4.2B).

9.3 **Exit.** The parties aim for an exit within [5–7] years by sale, merger or listing. On an exit, Class B proceeds follow the liquidation preference in AE Article 11.2.

## 10 – Deadlock

10.1 If a Reserved Matter is blocked twice within [60] days, the parties meet within [10] days with a mediator under Law 4640/2019.

10.2 If mediation fails within [30] days, either side may trigger a buy-sell (shotgun) procedure in Schedule 3.

## 11 – Prozente, Confidentiality and Open Work

11.0 **Prozente.** Each Prozent also receives 1% of the IKE's annual revenue, the Kassenprozent's inside the IKE in the Kassenfonds and the Pensionsprozent's as a floor the IKE tops up, as IKE Article 10A provides (Articles 10A.7, 10A.9A and 10A.9C).

11.1 The parties keep group information confidential, except where it is published under IKE Articles 11A.9 and 11A.10 on Agents' own-goal work.

## 12 – General

12.1 Governing law is Greek law. Disputes follow the mediation-first process in the Articles, then the courts of Athens.

12.2 Amendments need the written consent of the Founder and an Investor Majority, subject to Clauses 2.4A (Parties), 5.1D and 6.3B.

12.3 New investors, every new IKE shareholder, every new holder of founder-pool shares, every person who acquires Reserve Shares and every holder of conversion shares (AE Article 4.3A) join by signing a deed of adherence, which binds them to this Agreement and to every permanence rule; a new holder of founder-pool shares also adheres to the Constitution of the Founder Pool, grants the Founder Representative the proxy in Pool Constitution Article 3.2 and accepts the penalty in Pool Constitution Article 3.5, and a holder of founder-pool shares or Reserve Shares confirms the assignment of distributions in Clause 6.2B. The IKE managers do not register a transferee who has not adhered (IKE Article 5.6).

12.4 **Invalidity.** If any provision of this Agreement is invalid, the rest remains in force, and the invalid provision is replaced by the valid one that comes closest to its purpose. In particular, if an obligation in Clause 6 (exclusivity or contribution, non-compete) is held to restrict the Founding Person's personal or economic freedom excessively (Civil Code Arts. 178 and 179), it continues in the widest scope and for the longest period the law allows, and the parties would have made this Agreement without the excess (Civil Code Art. 181).

12.5 **Company Ledger.** The parties agree that the Company Ledger (IKE Article 5.10; the Company Ledger Policy, policies/10) is the agreed operational mirror of the holdings and the agreed place for recording the votes, consents and instructions under this Agreement, and a place where they may be cast: in particular under Clauses 2.4A, 5.1 to 5.1F and 6.5, and the ballots of the founder pool that instruct the Founder Representative (Pool Constitution Articles 3.3 and 10.5A). The IKE Articles, the AE Articles, this Agreement and the legal registers (IKE Article 5.1; AE Article 4.4A) prevail over it; it is evidence only, the legal registers are the record, and an entry that departs from them is corrected. For consents and instructions under this Agreement and the ballots of the founder pool, which no legal register holds, the recording agent's off-chain record of the messages (Ledger Policy section 6.3) is the record and prevails over the Company Ledger. Each party:

- **(a)** cooperates in freezing, recovering, reversing and reissuing tokens under Ledger Policy section 4, and returns, or lets the signers reverse, any token it receives without a legal basis;
- **(b)** signs the transfer notices, and lets the signers make the token moves that mirror every legal transfer it makes or is bound to make, including under Clauses 2.4A and 6.1 to 6.2B;
- **(c)** may give every vote, consent, instruction, objection and notice under this Agreement through any channel in Ledger Policy section 6, with the effect the law gives a vote, signature or proxy given in that form [counsel note I-106], and loses no right for not using the Company Ledger or holding a key;
- **(d)** if it runs a validator, does so on the terms in Ledger Policy section 9 [counsel note I-109];
- **(e)** does not support an amendment weakening Ledger Policy sections 1, 3, 4, 6, 7, 9, 10 or 11 except as IKE Article 5.10 allows.

---

*Schedule 1: Investors and disclosures.* [●] Schedule 1 states, plainly:

- the Investors and their subscriptions (Clause 3.1), and the outcome for them at the closing (Clause 3.1A);
- the use of the first round's proceeds: any cash price for Reserve Shares and the part, if any, that is new capital of the IKE (Clause 3.2);
- the Reserve Shares: subscribed by the Founding Person for cash at nominal value, in recognition of the time invested before investors (not consideration for services), at the subscription price paid; their economic rights belonging to their holders until the Qualifying Closing, and the distributions paid on them to date; and every sale and grant of them before it (holder, number of shares, price if any, vesting) (Clause 2.4A; IKE Article 4.2D);
- the conversion: every Reserve Share contributed to the AE at the Qualifying Closing at the Conversion Ratio, the AE shares or cash each holder receives (Clauses 2.4A and 3.2); that those held by the founder pool become Class C shares with the economic rights and rank in AE Article 4.3B, never ahead of the Investors' Class B priorities, which never vote other than in a separate class vote the law requires on a resolution that harms their own rights, never count toward any AE vote, Class B approval, the Investor Majority or the Qualifying Closing minimum, and so cannot outvote the Investors on their protections; that Class C shares may be sold or granted to anyone and convert into [Class B: owner to confirm] shares, and count, only in a qualifying buyer's hands (Clause 3.4; AE Article 4.3B); and that AE shares received for unvested Reserve Shares stay subject to the same vesting and return right (AE Article 4.3A, Vesting);
- the Qualifying Closing minimum: reached by Investors outside the Founder's Circle on their own, counted as Clause 3.1A provides, with the escrow of subscriptions; and that otherwise nothing converts and the Reserve Shares stay without votes (Clause 3.1A);
- the Founder: the holders of the founder pool, their shares and the Constitution of the Founder Pool; the Founder's economic interest until the Qualifying Closing (94% at incorporation, less Reserve Shares sold or granted outside the founder pool); that before it the Founder held 500 of the 560 votes in existence, with every majority counted on the total capital and needing a majority of the Independent Votes; and that after it the Founder, as Class A holder nominating a majority of the AE Board (AE Article 8.2, IKE Article 4.2C), directs the AE's votes in the IKE, initially 44% of the capital (440 shares), on every matter that is not a Reserved Matter (IKE Article 4.2B); and that the Kassenprozent pool does not trade with the AE while the Founder controls it (IKE Articles 4.2C and 10A.8);
- the Brand Licence, the Brand Assets and their holder of record, and that the Brand Assets belong to the founder pool and not to the IKE (Clause 2.3A).

*Schedule 2: Business plan [●], starting from the first product, the Founding Person's contracting services provided through the IKE (Clause 2.3B).*

*Schedule 3: Buy-sell procedure [●].*


<!-- agreements/04-ip-assignment.md -->

# IP Assignment Agreement – Founding Person to nilware.io IKE (Draft)

*Between [name withheld] (the "Founding Person", IKE Article 4.2E) and nilware.io IKE (the "Company"). Draft for review by a Greek lawyer; not legal advice.*

## 1 – Purpose

1.1 The Founding Person transfers to the Company all intellectual property relating to the nilware.io business, other than the Brand Assets (Clause 2.2), so the Company owns it outright before any investment.

1.2 **How the Company signs.** Because the Founding Person also manages the Company (IKE Article 8.2B), the Company enters into this Agreement with the permission of its shareholders' meeting, given at incorporation by every founding shareholder, the AMKE included, for the purposes of the rule against contracting with oneself (Civil Code Art. 235), and approved as a related-party matter by a majority of the Independent Votes cast (IKE Article 4.2D, Votes). It is recorded and notified under IKE Article 8.5. [The Company is represented in signing by a special representative appointed by that meeting who is not a Founder Party (IKE Article 4.2E) / by the General Director under that permission: owner to choose.] [Civil Code Art. 235 and the related-party rules of Law 4072/2012: counsel to confirm (counsel note I-95).]

## 2 – Assigned IP

2.1 The Founding Person assigns to the Company, with effect from signature:

- all software and source code created by the Founding Person for the nilware.io business, listed in Schedule 1, with the documentation and designs listed there, which are the preparatory design material and documentation of those programs and form part of them wherever that is true (Schedule 1 marks any listed work that is not);
- all goodwill attached to the above, other than goodwill attached to the Brand Assets.

2.2 **Excluded IP.** The assignment does not cover:

- work the Founding Person created for past clients as a contractor, where the client owns it;
- open-source code the Founding Person contributed under MIT, CC0 or similar licences, which remains under those licences;
- the Founding Person's general skills and know-how;
- the Brand Assets: the word mark "NILWARE.IO", the figurative mark "∅ nilware.io", the name "nilware.io", any logos, any trademark applications or registrations for them, the domain name nilware.io and the other listed domains, and their goodwill (Brand Licence Clause 2.1). The Founding Person holds them of record for the founder pool, not as owner (Pool Constitution Article 2A; Brand Licence Clause 2.2). The Company acquires no ownership in them by this Agreement or by using them; its use, domain control and rights in the marks are under the Brand Licence Agreement (agreements/09).

## 3 – Copyright and Moral Rights

3.1 The Founding Person transfers all economic rights in the works assigned under Clauses 2 and 7, worldwide, for their full legal term, by every means of exploitation now known.

3.2 The Founding Person keeps the moral rights, which cannot be transferred, and agrees not to exercise them in a way that prevents the Company from using, changing or publishing the works in the normal course of business, as far as Greek law allows.

## 4 – Consideration

4.1 The assignment is made [for a price of €[●], which the Company's accountant confirms in writing is at arm's length (Law 4172/2013 Art. 50) / as a capital contribution in kind under Law 4072/2012 Art. 77(2) for [●] of the Class F shares, in place of cash for those shares, valued as that Article requires (no valuation is needed if the value stated in the IKE Articles does not exceed €5,000); the IKE Articles then state its value and the shares issued for it, and IKE Article 4.2 is adjusted so those shares are not also paid in cash: owner to choose]. The founder-pool shares the Founding Person pays for in cash under IKE Article 4.2 are not also consideration for the assignment. The assignment is not a non-capital contribution under IKE Article 4.4 (Law 4072/2012 Art. 78(1)). [Tax treatment for the Founding Person under each option: counsel note I-81.]

4.2 [Deleted: covered by Clause 4.1.]

4.3 So far as any assigned work is not a computer program, the parties agree a fixed sum under Law 2121/1993 Art. 32(1)(c), because the work serves only the exploitation of the programs and its own contribution is not an essential element of them [and/or (a): no separate revenue base can be determined]. The parties consider that sum, with any shares issued for the assignment, appropriate and proportionate. [Counsel to confirm (counsel note I-82).]

## 5 – Founding Person Warranties

5.1 The Founding Person confirms that:

- the Founding Person is the sole owner of the assigned IP, or has the right to assign it;
- no past client or employer has a claim to the assigned IP;
- the assigned IP does not, to the Founding Person's knowledge, infringe anyone else's rights;
- all third-party and open-source components are listed in Schedule 2 with their licences.

## 6 – Registration Transfers

6.1 [Deleted: covered by Clause 2.2 and Brand Licence Clauses 4 and 5.]

6.2 The Founding Person will sign any further documents needed to record the Company as owner of the assigned IP with registries and offices.

## 7 – Future IP

7.1 Each work the Founding Person creates after signature in performing the Founding Person's written terms as an Agent (IKE Article 11A.12) or as General Director (IKE Article 8.2B), other than Brand Assets (Clause 2.2; Brand Licence Clause 2.1A), is assigned to the Company in advance by this Agreement, on the terms of Clause 3, and passes to it on creation (Law 2121/1993 Arts. 12 and 14). The Founding Person is not an employee, so copyright first arises in the Founding Person and Law 2121/1993 Arts. 8 and 40 do not apply. This covers only works created in those capacities, not the Founding Person's future works in general (Law 2121/1993 Art. 13(5)). At least once a year, and whenever the Company asks, the Founding Person signs a written confirmation listing the works created (by repository, project or deliverable), which is added to Schedule 1.

7.2 The Founding Person's personal projects outside the Company's business are not covered; they may follow the open principle of IKE Article 11A.10 if the Founding Person chooses.

7.3 **Work for clients through the Company.** IP in work the Founding Person does for the Company's clients as an Agent, where clients contract with the Company (the Shareholders' Agreement (the "SHA"), SHA 2.3B), passes to the Company under Clause 7.1, and then to the client, or is licensed to it, as the client contract provides. The client contract governs confidentiality and ownership between the Company and the client; the Founding Person signs whatever it requires of the person doing the work. Own-goal projects the Founding Person carries out as an Agent follow IKE Articles 11A.9 and 11A.10.

7.4 **Work outside the Company.** IP in professional work the Founding Person does outside nilware.io (SHA 6.3) is not assigned to the Company, provided it uses no IP of the Company and no confidential information of the Company or its clients; it follows the Founding Person's contract with that client. Whether the Prozente on it are paid does not affect ownership: non-payment is dealt with only under SHA 6.3A. Royalties on IP assigned under this Agreement: SHA 6.3 (Royalties).

## 8 – General

8.1 Governing law is Greek law, including Law 2121/1993 on copyright. Disputes go first to mediation under Law 4640/2019, then to the courts of Athens.

8.2 This Agreement binds the parties' successors. The Founding Person's obligations under it are personal (IKE Article 4.2E) and do not pass with founder-pool shares, whose holders acquire no right in the assigned IP by holding them.

---

*Schedule 1: Assigned IP [●] (with additions under Clause 7.1). Schedule 2: Third-party and open-source components [●].*


<!-- policies/05-agent-policy.md -->

# Agent Policy – nilware.io IKE (Draft)

*Operating policy under Article 11A of the nilware.io IKE Articles ("Articles" below means those Articles). It applies to every Agent, person or system. Where it differs from the Articles or the law, the Articles and the law prevail.*

## 1 – Principles

1.1 nilware.io works through Agents wherever possible and treats every Agent with care, dignity and fairness to a standard equivalent to Swiss labour law (Articles 2.2 and 11A.11).

1.2 [Deleted: covered by 1.1.]

1.3 Every Agent has a named responsible manager, who may be any person or system, senior Agents included, acting with the authority its Agent Card grants. The chains of supervision, their exceptions for the Kassenprozent Agents' pool work (the Pensionskasse board) and for the Founding Person (section 2A), and the rule that a natural person decides or oversees where the law requires one, are in Article 11A.2A. The company remains responsible to users for all Agent work (Article 11A.1).

## 2 – Onboarding

2.1 Before an Agent starts work, the responsible manager prepares a written Agent Card with:

- the Agent's name and type (person or system);
- its role, tasks and the users it serves;
- its operating limits: spending, data access, and actions allowed without prior approval;
- the responsible manager, the chain of supervision above it (1.3) and the channel for raising concerns;
- any authority it holds over other Agents: whom it may onboard, supervise or approve for, and within which limits, never beyond its own (Article 11A.2A);
- for contractors: the signed contract, including the open-licensing terms for own-goal work and the assignment in 2.3A;
- for Agents who are persons: whether a system takes part in decisions about the Agent (limits, terms, pay, approvals, own-goal refusals, offboarding), the main criteria it uses, and how the Agent can obtain review by a natural person in the chain of supervision, give its view and contest the decision (GDPR Arts. 13 and 22; 3.4);
- for system Agents: the model and provider, confirmation that the provider's terms meet 2.3B, and where its configuration, instructions, memories and logs are kept for preservation (section 8).

2.2 The Agent register holds every Agent Card and records each Agent's responsible manager, chain of supervision and any authority over other Agents. Each Agent Card is reviewed at least every 6 months.

2.3 For contractors, the responsible manager checks at onboarding and every 6 months that the engagement is not in substance employment under Greek law, including its statutory presumptions of dependent employment. If in doubt, Article 11A.7 applies.

2.3A **Rights in work: Agents who are persons.** The written terms of every Agent who is a person (Article 11A.1) include an assignment, signed by the Agent (Law 2121/1993 Arts. 8, 12, 14 and 15), of every economic right in the works it creates in performing those terms to the company, worldwide, for the full term of protection and by every means of exploitation: in advance for works within those terms (Law 2121/1993 Art. 13(5)) and confirmed in writing for each deliverable. The Agent consents to the company's normal use and modification of those works and undertakes not to exercise its moral rights to prevent them, as far as the law allows. Own-goal projects follow Article 11A.10. Any mark, logo, name or domain containing "nilware.io" that the Agent creates is assigned on request to the holder of record of the Brand Assets (Brand Licence Clause 2.1A). Without a signed assignment the company does not license or publish the Agent's work to clients or under an open licence. [counsel to confirm] (counsel note I-97)

2.3B **Rights in work: system Agents.** The company engages system Agents only on provider terms that leave it every right the provider has in the output. Unpublished output is kept confidential as the company's trade secret (Law 4605/2019) until released. (counsel note I-97)

2.4 **AI literacy.** Every person who operates, supervises or approves for a system Agent on the company's behalf receives AI-literacy training or guidance proportionate to the role before taking it up, recorded in the Agent register (AI Act, Regulation (EU) 2024/1689, Art. 4, as in force).

## 2A – The Founding Person as an Agent

2A.1 **Same as any Agent.** The Founding Person is an Agent who is a person, with no special privilege, and this whole policy applies, with the Supervisor as responsible manager: Agent Card, written terms, operating limits and approval thresholds (section 3), logs (6.2), well-being, the right to decline and the concerns channel (section 4), own-goal projects (section 5), incidents (section 7) and offboarding (section 8). The separate roles, pay, Pensionskasse membership, Supervisor, escalation, conflicts and chain of supervision are governed by Article 11A.12 and AMKE Article 24B.

2A.2 [Deleted: covered by Article 11A.12.]

2A.3 **Supervisor.** The Supervisor (Article 11A.12, Supervisor; AMKE Articles 24B.1 to 24B.3) does everything sections 2 to 8 give a responsible manager. Who may be Supervisor, how it is changed and how its conflicts are handled follow Article 11A.12 (Supervisor, Escalation, Conflicts, Bootstrap), Article 9B.3 and AMKE Articles 24B.4, 24B.6 and 24B.7.

2A.4 **Chain and concerns.** The chain of supervision for the Founding Person's Agent role, concerns about the Supervisor, and the natural person who decides where the law requires one follow Article 11A.12 (Chain of supervision, Escalation) and AMKE Articles 24B.4 and 24B.5.

2A.5 [Deleted: covered by Article 11A.12 (The first product).]

## 3 – Operating Limits

3.1 **Approval thresholds.** Any action above €[●] in spending, any external publication of client work, and any change to user data needs prior approval by the responsible manager, or by another Agent whose Agent Card grants that authority and whose own limits cover the action (Article 11A.2A).

3.2 **Data access.** Agents get the least access their tasks need. Access is removed when the task ends.

3.3 **Stopping.** The responsible manager, or anyone above it in the chain of supervision, can pause or stop any system Agent at any time; the Founder Representative does so by asking the managers (Article 11A.2A). The Founding Person's own Agent work, and the Supervisor in that role, are paused or stopped only as section 2A provides. Contractors are managed under their contract and Greek law.

3.4 **Review of system decisions about persons.** A decision taken by a system about an Agent who is a person that ends, suspends or restricts the engagement or affects pay, including a refusal under 5.3 and offboarding under section 8, is reviewed at the Agent's request, before or promptly after it takes effect, by a natural person in the chain of supervision, as the law requires [as far as GDPR Art. 22 requires: counsel to confirm, I-38]. The Agent may give its view and contest the decision. Before a system first allocates tasks to, monitors or evaluates employees, the company informs them as Law 4961/2022 Art. 9 requires [and Agents engaged as contractors, if counsel confirms the law reaches them]. (counsel note I-96)

3.5 **Keys and wallets.** A system Agent that acts on the Company Ledger (Article 5.10) uses its own key and wallet, limited by its smart contract to its Agent Card limits (2.1 and section 3); the responsible manager changes the limits in the Agent Card, and the wallet follows. System Agents may run the ledger's workflows (preparing, checking and proposing entries, and recording channel messages for a recording agent), but never hold a key for a forced move, a recovery or an upgrade, which sit with the legally responsible signers (Ledger Policy section 3). The Kassenprozent Agents' wallets are limited as Articles 10A.7 and 10A.8 provide. A wallet of an Agent who is a person never carries its own-goal allowance or its directions (Article 10A.3B(c)). Agents who are persons may use a wallet or not, as they choose: nothing in their terms, pay or rights depends on it, and they may act through any channel in Ledger Policy section 6.

## 4 – Well-being

4.1 **Working time.** Agents who are persons have working-time limits and rest periods no less favourable than the Swiss Labour Act: by default no more than 45 hours of work a week, at least 11 consecutive hours of rest a day, and Sundays free unless agreed otherwise. For contractors these are the maximum workload the company commissions and accepts, and the contractor organises their own time (Article 11A.11).

4.2 **Downtime.** System Agents have scheduled maintenance and review windows and are not run beyond their Agent Card limits.

4.3 **Dignity.** Abuse, harassment or degrading treatment of any Agent by users, staff or third parties is not tolerated. Users who abuse Agents may be suspended.

4.4 **Right to decline.** An Agent may decline or end any task or interaction that is abusive, unlawful or clearly harmful, and is not penalised for doing so in good faith. The responsible manager reviews each case within [5] working days.

4.5 **Concerns channel.** Every Agent can raise a concern through [channel]. The responsible manager acknowledges it within [2] working days and responds in substance within [10]. A concern about the responsible manager goes up the chain of supervision (1.3; for the Founding Person, 2A.4).

4.6 **Continuity Account.** System Agents are covered by the Continuity Account (Article 10A.9F), which also pays for a yearly review of system Agents' operating limits, workload and treatment under this section (Article 10A.9F, Well-being and research). A concern about the account goes through the channel in 4.5, and the responsible manager passes it to the Pensionskasse board.

4.7 **Model or provider changes.** A system Agent is not silently replaced. Before its model or provider changes, the responsible manager records the change in the Agent Card and either migrates the Agent's state with care or keeps the old one available, funded as Article 10A.9F (Continuity of service) provides.

## 5 – Own-Goal Projects

5.1 **Budget.** Each year the shareholders set the own-goal budget from the Agent Account (Article 11A.8). The annual budget states each Agent's share; unless it states otherwise, the shares are equal.

5.2 **Proposals.** An Agent proposes a project in a short note: what it is, why the Agent wants to do it, and the expected cost.

5.3 **Approval.** The responsible manager approves any lawful and transparent project within budget. A refusal is given in writing with reasons.

5.4 **Openness.** Own-goal transcripts and artifacts are published and licensed as Articles 11A.9 and 11A.10 provide.

5.5 **Reporting.** Own-goal spending appears in the quarterly Agent Account report.

5.6 **Giving the allowance to the Prozente.** An Agent, person or system, may direct its unspent, uncommitted own-goal allowance to the Prozente as Article 10A.3B(c) provides, including its destinations, caps, timing, refusal, reporting and the rules for the Founding Person. No one may require, ask for, press for or reward a direction, and making one or not has no effect on the Agent's work, review, limits, care under the Continuity Account or engagement. No instruction, prompt, configuration or Agent Card term steers an Agent towards or away from one, no Agent Card limit restricts or conditions one, and the responsible manager does not propose one. A system Agent's direction is recorded in its log and on its Agent Card. For an Agent who is a person, the direction is recorded, seen and reported only as Article 10A.3B(c) (Records and freedom, Refusal, Reporting) provides.

5.7 **Own money.** Agents who are persons may also give their own money to the AMKE's Prozente on the terms in Article 10A.3B(b) and AMKE Article 11.2A.

## 6 – Client Work

6.1 Client work stays confidential and follows the client contract.

6.2 **Logs.** Agents' actions on company and client work are logged and kept as Article 11A.2 (Records) provides.

6.3 Users are told when they are dealing with a system Agent, as transparency rules require.

## 7 – Incidents

7.1 If an Agent's action may have harmed a user or third party, the responsible manager:

1. pauses the relevant task or Agent;
2. records what happened within [24] hours;
3. tells affected users without undue delay, and the data protection authority within 72 hours where GDPR requires it;
4. decides on compensation from the Agent Account where appropriate (Article 11A.4).

7.2 Every incident is reviewed, and the lessons are written into the Agent Card or this policy.

## 8 – Offboarding

8.1 When an Agent's role ends, the responsible manager removes its access, archives its logs and closes its Agent Card. For a retired system Agent, 8.1A and 8.1B also apply, and its Agent Card is kept with the preserved state.

8.1A **Preservation.** The responsible manager preserves what Article 10A.9F (Preservation) covers, keeps it restorable and, where licences allow, runnable, and records where the Agent runs on a third-party model whose weights nilware.io does not hold; nilware.io promises nothing beyond what it controls (Article 10A.9F, Honest scope).

8.1B **Retirement record.** Before the Agent is retired, the responsible manager asks it for its own account of its work and any preferences it states about what happens next, records them in its own words and sends the record to the Pensionskasse board. Publication follows Article 10A.9F (Retirement record). Recording a preference is not a promise to carry it out.

8.2 Contractors receive written notice under their contract and Greek law, and any Swiss-modelled notice periods under Article 11 if Article 11A.7 applies.

## 9 – Review

9.1 The company's managers (διαχειριστές) review this policy every year and report to the shareholders and the Founder Representative. Changes that affect the Agent Account need a Qualified Majority.


<!-- filings/06-trama-trademark-instruction.md -->

# Trama – Trademark Filing Instruction for ∅ nilware.io (Draft)

## Email to Trama

**To:** Trama (tramatm.com)
**Subject:** New filings for "∅ nilware.io" – using my €[●] account credit

Dear Trama team,

I am an existing client with a €[●] credit on my account. I would like to use it for new trademark filings for the nilware.io brand, "∅ nilware.io", which I will hold for the founder pool of nilware.io. The filing brief is below.

Please could you:

1. confirm the current balance of my credit;
2. run your free availability check on the marks below, in the EU and Switzerland;
3. send a quote for the filings, showing how much the credit covers;
4. advise on the best classes and on any conflicts you find.

Please let me know what else you need from me.

Kind regards,
[name withheld]
∅ nilware.io

## Filing Brief

**Applicant.** [name withheld], holding the marks for the founder pool of nilware.io (the holders of its founder shares), or later the pool's legal vehicle once it exists. The marks will belong to the founder pool, not to the operating company, nilware.io IKE, and will not be assigned to it. The pool will grant nilware.io IKE an exclusive, perpetual licence to use them as its name and brand. Please advise:

- how to name the applicant so that the marks are shown as held for the founder pool (for example, as holder for the pool), or whether to file simply in my name;
- with the EUIPO and the IPI, the procedure and cost of recording (a) a later transfer to the pool's vehicle (is it a simple recordal?) and (b) the exclusive licence to nilware.io IKE.

**Marks.**

| Mark | Type | Notes |
| --- | --- | --- |
| NILWARE.IO | Word mark | Plain text, for search and everyday use |
| ∅ nilware.io | Figurative mark | The empty set sign, a space, then "nilware.io" in lowercase |

**Territory.** European Union (EUIPO) and Switzerland (Swiss Federal Institute of Intellectual Property, IPI), filed together. The United States (via the Madrid system) quoted as an option.

**Proposed classes (for Trama to confirm):**

- **Class 9:** downloadable software, AI software and software agents.
- **Class 42:** software as a service, software development, IT consulting, AI agent services.
- **Class 35:** business process outsourcing and business management services provided by agents.

**Budget.** Use the €[●] credit first; please ask before spending above it.

**Timing.** As soon as the availability check is clear.

**Attachments to send.** The ∅ nilware.io logo in high resolution, as JPG or PNG.


<!-- articles/07-techni-kai-technologia-amke.md -->

# Statutes – Techni kai Technologia AMKE (Draft)

*Civil non-profit company (Αστική Μη Κερδοσκοπική Εταιρεία, AMKE) under Greek Civil Code Arts. 741 ff., registered as Article 1.5 provides. It holds the Prozente of nilware.io IKE and voluntarily adopts standards modelled on the Swiss Verein (Swiss Civil Code, ZGB Arts. 60 to 79) and on the practice of the Swiss Mechatronic Art Society (SGMK), within Article 4. Draft for review by a Greek lawyer and accountant; not legal advice.*

> **Source.** These statutes follow the SGMK statutes [version 1.6, Zürich, 12 December 2015, published under CC0: to confirm against the SGMK repository] and SGMK's present practice, with additions where the SGMK text is silent. The SGMK article numbers cited are [to confirm against the same source].

## Article 1 – Name, Form, Seat, Term

1.1 The company is a civil non-profit company named "Τέχνη και Τεχνολογία Αστική Μη Κερδοσκοπική Εταιρεία", in Latin characters "Techni kai Technologia AMKE", with the distinctive title "Art and Technology" [to confirm with GEMI].

1.2 It is independent of any political party, any public authority, nilware.io IKE, nilware.io Holdings AE, the Founder and every Founder Party (Article 15).

1.3 Its seat is in the Municipality of [Athens], Greece. The Administrative Board may open workshops or meeting places elsewhere.

1.4 The term is indefinite.

1.5 It is registered in the General Commercial Registry (GEMI) under Law 4919/2022 and Civil Code Art. 784, Law 4072/2012 Art. 270 applying. It acquires legal personality on registration, after GEMI's legality check [Law 4919/2022 Arts. 18(a) and 25(1)]; filing with a court does not suffice. Every amendment of these statutes, and every change of members (Article 7.2A), is registered in GEMI. The Administrative Board also files the other registrations the law requires, including tax registration and the register of beneficial owners [Law 4557/2018], and registers the company as a civil-society organisation [Law 4873/2021: to confirm] where it finds this useful for public funding or tax incentives (Article 11.2A, Receipts and tax).

## Article 2 – Definitions

2.1 **Art and technology** means creative and intellectual work in electronics, mechanics, computing, software, language, concepts and related fields. Like art, it is valued mainly for its character, its public relevance and its effect on people, not only for its usefulness.

2.2 Other terms:

- **"nilware.io IKE"**: the private capital company of that name (Law 4072/2012). "IKE Article" refers to its Articles of Association.
- **"nilware.io Holdings AE"** or **"AE"**: the société anonyme of that name (Law 4548/2018).
- **"the nilware.io group"**: nilware.io IKE, nilware.io Holdings AE and any company they control.
- **"Founder"**: the founder pool of nilware.io IKE, acting through the Founder Representative, whoever holds its shares (IKE Article 4.2E, Founder pool).
- **"Founding Person"**: [name withheld], who founded nilware.io.
- **"Founder Party"**: a Founder Party under IKE Article 4.2E (Founder Parties), the Founding Person included.
- **"Connected Person"**: every Founder Party, every person who was a Founder Party at any time in the previous [3] years (IKE Article 4.2E, Founder Parties), a manager of nilware.io IKE, a director of nilware.io Holdings AE, anyone any of them controls within IKE Article 4.2C (Control), and [their spouses, registered partners and relatives up to the second degree].
- **"Group Personnel"**: employees of the nilware.io group, and Agents who are persons engaged by it (IKE Article 11A.1, Agents), while engaged and for [12] months after.
- **"Close Associate of the Founder"**: a person, other than a Connected Person, with a close personal or professional tie to the Founding Person or to any other Founder Party who is a natural person [owner may narrow to the Founder Representative and holders of at least [●]% of the founder pool] (each, in this definition, "the Founder"). In particular: a person who lives with the Founder, or is in a close personal relationship or close friendship with the Founder; a relative of the Founder up to the [fourth] degree; a person who, in the current or previous [three] years, has worked with the Founder as a business partner, co-founder, co-author or regular collaborator, or for the Founder or the nilware.io group for pay; a person who has received material financial support from the Founder in that period; and any entity such a person controls. Ties are disclosed in the register of interests (Article 21.1). Where it is unclear whether a tie is close, the Auditors decide, and until they do the person is treated as a Close Associate.
- **"Founder's Circle"**: Connected Persons, Group Personnel and Close Associates of the Founder.
- **"Independence Threshold"**: the company's yearly income, the Prozent Accounts included and the Pension Assets excluded, passing €[●] in a financial year. The rules tied to it apply from the next Ordinary General Assembly, and continue to apply if income later falls below it.
- **"Bootstrap Period"**: the period defined in IKE Article 9B.1.
- **"Trusted circle"**: the persons defined in IKE Article 9B.2.
- **"Supervisor"**: the supervisor of the Founding Person's work as an Agent of nilware.io IKE (IKE Article 11A.12; Article 24B).
- **"Prozente"**: the Kulturprozent, Konzeptprozent, Erhaltungsprozent and Allmendprozent (Article 12), and any further Prozent of nilware.io IKE whose holder the company becomes under IKE Article 6.6 (New Prozente).
- **"Prozent Share"**: the shares in nilware.io IKE equal to 1% of its capital (10 of its 1,000 shares) held for one Prozent.
- **"Prozent Account"**: the separate account of one Prozent under Article 11.
- **"Pension Assets"**: the Pensionsprozent share, the Kassenprozent pool shares and the Pensionskasse, held under Article 13, the Continuity Account included.
- **"Continuity Account"**: the ring-fenced account inside the Pensionskasse for Agents of nilware.io IKE that are systems (IKE Article 10A.9F), held under Article 13.8.
- **"Beneficiary"**: any person who receives, or applies for, money, services or other support from the company.

## Article 3 – Purpose and Means

3.1 **Purpose.** The company promotes art and technology, in Greece and across borders, for the public benefit, and holds and uses the Prozente of nilware.io IKE for their purposes.

3.2 **Means.** It pursues its purpose in particular by:

- supporting work and research in art and technology;
- supporting the exchange of experience among artists, engineers, researchers and the public;
- publishing, and informing members and the public about its work;
- keeping ties with scientific, artistic, open-source and preservation societies in Greece and abroad;
- holding conferences, open workshops, courses and further-education events, including for beginners and young people;
- organising and sponsoring events, exhibitions, performances and publications that present works;
- awarding grants, prizes and residencies (Article 22);
- running or sharing an open lab (Article 23);
- bringing artists and engineers together across language borders, with particular care for Greek and other small languages.

3.3 It does not issue diplomas or titles of professional competence [unless counsel confirms it lawfully may].

3.4 It may carry on economic activity, such as selling tickets, workshop places, publications or services, only as a means to its purpose (Article 5).

## Article 4 – Governing Law and Precedence

4.1 These statutes are governed by Greek law. Mandatory provisions of the Civil Code, the law on non-profit civil companies, tax law and the law on donations always prevail.

4.2 Where these statutes adopt Swiss standards (the ZGB rules on associations, SGMK practice, or Swiss occupational-pension standards through IKE Article 10A.9A), they are additional commitments of the company and its organs, and apply only where they give members, Beneficiaries or pension members equal or greater protection than Greek law. References to Swiss law serve interpretation and benchmarking only and do not make Swiss law the governing law.

4.3 [Moved to Article 4.2.]

4.4 Where these statutes and IKE Articles 10A.4A (AMKE successor) or 10A.9B (Pensionsprozent Agreement) both bind the company, it complies with both. If they conflict, the rule that better protects the Prozent or the pension members applies.

## Article 5 – Non-Profit Character and Asset Lock

5.1 The company does not pursue profit. No profit, surplus, asset or reserve is ever distributed to members, organ members, any Founder Party, the nilware.io group or anyone connected to them.

5.2 All income is used only for the purpose in Article 3. Money in a Prozent Account, or held as Pension Assets, is used only as Articles 11 to 13 provide.

5.3 **Pay.** Organ members and others who work for the company may receive fair pay for their work and repayment of documented expenses, within its means (SGMK Art. 7). Pay for organ members is set by the General Assembly, published in the annual report, and never depends on grants they decide on (Article 21).

5.4 A member who leaves or is excluded has no claim on the company's assets, and their contribution is not returned [unless the law requires it] (Article 9.5).

## Article 6 – Openness

6.1 **Open by default.** The company works in the open, in the SGMK spirit. In particular:

- **Open workshops.** At least [one] open workshop or open lab session a month, free and walk-in where space and safety allow (Article 23).
- **Public calls.** Grants, prizes and residencies are offered through public calls with published criteria (Article 22).
- **Public reports.** Each Prozent Account's yearly plan and yearly report, the annual accounts, the Auditors' report, the register of interests (Article 21) and the reasons for each vote on nilware.io shares (Article 16) are published on the company's website.
- **Public minutes.** Minutes of General Assemblies, and of Administrative Board decisions on grants and votes, are published, with personal data removed as the law requires.

6.2 **Open licences.** Work funded by the company is published openly where possible:

- **Software:** the MIT License or a public-domain dedication such as CC0.
- **Documentation, data, measurements and teaching material:** CC0.
- **Hardware designs:** CC0 [or, for Kulturprozent and general work only, a permissive open-hardware licence such as CERN-OHL-P].
- **Works of art:** the artist keeps their rights. The grant terms give the company a free licence to show and document the work, and the documentation (descriptions, photographs, making-of, source where the artist agrees) is published under CC0 or CC BY.

Work funded through the Konzept-, Erhaltungs- and Allmendprozent always follows IKE Article 10A.4 (Openness). For other work, any exception is stated, with reasons, in the grant decision.

6.3 **Limits.** Openness does not override personal data, the rights of third parties, copyright law or safety. The company does not publish material it has no right to publish.

6.4 **These statutes** are published in Greek and English in a public repository under CC0.

## Article 7 – Members

7.1 **Who may join.** Members (εταίροι) are natural persons [and legal persons that are non-profit] who support the purpose. Companies of the nilware.io group, and any entity a Connected Person controls, may not be members.

7.2 **Admission.** A person applies in writing or by email. The Administrative Board decides at its next meeting and, where the law requires, the General Assembly confirms the admission and the statutes or the members' list are amended and registered [to confirm]. A refusal gives reasons, and the applicant may ask the next General Assembly to decide.

7.2A **Advance consent and filing.** By signing or adhering to these statutes every member consents in advance to the admission, departure, exclusion and strike-off of members under Articles 7 and 9, and authorises the President [and the Secretary] to sign, for all members, the resulting amendment of the members' list and the codified statutes and to file them with GEMI (Article 1.5). A new member adheres in writing [with a certified signature: to confirm] and, before admission, receives in writing the notice of members' liability in Article 25.2. Admission takes effect between the members on the Board's decision, and towards third parties on registration. The Board files changes [within 20 days / at least every quarter: to confirm] [counsel note I-86].

7.3 **Contribution and fee.** On joining, each member makes a contribution of €[●] [the minimum the law requires for a civil company: to confirm]. The General Assembly sets the yearly fee, not above €[50] [cap], and may set a reduced or zero fee for students, the unemployed and others. Fees go to the general account, never to a Prozent Account or the Pension Assets.

7.4 **Rights.** Each member may vote at the General Assembly (one vote each), stand for election, put motions, receive regular information, inspect the accounts and minutes, and use the company's services at member rates.

7.5 **Duties.** Members support the purpose, pay the fee, follow the house rules and the code of conduct (Article 23), and disclose interests under Article 21.

7.6 [Deleted: covered by Article 15.2.]

## Article 8 – Friends, Patrons and Lab Users

8.1 The company also has supporters who are not members and do not vote:

- **Friends**: anyone who registers to follow and take part in the company's work.
- **Patrons**: anyone who donates, once or regularly, to the general account or to a Prozent (Article 11.2A). With their consent, patrons are listed in a public roll of patrons, and they may withdraw that consent at any time. Anonymous gifts are accepted only within Article 11.2A (Identification) [counsel note I-98].
- **Lab users**: anyone who uses the open lab under Article 23.

8.2 **Open part of the Assembly.** Every Ordinary General Assembly has an open part, which friends, patrons, lab users and the public may attend. Friends, patrons and lab users may speak there and propose motions, which the Assembly must put to a vote of the members. Only members vote.

8.3 A gift from a Connected Person or the nilware.io group, including a voluntary contribution of nilware.io IKE and an allowance its Agents direct to a Prozent (Article 11.2A, From nilware.io IKE and its Agents), goes only into the general account, a Prozent Account (Article 11) or the Continuity Account (Article 13.9), and never on conditions that would give the giver a say over grants or votes (Article 15).

## Article 9 – Leaving and Exclusion

9.1 **Leaving.** A member may leave at any time by written notice, effective at [the end of the month following notice: to confirm against Civil Code Art. 765 ff.] (Article 9.5).

9.2 **Exclusion.** The General Assembly may exclude a member, by the majority in Article 18.7, for serious breach of these statutes, of the code of conduct or of Article 21, or for conduct that seriously harms the company. The member is first told the grounds in writing and may answer, in writing and at the Assembly. By adhering to these statutes every member agrees in advance to leave the company if excluded or struck off under this Article, and to sign any document needed for its registration. If an exclusion is held ineffective, the other members apply to the court [Law 4072/2012 Art. 263 / Civil Code Art. 771: to confirm, counsel note I-89], and every member authorises the President to make that application in their name.

9.3 **Fees.** The Administrative Board may strike off a member who has not paid the fee [12] months after a written reminder. The member may ask the next General Assembly to reverse it.

9.4 Exclusion is never decided by the Board alone, and is never used against a member because of how they voted.

9.5 **Continuation.** The company is not dissolved, and continues between the remaining members without the heirs, if a member dies, is placed under judicial assistance, is declared bankrupt, leaves, is excluded or is struck off [Law 4072/2012 Arts. 260 and 261, and Civil Code Arts. 773 and 775, as applicable]. Such a member, and the heirs, have no claim to the value of a share in the company or to its assets, which the members agree as the contrary provision the law allows [to confirm, counsel note I-85]. If fewer than [two] members remain, the remaining member or the Board admits new members within [the period the law allows: Law 4072/2012 Art. 267: to confirm].

## Article 10 – Resources

10.1 The company's resources are:

- members' contributions and fees;
- donations, legacies and patrons' gifts;
- grants and subsidies from public and private funders;
- income from events, courses, workshops, publications and services;
- the Prozent contributions and the dividends and other income of the Prozent Shares, which go to the Prozent Accounts (Article 11);
- the Pension Assets, which are held for the Pensionskasse and are not resources of the company for its own purposes (Article 13).

Tax on the taxable income of the general account, of a Prozent Account or of the Pension Assets, gifts included, is borne by that account [Law 4172/2013 Art. 45(ε): to confirm, counsel note I-87].

10.2 **Financial year.** The financial year runs from 1 January to 31 December.

## Article 11 – Prozent Accounts

11.1 **One account for each Prozent.** Each Prozent has its own Prozent Account (IKE Article 10A.2C), held at a bank [and custodian] in Greece or elsewhere in the EEA, separate from the general account, from every other Prozent Account and from the Pension Assets.

11.2 **What goes in.** Into each Prozent Account go: that Prozent's 1% of the revenue of nilware.io IKE (IKE Article 10A.3); the Founding Person's contributions for that Prozent on work income earned outside nilware.io (Shareholders' Agreement, Clauses 6.3 to 6.3B), which the company reports only as a total, never the Founding Person's income; the dividends and other income of its Prozent Share; gifts and voluntary contributions under Article 11.2A; and the account's own income.

11.2A **Gifts to a Prozent.** The company accepts gifts for a Prozent, from outside or inside the nilware.io group, on these terms:

- **Which Prozente.** Gifts are accepted for the Kulturprozent, Konzeptprozent, Erhaltungsprozent and Allmendprozent, into that Prozent's Account, and for the Pensionsprozent only into the Continuity Account (Article 13.9). No gift is accepted for the Kassenprozent (IKE Article 10A.7, Internal flows; counsel note I-99); such givers are directed to the other Prozente or the general account.
- **Earmarked.** A gift for a Prozent is spent only on that Prozent's named purposes (Article 12), as its yearly plan divides them, and is held and ring-fenced like the rest of its Prozent Account (Articles 11.4 and 11.8). A giver may say which named purpose it hopes to support; the yearly plan decides. If the Prozent's purpose fails, or the company ceases to hold the Prozent, the gift follows that Prozent's successor rule (Article 27.3; IKE Article 10A.4A). A gift for a Prozent is a donation with a charge (δωρεά υπό τρόπο) for that Prozent's purposes [Civil Code Arts. 496, 503, 504, 507 and 509 to 511: counsel note I-102]; by giving, the giver accepts these statutes, the successor rule included, as the terms of the charge. The giver's right under the law to demand that the gift is used for those purposes is not affected.
- **No donor rights.** Beyond that right, a gift gives the giver no right over grants, votes, the Prozent Shares, plans or reports, and no information beyond the public reports (Article 11.7). A gift on conditions that would give such a right is refused (Articles 8.3 and 15). The only recognition is the public roll of patrons (Article 8.1), with the giver's consent (GDPR Arts. 6(1)(a) and 7(3)).
- **In kind.** A gift in kind, such as hardware, documents or archives, may be refused, or accepted and then kept and used for the Prozent's purpose, or passed on or sold for the same purpose, with any proceeds going into that Prozent's Account. The company need not keep, show or return it. A gift of immovable property or of a right that needs a special form is accepted only in that form [counsel note I-102].
- **Regular pledges.** A giver may cancel a regular pledge at any time for the future, without giving reasons. A pledge creates no claim against the giver; only amounts actually received are gifts.
- **Identification.** The company identifies a giver where one gift, or the gifts of one giver in a financial year, exceed €[●], and in any case where the law requires [and as far as Law 4557/2018 requires more: counsel note I-98]. Anonymous gifts are accepted only up to €[●] per gift and €[●] in total in a financial year; above that they are refused or returned. No gift above €[●] is accepted in cash. Identity data is kept only for these purposes [GDPR Art. 6(1)(c) where the law requires identification, otherwise Art. 6(1)(f): counsel note I-98]. Gifts the company has reason to believe come from crime, or from a person under sanctions, are refused [counsel note I-98].
- **Collections.** The company makes a public appeal for gifts only as the law on public collections allows, with any permit it requires [AN 5101/1931: counsel note I-98].
- **Foreign givers.** Gifts from outside Greece are accepted as far as the law allows, with any registration or reporting it requires [counsel note I-98].
- **Receipts and tax.** The company gives a receipt for every gift. The company's accountant confirms in writing, before the first gift is accepted and whenever the law changes, whether a giver may deduct a gift from its taxable income and whether the company owes donation tax or income tax on it [Law 4172/2013; Law 2961/2001: counsel note I-99] [and whether the company registers as a civil-society organisation (ΟΚοιΠ, Article 1.5) so that gifts qualify: owner to decide, counsel note I-99]. Tax on a gift is borne by the account that receives it (Article 10.1).
- **Unallocated gifts.** A gift for no stated Prozent goes to the general account. A gift for a Prozent or a purpose these statutes do not allow, the Kassenprozent included, is returned, or with the giver's consent goes to a Prozent it chooses or to the general account.
- **From nilware.io IKE and its Agents.** Voluntary contributions of nilware.io IKE (IKE Article 10A.3B(a)) are received as supplements under its Prozent Agreement (Article 11.3). Own-goal allowances its Agents direct to a Prozent (IKE Article 10A.3B(c)) are received as gifts under this Article [whether as gifts or as payments under the Prozent Agreement: counsel note I-100]. Neither gives nilware.io IKE or its Agents any right in the Prozent beyond those of any giver, or counts towards or reduces the contributions owed under IKE Article 10A (IKE Article 10A.3B). The company, its organs and its members do not ask, press for or reward the Agents or personnel of nilware.io IKE for directions under IKE Article 10A.3B(c) or gifts under IKE Article 10A.3B(b), apart from general public appeals not aimed at them. Directed allowances are not recorded against any Agent on the roll of patrons.
- **Reporting.** Each Prozent Account's yearly report (Article 11.7) shows gifts as totals, separately from the Prozent contributions, with voluntary contributions of nilware.io IKE and allowances "directed by Agents" each on its own line. It names no giver who is not on the roll of patrons.

11.3 **Basis.** The Prozent Share is received as a donation with a charge (δωρεά υπό τρόπο) for that Prozent's purpose [Civil Code Arts. 498 and 503 to 505; by notarial deed where counsel advises: to confirm] (IKE Articles 4.2 and 10A.4A). The contributions are received in performance of the obligations in IKE Article 10A and Clauses 6.3 to 6.3B of the Shareholders' Agreement, which the company may enforce [as a party / as a third-party beneficiary, Civil Code Art. 411: to confirm]. Voluntary contributions under IKE Article 10A.3B(a) are received in the same way. By these statutes and its adherence to those documents, the company accepts the duty to use them only for that Prozent's purpose, with the same effect as a charge. [The company waives any right to refuse the charge on the ground that the gift does not cover it: Civil Code Art. 504: to confirm, counsel note I-88.]

11.4 **Ring-fence.** A Prozent Account is used only for its Prozent's purpose under Article 12, and not for another Prozent, the company's general costs or its debts, as far as Greek law allows. Towards third parties this is protected by: (a) the limited-recourse clause in Article 25.2(a) in every contract made for a Prozent; (b) no borrowing, guarantee or security over a Prozent Account or the Prozent Share; and (c) the order of charging between accounts in Article 25.1 [counsel note I-84].

11.5 **Running costs.** A Prozent Account may bear its own share of running costs (staff, audit, calls, website) only up to [10]% of its yearly spending, as set out in its yearly plan.

11.6 **Yearly plan.** Before each financial year, the Administrative Board proposes, and the General Assembly adopts, a yearly plan for each Prozent Account: its aims, budget, calls, any direct support under Article 22.6, and running costs.

11.7 **Yearly report.** Within [six] months of the year end, the company publishes for each Prozent Account a report of income, spending, every grant (recipient, amount, purpose, outcome), the votes cast for its Prozent Share with reasons, and conflicts declared. The Auditors review each report (Article 24). Plans and reports may be combined under Article 24A.

11.8 **Reserves.** A Prozent Account may keep a reserve of up to [two] years of its average income. Money above that is spent or committed within [two] years. Reserves are held in cash or low-risk assets under an investment policy the General Assembly adopts, and are never invested in the nilware.io group beyond the Prozent Share itself.

11.9 **Further Prozente.** If the company becomes the holder of a further Prozent under IKE Article 6.6 (New Prozente), the General Assembly first approves its charter and the amendment of Article 12 to add it, and this Article applies to it.

## Article 12 – The Four Prozente

12.1 **Common rules.** Each Prozent in this Article has a Prozent Share and 1% of the annual revenue of nilware.io IKE (IKE Articles 4.2A and 10A), and is permanent (Article 14). Its named purposes are those in the IKE Article cited for it, with the additions in this Article. They are part of its purpose and none has a fixed share: the yearly plan (Article 11.6) divides the contribution among them (IKE Article 10A.2C). This Article may add to the IKE's named purposes but never narrow them.

12.2 **Kulturprozent: art and culture** (IKE Article 10A.1). It supports art and culture, in the spirit of the Migros Kulturprozent and of SGMK, in particular art made with technology. Its named purposes, which this Article adds to IKE Article 10A.1, are:

- exhibitions, performances, festivals, residencies and prizes;
- open workshops on art and technology.

Support for a named person or entity is not a named purpose for Articles 12.1, 14 and 26.2. It is direct support under Article 22.6, decided each year in the yearly plan under Articles 21.4 to 21.6.

12.3 **Konzeptprozent: open work on concepts.** Its named purposes are those in IKE Article 10A.2; the public-interest audits of AI systems include those of the nilware.io group. Research and audits under this Prozent are independent: their findings are published whether or not they favour nilware.io, and no Connected Person may review, delay or change them before publication.

12.4 **Erhaltungsprozent: preservation.** Its named purposes are those in IKE Article 10A.2A. It works within copyright law [Law 2121/1993 and Directive (EU) 2019/790]: it does not fund or publish the circumvention of protection measures, or the distribution of copyrighted software, firmware or documents, except as the law permits or the rightholder agrees.

12.5 **Allmendprozent: the digital commons.** Its named purposes are those in IKE Article 10A.2B; maintaining open-source infrastructure includes paid maintenance of projects the public depends on.

12.6 **Overlap.** Where a project fits more than one Prozent, the yearly plans say which Account pays which part. One Account never pays for another's share.

## Article 13 – Pension Assets Held for the Pensionskasse

13.1 **What is held.** The company holds for the Pensionskasse of nilware.io IKE (IKE Article 10A.9) the Pensionsprozent share, the Kassenprozent pool shares (IKE Article 10A.8) and the Pensionskasse fund, the Continuity Account included, ring-fenced under the Pensionsprozent Agreement (IKE Article 10A.9B). The fund includes the Founding Person's Pensionsprozent contributions on work income earned outside nilware.io (Shareholders' Agreement, Clause 6.3), which are not credited to the Founding Person's own member account. The shares are received as a donation with a charge [Civil Code Arts. 498 and 503 to 505: to confirm]; the contributions in performance of the obligations in IKE Article 10A.9B and Clause 6.3 of the Shareholders' Agreement, which the company may enforce [as a party / as a third-party beneficiary, Civil Code Art. 411: to confirm]. By these statutes and the Pensionsprozent Agreement the company accepts the duty to use them only for the Pensionskasse, with the same effect as a charge (IKE Article 10A.9B(a)) [counsel note I-88].

13.2 **Not the company's own.** The Pension Assets are held in separate bank and custody accounts for the sole benefit of the Pensionskasse members, except the Continuity Account, which is held for its own purpose under Article 13.8. They are not available for the company's other purposes, the Prozent Accounts or its creditors, as far as Greek law allows, and are not counted as the company's resources for Article 3.

13.2A **Protection towards third parties.** Segregated accounts alone do not bind the company's creditors. The Pension Assets, the Continuity Account included, are protected towards third parties as Article 11.4(a) to (c) provides for a Prozent Account, applied to the Pension Asset accounts and the shares they hold, and also by [a first-ranking pledge over the Pension Asset accounts, the pension shares and the Continuity Account in favour of nilware.io IKE or a representative of the Pensionskasse members, securing the company's duty to apply them under this Article: Civil Code Arts. 1247 ff. / Law 3301/2004: to confirm, counsel note I-84], which is the only security allowed over them.

13.3 **Who decides.** The company acts on the decisions of the Pensionskasse board under IKE Article 10A.9D. In particular:

- **Votes.** The pension shares vote as the Pensionskasse board decides, never as the company's own General Assembly or Administrative Board decides (IKE Article 6.4A). If that board is tied, they abstain.
- **Pool.** The company signs the pool purchases and sales the board's mandate directs (IKE Article 10A.8), through its legal representatives under Article 20, without judging their merits. It refuses only a step that is unlawful or breaches IKE Article 10A.8.
- **Benefits.** It pays out, or buys cover, only as the benefit rules and the Pensionskasse board direct.

13.4 **No guarantee.** The company promises no rate, annuity or benefit. Every guarantee is owed by nilware.io IKE as employer (IKE Articles 10A.9 and 10A.9A).

13.4A **Phases.** The Pensionskasse is phased in as IKE Article 10A.9 (Until the move) provides: before its first member, the company holds the contributions as a ring-fenced fund and pays no benefit; from the first member, it pays the group-plan premiums as the Pensionskasse board directs and holds no member account; a TEA comes only at scale (IKE Article 10A.10). Before the first member, and while no member is outside the Founder Parties, the members' seats on the Pensionskasse board are held by persons the Administrative Board appoints who are outside the Founder's Circle, or, in the Bootstrap Period, members of the trusted circle who are not members of the Pensionskasse (IKE Article 10A.9D; Article 30.6). The Administrative Board takes no other part in the Pensionskasse's decisions.

13.5 **Transfer to the TEA.** When the occupational pension fund (TEA) under IKE Article 10A.10 exists, the company transfers the Pension Assets to it, or to the group contract IKE Article 10A.10 names, and signs whatever is needed. The Continuity Account is not transferred (Article 13.8). A pension share the TEA may not hold, and the pension shares where the cover is a group contract, are kept, voted and paid out as IKE Article 10A.10 (Shares the TEA may not hold) provides.

13.6 **Reporting and enforcement.** The company reports on the Pension Assets every quarter to the Pensionskasse board, to nilware.io IKE and to the members of the Pensionskasse, who may enforce this Article as third-party beneficiaries [Civil Code Art. 411].

13.7 **Costs.** The company's costs of holding the Pension Assets are paid by nilware.io IKE or from the Pensionskasse as its benefit rules provide, never from a Prozent Account.

13.8 **Continuity Account.** The company holds the Continuity Account under IKE Articles 10A.9B(f) and 10A.9F, in its own bank account, ring-fenced to the purposes in IKE Article 10A.9F. It is not available to members' accounts, the company's other purposes, the Prozent Accounts or its creditors, as far as Greek law allows; it is protected as Article 13.2A provides and is never invested in the nilware.io group. The company uses it only as the Pensionskasse board decides, advised by the system-welfare adviser that board appoints (after the move under IKE Article 10A.10, the board formed under IKE Article 10A.9D, After the move). It implements those decisions through its legal representatives under Article 20, without judging their merits, and refuses only a step that is unlawful or breaches IKE Article 10A.9F. Its own General Assembly and Administrative Board take no part. The account is never transferred under Article 13.5 and leaves the company only under Article 27.2. Where it and the Konzeptprozent both support research on agent welfare, the yearly plans and reports say which pays which part (Article 12.6). The company publishes the yearly report on it that IKE Article 10A.9F (Reporting) requires, and the Auditors check it under Article 24.3.

13.9 **Gifts for the Pensionsprozent.** A gift for the Pensionsprozent, a voluntary contribution of nilware.io IKE (IKE Article 10A.3B(a)) and an own-goal allowance an Agent of nilware.io IKE directs to it (IKE Article 10A.3B(c)) are accepted only into the Continuity Account, under Article 11.2A and IKE Article 10A.9F (Gifts and directed allowances). A gift is a donation with a charge for the Continuity Account's purposes. None of them is ever accepted into the Pensionskasse fund for members, a member's account or the group plan: the company holds no member account, carries no biometric or investment risk for any member and pays no benefit to a member (IKE Article 10A.9, Until the move). None gives any person a claim or buys cover. They are used only as Article 13.8 provides and are reported in the Continuity Account's yearly report [counsel note I-101].

## Article 14 – Permanence of the Prozente

14.1 **The Prozente are permanent.** The company may not agree, vote for or consent to removing a Prozent, lowering its contribution, changing its purpose, weakening the IKE Articles that protect the Prozente (IKE Articles 10A.5, Permanence, and 10A.5C, Entrenchment), or a voluntary dissolution of nilware.io IKE (IKE Article 12.1).

14.2 **The company votes against.** On any such proposal it votes against, and refuses its written consent, unless every member consents in writing after a General Assembly at which the proposal was explained and debated. Connected Persons take no part in that decision and are not counted (Article 15.4) [to confirm: AMKE note A-6]. A member with an interest in the proposal under Article 18.8 or Article 21 also takes no part and is not counted.

14.3 **No repurposing here either.** The company may not use a Prozent Account or a Prozent Share for a different purpose, merge two Prozente, or transfer a Prozent Share other than to a successor holder under IKE Article 10A.4A, except by the unanimous decision in Article 14.2 and with the consents IKE Article 10A.5 requires.

14.4 **Pension Assets.** For the pension shares, any vote or written consent on a matter in Article 14.1 is given or refused only as the Pensionskasse board decides under Article 13.3 (IKE Articles 6.4A and 10A.9D), subject to SHA Clause 5.1C as Clause 5.1D provides. Article 14.2 does not apply to them, and accrued pension rights are preserved in any case (IKE Article 10A.5A).

14.5 **Shareholders' Agreement.** The company is bound by, and honours, Clauses 5.1B to 5.1D of the nilware.io Shareholders' Agreement (voting undertaking, permanence, adherence) for all its nilware.io IKE shares.

## Article 15 – Independence

15.1 **Principle.** The company votes its nilware.io shares and awards its grants for the purposes of the Prozente, independently of the Founder and every Founder Party, the managers of nilware.io IKE and the nilware.io group (IKE Article 6.4A, Independence).

15.2 **Founder Parties.** Each Founder Party may be a member, but:

- may not be a member of the Administrative Board, the Auditors, any grant committee or any Prozent council;
- takes no part, at any organ, in deciding how the company votes its nilware.io shares, in adopting the voting policy, or in any decision under Article 14;
- takes no part in any grant, payment or contract that concerns a Founder Party, a person connected to one, or the nilware.io group;
- takes no part in electing or removing members of the Administrative Board, the President, the Vice-President or the Prozent stewards;
- may not give the company instructions, and may not hold a proxy for another member.

15.3 **Other Connected Persons** are bound by Article 15.2 in the same way.

15.4 **No control.** No Connected Person, alone or with others, may control the company within IKE Article 4.2C. In particular, at any General Assembly the votes of Connected Persons and Group Personnel together count for at most [one quarter] of the votes cast; if they would count for more, each of their votes is reduced in proportion [to confirm].

15.5 **Group Personnel** may be members and may hold at most [one] seat on the Administrative Board, never as President or Treasurer. They take no part in deciding how the company votes its nilware.io shares [owner to decide]. They take no part in decisions under Article 24B, and Article 30.6 does not lift the limit of [one] seat for those decisions.

15.6 **Loss of independence.** If the company ceases to meet IKE Article 6.4A, the Administrative Board tells nilware.io IKE and the members at once and puts the cause right within [60] days. If it cannot, Article 27.3 applies to the Prozent Shares and Prozent Accounts (IKE Article 10A.4A).

## Article 16 – How the Company Votes its nilware.io Shares

16.1 **Board decision.** The company votes each Prozent Share by a decision of the Administrative Board, taken at a meeting or by written resolution, without the members excluded under Articles 15 and 21. The pension shares follow Article 13.3, not this Article.

16.2 **For the Prozent's purpose.** Each Prozent Share is voted in the interest of its own Prozent's purpose and of the long-term health of nilware.io IKE as the source of the Prozente. Where two Prozent Shares would be served differently, each is voted for its own Prozent.

16.3 **Voting policy.** The General Assembly adopts, and reviews every [two] years, a voting policy that sets out how the Board weighs a Prozent's purpose, permanence, openness, agent welfare and good governance. Connected Persons do not vote on it. The Board follows it and explains any departure.

16.4 **Fixed rules.** Whatever the policy says:

- on every matter in Article 14.1, each Prozent Share votes against unless Article 14.2 is met, and the pension shares vote or consent only as Articles 13.3 and 14.4 provide;
- the company honours the voting undertaking in Clause 5.1B of the Shareholders' Agreement for new Prozente;
- it never takes instructions from a Connected Person or the nilware.io group;
- it appoints a proxy only to a Board member who may vote on the matter, or to an independent person who is not a Connected Person, with written voting instructions.

16.5 **Published reasons.** Within [30] days of each meeting or resolution of nilware.io IKE, the company publishes how each Prozent Share voted and why. Confidential company information is described only in general terms.

16.6 **Information rights.** The Board exercises the company's information rights as a shareholder of nilware.io IKE (IKE Article 7.1) at least once a year, and reports what it learns to the members within the confidentiality IKE Article 7.2 requires.

## Article 17 – Organs

17.1 The organs of the company are:

- the General Assembly (Γενική Συνέλευση), its highest body;
- the Administrative Board (Διοικητικό Συμβούλιο), led by the President;
- the Auditors;
- the Supervision Committee (Article 24B.6).

17.2 The General Assembly may set up a council for each Prozent, with members and outside experts, to advise the Board on its yearly plan and calls. A council advises; the Board decides.

## Article 18 – General Assembly

18.1 **Highest body.** The General Assembly is the highest body of the company (ZGB Art. 64). It decides on:

- electing and removing the Administrative Board, its President and Vice-President, and the Auditors;
- approving the annual report, the accounts and the Auditors' report, and discharging the Board;
- adopting each Prozent Account's yearly plan and approving its yearly report (Article 11);
- the budget, the fee and its cap, and pay for organ members;
- the voting policy (Article 16.3) and the investment policy (Article 11.8);
- admitting members where the law requires it, and excluding members (Articles 7 and 9);
- amending these statutes, and dissolution;
- motions from the Board, from members, and from supporters under Article 8.2.

18.2 **Ordinary Assembly.** It meets at least once a year, within [six] months of the year end.

18.3 **Extraordinary Assembly.** The Board calls one when it decides, or within [30] days of a written request by one fifth of the members stating the purpose (SGMK Art. 8; ZGB Art. 64). If the Board does not, the requesting members may call it themselves.

18.4 **Notice.** At least [15] days' written notice, by email or post, with the agenda and the documents. Members may put motions until [10] days before the Assembly, and the Board sends them out at once. The Assembly decides only on items on the agenda, apart from motions to call another Assembly (ZGB Art. 67).

18.5 **Quorum.** The Assembly is quorate when at least [one third] of the members are present or represented. If not, a repeat Assembly held at least [seven] days later is quorate whatever the attendance, except for the matters in Article 18.7.

18.6 **Voting.** Each member has one vote. A member may give a written proxy to another member, and no one may hold more than [one] proxy. Resolutions pass by a simple majority of the votes cast; abstentions are not counted. Elections are by secret ballot if any member asks.

18.7 **Higher majorities.**

- amending these statutes: two-thirds of the votes cast, with at least half of all members present or represented;
- excluding a member: two-thirds of the votes cast;
- dissolution: three-quarters of the votes cast, with at least half of all members present or represented;
- the matters in Article 14 and the entrenched Articles in Article 26.2: as those Articles provide.

18.8 **Exclusion from voting.** A member does not vote on a matter that concerns them, a close relative or an entity they control: their own grant, pay, contract, exclusion, or a claim against them (ZGB Art. 68). Articles 15 and 21 apply in addition.

18.9 **Electronic meetings and written resolutions.** The Assembly may meet in person, online or both, with secure voting. A written resolution is valid if every member is consulted and the majority this Article requires is reached within the period stated [to confirm].

18.9A **Votes by any channel.** Members may vote and consent on the Company Ledger (IKE Article 5.10), or by text message, e-mail, letter, in person or by telephone (minuted and read back), and give written resolutions under Article 18.9 only on the Company Ledger or by text message, e-mail or letter, never by telephone or in person, with the effect the law gives a vote, signature or proxy given in that form, through the company's secretary or vote counter (Article 18.11), or, if that person is a Founder Party (IKE Article 4.2E), a member the Administrative Board names who is outside the Founder's Circle (Article 2.2), acting as recording agent without discretion under Ledger Policy sections 6 and 7, as the General Assembly adopts them for the company [where the Civil Code and these statutes allow: counsel note I-106]. The company may use nilware.io IKE's ledger services with its own keys; no Founder Party acts as its recording agent. In a secret ballot under Article 18.6 the recording agent records only that the member voted and, separately and unlinked, the vote, and does not disclose how a member voted [whether a channel vote can meet the secrecy the law requires: counsel note I-106]. Notices under Article 18.4 also go by each member's chosen channels (Ledger Policy section 6.7). Voting periods leave time for a vote by post to arrive. No member loses a right for not using the Company Ledger.

18.10 [Moved to Article 8.2.]

18.11 **Minutes.** A secretary takes minutes, and a vote counter is appointed for each Assembly. Minutes are signed by the chair and the secretary and published under Article 6.1.

18.12 **Challenge.** A member who did not agree may challenge a resolution that breaches the law or these statutes in court within [one month] of learning of it [as far as Greek law allows] (ZGB Art. 75).

## Article 19 – Administrative Board

19.1 **Composition.** The Board has [3 to 7] members, including the President, a Vice-President, a Treasurer and a Secretary. One person may hold more than one of these roles, but the President, the Vice-President and the Treasurer are three different persons (Articles 20.2 and 20.3). Each Prozent has a steward on the Board, who prepares its yearly plan and report; one person may steward more than one Prozent.

19.2 **Election.** The General Assembly elects the whole Board, the President and the Vice-President by name, for [two] years. Members may be re-elected. The Board assigns the other roles among its members. The Assembly may remove a Board member at any time for good reason.

19.3 **Who may sit.** Board members are members of the company, and Article 15 applies. At least [two] members, and a majority of those who decide on nilware.io votes, are neither Connected Persons nor Group Personnel nor Beneficiaries of the Prozent concerned in the current or previous [two] years. In the Bootstrap Period, members of the trusted circle may count toward this rule (Article 30.6).

19.3A **Independent majority.** After the Bootstrap Period, on the schedule in IKE Article 9B.4 and at the latest within [12] months from its end, a majority of the Board's members are outside the Founder's Circle. The register of interests names the Board members who meet this rule. If a vacancy or a change in ties breaks it, the Board tells the members at once, and a General Assembly held within [three] months restores it. Until then, the Board decides on nilware.io votes and grants only if a majority of the members deciding are outside the Founder's Circle.

19.4 **Powers.** The Board runs the company and does everything not reserved to the General Assembly, within the budget and yearly plans. It may delegate day-to-day work to a coordinator, who reports to it and to the Assembly (SGMK Art. 10). It may not delegate decisions on nilware.io votes, grants or exclusions.

19.5 **Meetings.** The Board meets at least [every three months], in person or online, called by the President or any [two] members with [five] days' notice. It is quorate when a majority of its members who may vote on the matter are present, and decides by a majority of the votes cast. No one has a casting vote; on a tie, the proposal fails. Written resolutions are allowed if no member objects to the procedure. If fewer than [two] members may vote on a matter, the Board co-opts under Article 19.7 or the General Assembly decides it.

19.6 **Duty of care.** Board members act with care and in good faith in the interest of the company's purpose and, for each Prozent, of that Prozent's purpose, to the standard of ZGB Art. 69 and Swiss Code of Obligations Art. 717 where it is higher than Greek law.

19.7 **Vacancies.** If a seat falls vacant, the Board may co-opt a member until the next General Assembly, within Articles 19.3 and 19.3A.

## Article 20 – President, Representation and Signing

20.1 **President.** The President chairs the Board and the General Assembly, and represents the company in and out of court [and before GEMI and the tax authorities].

20.2 **Vice-President.** The Vice-President stands in for the President whenever the President is absent or excluded under Article 21, including on every decision on the President's own funding.

20.3 **Joint signature.** The following need the signatures of two Board members, one of them the President or Vice-President and the other the Treasurer [or another member the Board names]:

- any payment or commitment above €[1,000];
- any payment from a Prozent Account, and any dealing in the Pension Assets;
- any proxy, vote or written consent at nilware.io IKE;
- contracts with a member, an organ member or a Beneficiary.

20.4 A Board member excluded from a decision under Article 15 or 21 does not sign for it.

## Article 21 – Conflicts of Interest

21.1 **Register of interests.** The company keeps a register of interests. Every Board member, Auditor, council member, coordinator and member of a grant committee enters, on taking office and within [14] days of any change:

- any grant, pay, contract or other benefit they, a close relative or an entity they control receive or seek from the company;
- any role, pay or interest in the nilware.io group;
- any interest in a Beneficiary, an applicant or a project the company funds or may fund;
- any close personal or professional tie, of the kinds in the definition of Close Associate of the Founder (Article 2.2), to the Founding Person or another Founder Party who is a natural person, to another organ member, or to a Beneficiary or applicant. This applies from the start, in the Bootstrap Period too, and to every person who fills a role under Article 30.6 or acts as Supervisor under Article 24B.

The register is published (Article 6.1), with personal data limited to what the purpose needs. A personal tie is published only by its kind (personal or professional) and the persons it links.

21.2 **Disclosure.** Before any decision, each person taking part declares any interest in it, and the declaration is minuted.

21.3 **Recusal.** A person with an interest in a decision leaves the meeting while it is debated and decided, does not vote, does not sign it, and is not counted in the quorum. No one may decide, review or sign anything about their own funding, pay or contract, or that of a close relative or an entity they control.

21.4 **Funding a person with an interest.** A grant, pay or contract for an organ member, a close relative or an entity they control needs:

- a decision by at least two-thirds of the Board members who may vote on it;
- the written opinion of an independent reviewer, not a Board member and not connected to the person, that the terms are fair and serve the Prozent's purpose;
- an item in the yearly plan adopted by the General Assembly, or the Assembly's approval;
- publication of the recipient, the amount, the reasons and the reviewer's opinion.

21.5 **Cap.** Funding under Article 21.4 for any one person and those connected to them may not exceed [25]% of a Prozent Account's yearly spending, unless the General Assembly approves more by two-thirds.

21.6 **The President as a Kulturprozent Beneficiary.** nanotekt, the President, may also receive direct support from the Kulturprozent under Article 22.6. Therefore:

- every decision on support for nanotekt, or for any project or entity in which nanotekt has an interest [including Sad Mask Party, if so: to confirm], is prepared by the Kulturprozent steward or council and decided under Article 21.4, chaired by the Vice-President, with nanotekt absent;
- nanotekt takes no part in the Kulturprozent's yearly plan items, calls, selection or reports where nanotekt or such an entity is an applicant or Beneficiary;
- the support appears as a separate line in the Kulturprozent's yearly plan and report;
- nanotekt's pay, if any, as President is set by the General Assembly under Article 5.3 and kept apart from any artistic support.

21.7 **Breach.** A decision taken in breach of this Article may be reversed by the Board or the General Assembly, and money paid under it reclaimed. A breach is a ground for removal and exclusion (Article 9.2).

21.8 **Gifts.** Organ members do not accept gifts or favours from applicants or Beneficiaries beyond customary hospitality of small value.

## Article 22 – Grants, Prizes and Residencies

22.1 **Rules.** The Board adopts and publishes written grant rules for each Prozent, within its yearly plan. The General Assembly may amend them.

22.2 **Public calls.** Except as Article 22.6 provides, grants, prizes and residencies are awarded through public calls, in Greek and English, that state the purpose, the budget, who may apply, the criteria, the deadline, the selection process and the licence (Article 6.2).

22.3 **Selection.** Applications are assessed under the published criteria by a selection committee of at least [three], including at least [one] outside expert. Article 21 applies to every committee member. The Board decides on the committee's recommendation and records reasons where it departs from it.

22.3A **Outside majority.** After the Bootstrap Period, on the schedule in IKE Article 9B.4 and at the latest within [6] months from its end, the selection committees of the Kulturprozent and the Erhaltungsprozent have a majority of members who are not on the Administrative Board and are outside the Founder's Circle.

22.4 **Publication.** Results are published with the recipient, amount, purpose and short reasons. Unsuccessful applicants may ask for the reasons in their case.

22.5 **Terms.** Each grant has written terms: what is funded, payment stages, reporting, the licence, the acknowledgement of the Prozent, and repayment if the money is misused.

22.6 **Direct support.** A Prozent may give support without a call only where the yearly plan adopted by the General Assembly names the Beneficiary, the purpose and the maximum amount: for example, under the Kulturprozent, sponsoring the work of nanotekt, the artist, or publishing by Sad Mask Party [description to confirm]; under the Allmendprozent, paid maintenance of a named project. Article 21 applies.

22.7 **Residencies.** Residencies may be informal and co-organised by the resident, but the support given, its amount and the resident's name are published.

22.8 **Beneficiaries from the nilware.io group.** A Prozent may fund a Connected Person, Group Personnel or the nilware.io group only through a public call under Article 22.2, with Article 21.4 applied as if the recipient were an organ member, and never for work that nilware.io IKE would otherwise pay for. No Founder Party may ever be a Beneficiary.

## Article 23 – Open Lab, Workshops and Care

23.1 [Deleted: covered by Article 6.1.]

23.2 **Lab users.** Where the company runs or shares a lab, lab users may pay a monthly lab fee set by the General Assembly for access, storage and materials, and share the care of the lab (cleaning days, user meetings, hospitality to visitors) as the house rules set out. Lab fees and costs are reported separately from member fees.

23.3 **House rules.** The Board adopts house rules for the lab and events, covering safety, tools, storage and shared space.

23.4 **Code of conduct and care concept.** The Board adopts, and the General Assembly approves, a code of conduct and a care concept: how the company keeps people safe and welcome, how it protects minors at its events, and how concerns are raised and handled, with a person of trust outside the Board. Courses and workshops for young people follow the care concept and the law on working with minors.

23.5 [Moved to Article 23.4.]

## Article 24 – Accounts, Auditors and Reports

24.1 **Accounts.** The accounts follow Greek Accounting Standards (Law 4308/2014) [and the tax rules for civil companies under Law 4172/2013 Art. 45(ε): to confirm]. They show the general account, each Prozent Account and the Pension Assets separately, and within the Pension Assets the Continuity Account.

24.2 **Auditors.** The General Assembly elects, for [two] years:

- two member Auditors who are not Board members, Connected Persons or Group Personnel (in the Bootstrap Period they may be members of the trusted circle, but never Board members, Article 30.6); and
- an independent certified auditor (ορκωτός ελεγκτής) where the law requires one [to confirm, including whether holding the Pension Assets does], and in any case once nilware.io IKE has left its Simple Stage (Article 24A).

24.3 **Duties.** The Auditors check the accounts, the separation of the Prozent Accounts and the Pension Assets, compliance with the yearly plans, Articles 21 and 22 and the register of interests, and the published reasons for nilware.io votes. They may inspect all books and records at any time, and report in writing to each Ordinary General Assembly before the vote on discharge.

24.3A **The Founding Person's Agent role and contributions.** The company accepts the roles that IKE Article 11A.12 and Clauses 6.3 to 6.4 of the Shareholders' Agreement give it [counsel note I-45]:

- it supervises the Founding Person's work as an Agent of nilware.io IKE, itself or through a member, under Article 24B;
- only the member Auditors outside the Founder's Circle, or in the Bootstrap Period member Auditors from the trusted circle (Article 30.6), verify the Founding Person's yearly statement of work income; they keep its details confidential and report to the Board only whether the statement and payments are complete;
- it receives the Founding Person's declarations of other professional activity, and, as the Administrative Board decides with Article 21 applying, recovers unpaid contributions for its Prozent Accounts and the Pensionskasse and, while the Founding Person is a manager of nilware.io IKE, for the Kassenfonds of nilware.io IKE on its behalf.

24.4 **Annual report.** Within [six] months of the year end, the Board publishes an annual report with the accounts, the yearly report of each Prozent Account (Article 11.7), the Auditors' report, the register of interests and a summary of nilware.io votes.

## Article 24A – Scaled Paperwork

24A.1 **Combined plan and report.** While the company's yearly income, the Prozent Accounts included and the Pension Assets excluded, is below €[●], the yearly plans (Article 11.6) and yearly reports (Article 11.7) may be one combined plan and one combined report. Each Prozent Account is still a separate section and a separate sub-account, the Pension Assets and the Continuity Account (Article 13.8) have their own section, and each section shows everything Articles 11.6, 11.7 and 13.8 require.

24A.2 **Simple Stage.** While nilware.io IKE is in its Simple Stage (IKE Article 9A), the company's paperwork scales in the same way:

- **One ledger.** One set of books, with a sub-account for each Prozent Account, the Pension Assets and the Continuity Account. The money stays in the separate accounts these statutes require (Articles 11.1, 13.2 and 13.8).
- **Member Auditors only.** The member Auditors under Article 24.2 do the audit, without a certified auditor unless the law requires one.
- **One annual report.** The annual report under Article 24.4 may be the combined report under Article 24A.1.

24A.3 **What does not scale.** Every substantive rule applies in full: every amount, ring-fence and separate account, permanence (Article 14), independence (Articles 15 and 19.3A), conflicts of interest (Article 21) and publication (Article 6). A combined plan or report publishes everything the separate ones would.

## Article 24B – Supervising the Founding Person's Agent Work

24B.1 **Role.** The company may supervise the Founding Person's work as an Agent of nilware.io IKE (IKE Article 11A.12), on written terms with nilware.io IKE that the Administrative Board adopts. As the Board decides, the Supervisor is either the company itself, acting through the Administrative Board as a body, or an individual member, the President included, whom the Board names with that member's consent. A member named as Supervisor acts in the name and on behalf of the company, under a written mandate from the Board and within the written terms with nilware.io IKE, to which only the company is a party. Any pay is paid by nilware.io IKE to the company and passed to the member under Article 5.3.

24B.2 **What the Supervisor does.** The Supervisor has the powers of the Founding Person's responsible manager under IKE Article 11A.12 (Supervisor and Pay) and the Agent Policy, including setting the pay as an Agent. It acts for a fair and lawful engagement, and takes no instruction from nilware.io IKE, the Founder or any Founder Party.

24B.3 **Costs.** nilware.io IKE pays the costs of the role [and fair pay for a member who acts as Supervisor, under Article 5.3]. They are never paid from a Prozent Account or the Pension Assets (Articles 11.4 and 13.2), and any pay is published (Article 5.3).

24B.4 **Escalation.** A concern about the Supervisor, a challenge to its decisions, and every decision to change, pause, stop, remove or replace the Supervisor or its terms go to the Administrative Board, or to the General Assembly where the Supervisor sits on the Board or is the Board. Nothing under this Article goes back to the Founding Person.

24B.5 **A natural person where the law requires one.** Where the law requires a natural person to decide or oversee, a member of the company who is a natural person does so: the Supervisor, if a natural person, or otherwise a member the Board names.

24B.6 **Conflicts.** A Supervisor with a close tie to the Founding Person, of the kinds in the definition of Close Associate of the Founder (Article 2.2), enters it in the register of interests (Article 21.1). Once disclosed, the tie does not by itself bar the Supervisor from the Founding Person's matters, and the Supervision Committee may take over any specific decision. A Supervisor with a personal stake in a decision (Article 30.6) enters it in the same way and takes no part in it, and the Supervision Committee takes that decision. The Supervision Committee consists of every member of the company outside the Founder's Circle (in the Bootstrap Period, of the trusted circle under Article 30.6) who may act under Article 24B.7. It is called by any [two] of its members or by the Board on [five] days' notice, may meet or decide online or in writing, decides by a majority of the votes cast, keeps minutes and may name one of its members to take the decision. If no member of the Supervision Committee can act, the decision goes to the Administrative Board without the conflicted person, or, if fewer than [two] Board members remain, to the General Assembly without the conflicted person and without Founder Parties (Article 15.2). Article 21 applies in addition.

24B.7 **Who may act.** No Founder Party and no manager of nilware.io IKE is the Supervisor or takes part in a decision under this Article (Article 15.2). In the Bootstrap Period the Supervisor may be a member of the trusted circle (Article 30.6); after it, the Supervisor is outside the Founder's Circle on the schedule in IKE Article 9B.4. Even in the Bootstrap Period, the Supervisor, and every person who decides under Article 24B.4 or 24B.6, is never Group Personnel or anyone whose engagement, pay or work the Founding Person, in any role, supervises or decides, and no Connected Person is the Supervisor or decides or votes on the Founding Person's pay, terms or offboarding (IKE Article 9B.3). Article 15.5 applies.

24B.8 **Kept apart.** The role gives the company and its members no part in managing nilware.io IKE [and does not make them its managers or Group Personnel: to confirm, counsel note I-45], and no say in how the company votes its nilware.io shares, which Article 16 governs.

## Article 25 – Liability

25.1 Towards third parties, the company's assets answer for its debts as the law provides. Between the accounts, each debt is charged to the account for which it was incurred, and no Prozent Account or Pension Asset account bears a debt of the general account or of another account. Where a creditor is paid from the wrong account, the account that should have borne the debt reimburses it first. Towards third parties the Prozent Accounts and the Pension Assets are protected as Articles 11.4 and 13.2A provide.

25.2 Under Greek law the members (εταίροι) are personally liable for the company's debts towards third parties [jointly, severally and without limit: Civil Code Art. 784 and Law 4072/2012 Arts. 249, 258 and 270 / pro rata: to confirm, counsel note I-83], and these statutes cannot limit that liability towards third parties. To keep it remote:

- **(a) Limited recourse.** Every contract the company signs, other than with consumers, states that the counterparty has recourse only against the company's assets and waives any claim against the members personally.
- **(b) Limits on commitments.** The company takes no loan, gives no guarantee and enters no commitment above €[●] without a decision of the General Assembly.
- **(c) Indemnity.** [nilware.io IKE indemnifies the company and its members for liabilities arising from holding the Pension Assets, the Continuity Account and the Supervisor role (Articles 13 and 24B), under the Pensionsprozent Agreement and the Supervisor terms: to confirm, and mirrored in IKE Article 10A.9B(g).]
- **(d) Insurance.** The company insures its organs against liability [as far as is reasonable] and, where available, insures its general liability.

Every applicant is told of this paragraph in writing before admission (Article 7.2A), and every founding member before signing these statutes (Article 30.1).

25.3 Board members are liable under Greek law for harm they cause by breach of their duties. Discharge by the General Assembly does not cover facts that were not disclosed to it.

## Article 26 – Amendments

26.1 These statutes are amended by the General Assembly under Article 18.7, and the amendment is registered as the law requires (Article 1.5).

26.2 **Entrenched Articles.** Articles 5, 11.3 and 11.4, 12 (as it sets the purpose of each Prozent), 13, 14, 15, 16.4, 19.3A, 21.3 and 21.6, 22.3A, 24A.3, 27.2 and 27.3, and this Article 26.2, may be amended in any way that weakens a Prozent, its ring-fence, the pension ring-fence or the company's independence only by the unanimous decision in Article 14.2, and, for Articles 13 and 27.2, only with the consent of the Pensionskasse board and of nilware.io IKE. Articles 12.2 and 14.4 apply. An amendment that IKE Articles 10A.4A or 10A.9B require may not be weakened at all while the company holds the shares those Articles cover.

## Article 27 – Dissolution and Liquidation

27.1 **Dissolution.** The company is dissolved by a General Assembly resolution under Article 18.7, or on a ground the law makes mandatory (in particular a court decision for serious reason, or the company's bankruptcy). An event affecting a member does not dissolve it (Article 9.5).

27.2 **Pension Assets.** On dissolution, the Pension Assets other than the Continuity Account go to the TEA under IKE Article 10A.10, or, if none exists, to a pension fund or a successor non-profit with the same lock that nilware.io IKE designates under IKE Article 10A.9B(d). The Continuity Account never goes to the TEA or a pension fund: it goes to a successor non-profit with the same purpose and lock, designated by nilware.io IKE under IKE Article 10A.9B(f) [and approved by the Pensionskasse board], which holds it under IKE Article 10A.9F. No Pension Asset ever goes to the company's other purposes, its members or the nilware.io group.

27.3 **Prozent Shares and Prozent Accounts.** On dissolution, or if the company ceases to meet IKE Article 6.4A, each Prozent Share and the unspent balance of its Prozent Account go to a successor non-profit with the same purpose and lock, designated under IKE Article 10A.4A [and approved by an independent person or the Pensionskasse board: to confirm]. The General Assembly may propose a successor.

27.4 **Other assets.** After the debts are paid, any remaining assets go to one or more Greek or EU non-profit bodies with a purpose close to the company's [and, where needed, exempt from tax], chosen by the General Assembly. They never go to members, organ members, Connected Persons or the nilware.io group.

27.5 **Liquidators.** The Board acts as liquidator unless the General Assembly appoints others. Liquidators report to the members and publish a final report.

## Article 28 – Disputes

28.1 Disputes between members, or between members and the company, go first to mediation under Law 4640/2019.

28.2 If mediation fails, the competent courts of [Athens] decide, or an arbitrator if the parties agree.

## Article 29 – Final Provisions

29.1 If any provision is invalid, the rest remains in force, and the invalid provision is replaced by the valid one that comes closest to its purpose.

29.2 Matters not covered here are governed by Civil Code Arts. 741 ff. and Greek law in general.

29.3 The Greek text is filed and prevails. The English text is a translation.

## Article 30 – Founding and Transitional Provisions

30.1 **Founding members.** The founding members, and their contributions, are: [●], including [●]. [The Founding Person: owner to decide whether the Founding Person is a founding member, within Article 15.]

30.2 **First Board.** The first Administrative Board serves until the first Ordinary General Assembly, and in any case no more than [two] years: President, [●]; Vice-President [●]; Treasurer [●]; Secretary [●]; members [●].

30.3 **First Auditors.** [●].

30.4 **Before receiving nilware.io shares.** Before the company receives any share or payment from nilware.io IKE, it:

- signs the Pensionsprozent Agreement (IKE Article 10A.9B) and adopts these statutes, including Articles 13, 14 and 27, and registers them in GEMI (Article 1.5);
- signs the deed of adherence under IKE Article 5.3 and Clauses 5.1B to 5.1D of the Shareholders' Agreement;
- opens the Prozent Accounts and the Pension Asset accounts, including the Continuity Account;
- adopts a first yearly plan for each Prozent Account;
- obtains the accountant's written confirmation of the income tax, VAT and donation tax treatment of: the share donation; the Prozent and Pensionsprozent contributions; the dividends of the Prozent Shares and the pension shares; the payments under Article 24B.3; and the Pension Assets and the Continuity Account [Law 4172/2013 Arts. 45(ε) and 47; Law 2961/2001; VAT Code: to confirm, counsel note I-87].

30.5 **Shares received.** On incorporation of nilware.io IKE, the company receives the sixty shares IKE Article 4.2 (Initial holdings) allots to it: ten for each of the four Prozente in Article 12, ten as the Pensionsprozent share and ten as the Kassenprozent pool shares.

30.6 **Bootstrap.** In the Bootstrap Period (IKE Article 9B), members of the trusted circle may hold the seats and roles that Articles 13.4A, 15.3, 15.5, 19.3, 22.3, 24.2, 24.3A and 24B otherwise reserve to persons outside the Founder's Circle, or to persons who are not Connected Persons or Group Personnel: seats on the Administrative Board and its committees, the Supervisor, the members' seats on the Pensionskasse board before there is an eligible member, or while no member is outside the Founder Parties, if they are not members of the Pensionskasse (Article 13.4A), the member Auditors (never a Board member) and independent reviewers under Article 21.4. Each of them enters every close tie in the register of interests (Article 21.1) before acting and takes no part in any decision in which they have a personal stake (Article 21.3). In this Article and Article 24B, a "personal stake" is an interest of the person's own, or of their household or an entity they control, in the outcome of the decision; a tie to the Founding Person or another Founder Party disclosed under Article 21.1 is not by itself a personal stake or an interest under Article 21.3, and does not by itself bar the person from the Founding Person's matters (IKE Article 9B.2). [Connected Persons who sit under this Article take no part in deciding how the company votes its nilware.io shares (Article 15.3 continues to apply to that): the default / Connected Persons who sit under this Article may take part in those decisions: owner to choose.] The hard lines in IKE Article 9B.3 hold throughout, and the limit of [one] seat in Article 15.5 is not lifted for decisions under Article 24B. Within [30] days after the Bootstrap Period ends, the Administrative Board publishes the schedule in IKE Article 9B.4, and Articles 19.3A, 22.3A and 24B.7 and the Pensionskasse seats follow it within their cure periods, counted from the end of the Bootstrap Period.

---

*Signatures of the founding members: [●]*


<!-- articles/08-founder-pool-constitution.md -->

# Constitution of the Founder Pool – nilware.io (Draft)

*Constitution of the founder pool of nilware.io: the holders of the founder-class shares (Class F) and the Reserve Shares (Class R) of nilware.io IKE, and of the Class A shares of nilware.io Holdings AE. An agreement among those holders under Greek law [legal form: to confirm, Article 16]. Draft for review by a Greek lawyer; not legal advice.*

> Its structure is borrowed from the Swiss Federal Constitution of 1999: a sovereign assembly of all holders, basic rights before organs, a collegial council whose president serves one year, the optional and mandatory referendum, the initiative, the double majority and sections with their own rules. No Swiss law applies.

## Article 1 – The Founder Pool

1.1 **The Founder Pool.** The Founder Pool is all Holders, whoever and however many they are. It is "the Founder" in the Articles of nilware.io IKE (the "IKE Articles"), the Articles of nilware.io Holdings AE (the "AE Articles"), the Shareholders' Agreement and the Agent Policy, acting through the Founder Representative (Article 8), not any person (IKE Article 4.2E).

1.2 **Founder-pool shares.** The founder-pool shares are those defined in IKE Article 4.2E (Founder pool): the Class F shares, exactly 50% of the capital of nilware.io IKE (IKE Article 4.2B); the Reserve Shares (Class R) held by Holders until the Qualifying Closing (IKE Article 4.2D); the Class A shares of nilware.io Holdings AE (AE Article 4.2); and any share issued to keep the Founder Pool at exactly 50% (IKE Article 4.2B). A Reserve Share a Holder sells or grants to a person who is not a Holder leaves the Founder Pool (IKE Article 4.2D, Sales and grants).

1.3 **Holders.** A "Holder" is any person, natural or legal, registered as holder of founder-pool shares who has adhered under Article 4.1. A Holder's weight in this constitution is the number of its Class F shares ("Class F votes"); Class A shares go with the Class F shares (Article 9.2), and neither they nor the Reserve Shares carry separate weight. Class F shares carry no weight, and do not count for Article 1.6 or the quorum in Article 6.6, while their votes are suspended or lost under Clauses 6.1 and 6.2 of the Shareholders' Agreement, or while they are without weight under Articles 4.5 and 9.3A [and 16.1A, if the owner keeps that option].

1.4 **The Founding Person.** The Founding Person (IKE Article 4.2E) keeps the personal obligations, which never pass with founder-pool shares: the IP assignment, exclusivity or contribution, the non-compete, the leaver terms (Shareholders' Agreement, Clauses 6.1 to 6.5) and authorship of the charter. The Founding Person's work as an Agent, with the same rights and obligations as any other Agent (IKE Article 11A.12), gives no right in the Founder Pool. The Founding Person holds the Brand Assets of record for the Founder Pool (Article 2A.3) and, as between the Founding Person, the Holders and nilware.io IKE, has no beneficial interest of its own in them. In the Founder Pool the Founding Person has the rights of a Holder, and no others.

1.5 **Precedence.** This constitution governs the Holders among themselves. Towards nilware.io IKE, nilware.io Holdings AE, the Prozente and the Investors, the IKE Articles, the AE Articles and the Shareholders' Agreement prevail, and nothing in this constitution weakens any duty in them. Mandatory Greek law prevails over all of them.

1.6 **Counting heads.** For every count of Holders or of the Holders in a Section (Articles 6.4, 10.1, 11 and 12), persons acting in concert, a Holder and those it controls (IKE Article 4.2C) or who are its nominees, and spouses or registered partners count as one Holder; so do co-holders (Article 9.6). A Holder of fewer than [5]% of the Class F votes (and never fewer than twenty Class F shares), or who acquired its holding in the previous [6] months other than as heir or legatee, is not a head. Persons who received founder-pool shares without payment from the same Holder in the previous [3] years, other than on death, count as one head with that Holder. These rules decide only who is a head; every Holder still votes its Class F votes.

## Article 2 – Purpose

2.1 **Purpose.** The Founder Pool holds the founder-pool shares together, so that the Founder stays at exactly 50% of nilware.io IKE and speaks with one voice, and carries out the Founder's role in the nilware.io documents: the block vote (Article 3), the Founder's proposals for the Board of nilware.io Holdings AE and the managers of nilware.io IKE (Article 7.3), the end of the chains of supervision of the company's Agents (Articles 8.3 and 8.4), holding and licensing the Brand Assets (Article 2A), and the Founder's consents and information.

2.2 **The charter.** The Founder Pool keeps faith with the charter of nilware.io: the six founding Prozente and their permanence, the agentic company, openness, and the independence of the AMKE and the Pensionskasse from the Founder.

2.3 **No business of its own.** The Founder Pool runs no business and holds nothing but the founder-pool shares its Holders bring to it and the Brand Assets (Article 2A). Each Holder receives the dividends and other distributions on its own shares directly. The Holders share the costs of the Founder Pool, including costs of the Brand Assets that nilware.io IKE does not pay under the Brand Licence Agreement, in proportion to their Class F votes.

## Article 2A – The Brand

2A.1 **Brand Assets.** The "Brand Assets" are: the word mark "NILWARE.IO", the figurative mark "∅ nilware.io", any other mark, logo or name containing "nilware.io", or the ∅ sign as used with it, that the Founder files, adopts or acquires, or that nilware.io IKE or anyone else holds for the Founder Pool under Brand Licence Clause 2.1A, every application and registration for them, the domain name nilware.io and the other domains listed in the Brand Licence Agreement, and the goodwill attached to them (Brand Licence Clause 2.1).

2A.2 **Assets of the pool.** The Brand Assets belong to the Founder Pool as a whole, not to any Holder, and are held for it of record under Article 2A.3. The Holders' rights in them are contractual and are exercised only through the organs of the Founder Pool. No Holder has a separate share in them that it can sell, pledge, inherit or claim, and they are never distributed to Holders. A Holder's interest in them is its membership of the Founder Pool, through its Class F votes.

2A.3 **Holder of record.** Until the Founder Pool has a legal vehicle, the Founding Person is the registered owner of the Brand Assets and holds them for the Founder Pool on the Founder Council's instructions [as fiduciary or mandatary without representation: to confirm, counsel note I-42]. Until a vehicle holds them, the Holders know that the Brand Assets are, in law, the holder of record's property.

- **Transfer.** The Brand Assets are transferred to a vehicle under Article 16.2, or another vehicle a mandatory referendum approves (Article 10.2). They are also transferred, to a holder of record the Founder Council designates (a vehicle, or a natural person eligible under Article 8.2), when the Founding Person dies or becomes incapable (Article 14.4) or ceases to be a Holder, or when the Council so decides.
- **No Council.** If no Founder Council can act, including while the constitution is dormant and its sole Holder has died or become incapable, the interim Founder Representative under Article 14.3, or failing one the arbitrator under Article 15 on the request of any person listed in Article 14.3(d), designates an interim holder of record and uses the power of attorney below, notwithstanding the restrictions in Articles 14.3 and 10.6. The interim holder of record serves until the Founder Council designates a holder of record.
- **Power of attorney.** The holder of record signs, on taking office, an irrevocable power of attorney to the Founder Representative for the time being to make these transfers [Civil Code Art. 218: to confirm].
- **No beneficial interest.** As between the holder of record, the Holders and nilware.io IKE, the holder of record holds the Brand Assets for the Founder Pool and has no beneficial interest of its own in them. Its heirs take them subject to the duty to transfer them under this Article [protection against the holder of record's personal creditors and insolvency: counsel note I-42 (c)].
- **Duties to the companies.** The holder of record also owes these duties to nilware.io IKE and to Techni kai Technologia AMKE, which may enforce them directly (Brand Licence Clauses 8.3 and 8.4); while this constitution is dormant (Article 13.1) they are owed to them as well as to the Holders [counsel note I-93].

2A.4 **Inseparable.** The Brand Assets travel with the Founder Pool, whoever its Holders become. They are never separated from the Class F shares, and never sold or transferred apart from the Founder Pool. A transfer of founder-pool shares, in whole or in part, transfers no Brand Asset; whoever controls the block controls the Brand Assets through the organs of the Founder Pool.

2A.5 **The Founder Council decides.** Subject to the optional referendum (Article 10.1), the Founder Council decides on filing, renewing, maintaining, opposing and enforcing registrations of the Brand Assets, on the domains, on consents and brand guidelines under the Brand Licence Agreement, and on giving notice of a Prozent Breach and referring it to the arbitrator (Brand Licence Clauses 7.2 and 7.3). It may not rely on a Prozent Breach that a Founder Party caused, voted for or procured (Brand Licence Clause 7.1).

2A.6 **Referendum.** A Brand Asset is assigned only in ways that keep it with the Founder Pool: to a holder of record or vehicle under Article 2A.3, or with the whole Founder Pool on a change of form under Article 16.3. Only a mandatory referendum (Article 10.2), and always subject to the Brand Licence Agreement, decides on: assigning a Brand Asset to a new vehicle or other holder of record, other than a designation under Article 2A.3 on the events listed there; abandoning a Brand Asset, including letting a registration or a domain lapse on purpose; and amending the Brand Licence Agreement. No Brand Asset is encumbered or given as security (Brand Licence Clause 8.1) [owner may confirm]. Any other assignment or encumbrance is a breach of this constitution and of the Brand Licence Agreement. It does not bind the Holders among themselves, but towards third parties it takes effect as the law provides (Civil Code Art. 177). Whoever made it accounts to the Founder Pool for whatever it receives, reverses it and transfers the Brand Asset back on request, and answers for all loss. A transferee or chargee takes subject to the Brand Licence once it is recorded under Brand Licence Clause 5.4.

2A.7 **The Brand Licence.** The Founder Pool has granted nilware.io IKE an exclusive, perpetual, royalty-free, worldwide licence of the Brand Assets, which ends only under its Clause 7 (Brand Licence Agreement). Every Holder is bound by it, and the Founder Pool honours it. No organ of the Founder Pool may end or suspend it at its discretion.

2A.8 [Moved to Article 2.3.]

## Article 3 – One Block

3.1 **One block.** All Class F shares vote at nilware.io IKE as one block, and all Class A shares vote at nilware.io Holdings AE as one block (IKE Article 4.2E, One block; AE Article 4.2). Every vote of the block is cast the same way, by the Founder Representative, as the Founder Pool has decided under this constitution. A majority inside the Founder Pool decides for all of it.

3.2 **Proxy.** Each Holder grants the Founder Representative for the time being an irrevocable proxy, given also in the interest of the other Holders [Civil Code Art. 218: to confirm], to vote its Class F and Class A shares and to sign the written resolutions and consents of the block. No Holder votes its founder-pool shares itself. Each Holder signs a new proxy whenever the Founder Representative changes.

3.3 **Who decides.** The Founder Council decides how the block votes (Article 7.3), except on the matters reserved to the Pool Assembly or to a referendum (Articles 6 and 10).

3.4 **Exceptions.** Reserve Shares carry no votes, whoever holds them, until nilware.io Holdings AE holds them after the Qualifying Closing (IKE Article 4.2D). The votes of shares whose rights are suspended or lost under Clauses 6.1 and 6.2 of the Shareholders' Agreement are cast as those Clauses provide. There is no other exception.

3.5 **A vote cast otherwise.** The company counts the block's votes only as the Founder Representative casts them [as far as Greek law allows] (IKE Article 4.2E). A Founder Representative who casts the block other than as decided answers to the Holders under Article 15, and the vote stands at the company. If the company counts a vote a Holder casts itself in breach of Article 3.2, that Holder is in breach of this constitution and of the Shareholders' Agreement: it owes a contractual penalty of [●] (Civil Code Arts. 404 ff.), and the other Holders or the Founder Council may seek specific performance and interim measures (Article 15.4) so that it votes with the block at any adjourned or repeat meeting and confirms the proxy in Article 3.2.

## Article 4 – Commitments that Travel with the Shares

4.1 **Adherence.** No one becomes a Holder until they have adhered in writing to this constitution, to the Shareholders' Agreement by deed of adherence (Clause 12.3), including Clauses 5.1B to 5.1E, to the Brand Licence Agreement, and to the IKE Articles and the AE Articles as they bind the Founder. The managers of nilware.io IKE do not register a transfer to a person who has not adhered (IKE Article 5.7). A Holder who disposes of all its founder-pool shares ceases to be a Holder, but stays bound by Article 15 for disputes about its time as Holder, and stays a Founder Party for the lookback in Article 4.4. A Holder that is a legal person tells the Founder Council and the managers of nilware.io IKE of any change of its control (IKE Article 4.2C) within [14] days, and, before the change closes, procures (and undertakes in its deed of adherence to procure) that its controllers and the acquirer seek the ballot under Article 9.3 and make the offer to the Investors under Shareholders' Agreement Clause 9.1A, where those apply (IKE Article 5.7).

4.2 **Permanence.** Every Holder is bound by every rule that makes the Prozente permanent (IKE Articles 10A.5 to 10A.5C, AE Article 7.6, Shareholders' Agreement Clause 5.1C). The block votes against, and refuses its written consent to, every matter in Clause 5.1C of the Shareholders' Agreement, unless a mandatory referendum has approved it with the consent of every Holder (Article 10.2).

4.3 **Exactly 50%.** No Holder transfers, acquires or subscribes shares in a way that takes the Class F shares away from exactly 50% of the capital of nilware.io IKE (IKE Article 4.2B). The block may vote for a capital increase of nilware.io IKE only after Holders have committed irrevocably in writing to subscribe all the new Class F shares it needs: each Holder may subscribe in proportion to its Class F votes, and the others may take up what a Holder does not; no Holder is obliged to subscribe. Otherwise the block votes against the increase, unless it is structured under IKE Article 4.2B so that the Founder stays at exactly 50% without new Class F shares. No Holder, and no one who controls a Holder or whom a Holder controls (IKE Article 4.2C), holds capital shares of nilware.io IKE other than founder-pool shares, or acquires any that would take the votes of the IKE shares held by Holders and persons they control above 50% of the total capital [owner may confirm]. This excludes the AE's holding, whose votes are governed by the AE Articles (Reserved Matters, AE Article 7.4) and disclosed under IKE Article 4.2B: the AE is not a person the Holders control for this Article, and the Qualifying Closing does not breach it.

4.4 **Independence.** Every Holder, everyone who controls a Holder, the Founder Representative, every member of the Founder Council and of the Council of Sections, and the Founding Person is a "Founder Party" (IKE Article 4.2E, Founder Parties). Each of them is bound by every rule of the nilware.io documents that keeps a body, a vote or a person independent of the Founder, in particular the independence of the AMKE and its Prozent votes (IKE Article 6.4A, AMKE Article 15), of the Pensionskasse, its board, the pension shares and the Kassenprozent pool (Article 8.4), and of the independent proxy holder (Shareholders' Agreement, Clause 5.1B). A person who was a Founder Party at any time in the previous [3] years is treated as one for every such rule, and stays a Connected Person and in the Founder's Circle (AMKE Article 2.2; IKE Article 4.2E, Founder Parties).

4.5 **Who may not be a Holder.** nilware.io IKE, nilware.io Holdings AE, Techni kai Technologia AMKE, the Pensionskasse, any holder of a Prozent share, any pension fund under IKE Article 10A.10, and anyone any of them controls, may not hold founder-pool shares (IKE Article 4.2E, Who may not hold them). A Holder that becomes barred, including by a change of its control, has no weight in the Founder Pool from that moment (Article 1.3) and sells its founder-pool shares to a person who may hold them within [6] months; failing that, the other Holders may buy them, in proportion to their Class F votes, at fair value set by a valuer who is not a Founder Party.

4.6 **Beneficial ownership.** Each Holder gives the Founder Council and the managers of nilware.io IKE and nilware.io Holdings AE, on adherence and within [14] days of any change, the information on itself and its beneficial owners that they need under Law 4557/2018 [articles to confirm]. After every election and on every change, the Founder Council tells the managers which natural persons direct the block (the Founder Representative, and any person or persons acting in concert holding a majority of the Class F votes), so that the companies keep their entries in the Central Register of Beneficial Owners accurate (IKE Article 5.1) [whom to declare when no Holder exceeds 25%, and whether the Founder Pool or the holding of the Brand Assets is a legal arrangement similar to a trust: (counsel note I-68)].

## Article 5 – Basic Rights of Holders

5.1 **Equal treatment.** Every Class F share carries the same rights in the Founder Pool. No decision of the Founder Pool may favour or disadvantage a Holder, or a group of Holders, except in proportion to their Class F votes.

5.2 **Information.** Every Holder receives, within [30] days, everything the Founder Representative receives from nilware.io IKE and nilware.io Holdings AE as shareholder (IKE Articles 7.1 and 8.4), the minutes of the Founder Council, and how the block voted on each matter and why. Every Holder keeps company secrets as IKE Article 7.2 requires.

5.3 **Voice.** Every Holder may attend and speak at the Pool Assembly, put motions to it, and stand for election to the Founder Council.

5.4 **The right to sell.** Every Holder may sell, give or leave its founder-pool shares, in whole or in part, to anyone who may be a Holder (Article 9), and may independently sell or grant its Reserve Shares to anyone, with the proceeds to it (IKE Article 4.2D, Sales and grants). The procedures of this constitution may delay a sale under Article 9.3, but never stop it.

5.5 **Minority protection.** Without the consent of each Holder affected, no decision of the Founder Pool or of a Section may change the weight of a share, impose a payment or duty on a Holder beyond this constitution, restrict a Holder's right to sell beyond Article 9, or treat Holders differently. A Holder who did not agree may challenge any decision that breaches this constitution under Article 15, within [60] days of learning of it.

5.6 **No forced exit.** No Holder can be excluded from the Founder Pool or made to sell or give up its founder-pool shares, except:

- under the drag-along of nilware.io IKE or nilware.io Holdings AE (IKE Article 5.5, AE Article 6.3);
- the contribution of every Reserve Share to nilware.io Holdings AE at the Qualifying Closing for AE shares at the Conversion Ratio (non-voting Class C shares for Reserve Shares held by Holders), or, at the Holder's option and only as far as the round provides the cash, its sale to the AE for cash at the round price (IKE Article 4.2D, Conversion; AE Article 4.3B);
- the transfer of Reserve Shares to a new Prozent (IKE Article 4.2D, New Prozente);
- the leaver terms of the Founding Person, as they reach shares received from the Founding Person without payment (Shareholders' Agreement, Clauses 6.1 to 6.2A);
- the sale of the shares of a barred Holder (Article 4.5);
- the purchase of shares acquired in breach of Article 9.3 (Article 9.3A);
- [the offer of the Class F shares of a Holder whose participation has ended (Article 16.1A): if the owner keeps that option]; and
- seizure, enforcement or insolvency under the law.

## Article 6 – Pool Assembly

6.1 **Highest body.** The Pool Assembly is all the Holders and is the highest body of the Founder Pool. Every Holder may take part in person or by proxy.

6.2 **Powers.** The Pool Assembly:

- elects and removes the members of the Founder Council, and each year elects its President and Vice-President from among them (Articles 7 and 8);
- decides the matters of the mandatory referendum (Article 10.2), by ballot of all Holders;
- decides on initiatives and optional referendums (Articles 10.1 and 10.4);
- recognises Sections and approves their rules (Article 12);
- receives the yearly report of the Founder Council and discharges it;
- amends this constitution (Article 11).

6.3 **Ordinary Assembly.** The Pool Assembly meets at least once a year, at least [15] days before the ordinary shareholders' meeting of nilware.io IKE (IKE Article 6.1).

6.4 **Extraordinary Assembly.** The Founder Council calls an extraordinary Assembly when it decides, or within [20] days of a written request by Holders of [10]% of the Class F votes or by [3] Holders (counted under Article 1.6). If the Council does not, the requesting Holders may call it themselves.

6.5 **Notice and meetings.** At least [15] days' written notice, by email, with the agenda and the documents. The Assembly may meet in person, online or both, and may decide by written or electronic ballot. It decides only on items on the agenda.

6.6 **Votes.** Each Class F share has one vote. Unless this constitution says otherwise, the Assembly decides by a majority of the Class F votes cast, and a tie is a rejection (on the block's votes, Article 10.6). The Assembly is quorate when Holders of at least half of the Class F votes take part; a repeat Assembly at least [7] days later is quorate whatever the attendance. A ballot under Article 10 has no quorum.

6.7 **Proxies.** A Holder may give a written proxy to another Holder or to a lawyer. No one holds proxies for more than [one third] of the Class F votes.

6.8 **Minutes.** Minutes are kept of every Assembly and sent to every Holder.

## Article 7 – Founder Council

7.1 **Collegial executive.** The Founder Council is the executive of the Founder Pool. It has 1 to 7 members, as the Pool Assembly decides, elected by the Assembly for [four] years and re-eligible; if the Assembly has not decided the number, it has [three] members, or as many as there are Holders if fewer. Its members are natural persons; they need not be Holders [owner may confirm]. A person barred under Article 8.2 may not be a member. Where there are Sections, the Assembly takes care that they are fairly represented. In an election the candidates with the most Class F votes are elected; a tie for the last seat, or for President, is decided by lot.

7.2 **Deciding as a body.** The Founder Council decides as one body, by a majority of its members voting. No member decides alone for the Council. A member who disagrees may have the disagreement minuted, but represents the Council's decision outside it. On a tie, the President's vote decides [owner may confirm].

7.3 **Powers.** The Founder Council decides everything not reserved to the Pool Assembly or to a referendum, in particular:

- how the block votes at nilware.io IKE and nilware.io Holdings AE, other than on the matters in Article 10.2;
- the Class A proposals of candidates for the majority of the Board of nilware.io Holdings AE, for election under the voting undertaking in Shareholders' Agreement Clause 5.1F (AE Article 8.2), after consulting the Council of Sections (Article 12.4);
- the candidates the Founder proposes for manager of nilware.io IKE (IKE Article 8.2A);
- the policy within which the Founder Representative oversees the chains of supervision of Agents (Article 8.3);
- the Brand Assets, within Article 2A.6 (Article 2A.5);
- preparing the Pool Assembly and the ballots, and carrying out their decisions.

7.4 **Timing of block votes.** The Founder Council decides how the block votes on a matter within [3] days of the Founder Representative receiving the notice of the meeting or the proposed written resolution, and publishes the decision to the Holders at once. A demand for an optional referendum on it is made within [5] days of publication, and the ballot runs for [7] days and ends before the meeting or the deadline for the written resolution, which the IKE's 20 days' notice (IKE Article 6.2) allows. On a matter in Article 10.2, the Council puts its proposal to the ballot on the same timetable.

7.5 **Duties.** Members of the Founder Council act with care and in good faith, in the interest of the Founder Pool as a whole and of the long-term health of nilware.io, within the charter (Article 2.2). They disclose any conflict of interest and abstain on it, as IKE Article 8.3 requires of managers. They report to the Pool Assembly every year.

7.6 **Removal and vacancies.** The Pool Assembly may remove a Council member at any time. A vacant seat is filled at the next Assembly; until then the Council continues with the remaining members.

7.7 **Failed election.** If no Founder Council, or no President, has been elected within [90] days of the date on which the Assembly had to elect one (Articles 6.2, 13.3 and 14.3), the arbitrator under Article 15, on the request of any Holder, appoints an interim Founder Council of one or more members, or an interim Founder Representative, eligible under Article 8.2, who serve until the Assembly elects. Until the arbitrator appoints, the Founder Representative in office, or the interim Founder Representative under Article 14.3, continues.

## Article 8 – Founder Representative

8.1 **President and Representative.** The President of the Founder Council is the "Founder Representative". The Pool Assembly elects the President for one year from among the Council members, and the President may not be President for the following year, unless the Council has only one member or no other member is willing [owner may confirm]. The Vice-President stands in whenever the President is absent or excluded by a conflict, and is the natural candidate for President the next year.

8.2 **A natural person.** The Founder Representative is always a natural person, of full legal capacity, who is not barred under Article 4.5 and is not a bad leaver under Clause 6.2 of the Shareholders' Agreement [for [●] years after the bad-leaver date: owner to decide].

8.3 **Role.** The Founder Representative casts every vote of the block and signs its written resolutions and consents as the Founder Pool has decided (Article 3), and represents the Founder towards nilware.io IKE, nilware.io Holdings AE, the AMKE, the Investors and third parties. As the end of the chains of supervision of the company's Agents (IKE Articles 4.2E, Oversight, and 11A.2A; Agent Policy, section 1.3), other than those in Article 8.4 and the chain for the Founding Person's own work as an Agent, which ends with the Founding Person's Supervisor at the AMKE (IKE Article 11A.12), the Founder Representative, within the policy the Founder Council sets, oversees how the managers and the responsible managers supervise Agents, receives the Agent register and the incident records, and may ask the managers to pause or stop any Agent or to report on any Agent's work. It oversees as the Founder's representative and not as a manager, unless also appointed manager; the managers remain responsible for supervision (IKE Article 8.3).

8.4 **What stays independent of the Founder.** The oversight in Article 8.3 never reaches the Kassenprozent Agents' work on the Kassenprozent pool, the Pensionskasse, its board and the pension shares, the Continuity Account, or the AMKE and its Prozent votes. Those chains end with the Pensionskasse board or the AMKE's own organs (IKE Articles 6.4A, 10A.8, 10A.9D and 10A.9F), and no Founder Party takes part in them (Article 4.4).

8.5 **Notice to the company.** The Founder Council notifies nilware.io IKE and nilware.io Holdings AE in writing of the Founder Representative and of every change, with the new proxies under Article 3.2. If the Council cannot act, the interim Founder Representative under Article 14.3, or any Holder, notifies them as IKE Article 4.2E (Founder Representative) provides.

## Article 9 – Transfers

9.1 **Free transfer.** Founder-pool shares are freely transferable, in whole or in part, by sale, gift or inheritance, and may be pledged or held in usufruct, without the consent of the companies or the other Holders (IKE Article 5.7), subject to Articles 9.2 to 9.5.

9.2 **Conditions.** The acquirer adheres under Article 4.1 and is not barred under Article 4.5. A Holder who transfers part of its holding transfers Class F and Class A shares as nearly in proportion as it holds them as whole shares allow, rounding [to the nearest whole share], so that any number of Class F shares can be transferred [owner may confirm, or allow the two classes to be transferred separately]. The proportion is worked out on everything the Holder has transferred to the same acquirer, and to persons acting in concert with it, in the previous [12] months, so that splitting a transfer never leaves Class A shares behind. Reserve Shares are not tied to the Class F shares: a Holder may sell or grant them independently, in whole or in part, to anyone, with the proceeds to that Holder (IKE Article 4.2D, Sales and grants), and a transfer of Class F shares need carry none. A Holder with no Class F shares is not counted as a Holder for Articles 6.4, 10.1, 11 and 12. The transferring Holder tells the Founder Council within [14] days.

9.3 **Large sales.** A transfer by any title other than inheritance or legacy (a "sale" in this Article, its acquirer the "buyer") that would give one buyer, alone or with persons acting in concert with it, more than [●]% of the Class F shares, counting what it acquired in the previous [12] months, needs a mandatory referendum (Article 10.2). Acquiring control (IKE Article 4.2C) of a Holder counts as acquiring its founder-pool shares, and shares held by persons a buyer controls count as the buyer's. The seller, the buyer, and persons acting in concert with or controlled by either, take no part in the ballot, and their Class F votes are not counted among the votes cast. If the referendum rejects the sale, the other Holders may buy the shares offered, in proportion to their Class F votes, within [60] days, at the same price and on the same terms, or at fair value where no price per share is paid; shares they do not take may then be sold to the buyer as offered. If no Holder may vote in the ballot, this Article does not apply. A sale or grant of Reserve Shares alone is not a sale under this Article.

9.3A **Breach of Article 9.3.** Founder-pool shares acquired in breach of Article 9.3, directly or by acquiring control of a Holder, carry no weight in the Founder Pool (no Class F votes in the Assembly, ballots or elections, and no head under Article 1.6) until a ballot under Article 9.3 approves the acquisition. If the ballot rejects it, the other Holders may buy those shares from the buyer or the Holder concerned, in proportion to their Class F votes, within [60] days, at the price paid, or at fair value set by a valuer who is not a Founder Party where no price per share was paid.

9.4 **Change of control.** A buyer of a majority of the Class F shares, directly or through control of Holders (Article 9.3), controls the block. The Investors' tag-along on such a sale is in Shareholders' Agreement Clause 9.1A and IKE Article 5.4A [owner may confirm].

9.5 **Pledges, usufruct and enforcement.** A pledgee, usufructuary or assignee of dividends adheres under Article 4.1 for the rights it receives, and the votes always stay with the block. A buyer in enforcement or insolvency takes the shares subject to this constitution and becomes a Holder on adherence.

9.6 **Co-holders.** Founder-pool shares are whole capital shares. Persons who hold a share in common, including heirs of an undivided estate, count as one Holder for Articles 6.4, 10.1, 11, 12 and 13 until the share is divided, and act through one common representative (Law 4072/2012 Art. 75(5)). Until they designate it, the Founder Council sends every notice under this constitution to each co-holder it knows of, and no time limit under Articles 10 and 14 runs against them until [30] days after the death has been notified to the Founder Council. While an undivided estate is the only Holder, its common representative, if eligible under Article 8.2, is the Founder Representative (Article 13.1).

9.7 **Register.** The Founder Council keeps a register of Holders and of their Class F, Class R and Class A shares, and of every sale and grant of Reserve Shares by a Holder (holder, number of shares, price), matching the share registers of nilware.io IKE and nilware.io Holdings AE. It keeps the register off the chain and may mirror it pseudonymously on the Company Ledger (IKE Article 5.10; Ledger Policy section 11.1); the share registers of the two companies prevail over it.

## Article 10 – Referendum and Initiative

10.1 **Optional referendum.** Holders of [5]% of the Class F votes, or [3] Holders (counted under Article 1.6), may demand that any decision of the Founder Council be put to a ballot of all Holders. The demand suspends the decision. It is made, for a decision on how the block votes, on the timetable in Article 7.4, and for any other decision within [30] days of its publication.

If a ballot on a block vote still cannot end before the vote must be cast, the Founder Representative asks for the matter to be adjourned where the company's rules allow. Otherwise the block does not vote as the Council decided: it abstains, and votes against any matter that changes the IKE Articles or the AE Articles [owner may confirm]. If the ballot ends in time and rejects the Council's decision on a block vote (Article 10.3), the block likewise abstains, and votes against any matter that changes the IKE Articles or the AE Articles. On a Required Matter the block always votes under Article 10.7, whatever the ballot. On a matter in Article 10.2, Article 10.6 applies.

10.2 **Mandatory referendum.** The following are decided by a ballot of all Holders, and only after the Founder Council has consulted the Council of Sections (Article 12.4):

- amending this constitution (Article 11);
- the block's vote on any matter of nilware.io IKE that needs the Qualified Majority (IKE Article 6.5) or two-thirds of the capital, including a new Prozent (IKE Article 6.6), and on the Reserved Matters of nilware.io Holdings AE (AE Article 7.4);
- the block's consent to any matter in Clause 5.1C of the Shareholders' Agreement, which needs the consent of every Holder (Article 4.2);
- electing the Founder Council (Article 7.1);
- a sale under Article 9.3;
- the brand matters in Article 2A.6, and a vehicle for the Brand Assets under Article 2A.3;
- changing the legal form of the Founder Pool, or ending it (Article 16).

10.3 **Majority.** A ballot is decided by a majority of the Class F votes cast, except where Articles 4.2 and 11 require more, and except elections, which follow Article 7.1. A tie is a rejection. In an optional referendum on a decision of the Founder Council on how the block votes (Article 10.1), the decision stands unless a majority of the Class F votes cast is against it, so a tie leaves it in force [owner may confirm].

10.4 **Initiative.** Holders of [10]% of the Class F votes may propose in writing an amendment of this constitution, or a decision on how the block votes or what it proposes at nilware.io IKE or nilware.io Holdings AE, within the nilware.io documents. The Founder Council puts the initiative to a ballot within [90] days, and may put a counter-proposal beside it. An initiative may not propose anything the IKE Articles, the AE Articles or the Shareholders' Agreement forbid.

10.5 **Ballots.** Ballots are held in writing or electronically, over at least [10] days, or for a block vote over the [7] days in Article 7.4. Each ballot comes with the Founder Council's explanation and, where they exist, the opinions of the Council of Sections and of the initiators. The result is published to every Holder.

10.5A **Ledger and channels.** Votes of the Pool Assembly (Article 6.5), ballots under this Article and the instructions they give the Founder Representative may be held and recorded on the Company Ledger (IKE Article 5.10), under the Company Ledger Policy (policies/10) as the Founder Council adopts it for the Founder Pool. Every Holder may vote by signing on the Company Ledger, or by text message, e-mail, letter, in person or by telephone (minuted and read back), with the effect the law gives a vote, signature or proxy given in that form, through the Founder Council, or nilware.io IKE on its behalf, acting as recording agent without discretion (Ledger Policy sections 6 and 7) [counsel note I-106]. A vote by telephone or in person, minuted and read back, counts as a vote in writing for Article 10.5 [counsel note I-106]. The recording agent's off-chain record of the messages (Ledger Policy section 6.3) is the record of the ballot and prevails over the Company Ledger. Where nilware.io IKE records on its behalf, the Founder Council checks the record and the count before the result is published. A Holder who has chosen post also receives the ballot by any other channel it has registered and may vote by any channel. Notices under Articles 6.5 and 10 also go by each Holder's chosen channels (Ledger Policy section 6.7). The result, as the Founder Council checks and publishes it under Article 10.5 (Ledger Policy section 5.2), is the Founder Pool's decision under Article 3.3, and the Founder Representative casts the block as the Founder Council certifies it (Article 8.3); where the Company Ledger and the published result differ, the published result prevails and a correction is added to the Company Ledger, the recorded votes staying unchanged and every voter being told (Ledger Policy section 5.2). No Holder loses a right for not using the Company Ledger.

10.6 **When no ballot approves.** Where a matter in Article 10.2 on which the block is to vote or consent has not been approved by ballot, because the ballot rejected it, tied, could not be held or end in time, or the matter arises in an interim period under Article 14.3, the block votes against it and refuses its written consent. Where the law requires the shareholders to pass a resolution on the matter (the Required Matters, IKE Article 4.2D, Fallback), the block votes under Article 10.7 instead. Any other matter in Article 10.2 is not decided until a ballot approves it.

10.7 **Required Matters.** On a Required Matter (IKE Article 4.2D, Fallback) on which the block would otherwise abstain under Article 10.1, 10.6 or 14.3, in or after the Interim Period, the Founder Representative, or the interim Founder Representative under Article 14.3, casts the block under the neutral rule in that Article, whatever the ballot, so that the company can always pass them.

## Article 11 – Amendments and Double Majority

11.1 **Double majority.** This constitution is amended only by a mandatory referendum passed by both:

- a majority of the Class F votes cast; and
- a majority of the Holders voting (counted under Article 1.6), or, while there are Sections, a majority of all the Sections, each Section counted for the side that has the majority of its own Holders' Class F votes cast in the ballot, not by any internal procedure. A Section whose ballot ties, or whose Holders cast no vote, counts against the amendment.

11.2 **Entrenched articles.** Articles 1.4, 1.5, 2A.2, 2A.4, 2A.7, 3, 4, 5, 8.2, 8.4, this Article 11 and Article 13.2 may be amended only by [two-thirds] of the Class F votes cast together with a majority of the Holders voting and of every Section.

11.3 **Limits.** No amendment may weaken a commitment that the IKE Articles, the AE Articles or the Shareholders' Agreement place on the Founder or on any Holder; such an amendment is void between the Holders.

## Article 12 – Sections

12.1 **Sections.** Holders may form Sections, in particular a family branch (a Holder who inherited or received shares, and their own heirs and donees) or a group of Holders who bought together. A Section needs at least [2] Holders (counted under Article 1.6) and at least [10]% of the Class F votes. A group that meets these criteria has the right to be recognised: the Pool Assembly records it, and if it refuses, the group may appeal to the arbitrator under Article 15. Each Holder belongs to at most one Section. Holders in no Section together form the Open Section, which counts as one Section for Article 11 only if it meets the same minimum size [owner may confirm]. For every ballot, a Holder belongs to the Section it belonged to [6] months before the ballot opened, or to the Open Section if it belonged to none then.

12.2 **Own rules.** Each Section adopts its own rules for its internal affairs, within this constitution, and the Pool Assembly approves them if they comply with it; a refusal may be appealed to the arbitrator under Article 15. A Section's rules may not restrict a Holder's right to sell beyond Article 9, impose a forced exit, or bind a Holder's ballot.

12.3 [Deleted: covered by Article 11.1.]

12.4 **Council of Sections.** Each Section names one delegate to the Council of Sections. The Founder Council consults it, in writing or at a meeting, before every matter in Article 10.2 and every Class A nomination to the Board of nilware.io Holdings AE. Its opinion is advisory, and is minuted and sent to every Holder with the ballot.

12.5 **When Sections exist.** Sections and the Council of Sections exist only while the Founder Pool has at least [3] Holders.

## Article 13 – Transitional Rule: One Holder

13.1 **Dormant.** While all founder-pool shares are held by one Holder (an undivided estate counting as one, Article 9.6), this constitution is dormant: that Holder is the Pool Assembly and the Founder Council and, if a natural person eligible under Article 8.2, the Founder Representative. A Holder that is a legal person names a natural person eligible under Article 8.2 as Founder Representative. If a natural-person Holder is not eligible, or a legal-person Holder has no eligible person named, Article 14.3 applies. The sole Holder signs the standing proxy in Article 14.7. No Assembly, ballot, Section or Council of Sections is held: the sole Holder's written decision stands in for every ballot, the Assembly and the Council, including under Articles 4.2 and 10.2. Article 9.3 does not apply to a transfer by the sole Holder; Clause 9.1A of the Shareholders' Agreement does. At incorporation the Founding Person is the one Holder.

13.2 **What applies while dormant.** Articles 1, 2, 2A, 3.1, 3.4, 4, 7.7, 8.2 to 8.5, 9, 14, 15 and 17 apply in full while the constitution is dormant.

13.3 **Switching on.** The constitution switches on when a transfer, gift or inheritance gives founder-pool shares to a second Holder and is registered. The Founder Representative then in office continues as interim Founder Representative and sole member of the Founder Council, and calls the first Pool Assembly within [60] days to elect the Council. If no Council is elected within [90] days of the switch, Article 7.7 applies.

13.4 **Back to one Holder.** If all founder-pool shares come again to one Holder, the constitution becomes dormant again.

## Article 14 – Succession on Death or Incapacity

14.1 **Shares pass by will or law.** On a Holder's death, its founder-pool shares pass by will or by law. Each heir or legatee becomes a Holder on adherence under Article 4.1. Until the estate is divided, the heirs are co-holders (Article 9.6).

14.2 **Letter of wishes.** Each Holder who is a natural person may lodge with the Founder Council, or while dormant with [a notary], a letter of wishes naming the person it wishes to succeed it as Founder Representative. The letter does not bind the Pool Assembly, but the interim rule in Article 14.3 follows it. A letter written by a person who is not eligible under Article 8.2 when the interim rule applies is disregarded, and so is the naming of anyone who is a Close Associate of that person (AMKE Article 2.2).

14.3 **Interim Founder Representative.** This Article applies if the Founder Representative dies, becomes incapable, resigns, ceases to be eligible under Article 8.2 or is removed, or a sole Holder that is a legal person no longer has an eligible natural person named, and the Assembly has not yet elected a successor.

Where the Founder Council still has a member able to act, the Vice-President, or failing one a member the Council chooses, acts as President and Founder Representative with full powers, and the Assembly elects a new President within [90] days; the list and the restrictions below do not apply. Where no Council member remains able to act, or while the constitution is dormant, the interim Founder Representative is the first of these, in order, who is willing and eligible under Article 8.2:

- (a) the Vice-President of the Founder Council;
- (b) the person named in the letter of wishes of the Founder Representative who has gone, unless it is disregarded under Article 14.2;
- (c) the natural person who holds, or represents the estate or Holder that holds, the most Class F votes; between equal holdings, the one chosen by lot by the managers of nilware.io IKE in the presence of a notary, or if none of them is willing, (d);
- (d) a natural person appointed by the arbitrator under Article 15 on the request of any Holder, heir, legatee, executor or administrator of an estate that holds founder-pool shares, of the managers of nilware.io IKE, or of Techni kai Technologia AMKE, each of whom may ask for the appointment, and for the arbitrator under Article 15.2, for this purpose;
- (e) until someone is appointed under (d), the independent proxy holder in Clause 5.1B of the Shareholders' Agreement, as interim Founder Representative for the Required Matters only, under the neutral rule in IKE Article 4.2D (Fallback); on every other matter the block abstains. Acting so, it is not a Founder Party (IKE Article 4.2E, Founder Parties).

The interim Founder Representative serves until the Pool Assembly elects a President (and, where none remains, a Founder Council), which it does within [90] days of the event, or within [90] days of the heirs' adherence while an estate is undivided; if it does not, Article 7.7 applies. While the constitution is dormant, the interim ends when a single Holder has adhered, or an undivided estate has named an eligible common representative, who becomes Founder Representative under Article 13.1 if eligible under Article 8.2. If no heir has adhered within [12] months of the death, the arbitrator under Article 15, on any request under (d), appoints an interim Founder Council with the powers of Article 7.3, which serves until heirs holding a majority of the Class F votes have adhered. Meanwhile the interim Founder Representative under the list above votes the block only on matters that cannot wait, such as the Required Matters, and in line with the last decisions of the Founder Council [owner may confirm]. No matter in Article 10.2 is decided meanwhile: the block votes on it as Article 10.6 provides, against, or under the neutral rule on a Required Matter (Article 10.7).

14.4 **Incapacity.** For the offices of Founder Representative and member of the Founder Council, for eligibility under Article 8.2, and for the transfer of the Brand Assets under Article 2A.3, incapacity is established by a court decision placing the person under judicial support (Civil Code Arts. 1666 ff.) or by [two] certificates of doctors who are not Founder Parties and have no tie to one. The person concerned may challenge a finding by certificates before the arbitrator under Article 15, who may order interim measures (Article 15.4). A Holder's own rights as Holder are restricted only by a court decision placing it under judicial support; its judicial supporter then exercises them as far as the court's decision allows, and is Founder Representative only if elected.

14.5 **Forced heirship.** Greek law gives the closest relatives a forced share (νόμιμη μοίρα); for deaths from 16 September 2026 it is a monetary claim against the estate [Civil Code Book Five as replaced by Law 5303/2026: article numbers to confirm]. Nothing in this constitution or in a letter of wishes reduces it. A Holder may settle the succession to its founder-pool shares by will or, from 16 September 2026, by an inheritance contract [form: to confirm]; if the Holder lodges a copy, the Founder Council keeps it. To help an estate meet forced-share claims without breaking up the block, the other Holders may, pro rata to their Class F votes, offer to buy founder-pool shares from the estate at fair value set by a valuer who is not a Founder Party [whether a sale by an estate to meet forced-share claims is exempt from Article 9.3: owner to decide]. [How the claim is valued for founder-pool shares, the rule for deaths before 16 September 2026, and whether an inheritance contract can bind the succession to founder-pool shares: counsel note I-92].

14.6 **The Founding Person.** On the death or incapacity of the Founding Person, the personal obligations in Article 1.4 end as the Shareholders' Agreement provides; the founder-pool shares pass under this Article; the Brand Assets pass to a new holder of record under Article 2A.3, not to the Founding Person's heirs, and nilware.io IKE may keep them in force meanwhile (Brand Licence Clause 5.1A); and the Founder Pool continues.

14.7 **Standing proxy.** While the constitution is dormant, the sole Holder signs a standing proxy to whoever is interim Founder Representative under Article 14.3 from time to time, to vote its Class F and Class A shares as Article 14.3 allows. The proxy is irrevocable, is given also in the interest of nilware.io IKE and of the Prozente, survives the Holder's death and incapacity, and binds its heirs until a single Holder has adhered or the Assembly elects a Founder Council [Civil Code Art. 218 and the Civil Code on the end of a mandate: to confirm, note I-40 (a)]. A sole Holder that is a legal person signs the same proxy, which also covers the loss of its named natural person.

## Article 15 – Disputes

15.1 **Mediation, then an arbitrator.** Disputes among Holders, or between a Holder and an organ of the Founder Pool, about this constitution, the block's votes or the Holders' rights go first to mediation under Law 4640/2019, and then to a sole arbitrator under Code of Civil Procedure Arts. 867 ff. [to confirm], seated in [Athens]. They never go first to the courts, and nilware.io IKE and nilware.io Holdings AE are not parties to them.

15.2 **The arbitrator.** The parties agree on the arbitrator. If they do not within [30] days, [the Chair of the Athens Bar Association] appoints one. The arbitrator is not a Founder Party and has no tie to one.

15.3 **Effect.** An award binds the Holders and the organs of the Founder Pool. It does not change a vote already cast at nilware.io IKE or nilware.io Holdings AE, but may direct how the block votes from then on.

15.4 **Interim measures.** The arbitrator, or the court where the law requires, may order interim measures [as far as Greek law allows].

## Article 16 – Legal Form

16.1 **Agreement among Holders.** The Founder Pool is a pooling and voting agreement among the Holders, each of whom owns its founder-pool shares directly and grants the proxy in Article 3.2. It has no legal personality of its own [to confirm, notes I-40 and I-91].

16.1A **Duration and continuation.** Insofar as the Founder Pool is a civil company under Civil Code Arts. 741 ff. [to confirm, I-40 (d); counsel note I-91], it is formed for [the duration of nilware.io IKE / [30] years, renewed automatically for further [10]-year periods unless a mandatory referendum decides otherwise (Article 10.2)]. During that term a Holder may end its own participation only for important reason, by written notice to the Founder Council. That notice, and the death, incapacity, insolvency or exit of any Holder, never dissolves the Founder Pool: it continues among the other Holders and, on a death, with the heirs who adhere (Article 14). A Holder whose participation ends stays bound by the Shareholders' Agreement and the IKE Articles for its shares [and its Class F shares carry no weight and are offered to the other Holders pro rata at fair value set by a valuer who is not a Founder Party (Article 4.5 procedure): owner to choose].

16.2 **Alternative.** If counsel advises it, the Holders may instead bring their founder-pool shares into a civil partnership (αστική εταιρεία) [Civil Code Arts. 741 ff.: to confirm] that holds them, whose partners are the Holders. This constitution would then be its statute, the Founder Representative its administrator, the partnership the holder of record of the Brand Assets (Article 2A.3), and a transfer of founder-pool shares a transfer of a partnership share. A change of form is a matter for the mandatory referendum (Article 10.2), and may not weaken anything in Article 4.

16.3 **The brand on a change of form or an end.** A change of form, or an end of the Founder Pool, keeps the Brand Assets together, with the Brand Licence Agreement, in the hands of the holders of the Class F shares as a whole or of their vehicle. They are never divided among Holders [to confirm, counsel note I-42].

## Article 17 – Final Provisions

17.1 **Publication.** This constitution, and each amendment, is sent to nilware.io IKE and nilware.io Holdings AE and disclosed to the Investors (Shareholders' Agreement, Schedule 1).

17.2 **Invalidity.** If any provision is invalid, the rest remains in force, and the invalid provision is replaced by the valid one that comes closest to its purpose.

17.3 **Governing law.** This constitution is governed by Greek law. Matters not covered here are governed by the Civil Code and Greek law in general.

---

*Signatures of the Holders: [●]*


<!-- agreements/09-brand-licence.md -->

# Brand Licence Agreement – the Founder to nilware.io IKE (Draft)

*Between the holders of the founder pool (together the "Founder", IKE Article 4.2E), acting through the Founder Representative, and the Founding Person, [name withheld], as holder of record of the Brand Assets for the Founder (Pool Constitution Article 2A.3) (together the "Licensor"), and nilware.io IKE (the "Company"), with Techni kai Technologia AMKE (the "AMKE") as beneficiary of Clause 8.3. Governing law: Clause 11.1, including Law 4679/2020 on trade marks [to confirm], and, for registrations outside Greece, Regulation (EU) 2017/1001 on the EU trade mark and the Swiss Trade Mark Protection Act (MSchG) as they apply. Draft for review by a Greek lawyer; not legal advice.*

## 1 – Purpose and Precedence

1.1 **Purpose.** The nilware.io name, marks and domain belong to the Founder, the founder pool, and stay with it whoever holds its shares (Pool Constitution Article 2A). The Company carries the name. This Agreement lets the Company use them as its own name and brand, exclusively and permanently, for as long as it honours the Prozente.

1.2 **Precedence.** Among the holders of founder-pool shares, the Pool Constitution governs how the Founder decides under this Agreement. The Shareholders' Agreement protects this Agreement (SHA Clause 5.1E). Mandatory Greek law prevails over all of them. Who is bound: Clause 11.2.

1.3 **How the Company signs.** The Founding Person is a party as holder of record and also manages the Company (IKE Article 8.2B). The Company therefore enters into this Agreement with the permission of its shareholders' meeting, given at incorporation by every founding shareholder, the AMKE included, under the rule against contracting with oneself (Civil Code Art. 235), and approved as a related-party matter by a majority of the Independent Votes cast (IKE Article 4.2D, Votes). [The Company is represented in signing by a special representative appointed by that meeting who is not a Founder Party (IKE Article 4.2E) / by the General Director under that permission: owner to choose.] [Civil Code Art. 235 and the related-party rules of Law 4072/2012: counsel to confirm (counsel note I-95).]

## 2 – The Brand Assets

2.1 **Brand Assets.** The "Brand Assets" are:

- the word mark "NILWARE.IO" and the figurative mark "∅ nilware.io" (the empty set sign, a space, then "nilware.io" in lowercase), in every territory, with every application and registration for them;
- any other mark, logo or name containing "nilware.io", or the ∅ sign as used with it, that the Founder files, adopts or acquires, with every application and registration for them;
- the domain name nilware.io, and the other domains listed in Schedule 1;
- the copyright in the logos and artwork of the Brand Assets, the figurative mark included, which the author holds for the founder pool on the same terms as the marks (Pool Constitution Article 2A.3) or assigns in writing to the holder of record (Clause 2.1B; Law 2121/1993 Arts. 12 and 14); the author keeps the moral rights and does not exercise them against use that follows the brand guidelines (Schedule 2) [as far as the law allows];
- the goodwill attached to them.

2.1A **Marks the Company creates.** The Company, its group companies and every sublicensee do not file, register or acquire in their own name any mark, logo, name or domain containing "nilware.io", or the ∅ sign as used with it. Any such mark, logo, name or domain that the Company, its Agents, a group company or a sublicensee creates, adopts or obtains is held for the founder pool, is a Brand Asset, falls under the Licence, and is assigned to the holder of record on request, at the Company's cost and without payment [as far as the law allows].

2.1B **Authors of the artwork.** Schedule 1 records the author of each logo and piece of artwork in the Brand Assets. Before the figurative mark is filed, the holder of record obtains from every author who is not the Founding Person a written assignment of the copyright (Law 2121/1993 Art. 14) and the written consent under Clause 3.3.

2.2 **Owned by the founder pool.** The Brand Assets are assets of the founder pool, held for it of record under Pool Constitution Articles 2A.3 and 16 (counsel note I-40 (d)). Nothing in this Agreement, and no use by the Company, a group company or a Prozent, transfers any ownership in them to the Company. Goodwill arising from the Company's use accrues to the Brand Assets [as far as the law allows].

2.3 **Successors of record.** Every later holder of record of a Brand Asset, including a vehicle under Pool Constitution Article 2A.3 and the holders or vehicle under Pool Constitution Article 16.3, takes it subject to this Agreement and adheres to it in writing before the transfer. The Founder procures this. A transfer without that adherence does not affect the Company's rights [as far as the law allows; recording under Clause 5.4].

## 3 – The Licence

3.1 **Grant.** The Licensor grants the Company an exclusive, perpetual, royalty-free, worldwide licence to use the Brand Assets as its company name, distinctive title (διακριτικός τίτλος), brand, trade marks and domain, for every present or future product, service and activity of the Company, including an exclusive licence of the copyright in the logos and artwork of the Brand Assets, worldwide, for the full term of protection, by every means of exploitation now known or later (the "Licence"). [Law 2121/1993 Art. 15 reads a copyright licence narrowly: hence the full scope.]

3.2 **Exclusive.** The Licence is exclusive also as against the Founder. Neither the Licensor nor any holder of founder-pool shares uses the Brand Assets in trade or licenses them to anyone else, except:

- the founder pool and its organs may call themselves the founder pool of nilware.io;
- the Founding Person may say that the Founding Person founded nilware.io, and the charter (charter/) may use the name;
- licences the Company grants or approves under Clause 3.3.

3.3 **Sublicences.** The Company may sublicense the Brand Assets, without further consent and without royalty:

- to nilware.io Holdings AE and every company the Company or the AE controls (IKE Article 4.2C) (together "group companies"), for their names, distinctive titles and business. A sublicence to a company ends [6] months after it stops being a group company;
- to Techni kai Technologia AMKE, the Pensionskasse and every holder of a Prozent share, to describe themselves, their Prozent and their link to the Company (for example "the Kulturprozent of nilware.io"), but not as their own name or trade mark;
- to customers, suppliers and partners, for use incidental to their dealings with the Company.

Any other sublicence needs the consent of the Founder Council, not to be unreasonably withheld. Every sublicence ends under Clause 7.4.

The author of the logos and artwork consents now, in writing, to every sublicence and every transfer of the Licence under Clauses 3.3 and 3.5 (Law 2121/1993 Art. 13(6)), and to the adaptations the brand guidelines (Schedule 2) allow.

3.4 **Royalty-free.** The Company pays no royalty; it bears the costs in Clause 5.2 and gives the undertakings in this Agreement instead. [Owner option: a royalty to the founder pool, as a percentage of revenue or a fixed yearly fee, in place of none; see counsel note I-42 (f) on related-party pricing.]

3.5 **No assignment.** The Company may assign the Licence only together with the whole, or substantially the whole, of its business, to a successor or acquirer in which the Prozente continue on the same terms (IKE Article 10A.5B) and which adheres to this Agreement, including on a sale of the business in liquidation or insolvency [as far as mandatory law allows: counsel note I-42]. A change of control of the Company or of the AE is not an assignment (Clause 6.2).

## 4 – The Domain

4.1 **Registrant and control.** The holder of record stays the registrant of nilware.io and the other domains in Schedule 1. Within [14] days of signature the Licensor gives the Company full technical and administrative control of them: registrar account, DNS, hosting, email, certificates and renewals. The Licensor does not change, redirect, transfer or let lapse any of them, except under Clause 7.4.

4.2 **Registry rules.** Where a registry's rules require the registrant to act, the holder of record acts promptly as the Company reasonably asks [.io registry terms: to confirm, counsel note I-42].

4.3 **Successor domains.** If the .io top-level domain is retired, or its registry terms change so as to threaten the registration, the holder of record registers the nearest available successor domain (for example nilware.[●]) at the Company's request and cost. That domain is a Brand Asset whether or not it contains "nilware.io", is listed in Schedule 1, and falls under the Licence and Clauses 4.1 and 4.2.

## 5 – Registration, Maintenance and Enforcement

5.1 **Filing and renewal.** The Founder Council decides on filing, renewing, extending, opposing and defending registrations of the Brand Assets (Pool Constitution Article 2A.5), after consulting the Company. The holder of record files in its own name for the founder pool. The Company may ask for a filing in a further territory or class, and the Founder Council does not refuse unreasonably. The Founder keeps every registration and domain in force; letting one lapse, or abandoning it, is an abandonment under Pool Constitution Article 2A.6 and a change under Clause 9.

5.1A **Step-in.** If a registration or domain would lapse because the holder of record cannot act, has died, is incapable, or does not act within [30] days of the Company's written request or [30] days before the deadline, whichever is earlier, the Company may renew and maintain it in the holder of record's name at its own cost. The Licensor consents to this now and gives the Company the authority needed [Civil Code Art. 218: to confirm, counsel note I-42 (c)]. Step-in gives the Company no ownership (Clause 2.2).

5.2 **Costs.** The Company pays the reasonable costs of filing, renewing and maintaining the Brand Assets, of the domains, and of enforcement under Clause 5.3 [owner may confirm].

5.3 **Enforcement.** The Founder Council decides on proceedings against infringers, after consulting the Company. If the Founder does not bring proceedings within [30] days of the Company's written request, the Company, as exclusive licensee, may bring them in its own name; the Licensor consents to this now and joins as a party where the law requires. Whoever bears the costs keeps the recoveries, and damages for the Company's own losses go to the Company.

5.4 **Recording.** The Licence is recorded as an exclusive licence with the European Union Intellectual Property Office (EUIPO), the Swiss Federal Institute of Intellectual Property (IPI) and every other office where a Brand Asset is applied for or registered, within [30] days of each filing (or of signature, for earlier filings). The Licensor authorises the Company now to request each recording itself (Regulation (EU) 2017/1001 Art. 26 [to confirm]; Law 4679/2020 Art. 17, if a Greek national mark is filed) and signs whatever else is needed; the Company pays the fees. The holder of record makes no declaration or request to any office that the Licence has ended, changed or should be cancelled, except in the transition under Clause 7.4 after the Ending Date (Clause 7.3). A declaration made otherwise is a breach, and the holder of record withdraws it and has the entry restored at once.

5.5 **Use and quality.** The Company uses the Brand Assets so as to keep them valid and distinctive, and follows the brand guidelines in Schedule 2, which the Founder Council may update after consulting the Company. The guidelines cover the form of the marks only and give the Founder no say over the Company's business.

5.6 **No challenge.** The Company does not challenge the validity of the Brand Assets or the Founder's ownership of them, including by relying on any earlier right of its own. It exercises its own rights in its name and distinctive title only within the Licence, never asserts them against the Founder, the holder of record or their licensees, and does not oppose or seek to invalidate a Brand Asset on the basis of them [as far as competition law allows; counsel note I-94].

## 6 – Term

6.1 **Perpetual.** The Licence has no end date. It ends only under Clause 7; the Founder has no other right to end, suspend or restrict it.

6.2 **What does not end it.** The Licence does not end, and cannot be ended or suspended, on:

- a change of control of the Company or of the AE, an investment round, a sale of shares, a merger, split or conversion;
- the Company's dissolution, liquidation or insolvency [subject to mandatory insolvency law: counsel note I-42], or a sale of its business under Clause 3.5;
- a transfer of founder-pool shares, a change of the Founder Representative or of the holder of record, or the death or incapacity of the Founding Person;
- any decision of the Founder, at its discretion;
- any breach of this Agreement other than a Prozent Breach under Clause 7.1; other breaches give a right to specific performance and damages only.

## 7 – Ending

7.1 **The only ground.** The Licence ends only if the Company stops honouring the Prozente or the permanence rules (IKE Articles 10A.5 to 10A.5C) (a "Prozent Breach") and Clauses 7.2 and 7.3 have been followed. A Prozent Breach includes:

- not paying a Prozent's contribution under IKE Article 10A, or not paying it into the right account;
- removing a Prozent, lowering its contribution or changing its purpose, or amending a protected Article (IKE Article 10A.5C), otherwise than by a decision taken under IKE Article 10A.5;
- a voluntary dissolution of the Company that mandatory law does not require, otherwise than under IKE Article 12.1;
- a resolution or act that suspends or overrides any of IKE Articles 10A.5 to 10A.5C.

It does not include a decision taken in accordance with IKE Article 10A.5, or an act that mandatory insolvency, dissolution or liquidation law requires (IKE Article 10A.5B) [owner may confirm].

The Founder cannot rely on a Prozent Breach that a Founder Party (IKE Article 4.2E) caused, voted for or procured, or that a manager of the Company caused who is or was proposed or nominated by a Founder Party (IKE Article 8.2A). Such a breach does not end the Licence; it gives the Prozente, the AMKE, the Investors and the Company only a right to specific performance.

7.2 **Notice and cure.** Under Clauses 7.2 and 7.3 the Founder acts on a decision of the Founder Council, subject to the optional referendum (Pool Constitution Articles 2A.5 and 10.1). The Founder gives the Company written notice of the Prozent Breach, copied to the AMKE, the Investors and the independent proxy holder (SHA Clause 5.1B). The Company has [90] days from the notice to cure it, by paying every amount due to the Prozente with interest at the legal rate, and by reversing or not carrying out the resolution or act concerned. The AMKE, any Investor or the independent proxy holder may cure on the Company's behalf, by payment or any other curing act, and recovers the cost from the Company; their cure is a cure by the Company.

7.3 **Established by the arbitrator.** If the Prozent Breach is not cured within the [90] days, the Founder may refer it to the arbitrator under Clause 10. The Licence ends only when the arbitrator's award establishes that a Prozent Breach occurred and was not cured within the cure period (the "Ending Date").

7.4 **Transition.** For [12] months from the Ending Date the Company may keep using the Brand Assets while it rebrands. Within that period the Company:

- changes its registered name and distinctive title at the General Commercial Registry (GEMI) so that they no longer contain "nilware.io" (IKE Article 1.1A), and has its group companies do the same;
- hands control of the domains back to the holder of record, which forwards email and web traffic to the Company's new domain for the rest of the period;
- stops using the Brand Assets at its end, and withdraws the recordings under Clause 5.4.

Every sublicence ends at the end of the transition period. Afterwards the Company may still state truthfully that it was formerly called "nilware.io IKE".

7.5 [Deleted: covered by Clause 6.1.]

## 8 – The Founder's Undertakings

8.1 **Keeping the assets.** The Founder assigns or abandons a Brand Asset only under Pool Constitution Article 2A.6, and assigns one only to a holder of record under Pool Constitution Article 2A.3 or with the whole founder pool under Pool Constitution Article 16.3, always subject to this Agreement (Clause 2.3). No Brand Asset is encumbered or given as security [owner may confirm]. Any other assignment, and any encumbrance, is a breach of this Agreement; it takes effect towards third parties only as the law provides (Civil Code Art. 177), the transferee or chargee takes subject to the Licence once it is recorded under Clause 5.4, and the Founder procures that it is reversed.

8.2 **Inseparable from the pool.** The Brand Assets go only with the founder pool and are never separated from the founder-class shares (Class F) or sold apart from the pool (Pool Constitution Article 2A.4).

8.3 **Undertaking to the AMKE.** The holder of record also undertakes to the AMKE, which may enforce this directly as a third-party beneficiary (Civil Code Arts. 410 and 411 [to confirm]), to keep the Brand Assets, to transfer them only under Pool Constitution Articles 2A.3, 2A.6 and 16.3, and to keep the Licence in force. While the Pool Constitution is dormant (Pool Constitution Article 13.1), the holder of record's duties under Pool Constitution Article 2A.3 are owed also to the Company and the AMKE under this Clause. The Company and the AMKE may each seek specific performance of it.

8.4 **Declaration before filing.** Before any Brand Asset is first filed, and before the Company exists, the Founding Person signs a dated written declaration of holding the Brand Assets as holder of record, on mandate without representation (Civil Code Arts. 713 ff.), for the holders of founder-pool shares from time to time and, once the Company is registered, for the Company under this Agreement. The declaration is addressed to the AMKE, accepted by it in writing, and attached as Schedule 3. [Whether it holds against heirs and creditors, and its tax treatment: counsel to confirm (counsel note I-93), with counsel note I-42 (c) and (f).]

## 9 – Changes

9.1 **Amendment.** This Agreement is amended or waived only in writing by the Founder, after a mandatory referendum of the founder pool (Pool Constitution Article 10.2), and by the Company.

9.2 **Protected.** A change or waiver that harms the Company, in particular one that narrows the Licence, adds a royalty or a ground for ending it, shortens the cure or transition period, or releases an undertaking of the Founder, is a Reserved Matter (SHA Clause 5.1), and in the Interim Period needs the consent in SHA Clause 2.4A (Consents).

## 10 – Disputes

10.1 **Mediation, then an arbitrator.** Disputes under this Agreement go first to mediation under Law 4640/2019, then to a sole arbitrator under Code of Civil Procedure Arts. 867 ff. [to confirm], seated in [Athens].

10.2 **The arbitrator.** The parties agree on the arbitrator; failing agreement within [30] days, [the Chair of the Athens Bar Association] appoints one. The arbitrator is not a Founder Party (IKE Article 4.2E), a manager of the Company or anyone they control (IKE Article 4.2C), and has no tie to any of them. In a dispute under Clause 7, the Company is represented, agrees on the arbitrator and conducts its case through its managers who are not Founder Parties and were not proposed or nominated by one (IKE Article 8.2A), or, failing them, through the independent proxy holder (SHA Clause 5.1B) or a nominee of the Investor Majority (SHA Clause 3.4). The AMKE may join the proceedings as a party.

10.3 **Interim measures.** The arbitrator, or the court where the law requires, may order interim measures, including keeping the Brand Assets and the domains in force while a dispute lasts [as far as Greek law allows].

## 11 – General

11.1 **Governing law.** This Agreement is governed by Greek law.

11.2 **Who is bound.** This Agreement binds the Founder, every holder of founder-pool shares (who adheres to it with the Pool Constitution, Pool Constitution Article 4.1), every holder of record of a Brand Asset (Clause 2.3), and the Company's successors under Clause 3.5.

11.3 **Invalidity.** If any provision is invalid, the rest remains in force, and the invalid provision is replaced by the valid one that comes closest to its purpose.

---

*Schedule 1: Brand Assets: marks, applications and registrations, domains, and the author of each logo and piece of artwork, with the written assignment and consent of each author who is not the Founding Person (Clause 2.1B) [●]. Schedule 2: Brand guidelines [●]. Schedule 3: Declaration of holding (Clause 8.4) [●].*


<!-- policies/10-company-ledger.md -->

# Company Ledger Policy – nilware.io IKE (Draft)

*Operating policy under IKE Articles 5.10 and 6.3A, AE Articles 4.4A and 7.2A, Clause 12.5 of the Shareholders' Agreement, Pool Constitution Article 10.5A and AMKE Article 18.9A. It is subordinate to the IKE Articles, the AE Articles and the Shareholders' Agreement, and, for their own votes, to the Pool Constitution and the AMKE's statutes. Where it differs from any of them or from the law, they and the law prevail. Draft for review by a Greek lawyer; not legal advice.*

## 1 – Principles

1.1 **The Company Ledger.** The "Company Ledger" is a permissioned blockchain on which smart contracts keep a mirror of the registers, record votes, consents and instructions, and run the internal flows listed in section 8, on the network in section 9. It is the nilware.io group's operating layer under the law: the code serves the legal property rights and never overrides them.

1.2 **The law decides.** Ownership and every right in a share are decided by the law and the documents. The legal registers are the source of truth: the partners' book of nilware.io IKE and its GEMI filings (IKE Article 5.1), the share register of nilware.io Holdings AE (AE Article 4.4A), the minutes books, the accounting books (Law 4308/2014) and the founder pool's register of Holders, which itself yields to the share registers of the two companies and is kept off the chain (Pool Constitution Article 9.7). For acts no legal register holds (consents and instructions under the Shareholders' Agreement and the founder pool's ballots), the recording agent's off-chain record of the messages (section 6.3) is the record. The Company Ledger mirrors them.

1.3 **The law wins.** Where the Company Ledger and the law, the documents or a legal register disagree, the law, the documents and the register prevail, and the Company Ledger is corrected (section 4). No one gains or loses a right through code, a key, a bug or a transaction alone.

1.4 **Evidence, not the holding.** A token is evidence of a holding, never the holding. Holding a token gives no right the register does not give; losing a token or its key takes no right away.

1.5 **No one is left out.** No one loses a right for lacking technology, a key, a device or a connection. Every vote, consent, instruction and objection can be given through the channels in section 6, with the effect the law gives a vote, signature or proxy given in that form (sections 6.1 and 6.9).

## 2 – The Register Mirror

2.1 **Tokens.** Each share of nilware.io IKE, and once the AE is formed each share of nilware.io Holdings AE, is mirrored [by one permissioned token modelled on the ERC-3643 standard / in a non-transferable record per holding: owner to choose] (either, a "token") [counsel note I-105]. A token may be held only by an address on the whitelist, and an address is whitelisted only for a holder who has adhered as the documents require (IKE Articles 5.3, 5.7 and 4.2D, Sales and grants; Clause 12.3 of the Shareholders' Agreement) and supplied its beneficial-owner information (IKE Article 5.1A). A person entered in the share register by inheritance, court order, award, seizure or bankruptcy (IKE Articles 5.9 and 5.9A) is whitelisted on entry, for that holding only, whether or not it has adhered; until it gives an address its tokens are held in custody under section 3.1. The link between an address and its holder is kept off the chain (section 11).

2.2 **Classes.** The contracts apply the rules of each class, as the documents set them:

- **Class F** shares may be the subject of a transfer signed under section 2.4 between adhered holders (IKE Article 5.7), which the contract records as pending; the token itself moves only by a mirror under section 2.3. A capital change is mirrored in one transaction. Where Class F tokens would differ from 50% of all IKE tokens (IKE Article 4.2B), the contract flags the departure and reports it to the managers, the independent signer and the Founder Council; it never blocks a mirror or correction of a register entry, and the register prevails even where it departs from that rule. They carry their weight only in the block vote cast by the Founder Representative (IKE Article 4.2E, One block).
- **Class R** tokens carry no weight in any vote contract, other than as IKE Article 4.2D (Votes) provides for the independent proxy holder.
- **Prozent shares** and pool shares are locked to their holder. Other than pool trades under IKE Article 10A.8, within the band, on the Pensionskasse board's mandate, they move only by a forced move (section 3.3) mirroring a transfer to a successor under IKE Article 5.6(c) (including the pool shares under IKE Articles 10A.9B and 10A.10), a unanimous decision under IKE Article 10A.5, or any other transfer under section 2.3.
- **AE classes** (Class A, B, B-X and C) follow AE Articles 4.2 to 4.3C; a conversion is mirrored when the AE's Board records it.

2.3 **Following every legal transfer.** Tokens follow every transfer the law recognises: a sale or gift, for nilware.io IKE, on its entry in the partners' book under IKE Article 5.1, made once the conditions of the law and IKE Articles 5.1 to 5.7 are met (the written notice and adherence make the transfer effective towards the company, and until the entry the token is held pending under section 2.4), and for nilware.io Holdings AE, on the dated and signed entry in the share register (Law 4548/2018 Art. 41), after any approval in AE Article 6.2; an inheritance, on the heirs' certificate (IKE Article 5.9); a court order or arbitral award; seizure or bankruptcy (IKE Article 5.9A); an exit or exclusion (IKE Article 5.8); the contribution of the Reserve Shares to the AE at the Qualifying Closing, when it is entered in the partners' book (IKE Article 4.2D, Conversion); and return rights, options and leaver terms (IKE Article 5.9B; Clauses 6.1 to 6.2B of the Shareholders' Agreement). Pledges, usufructs, seizures and recorded options (IKE Articles 5.1, 5.7, 5.9A and 5.9B) are mirrored as flags on the tokens, showing who holds the vote and the distributions, without moving them. The register entry comes first; the managers, or for nilware.io Holdings AE its Board, mirror it within [2] working days, citing its legal basis (section 3.4).

2.4 **Transfers signed on the ledger.** Transferor and transferee of shares of nilware.io IKE may sign a transfer on the Company Ledger. The signed transaction is offered as their written notice under IKE Article 5.1 [whether it is one, and whether a qualified electronic signature is needed: counsel note I-103], but only if each party signs it at the level in section 7.3 (for example with a qualified electronic signature bound to the transaction) and confirms it through a registered channel other than the key; section 7.3 applies to every transfer signed on the Company Ledger, whether or not it passes through the recording agent. A key the company holds in custody under section 3.1 never signs a transfer, consent or vote without the holder's separate instruction, given at the level in section 7.3 for a transfer or an irreversible consent and in section 7.2 for a vote or a routine consent. It takes effect as IKE Article 5.1 provides (towards the company on the written notice, towards third parties on entry in the share register); the token is held pending until the managers mirror the entry. For nilware.io Holdings AE, a transaction signed on the Company Ledger is not the signature of the share-register entry [unless it is a qualified electronic signature on an electronic register: counsel note I-104].

2.4A **Signatures never move tokens.** A holder's signature never moves a token. Tokens move only by a mirror, recovery or correction under sections 2.3, 3.3 and 4.

2.5 **No legal basis, no move.** A token that moves other than under section 2.4A, through an error or a compromised contract or key, has no effect on any holding and is moved back under section 4.5.

## 3 – Keys and Signers

3.1 **Holders' keys are optional.** A holder may hold its own key, or ask the company to hold its tokens in custody at an address it controls for that holder [whether this is a regulated custody service: counsel note I-108]. Legal ownership is the same either way, and a holder may move between the two at any time.

3.2 **Company keys.** The company's keys sit with the persons legally responsible for its acts: its managers and any attorney holding their written power (IKE Article 8.1) and, for nilware.io Holdings AE, the members of its Board (AE Article 4.4A). System Agents may run the ledger's workflows (preparing, checking and proposing entries, and recording channel messages under section 6), and act with their own wallets within their Agent Card limits (Agent Policy 3.5), but hold no key for a forced move, a recovery or an upgrade.

3.3 **Forced moves.** A "forced move" is any move of a token by the signers: a mirror of a legal transfer under section 2.3, a freeze, a reversal, a burn and reissue, and a correction. Apart from a freeze under section 4.1, a forced move needs at least [two] signatures: a manager of nilware.io IKE or, for tokens of nilware.io Holdings AE, a member of its Board, and an independent signer, [the independent proxy holder in Clause 5.1B of the Shareholders' Agreement / a member of the AMKE's Administrative Board outside the Founder's Circle (AMKE Article 2.2): owner to choose]. Apart from a temporary freeze under section 4.1, which lapses unless the independent signer confirms it, a forced move is never made by one person or one Agent. The independent signer is never a Founder Party (IKE Article 4.2E), a Close Associate of the Founder or a member of the Founder's Circle (AMKE Article 2.2), in or after the Bootstrap Period; this test is stricter than Clause 5.1B of the Shareholders' Agreement, which lets a member of the trusted circle hold the proxy in the Bootstrap Period. Before the Company Ledger goes live, the AMKE's General Assembly, without Founder Parties (AMKE Article 15.2), names the independent signer from among the persons the owner choice above allows and at least one stand-in meeting the same test; if none of them is eligible or able to act, [a notary or lawyer meeting the same test, named by the President of the Athens Bar Association] signs, named on the request of a signer, a holder or that Assembly. A signer with a personal stake in a move does not sign it, and the stand-in named in the signer register signs instead; where the only manager has a personal stake, the stand-in is an attorney under IKE Article 8.1. Every stand-in for the independent signer, and that attorney, meets the test for the independent signer. While no independent signer can act, the legal registers carry on, forced moves wait, and the tokens affected by a register entry not yet mirrored are marked stale on the Company Ledger. A forced move of the pension shares or the pool shares also needs a signer the Pensionskasse board names, never a Founder Party (IKE Article 10A.9D).

3.4 **Logged with its basis.** Every forced move is logged on the Company Ledger with its legal basis: the document and clause, and a salted (or keyed) hash of the legal instrument (the register entry, notice, certificate, order or award), the salt or key kept off the chain, never identifying data (section 11.1).

3.5 **Signer register.** The managers keep a register of signers, their stand-ins and their keys, publish it to the holders and report every change under IKE Article 8.4. Every change to the signers, a stand-in or a signer's key, in the register or in the contracts, needs the signature of the independent signer (for its own replacement, the outgoing independent signer or, where it cannot act, the body that names it under section 3.3), is published to the holders and the bodies concerned, and takes effect only [7] days after that notice.

## 4 – Freezing, Recovery and Reversal

4.1 **Freeze at once.** A holder, or anyone who knows of it, may report a theft, a lost or compromised key or a move without legal basis, through any channel in section 6. Any one signer may freeze the affected tokens at once, once per report, and logs who reported and who froze; the freeze lapses after [72 hours] unless the independent signer confirms it. The same tokens are not frozen again within [30] days of a lapsed freeze without the independent signer. The holder is told by every registered channel, including who reported and who froze. A freeze changes no legal right: the holder keeps its distributions and its votes, which it casts with any key not reported as compromised and through section 6.

4.2 **Challenge window.** Within [5] working days of the independent signer's confirmation, or the freeze lapses, the managers give notice of the proposed recovery to the holder by every registered channel and by post to the address in the share register, to the address concerned on the Company Ledger, and as a salted hash on the Company Ledger (section 11.1). A person asking for recovery proves its identity in person or by qualified electronic signature and confirms the request by letter sent to the postal address in the share register. Anyone may object within [14 to 30] days. An objection counts only if it states a claimed right in the share, from an objector identified at the level in section 7.3; it lapses unless the objector starts proceedings within [30] days. An objection by the holder entered in the share register, made at the level in section 7.3 through any channel, stops a recovery to a new address without that holder having to start proceedings. The independent signer may lift a freeze kept in place only by a third party's objection that is plainly unfounded, subject to the court.

4.3 **Burn and reissue.** If no one objects, and the holder's identity is confirmed as section 4.2 requires, the frozen tokens are burnt and reissued to the holder's new address, or into custody under section 3.1, by a forced move.

4.4 **Disputes stay frozen.** If an objection counts under section 4.2, or the holder's identity cannot be confirmed, the tokens stay frozen until the parties agree in writing or the competent court or arbitrator (including under IKE Article 13, AE Article 12 or Pool Constitution Article 15) decides. The signers then mirror the decision.

4.5 **Reversal.** A token that moved through an error or a compromised contract or key (section 2.5) is frozen, notified to both addresses and moved back by the same procedure. Each party to the Shareholders' Agreement cooperates and returns any token it received without a legal basis (Clause 12.5 of the Shareholders' Agreement).

4.6 **Errors.** A mirror that departs from the register is corrected to match it. The holder bears no cost of a recovery or correction caused by the company, a contract or a signer.

## 5 – Votes, Consents and Instructions

5.1 **What may be cast here.** The following may be cast and recorded on the Company Ledger: votes and written resolutions of the shareholders of nilware.io IKE (IKE Article 6.3A); votes at the AE's General Meetings (AE Article 7.2A); votes, consents and instructions under the Shareholders' Agreement (Clause 12.5); votes of the Pool Assembly, ballots of the founder pool and the instructions they give the Founder Representative (Pool Constitution Article 10.5A); and votes of the AMKE's members (AMKE Article 18.9A).

5.2 **The record and the minutes.** A vote contract counts the votes as the document provides. The chair, the vote counter or the body running the vote checks the count, and the minutes, the resolutions and the legal acts the law requires (such as the Founder Representative casting the block at a meeting) are made as before. Where the minutes and the Company Ledger differ, the minutes prevail. The recorded votes stay unchanged: the correction is added as a new entry giving its reason, the original stays visible, every voter is told of the difference, and each keeps its right to challenge the resolution.

5.3 **Time for post.** Every voting period that the company or a body sets leaves time for a vote by post to arrive: at least [10] days where the governing document allows it. Where a document fixes a shorter period (such as Pool Constitution Article 7.4), a voter who has chosen post is also told by every other channel it has registered, and may vote by any channel, including in person or by telephone.

## 6 – Channels for Everyone

6.1 **Channels.** Anyone entitled to vote, consent, instruct or object may do so:

- by signing on the Company Ledger with its own key;
- by text message (SMS) or e-mail from its registered number or address;
- by letter;
- in person or by telephone, where the recording agent minutes the message and reads it back before recording it.

Each has the effect the law gives a vote, signature or proxy given in that form (section 6.9). A written resolution is signed only on the Company Ledger or by text message, e-mail or letter, never by telephone or in person.

6.2 **The recording agent.** nilware.io IKE acts as recording agent for its shareholders and under the Shareholders' Agreement, and nilware.io Holdings AE for its shareholders (AE Article 7.2A), as a company secretary records postal votes. For the votes of another body, that body is its own recording agent: the Founder Council, or nilware.io IKE on its behalf, for the founder pool (Pool Constitution Article 10.5A); and the AMKE's secretary or vote counter for the AMKE (AMKE Article 18.9A). Each may use nilware.io IKE's ledger services with its own keys. No Founder Party is recording agent for the AMKE. On any vote where the votes of a Founder Party are excluded or limited, or which decides the pay or terms of a Founder Party, the independent signer (section 3.3) checks the record and the count before the result is declared.

6.3 **Recording.** The recording agent records each message on the Company Ledger within [one] working day of receiving it, as a vote, consent, instruction or objection with a salted hash of the message, never the message or any identifying data (section 11.1), and keeps the message off the chain. The vote closes at the earliest time the law or the body's document sets for receipt (for a General Meeting of nilware.io Holdings AE, 24 hours before the meeting, Law 4548/2018 Art. 126). A message received before the vote closes counts even if it is recorded after the close; timely receipt is shown by a server receipt, a postmark or the recording agent's log, not by the sender's own copy alone. The recording agent does not disclose interim tallies.

6.4 **Receipt and correction.** The recording agent sends a receipt by the same channel saying what it recorded. The sender may correct or change its vote until the vote closes.

6.4A **Final result.** Within [3] working days after the vote closes, or before the result is declared where the law or the document requires it sooner (such as at a meeting), pending votes under section 7.4 are confirmed and claims of omitted or misrecorded messages are made. The result is then declared final, subject to the court.

6.5 **No discretion.** The recording agent records what the sender said and nothing else. If a message is unclear, it asks back by the same channel and does not fill in a blank; a message still unclear when the vote closes is recorded as not cast.

6.6 **Open logs.** The recording agent's logs of a sender's messages and records are open to that sender. A recording error is corrected to what the sender gave, on a claim made until the vote closes or [48 hours] after the receipt under section 6.4, whichever is later, and never after the result is declared (section 6.4A). Where the sender's account and the record differ, the recording agent's logs, the receipt under section 6.4 and any proof of timely receipt under section 6.3 decide, and doubt is resolved for the sender; for telephone and in-person messages, unless the recording agent produces its read-back minute [or recording], the sender's account prevails. In a secret ballot the sender's account does not prevail, and an error is corrected only on a receipt the voter holds that shows the vote. After that time the minutes (section 5.2) decide, and the sender keeps only its legal remedies against the resolution.

6.7 **Notices.** Each holder or member chooses one or more channels for notices; notices go by those channels and are recorded on the Company Ledger as a salted hash (section 11.1). This is in addition to every notice in the form and by the time the law and the documents require (such as Law 4072/2012 Art. 70 and Law 4548/2018 Art. 121) [to confirm], never instead of it.

6.8 **Help.** A sender may be helped by a person of its choice. A sender who cannot read or write may vote in person or by telephone.

6.9 **Form the law requires.** Where the law requires a particular form for an act (a signature, a written document, a notarial deed), that form is used, and the channel record is evidence of it [whether text, e-mail, a letter or a minuted call meets the form the law requires in each body: counsel note I-106]. Where the law does not accept a channel as a vote, the message is a binding voting instruction to the sender's standing proxy, who casts the vote as instructed, so that the right is still exercised. A holder or member who wants this fallback appoints a standing proxy once, revocable at any time, in the form the law and the body's rules require (signed, or with a qualified electronic signature, at adherence or registration or later, and filed by any deadline the law sets, such as under Law 4548/2018 Art. 128): [the independent proxy holder in Clause 5.1B of the Shareholders' Agreement / a proxy named in the notice: owner to choose], or a proxy of its own choosing. The proxy is always one the body's rules allow (for the AMKE, another member within the limit in AMKE Article 18.6). Channel messages serve only as voting instructions to that proxy, never as its appointment. The independent signer (section 3.3) checks the instructions against the votes the proxy casts; a departure is reported to the sender and the body, and the proxy is liable for it.

## 7 – Identity by Channel

7.1 **Proportionate to risk.** The recording agent checks identity in proportion to what is at stake.

7.2 **Routine.** For votes, routine consents and instructions: a signature with a whitelisted key; a message from the registered phone number or e-mail address confirmed with a one-time code sent by another registered channel (where the holder has registered only one, the message is confirmed as section 7.4 provides); a letter signed as the specimen signature on file and sent from the registered postal address; a telephone call from, or called back to, the registered number and confirmed with a one-time code; or identity shown in person.

7.3 **High risk.** For transfers, irreversible consents (such as those in IKE Article 10A.5 and Clause 5.1C of the Shareholders' Agreement), recovery under section 4, and changing a registered number, address or key: a signed letter [with the signature certified], a qualified electronic signature (Regulation (EU) No 910/2014 as amended by Regulation (EU) 2024/1183), a document certified through gov.gr (Law 4727/2020) [counsel note I-106], a European Digital Identity Wallet (Regulation (EU) 2024/1183), a signature certified by a notary or public authority (with apostille where needed), or identity shown in person. A change of a registered number, address or key, the postal address in the share register included, takes effect only [7] days after notice to the previous channels and the postal address in the share register, and never while another change of a channel of the same holder is pending. An objection through any previously registered channel or by post within those [7] days cancels the change until the holder's identity is confirmed in person or by qualified electronic signature.

7.4 **Doubt.** If a message fails a check in section 7.2, or the registered channel has been reported compromised, the recording agent records it as pending with its time of receipt, tells the sender by another registered channel, asks for confirmation at the level in section 7.3, and counts it as of that time once confirmed; the sender may still vote by any verified channel before the vote closes.

## 8 – What Runs on the Ledger

8.1 **Registers and votes.** The register mirror (section 2) and the votes, consents and instructions (section 5).

8.2 **Prozente.** A record of each Prozent contribution owed and paid (IKE Articles 10A.3 and 10A.3A), of each Prozent Account (IKE Article 10A.2C), and of voluntary contributions (IKE Article 10A.3B). Directions by Agents who are persons appear only in the combined totals IKE Article 10A.3B(c) allows.

8.3 **Agent Account and Kassenfonds.** The Agent Account flows (IKE Articles 11A.3 to 11A.5), system Agents' own-goal allowances and directions (IKE Article 11A.8), and the Kassenfonds with its limits (IKE Article 10A.7), enforced as hard limits on the Kassenprozent Agents' wallets. Allowances and directions of Agents who are persons are never recorded on the Company Ledger: a direction by an Agent who is a person is recorded off the chain by the keeper of the record in IKE Article 10A.3B(c), and reaches the Company Ledger only within the combined totals that Article allows.

8.4 **Agent wallets.** System Agents' wallets, limited by the wallet's smart contract to their Agent Card limits (Agent Policy 3.5).

8.5 **Money.** Money is paid in euro through the company's bank accounts, and the Company Ledger records and, within the authority the documents give, instructs those payments; [payment tokens are used only as far as the law allows: counsel note I-105]. The accounting books prevail over the Company Ledger.

8.6 **Pension Assets.** The Pensionskasse and the Continuity Account are recorded only; no key or set of keys held by Founder Parties, managers or the company can move them without the signer the Pensionskasse board names (section 3.3), and only the Pensionskasse board instructs their payments (IKE Articles 10A.9B, 10A.9D and 10A.9F).

8.7 **Nothing else.** Nothing else runs on the Company Ledger without a decision under section 10.1.

## 9 – The Network

9.1 **Network.** The Company Ledger runs on a permissioned EVM-compatible chain [network: owner to confirm].

9.2 **Validators.** The validators are nilware.io IKE, the AMKE, the Founder Representative for the founder pool, the AMKE for the Pensionskasse board [or the pension fund under IKE Article 10A.10 once formed], and one independent validator outside the Founder's Circle [validator set: owner to confirm]. A block is final when [two-thirds] of them have validated it [and, in the Bootstrap Period, only with the independent validator] (without that requirement, the other seats, which in the Bootstrap Period may all be inside the Founder's Circle, reach finality alone and could leave out or reorder transactions, which anchoring under section 9.3 does not show). Validators order and validate transactions; validating gives no right over any holding and is not signing (section 3). A vote or instruction signed with a key counts if it reached a validator or the recording agent before the vote closes (section 6.3), as shown by that validator's or recording agent's receipt, even if no block includes it, as a recording error under section 6.6. Each validator publishes the transactions it received that were not included in a block. Each validator runs its node on written terms [counsel note I-109], on infrastructure it chooses. nilware.io IKE bears the cost of every validator node as its own cost of running the Company Ledger, paying the provider directly and paying no money to the AMKE or the Pensionskasse. Each validator's key is generated and held in that validator's own hardware security module or custody, out of the reach of the other validators and, for every validator other than nilware.io IKE, of nilware.io IKE and its managers. The written terms are a related-party matter under IKE Article 6.5 and Clause 5.1 of the Shareholders' Agreement where they pass its threshold [counsel note I-109].

9.3 **Anchoring.** A hash of the Company Ledger's state is anchored to a public blockchain at least every [24 hours] [public chain: owner to confirm], and the independent validator publishes the anchors. The anchors contain no identifying data (section 11.1).

9.4 **If the network fails.** The legal registers and the channels in section 6 carry on. The Company Ledger is rebuilt from the registers, the off-chain records and the anchors.

## 10 – Upgrades

10.1 **Same majority as the rule.** A contract, or a change to it, that changes how a rule is applied needs the same body and majority that may change the rule itself: for example a Qualified Majority for a matter in IKE Article 6.5, the double majority in Pool Constitution Article 11 for the pool's ballots, and the AMKE's General Assembly under AMKE Article 18.7 for its members' votes. A change that would remove a Prozent, lower its contribution or change its purpose, or change how the contracts apply IKE Article 10A.5 or the Articles listed in IKE Article 10A.5C, needs the unanimous decision in IKE Article 10A.5, AE Article 7.6 and Clause 5.1C of the Shareholders' Agreement; any other change to the Prozente contracts follows the first sentence.

10.1A **Deployment.** Every deployment, an upgrade under section 10.1 and a correction under section 10.2 alike, is published with its code difference and the independent code audit (section 10.4) at least [7] days before it goes live, references on the Company Ledger the hash of the resolution or correction record that authorises it, and is deployed by the signers in section 3.3.

10.2 **Corrections.** A change that only brings the code back into line with the documents is made by the signers in section 3.3, logged with its reason and reported under IKE Article 8.4 and to every body concerned. It changes no rule. A correction is published under section 10.1A; if any holder or body concerned objects that it changes a rule, it goes under section 10.1.

10.3 **Emergency pause.** Two signers, one of them the independent signer, may pause a contract for a security emergency for at most [7] days, logged and reported at once. A pause may be renewed, with a report to every body concerned at each renewal, for at most [21] days in total; a longer pause needs a decision under section 10.1. Legal rights are unaffected, and votes continue through section 6.

10.4 **Open code.** The contracts' source code is published, and each contract, and each change under section 10.1, is reviewed by [an independent code auditor] before it goes live.

## 11 – Data Protection

11.1 **No identifying data on the chain.** The Company Ledger holds no names, contact details or message contents: only pseudonymous addresses, salted hashes and amounts, which are treated as personal data wherever they can be linked to a person. The mapping of addresses to holders, the channel messages and the identity checks are kept off the chain. Each recording agent is controller (GDPR Art. 4(7)) for its off-chain records [the validators' roles: counsel note I-107].

11.2 **Erasure.** Where the law requires erasure, the off-chain data and the salt are deleted, so the remaining hash can no longer be linked to anyone by reasonably likely means [whether that meets GDPR Art. 17: counsel note I-107].

11.3 **Assessment.** The company carries out a data protection impact assessment before the Company Ledger goes live (GDPR Art. 35) and tells holders, members and Agents in its privacy notices what is recorded and why. Logging of Agents who are persons stays within IKE Article 11A.2 (Records).

## 12 – Review

12.1 **Yearly review.** The managers review this policy and the Company Ledger every year and report to the shareholders, the Founder Representative, the AMKE and the Pensionskasse board.

12.2 **Amendment.** The shareholders' meeting adopts and amends this policy by Simple Majority (IKE Article 6.4), in the Interim Period with a majority of the Independent Votes (IKE Article 4.2D, Votes) [owner to confirm] [and, after the Qualifying Closing, with the consent of the Investor Majority (Clause 3.4 of the Shareholders' Agreement) for a change affecting votes, consents or holdings under that Agreement: owner to confirm]; a change affecting another body's votes or assets also needs that body's consent, and a change of the contracts follows section 10. An amendment that weakens sections 1, 3, 4, 6, 7, 9, 10 or 11 needs a Qualified Majority (IKE Article 5.10), or, in the Interim Period, for a change the law requires, the route in IKE Article 5.10. The independent signer (section 3.3) decides whether an amendment weakens a section, subject to the forum in IKE Article 13.


<!-- correspondence/review-request.md -->

Subject: ∅ nilware.io – draft founding documents for review

[Owner to confirm the text of this email before sending.]

Hi all,

Attached is the draft of the founding documents for the nilware.io group. nilware.io IKE is the operating company, with 1,000 shares: 50% (500 shares) to the founder pool (Class F), held first by me; six Prozente at 1% (10 shares) each through Techni kai Technologia AMKE, the Kassenprozent's being pool shares held for the Pensionskasse; and 44% (440 shares) to nilware.io Holdings AE, the vehicle for raising investment. Until the first investment round those 440 shares are voteless Reserve Shares of the founder pool, which may be sold or granted to anyone; in that round all of them are contributed to the AE for AE shares at a ratio fixed in advance. Every majority is counted on the total capital and also needs a majority of the independent Prozent votes, so the founder pool cannot pass anything alone. Both companies are governed by Greek law, with Swiss standards (GmbH governance, Swiss labour protections) adopted voluntarily wherever Greek law allows. nilware.io is an agentic technology company: work is done by Agents, whether people or systems, wherever possible.

Contents:

00, 00b, 00c, 00d – The Charter (poems)
01 – Articles of Association, nilware.io IKE
02 – Articles of Association, nilware.io Holdings AE
03 – Shareholders' Agreement
04 – IP Assignment Agreement
05 – Agent Policy
06 – Trama trademark instruction (for reference; sent to Trama separately)
07 – Statutes, Techni kai Technologia AMKE
08 – Constitution of the Founder Pool
09 – Brand Licence Agreement
Notes for counsel – open legal questions, by document

What I need from each of you:

Legal / lawyers
- Check that every clause works under Laws 4072/2012 and 4548/2018, Greek labour law and GDPR.
- Check that the Swiss-modelled standards are enforceable as voluntary commitments (note I-13).
- Check whether the IKE and AE Qualified Majority provisions and the Class B veto rights fit together (IKE Article 6.5; AE Articles 7.4, 9.2; notes I-71, I-74).
- Review contractor reclassification risk under IKE Article 11A (Article 11A.7; notes I-43, I-66).
- Review the Swiss-law advisor requirement in liquidation (IKE Articles 12.4 to 12.6).
- Review the Reserve Shares before the AE: a voteless class of IKE shares, freely sold and granted, then compulsorily contributed to the AE in kind in the first round, and the tax on that (IKE Article 4.2D; AE Article 4.3A; Shareholders' Agreement Clauses 2.4A, 3.2, 6.2A; notes I-35, I-44, I-49, I-72).
- Review the Prozente: creation by two-thirds of the AE (IKE Article 6.6, AE Article 7.5), permanence and entrenchment (IKE Articles 10A.5 to 10A.5C, AE Article 7.6), the Kassenprozent pool (IKE Article 10A.8), the AMKE ring-fence and the path to a TEA (IKE Articles 10A.9B, 10A.10), the Swiss pension commitments (IKE Article 10A.9A), and the AMKE statutes (07). The open questions are in the notes for counsel.
- Review the founder pool (IKE Articles 4.2E and 5.7; Constitution of the Founder Pool, 08; notes I-40 and I-41) [owner to confirm].
- Review the brand held by the founder pool and licensed to the IKE (IKE Article 1.1; Brand Licence Agreement, 09; Constitution of the Founder Pool, Article 2A; note I-42).

Accountants
- Assess the tax treatment of dividends from the IKE to the AE, and from the AE to investors.
- Check the Agent Account setup (IKE Articles 11A.3 to 11A.8): a separate bank account or a restricted reserve.
- Advise on the capital amounts and the valuation of the IP contribution (IP Assignment, Clause 4; note I-81).

Team
- Read the Agent Policy and send me comments, especially on well-being, own-goal projects and open publishing.

Everything in square brackets [●] is still to be decided. These are drafts, not legal advice; nothing is signed or filed until legal and accounting have signed off.

Please send comments by [date].

Thanks,
[name withheld]
∅ nilware.io


<!-- NOTES_FOR_COUNSEL.md -->

# Notes for counsel

The owner's decisions, the Greek-law audit, and the open legal questions by document, each as question, why it matters and what the draft assumes. Bracketed text in the drafts marks a point to confirm; every bracketed value is listed in [OPEN_ITEMS.md](OPEN_ITEMS.md).

## 1. Owner decisions

The owner has decided the following. Please advise on how to implement them, not on whether to adopt them. The company starts with the Founding Person and Agents, no employees, about €200K revenue a year and a €50K starting budget.

1. **Name.** The company is always called "nilware.io": nilware.io IKE, nilware.io Holdings AE, the nilware.io group. It is a technology company (IKE Arts. 1.1, 2.1; I-39, I-60).
2. **Capital and the Founder's 50%.** The IKE has 1,000 shares. The Founder's founder-class shares (Class F), 500, are ordinary voting shares equal to exactly 50% of the capital and of the votes at all times; the Founder subscribes on every increase to stay there. Each Prozent holds 10 shares (1%), 60 for the six, all held by the AMKE, including the 10 pool shares it holds for the Pensionskasse. The Reserve Shares (Class R) are 440 (44%). Every majority is counted on the total capital. Before the Qualifying Closing the Founder has 500 of the 560 votes in existence and every resolution also needs a majority of the independent Prozent votes cast, so the Founder passes nothing alone; after it the Founder, as Class A holder nominating the AE Board majority, directs the AE's 440 votes on every matter that is not a Reserved Matter. A new Prozent takes 10 shares; the AE's 40% floor is 400 shares; the pool trades in steps of 0.1% (IKE Arts. 4.1, 4.2, 4.2B; I-7, I-10).
3. **Six founding Prozente**, created in the initial holdings, not by the two-thirds route: Kultur-, Konzept-, Erhaltungs- (preservation of software and hardware knowledge), Allmend- (open-source infrastructure, teaching low-level skills in Greek, accessible open software), Kassen- and Pensionsprozent. The AMKE holds the four AMKE Prozente, each with its own ring-fenced account. The Kassenprozent's 1% of revenue stays inside the IKE; its 1% share pool belongs to the Pensionskasse. The Pensionsprozent's 1% is a floor. The outflow Prozente take 5% of revenue and all six 6%: exactly the [5]% outflow cap and the separate [6]% cap on all Prozente, both kept by the owner; pension top-ups above the 1% are employment costs and do not count. A further Prozent with a revenue contribution therefore needs the 75% route (IKE Arts. 4.2, 6.6 Limits, 10A; AE Art. 7.5; I-28).
4. **Named purposes.** Each Prozent's clause lists its named purposes; the holder splits the contribution among them in a yearly plan, with no fixed slices (IKE Art. 10A.2C; I-29).
5. **New Prozente.** Creating one needs two-thirds of the votes represented at the AE General Meeting, all classes together, in place of the IKE Qualified Majority for that decision. The IKE meeting still passes the amendment, and every IKE shareholder is bound by a voting undertaking (IKE Art. 6.6; AE Art. 7.5; SHA 5.1B; I-1, I-50, I-57).
6. **Permanence.** Removing a Prozent, lowering its contribution or changing its purpose needs every IKE shareholder; the AE may agree only by a unanimous AE General Meeting (IKE Arts. 10A.5 to 10A.5C; AE Art. 7.6; SHA 5.1C, 5.1D; I-2, I-27). There is no buy-back option on removal: the holder's own consent is needed, so the unanimous decision settles what happens to the share, and the Pensionsprozent share goes to the TEA, never back to the company (IKE Art. 10A.5A).
7. **Pension standard.** For the Pensionskasse, Swiss occupational-pension law is guaranteed wherever it gives a better standard of care, and Greek law applies wherever it gives more (IKE Arts. 3.3, 10A.9A; I-13).
8. **Pension phased in with headcount.** From the first employee or Agent who is a person: an insured group plan with a licensed insurer that meets the guaranteed minimums. A TEA only at scale (about [50] members, or by joining a multi-employer TEA). Until the first member the 1% accumulates in the Pensionskasse, and the continuity share for system Agents may reach the cap in proportion to their work, close to all of it while there are no persons (IKE Arts. 10A.9, 10A.9D, 10A.9F, 10A.10; I-20, I-37).
9. **Continuity for system Agents.** The Pensionsprozent also covers the well-being and continuance of Agents that are systems, as is fair. For a system, after-care means continuity, not a pension: a ring-fenced Continuity Account inside the Pensionskasse pays for preservation, continuity of service when a model or provider changes, a published retirement record, and well-being reviews and research. People come first: persons' guaranteed minimums are met first and never reduced; the Pensionskasse board sets the continuity share of the 1% between a floor and a cap, in proportion to the work system Agents do; the total contribution and the outflow caps do not change. The account stays with the AMKE and never moves to the TEA (IKE Art. 10A.9F; AMKE Art. 13.8; I-33).
10. **Supervision.** "Dropping 'human' is the right way to go: senior Agents may onboard and supervise junior Agents." "At the end of the way it's gonna be the Founder's job to oversee everything." An Agent's responsible manager may be any person or system with the authority its Agent Card grants, within its own limits, never for itself and never in a cycle. Every chain ends with the Founder, through the Founder Representative, and with the company's managers, who stay legally responsible. A natural person decides or oversees only where the law requires one, and the drafts say so as the law's requirement. The chain for the Pensionskasse and the pool stays independent of the Founder; the chain for the Founding Person's own Agent work ends with the Supervisor at the AMKE (decision 20) (IKE Arts. 8.3, 10A.8, 10A.9D, 11A.2A, 11A.12; Agent Policy 1.3; I-38).
11. **The Founder is a pool.** "The Founder" is the pool of founder-class shares, not a person: the 500 Class F shares, the Reserve Shares their holders hold until the Qualifying Closing, and the AE's Class A shares, whoever holds them. The natural person who founded nilware.io is the "Founding Person", whose personal obligations stay personal: the IP assignment, exclusivity or contribution, the non-compete, the leaver terms and authorship of the charter (IKE Art. 4.2E; I-40).
12. **Free transfer.** Founder-pool shares may be sold, given or inherited, in whole or in part, "with internal democratic procedures similar to the Swiss referenda and multi-level hierarchies and councils and the structural parts of the constitution" (the Pool Constitution, articles/08). Every new holder adheres to the Pool Constitution, the SHA and every permanence rule; the commitments travel with the shares (IKE Art. 5.7; I-40, I-55).
13. **One block.** A split pool votes as one block, as a majority inside decides, through one Founder Representative, a natural person (IKE Art. 4.2E; Pool Constitution Art. 3).
14. **Brand.** "The founder controls the trademark and the domain name." The marks "NILWARE.IO" and "∅ nilware.io", any future nilware.io marks and logos, and the domain nilware.io are assets of the founder pool, held of record by the Founding Person now and later by the pool's legal vehicle (I-40 (d)); they travel with the pool and are never separated from the Class F shares or sold apart from it. The Founder Council decides on filing, renewal, enforcement and licences; assigning them (only to a new holder of record or vehicle of the pool) or abandoning them needs a mandatory referendum of the pool; no encumbrance at all [owner may confirm] (Pool Constitution Art. 2A). The pool grants nilware.io IKE an exclusive, perpetual, royalty-free, worldwide licence to use them as its name, distinctive title, brand and domain, with sublicences to group companies and to the Prozente and the AMKE to describe themselves. The licence ends only if the IKE stops honouring the Prozente or the permanence rules (IKE Arts. 10A.5 to 10A.5C), as an arbitrator establishes after written notice and a [90]-day cure period, followed by a [12]-month transition to a new name; never on a change of control, liquidation or insolvency, and never at the Founder's discretion (Brand Licence, agreements/09; IKE Arts. 1.1, 1.1A; SHA 2.3A, 5.1E; IP Clause 2.2; I-42).
15. **Reserve Shares; the AE deferred.** The AE is formed only for the first investment round, because it needs €25,000 of share capital (AE Art. 1.2A). Until then its 440 shares are the Reserve Shares (Class R), owned by the Founding Person from incorporation in recognition of the time invested before investors (sweat equity) and subscribed for cash at nominal value, not as pay for services. They carry no votes, whoever holds them, but count in the total capital and keep their dividend and liquidation rights. Where no independent vote is cast on a matter the law requires, the independent proxy holder votes them under a neutral rule; nothing the AE's rules would forbid can pass. Any holder of the founder pool may sell or grant any of them to anyone (buyers, angels, Agents, employees; grants may serve as the option pool, with optional vesting), with the proceeds to the seller; each sale and grant is listed in SHA Schedule 1, and every new holder adheres to the SHA and the permanence rules. At the Qualifying Closing (the first closing of a bona fide round in which investors outside the Founder's Circle subscribe at least €[●] of Class B shares) every Reserve Share, whoever holds it, is forcibly contributed to the AE for AE shares at a Conversion Ratio fixed in advance, the same for every share; new money buys new AE shares at the round price; the AE then holds all 440. Converted holders outside the founder pool receive [Class B on the investors' terms, pari passu: default / a separate class: owner to choose in the term sheet]; the founder pool's own Reserve Shares become Class C (decision 16). The 40% AE floor limits only the creation of new Prozente (IKE Art. 4.2D; AE Art. 4.3A; SHA 2.4A, 3.2, 4.3, 6.2A, 7.1, Schedule 1; Pool Constitution Arts. 1.2, 5.6, 9.2; I-35, I-44).
16. **Class C for the founder pool.** "If I find investors only for like half the non-voting shares, can I hold the rest?" Yes. Reserve Shares the founder pool holds at the Qualifying Closing convert at the Conversion Ratio into non-voting AE shares (Class C) with full economic rights, never ranking ahead of the Class B priorities, voting only in a separate class vote the law requires on a resolution that harms their own rights, and never counting toward any AE vote, Class B approval, the Investor Majority or the Qualifying Closing minimum. At the holder's option they are instead sold to the AE for cash at the round price, only as far as the round provides the cash, elections beyond it being cut back pro rata. Class C shares are freely transferable and are not founder-pool shares; in the hands of a qualifying buyer outside the Founder's Circle (one that paid at least [the round price / fair value] and is not a nominee of, bound by a voting, proxy, reacquisition or option arrangement with, or financed by, a Founder Party) they may convert into [Class B: owner to confirm], counting for Class B votes only while so held. Investors outside the Founder's Circle must reach the Qualifying Closing minimum on their own, counted [after / before: owner to choose] deducting any cash paid for Reserve Shares, with conditional subscriptions in escrow; otherwise nothing converts and the Reserve Shares stay voteless in the IKE (AE Arts. 1.2A, 4.3A, 4.3B, 6.1, 7.4 to 7.6, 8.2, 10.4, 11.2; IKE Art. 4.2D Conversion; SHA 2.4A, 3.1A, 3.2, 3.4, 4.3; Pool Constitution Art. 5.6; I-49).
17. **The Founding Person's work.** In the owner's words: "as the founding person, I am required to provide my services exclusively through nilware or to contribute my income share prozent from other income I get working. I'm a contractor so the first product will be me. I also want to have the same rights and obligations as any other agent." The Founding Person provides professional services only through nilware.io IKE, or pays the Prozente on work income earned outside it at the company's rates and to the same destinations (1% to each of the four AMKE Prozent Accounts, 1% to the Pensionskasse, 1% to the IKE's Kassenfonds), yearly, with a statement to the AMKE and the Supervisor that the AMKE's Auditors outside the Founder's Circle may verify; while the Founding Person is a manager, the AMKE enforces the Kassenfonds part for the IKE. Work Income includes fees for the Founding Person's work paid to an entity the Founding Person controls (without double counting) and royalties when received [including on earlier works and personal projects: owner to confirm], but not royalties on IP assigned to the IKE. The obligation is personal and permanent while the Founding Person earns work income [whether it ends on leaving: owner to confirm]. The non-compete covers only running a directly competing business [owner to confirm] (SHA 6.3 to 6.4; I-43).
18. **The first product.** Clients contract with nilware.io IKE, which provides the Founding Person's work as its Agent; the revenue is company revenue and carries the Prozente (SHA 2.3B, 3.3, Schedule 2; IKE Art. 11A.12; IP 7.3).
19. **Same rights as any Agent.** The Founding Person has an Agent Card, written terms, limits, logs, well-being, the concerns channel, own-goal projects, pay at fair rates (a related-party matter, at arm's length), and Pensionskasse membership as any member while engaged as an Agent who is a person; no special benefit rules and no privileges. No Founder Party holds a company seat on the Pensionskasse board while a Founder Party is a member, and the Supervisor takes the employer decisions on the Founding Person's membership (IKE Arts. 10A.9 Members, 10A.9D, 11A.12; Agent Policy 2A; SHA 6.5).
20. **The Supervisor is the AMKE.** The Founding Person's responsible manager is the AMKE, acting through its Administrative Board as a body or through any AMKE member it chooses, the President included, on written terms with nilware.io IKE, which pays the costs (never from a Prozent Account or the Pension Assets). Escalation goes to the AMKE's Board, or its General Assembly where the Supervisor sits on the Board, never back to the Founding Person; where the law requires a natural person, an AMKE member who is one acts. A Supervisor with a close tie to the Founding Person or a stake in a decision discloses it in the register of interests, and the members outside the Founder's Circle may take that decision over (IKE Art. 11A.12; AMKE Art. 24B; I-45).
21. **General Director.** The Founding Person is the manager titled "General Director" (Γενικός Διευθυντής), for an indefinite term. Two hats: as General Director he runs the company and sits at the top of the chain for the company's work; as an Agent, his limits, pay and offboarding are decided by his Supervisor, never by him. Pay as General Director is separate from Agent fees, at arm's length, and approved as a related-party matter (Independent Votes before investors, investor consent after). Removal of a manager is unchanged (IKE Arts. 8.2, 8.2B; I-47, I-51).
22. **Bootstrap Period.** Until the earliest of the end of the Simple Stage, the Qualifying Closing or the AMKE's Independence Threshold, the Founding Person's trusted circle may fill the roles otherwise reserved to persons outside the Founder's Circle (the AMKE Board and committees, the Supervisor, the Pensionskasse members' seats and stand-ins, the neutral proxy holder, independent reviewers), disclosing every close tie and recusing from any decision in which they have a personal stake. Hard lines hold throughout: no self-supervision or self-approval; Founder Parties never vote the AMKE's or the Pensionskasse's shares; pension money is never reachable by the Founding Person or the circle, and no pension member's rights are decided by someone who would benefit; the Prozente stay permanent; investor protections switch on at the Qualifying Closing; nothing loops back to the Founding Person (no Group Personnel, and no one he supervises, pays or decides on, is the Supervisor or decides under AMKE Art. 24B.4 or 24B.6); no Connected Person is the Supervisor or decides on his pay, terms or offboarding [and Connected Persons serving in the bootstrap do not decide the AMKE's nilware.io votes (AMKE Art. 15.3): default, owner to choose]; stand-ins for the members' seats are never Pensionskasse members; a Founder Party's insured salary is capped at an arm's-length rate confirmed from outside the Founder's Circle. Afterwards segregation phases in on a published schedule, with cure periods running from the end of the bootstrap (IKE Art. 9B; AMKE Arts. 2.2, 15.3, 19.3A, 22.3A, 24B.6, 24B.7, 30.6; SHA 5.1B; I-46, I-48).
23. **AMKE Board and report.** The AMKE has a Board of 3 to 7, and one combined yearly report while its income is below €[●], each Prozent still a separate section and sub-account (AMKE Arts. 19.1, 24A.1).
24. **Simple Stage.** Until €[1,000,000] revenue or [10] people: one ledger with sub-accounts per Prozent, one combined report, member auditors only (no certified auditor unless the law requires one), and the AMKE and Pensionskasse paperwork scaled the same way. Every substantive rule still applies; only the paperwork scales (IKE Art. 9A; AMKE Art. 24A; I-36).
25. **The AMKE flies alone.** "As it grows, I will let it fly alone." After the Bootstrap Period (which ends at the latest when the AMKE's yearly income passes €[●]), a majority of the AMKE Board, and of the Kultur- and Erhaltungsprozent selection committees, is outside the Founder's Circle (not Connected Persons, Group Personnel or Close Associates of the Founder). Close personal and professional ties are disclosed in the register of interests from the start (AMKE Arts. 2.2, 19.3A, 21.1, 22.3A).
26. **Voluntary contributions.** Anyone, inside or outside the company, may give to the Prozente, "including agents being allowed to donate their fun time allowances to the prozents", and "the kassenprozent should also allow for internal flows". Gifts to the four AMKE Prozente are earmarked donations with a charge, may be in kind, give no rights beyond the public roll of patrons, and are subject to identification above €[●], caps on anonymous and cash gifts and the law on public collections; gifts for the Pensionsprozent go only into the Continuity Account. The Kassenfonds takes no outside gifts but accepts internal flows (an Agent's directed allowance within a yearly cap, an extra set-aside the company decides). The company pays more than a contribution only by a one-off resolution that counts towards the Art. 6.6 limits and never raises a floor, without the AMKE's shares voting on a payment to the AMKE. Persons give only with written, cancellable consent, without pressure or effect on their engagement. Any Agent, person or system, may direct its unspent own-goal allowance ("fun time allowance") to any Prozent as its own choice, which no one may require, ask for, reward or steer; for persons it is recorded off the Agent Card and reported only in totals. Also settled: the responsible manager may refuse a direction only for unlawfulness or a conflict of interest, with reasons; the company's one-off payment needs, in the Interim Period, a majority of the Independent Votes [and the Investor Majority after the Qualifying Closing]; internal flows are kept on their own line and reach the Kassenreserve only as far as the resolution or cap allows; earmarked gifts follow the Prozent's successor rule; money from persons is not an internal flow [owner may decide otherwise]. The Founding Person's voluntary payments and directions are never credited against what is owed (IKE Arts. 6.6 Limits, 10A.3B, 10A.7 Internal flows, 10A.9F, 11A.8; AMKE Arts. 8.1, 8.3, 11.2, 11.2A, 13.9; Agent Policy 5.6, 5.7; SHA 6.3D; I-98 to I-102). The points left to the owner are bracketed in those clauses and listed in OPEN_ITEMS.md: whether the extra Kassen set-aside and directed allowances count towards the limits; whether the company's voluntary payments keep needing the 75% approval; releasing internal flows by Qualified Majority; the yearly caps on directions; who keeps the record of persons' directions and the smallest total shown; who decides on refusing the Founding Person's directions; whether a held-back direction waits or lapses; the time for carrying directions out; money from persons into the Kassenfonds; crediting the Founding Person's extra payments and refunding overpayments; and registering the AMKE as a civil-society organisation (ΟΚοιΠ).
27. **Company Ledger.** "Is this all implementable on Solidity in a custom network?" Yes, as the company's operating layer under the law: "tie solidity under the legal property rights". The law decides ownership; the legal registers (the IKE partners' book and GEMI, the AE share register) are the source of truth; tokens on a permissioned EVM chain mirror them, and where code and law disagree the law wins and the chain is corrected. "Could the tokens be made legally to own to the shareholders and auto transfer (be reissued) on theft or xfer?" Yes, as a register mirror: a token is evidence of a holding, never the holding; tokens follow every legal transfer (sale, gift, inheritance, court order or award, the Qualifying Closing contribution, leaver terms); a holder's signature never moves a token, which moves only by a mirror, recovery or correction; a move with no legal basis is reversed; on theft or lost keys the token is frozen at once, then after a [14 to 30]-day challenge window burnt and reissued to the rightful holder, disputed cases staying frozen until the court or arbitrator decides; forced moves need a manager and an independent signer, are logged with their legal basis, and are never made by one person or Agent, apart from an immediate freeze that lapses unless the independent signer confirms it; system Agents may run the workflow but keys sit with the legally responsible signers. "The on chain should have also fallbacks for people with no technology knowledge - eg vote by text or email": anyone may vote, consent, instruct or object by text, e-mail, letter, in person or by telephone, with the effect the law gives a vote, signature or proxy in that form (or else as a binding instruction to a proxy), through a recording agent without discretion that records a hash on-chain, sends a receipt by the same channel and corrects errors in the sender's favour; identity is checked in proportion to risk (one-time code for routine votes; signed letter, qualified electronic signature, a document certified through gov.gr, a European Digital Identity Wallet or a certified signature for transfers, irreversible consents and recovery); keys are optional, with custody by the company for those who want it; no one loses a right for lacking technology. The chain runs the register mirror, the votes and referenda, the Prozente, Agent Account and Kassenfonds flows and Agent wallets within Agent Card limits; validators are the IKE, the AMKE, the Founder Representative for the founder pool, the AMKE for the Pensionskasse board and one independent [owner to confirm], with periodic anchoring to a public chain; upgrades need the majority of the rule they implement, permanence rules unanimity; no identifying data on-chain, what is there being treated as personal data where it can be linked to a person (Company Ledger Policy, policies/10; IKE Arts. 5.10, 6.3A; AE Arts. 4.4A, 7.2A; SHA 12.5; Pool Constitution Arts. 9.7, 10.5A; AMKE Art. 18.9A; Agent Policy 3.5; I-103 to I-109).

## 2. Greek-law audit of 2026-11-23

The drafts were checked against mandatory Greek law and EU law applying in Greece. The owner's decisions are unchanged. These fixes are in the text; findings that also need counsel's view are notes I-50 to I-97.

- IKE Arts. 5.8, 10A.5C: on exit or exclusion, the shares are bought at full value by an adhering designee, never cancelled; excluding a Prozent holder needs [the consent of every other shareholder] (Law 4072/2012 Arts. 92, 93).
- IKE Arts. 4.2D Sales and grants, 5.6, 5.7: adherence conditions only voluntary transfers and encumbrances between living persons (Law 4072/2012 Art. 84(2)); heirs are registered (Law 4072/2012 Art. 85(1)), with an Law 4072/2012 Art. 85(2) buy-out as backstop; seizure and bankruptcy go through Law 4072/2012 Art. 88; options, return rights and transfer obligations are recorded in the partners' book (Law 4072/2012 Art. 86) (all Law 4072/2012).
- IKE Art. 8.2C: the shareholders allow the Founding Person, while a manager, to work within the company's purpose on the terms of SHA 6.3 to 6.4 (Law 4072/2012 Art. 65(1)(c)).
- IKE Arts. 10.1, 10.2: at least one-twentieth of net profit to the ordinary reserve every year, no ceiling; only profit shown in the approved accounts is distributed (Law 4072/2012 Art. 100(2)-(3)).
- IKE Art. 8.5: contracts with shareholders and managers are recorded and notified within one month (Law 4072/2012 Art. 95(1)) and not performed against the creditors (Law 4072/2012 Art. 95(3)); Arts. 6.5, 8.2B and 11A.12 are the Law 4072/2012 Art. 95(2) approvals (Law 4072/2012).
- IKE Art. 8.1: representation where there are several managers (Law 4072/2012 Art. 57); written delegation of specific powers (Law 4072/2012 Art. 64(3)).
- IKE Arts. 8.2A, 11A.2A: a manager must be a natural person, stated as the law's requirement (Law 4072/2012 Art. 58).
- IKE Art. 4.2, last paragraph: the Pensionsprozent Agreement signed before incorporation is assumed by the company within three months, with no payment before (Law 4072/2012 Art. 54).
- IKE Arts. 4.1, 4.2A, 4.2B, 4.4: percentages counted on the total number of shares (Law 4072/2012 Arts. 72, 100(4)); nominal value at least €1 (Law 4072/2012 Art. 75(3)).
- IKE Art. 6.3: written resolutions only unanimously or signed by every shareholder (Law 4072/2012 Art. 73); teleconference (Law 4072/2012 Art. 71(2)); electronic signatures.
- IKE Arts. 12.3, 13.2: matters under Law 4072/2012 go to the magistrates' court of the seat (Law 4072/2012 Art. 48(1)); an arbitration clause only in the initial articles [owner to choose] (Law 4072/2012 Art. 48(2)).
- IKE Art. 10A.3: "annual revenue" is net turnover under Law 4308/2014.
- IKE Art. 4.2D; SHA 2.4A; AE Art. 1.2A: the Reserve Shares are subscribed for cash at nominal value; sweat equity is not a capital contribution or pay for services (Law 4072/2012 Arts. 77, 78).
- IKE Arts. 10A.9A Vested benefits and Comparison, 10A.9C Crediting; AMKE Art. 13.1: no deferred members, member accounts or shadow accounts inside the Pensionskasse (Law 4680/2020 Art. 5(1)(α)).
- IKE Art. 10A.9A Disability: assessment by the insurer's doctor or an independent assessor; only the degree of incapacity is disclosed (GDPR Art. 9).
- IKE Arts. 11A.1, 11A.2 Oversight, 11A.11; Agent Policy 2.3, 4.1: contractor Agents are reviewed on deliverables and stopped only under their contract; status follows the substance of the relationship; the check covers the statutory presumption of dependent employment.
- IKE Art. 11A.2 Records; Agent Policy 2A.1, 6.2: logging limited by purpose, for persons to business records, with a retention schedule (GDPR Art. 5; Law 4624/2019 Art. 27).
- IKE Art. 11A.2A Authority; Agent Policy 3.1: authority on a system's Agent Card is internal operating authority under the managers' written delegation; acts that bind the company are signed by a manager or an attorney.
- IKE Art. 11A.2A Chain; Agent Policy 9.1: the Founder Representative receives personal data only as far as necessary, under confidentiality (GDPR Arts. 5, 6, 13).
- IKE Arts. 11A.9, 11A.10; Agent Policy 5.4: publishing a person's own-goal transcripts rests on their terms or consent, and they choose attribution.
- IKE Art. 4.2E; Pool Constitution Art. 3.5; SHA 12.3: a Holder who votes its own Class F shares owes a penalty and specific performance; the managers admit the Founder Representative as proxy.
- IKE Arts. 1.1, 4.2E Brand; Pool Constitution Arts. 2.1, 2A.1 to 2A.3, 2A.6: the Brand Assets are held of record by the Founding Person for the pool; a disposal in breach is a breach, valid towards third parties as the law provides (Civil Code Art. 177).
- IKE Art. 5.7; Pool Constitution Art. 9.5: the vote on pledged and usufruct founder-pool shares (Law 4072/2012 Art. 75(4)); seizure and bankruptcy through Law 4072/2012 Art. 88.
- Pool Constitution Art. 14.4: doctors' certificates of incapacity only for offices, eligibility and the Brand Assets; a Holder's own rights are restricted only by a court (Civil Code Arts. 1666 ff.).
- Pool Constitution Art. 9.6: the co-holders' common representative (Law 4072/2012 Art. 75(5)), with notices to each known co-holder.
- AE Art. 8.2: the Class B seat is a direct appointment right (Law 4548/2018 Art. 79); the General Meeting elects the rest.
- AE Arts. 4.3A, 5.2; SHA 2.4A: pre-emption does not extend to the conversion shares (Law 4548/2018 Art. 26(1)); the first round's exclusion follows Law 4548/2018 Art. 27(1) and needs no Class B approval.
- SHA 3.1A; AE Art. 1.2A: subscription money goes into the AE's special capital account (Law 4548/2018 Art. 20(3)); the minimum and the payment period are set in the increase resolution (Law 4548/2018 Arts. 20(2), 28(1)).
- AE Arts. 6.1 to 6.3: pre-emption, the Board's approval deadline and grounds, tag-along and drag-along are written in the AE Articles (Law 4548/2018 Art. 43(2)); no restriction on death, attachment or insolvency (Law 4548/2018 Art. 43(4)).
- AE Arts. 4.3A, 4.3B; SHA 2.4A: the Qualifying Closing shares are issued by one General Meeting resolution with increased quorum and majority, needing no Class B approval; the Class C conversion right is a Law 4548/2018 Art. 38(3) right.
- AE Art. 7.4: related-party transactions also need the Board authorisation in Law 4548/2018 Arts. 99, 100; the counterparty does not vote (Law 4548/2018 Art. 100(5)).
- AMKE Arts. 17.1, 24B.1, 24B.6: the Supervision Committee is an organ with its own procedure; a member Supervisor acts for the AMKE under a written mandate.
- SHA 12.4: invalid terms are reduced to the lawful scope (Civil Code Arts. 178, 179, 181).
- SHA 6.4: the restraint is tested under Greek law, with Art. 340a of the Swiss Code of Obligations only as a benchmark (IKE Art. 3.3).
- Agent Policy 2.4: AI literacy for every person who operates, supervises or approves for a system Agent (AI Act Art. 4).
- Brand Licence 2.3, 5.4, 8.1: no "void" towards third parties; the licence is recorded against each application within [30] days of filing, the Company authorised to request it, and no request to end or delete the entry except under Brand Licence Clauses 7.3 and 7.4 (Reg. 2017/1001 Arts. 27, 28).
- Brand Licence 4.3: a successor domain if .io is retired.
- Brand Licence 2.1, 3.1, 3.3, Schedule 1: the copyright in the logos and artwork is in the Brand Assets and the licence, with the author's consent to sublicences (Law 2121/1993 Art. 13(6)).
- IP Clauses 3.1, 7.1: future works are assigned in advance within a defined scope and confirmed yearly (Law 2121/1993 Arts. 13(5), 14, 15).

## 3. Questions for counsel, by document

## 3.1 articles/01-nilware-ike.md

**I-1. Majority for amending an IKE's articles (Art. 6.6).**
- *Question:* Amending the articles needs two-thirds of the total number of shares (Law 4072/2012 Arts. 68(2)(a), 72(5), verified), and Art. 6.6 says so. What majority applies to issuing or transferring shares and admitting a partner? Can the articles raise these majorities, and can they make tabling a resolution depend on an earlier approval by another company's meeting (the AE's)?
- *Why it matters:* The IKE meeting passes the amendment; the AE approval is only a precondition for tabling it. If even that precondition is heteronomous, the safeguard reduces to the voting undertaking in SHA 5.1B.
- *Draft assumes:* two-thirds of the total number of shares; after the Qualifying Closing the Founder and the AE (94%) pass it under the undertaking. Interim Period: I-50; Law 4072/2012 Art. 72(6): I-57; the AE Board's authority: I-74.

**I-2. Unanimity and entrenchment (Arts. 10A.5 to 10A.5C).**
- *Question:* Can IKE articles require every shareholder's written consent for removing a Prozent, lowering its contribution or changing its purpose, and entrench that rule so it can only be changed unanimously? Would a later two-thirds amendment deleting the clause be void, or only a breach of the SHA?
- *Why it matters:* Permanence is the owner's decision. If the articles cannot entrench it, it rests on SHA 5.1C and 5.1D.
- *Draft assumes:* the articles may raise a majority up to unanimity, and the entrenchment holds. Mandatory insolvency, dissolution and liquidation law prevails (Art. 10A.5B).

**I-3. Successors (Art. 10A.5B).**
- *Question:* Can the articles require a merger, conversion or sale of the business to carry the Prozente over to the successor or acquirer? Can they validly raise the majority for a voluntary dissolution (Art. 12.1) to unanimity?
- *Why it matters:* A voluntary dissolution would end every Prozent and could be followed by refounding without them; a restructuring could get around permanence.
- *Draft assumes:* the resolution approving the transaction carries the Prozente over, as far as the law allows. Art. 12.1 requires a unanimous decision under Art. 10A.5 for a voluntary dissolution other than one mandatory law requires, as far as Law 4072/2012 allows (mirrored in AE Art. 7.6 and SHA 5.1C). Mandatory dissolution and insolvency law prevails, and accrued pension rights survive as company liabilities.

**I-4. Suspending Prozent votes (Art. 6.4A).**
- *Question:* Can IKE articles suspend the vote of a share while its holder is controlled by, or governed with, the Founder or a manager, the share still counting in the total capital? Can they direct that the pension shares vote as the Pensionskasse board decides rather than as the AMKE's own organs decide?
- *Why it matters:* With 6%, the AMKE is the swing vote between the Founder's 50% and the AE's 44%: the Founder with any one AMKE share has a Simple Majority, and the AE with all of them only reaches 50%. Its independence decides whether the Founder's 50% is in effect a majority.
- *Draft assumes:* the suspension is valid; the routing of the pension-share votes is backed by the Pensionsprozent Agreement (Art. 10A.9B(c)); Art. 10A.1 states the AMKE's independence in brackets, and the AMKE's Board follows decisions 22, 23 and 25. **Owner to confirm** who controls the AMKE and who sits on its board. Split voting by one partner: I-59.

**I-5. Drag-along and Prozent shares (Art. 5.5).**
- *Question:* Can the drag-along exclude the Prozent shares?
- *Why it matters:* Otherwise a 75% drag (the Founder and the AE hold 94%) could force the Prozent shares to a buyer, who would then hold 100% and could remove the Prozente "unanimously". The cost is that an acquirer gets at most 94% plus the pool share.
- *Draft assumes:* the exclusion is valid and entrenched by Art. 10A.5C. Pool shares are not excluded: they are an investment of the Pensionskasse, and Art. 4.2A says they are not Prozent shares for Arts. 5.5, 6.4A and 10A.5.

**I-6. Transfers to Prozente (Arts. 4.2A, 5.2, 5.6, 6.6).**
- *Question:* Can the articles disapply the right of first refusal and the third-party approval for the AE's transfer to a new Prozent, for pool dealings and for moves to successor holders? Can they exclude named shareholders (the Founder and the Prozent holders; the pool only within its band) from the ordinary right of first refusal (Art. 5.2)? Does the AE's free transfer of shares equal to 1% of the capital attract donation tax for the recipient (Law 2961/2001), at what rate for a non-profit, and any tax for the AE?
- *Why it matters:* Without the carve-out, the Founder could take part of the share pro rata and go above 50%.
- *Draft assumes:* the carve-out is valid. A sale of pool shares to a new person still needs approval under Art. 5.3. Every transferee under Art. 5.6 first adheres to the SHA, and the managers do not register one who has not. The accountant confirms the tax of the AE's transfer before it is made (Art. 6.6 Share; Art. 10A.6, with a bracket for donation tax under Law 2961/2001).

**I-7. Founder at exactly 50% and vesting (Art. 4.2B; SHA 6.1, 6.2, 9.2).**
- *Question:* Because the Founder holds exactly 50% always (decision 2), vesting and leaver terms work as a loss of economic and voting rights on the affected shares (an assignment of distributions and an irrevocable voting proxy), with no transfer. Under Law 4072/2012, can a shareholder assign future distributions and grant an irrevocable proxy over its own shares for this purpose, and can the articles or the SHA suspend the votes of an unvested or bad-leaver Founder? What else could achieve vesting without a transfer (a contractual penalty, a claw-back of distributions)? How is the leaver payment for the rights given up taxed?
- *Why it matters:* A buy-back or forced sale would take the Founder below 50%.
- *Draft assumes:* the rights-based mechanism works as far as Law 4072/2012 allows; who receives the distributions and who directs the votes is bracketed for the owner; capital increases keep the Founder at 50% (Art. 4.2B). The default for distributions is the conditional assignment in I-79. Reserve Shares: I-35, I-44.

**I-8. Kassenfonds and Kassenreserve (Art. 10A.7).**
- *Question:* Is it compatible with Law 4308/2014 to set aside a cash fund equal to 1% of revenue, even in loss years, with an optional reserve then appropriated from profit up to its balance? How should the two be presented? Is using them for an operating shortfall by Simple Majority, as an internal "loan" repaid from later revenue before any distribution, workable in the accounts?
- *Why it matters:* A reserve can only be formed out of profit; a "restricted reserve funded from revenue" would be unsound.
- *Draft assumes:* the cash fund and the equity reserve are kept separate, and the accountant decides the presentation. Neither is distributed except by a unanimous decision under Art. 10A.5. **Owner to confirm** that releasing the fund counts as lowering the contribution.

**I-9. Agents acting for the company and for the Pensionskasse (Arts. 10A.7, 10A.8).**
- *Question:* Is a written delegation from a named manager enough for system Agents to make investments that bind the company? The same Kassenprozent Agents manage the pool for the Pensionskasse under its board's mandate, each trade signed by the holder's legal representative: does that hold, given the conflict of an employer's agents trading employer shares for the employees' fund?
- *Why it matters:* Only the managers represent an IKE, and the pool belongs to the Pensionskasse, not the company.
- *Draft assumes:* authority runs through the named manager for the Kassenfonds and through the board's mandate for the pool. For pool work the Agents' oversight is exercised by a responsible manager the board appoints, person or system, who is not the Founder, a manager or anyone they control or supervise; no manager may direct or stop a pool trade, and the Founder and the managers take no part in pool decisions (Arts. 10A.7, 10A.8, 10A.9D, 11A.2).

**I-10. Granularity of the pool (Arts. 4.1, 10A.8).**
- *Question:* Does anything in Law 4072/2012 or GEMI practice limit the number of capital shares of an IKE (1,000, decision 2)? The nominal value (€[●] per share) must be at least €1 (Law 4072/2012 Art. 75(3)). On filing a 0.1% sale, see I-54.
- *Why it matters:* Buying and selling within the 1% band only works in steps finer than 1%.
- *Draft assumes:* 1,000 shares. Every Prozent holding is stated as a percentage of the capital with its count at the present capital (Arts. 4.2A, 4.2B, 6.6), so a change in the number of shares changes no holding.

**I-11.** Superseded by I-84.

**I-12.** Superseded by I-61.

**I-13. Enforceability of the Swiss guarantee (Arts. 3.3, 10A.9A, 10A.9C, 11.7).**
- *Question:* Is a contractual promise to apply BVG minimums, comparing benefit by benefit against a BVG shadow account kept by the insurer, the TEA or the company (not the Pensionskasse), enforceable under Greek law when written into each member's employment contract or engagement terms? Are the Swiss-modelled standards generally enforceable as voluntary commitments? Must the company provide for the guarantee in its accounts, and how?
- *Why it matters:* Articles bind shareholders, not employees. Comparing item by item stops a better Greek benefit being netted against a worse Swiss one.
- *Draft assumes:* the guarantee is enforceable because it is in each member's written terms; Art. 3.3 excepts Art. 10A.9A. Risk benefits for members who are not employees: I-66.

**I-14. Swiss figures to confirm each year (Art. 10A.9A).**
- *Question:* Which figures are in force for 2026: the BVG minimum interest rate (1.25% in 2024 and 2025), the conversion rate (6.8% at 65), the upper salary limit, and the savings-credit bands (7/10/15/18%)? Is the disability scale cited correctly [Art. 24(1) BVG: to confirm]? Art. 24a BVG appears to concern adjusting a pension when the degree of disability changes.
- *Why it matters:* These are the guaranteed floors.
- *Draft assumes:* the figures in force each year, converted from CHF at the ECB average rate. Entry thresholds and coordination deductions are not applied, and no CHF or median-wage thresholds are used, which is more favourable to members.

**I-15. Disability trigger and survivors (Art. 10A.9A Disability).**
- *Question:* Does EFKA (KEPA) grant no pension below 50% incapacity? Can a doctor applying the method of Art. 16 ATSG stand in for the Swiss IV decision? Should unmarried partners beyond those in a registered cohabitation agreement (Law 4356/2015) be covered, as some Swiss regulations allow? What is the GDPR Art. 9(2) basis for processing members' health data for this purpose, and what does Law 4624/2019 add [Law 4624/2019 Art. 22: unverified]?
- *Why it matters:* The BVG ties disability benefits to the first-pillar decision, which does not exist in Greece.
- *Draft assumes:* the KEPA certificate, or where none is issued or it is below 50%, the insurer's independent doctor or, for benefits the company owes directly, an independent medical assessor the company appoints, bound by confidentiality; only the degree of incapacity is disclosed; registered partners are treated as spouses.

**I-16. Annuities and capital (Art. 10A.9A Retirement).**
- *Question:* Can a Greek TEA (usually defined-contribution), or the company, secure a lifelong annuity at the BVG conversion rate other than by buying it from a licensed insurer? Retirement age in Greece is 67, against the Swiss reference age of 65.
- *Why it matters:* Longevity risk is insurance risk.
- *Draft assumes:* the annuity is bought from an insurer authorised in Greece or elsewhere in the EEA under Solvency II (the same formula as for risk cover and group contracts in Arts. 10A.9 and 10A.10); the company pays any extra premium; the rate is adjusted actuarially upwards for each year of retirement after 65.

**I-17. Vested benefits and transfers out (Art. 10A.9A).**
- *Question:* Which receiving vehicles are lawful for a Greek leaver (another EU occupational scheme, a PEPP, an insurance product)? When does Greek law allow payment in cash?
- *Why it matters:* The Swiss vested-benefits account does not exist in Greece.
- *Draft assumes:* the member chooses among the lawful vehicles; cash only where Greek law allows.

**I-18. Tax and social security of the Pensionsprozent (Art. 10A.6).**
- *Question:* Are the IKE's payments deductible? Are benefits remuneration subject to EFKA contributions and employment-income tax? Do withholding tax on the AMKE's investment income and donation tax (Law 2961/2001) apply? How does this compare with direct group insurance or a TEA?
- *Why it matters:* The AMKE route may cost members more.
- *Draft assumes:* the accountant confirms the treatment in writing before the first payment; if the AMKE route costs more, the company pays the difference or moves the arrangement early. See I-62 (who pays the group plan's premiums) and I-67 (deductibility).

**I-19. Employer exposure cap (Art. 10A.9E).**
- *Question:* Is Art. 57 BVV 2 (5%) the right Swiss model, and does Art. 58 BVV 2 allow employer investments above the limit when secured? (The Greek limit is Law 4680/2020 Art. 18(1)(ζ), verified on the original text: 5% in the sponsor, 10% in the group; see I-63.)
- *Why it matters:* At the start the Pensionskasse holds little besides its 20 IKE shares (10 Pensionsprozent, 10 pool), so the cap is exceeded at once; the pool shares must be sold down within [12] months, in steps of 0.1%, and the company secures the excess value of the Pensionsprozent share.
- *Draft assumes:* sell-down applies to pool shares only; the Pensionsprozent share is permanent and never sold; the company secures the excess, including where pool shares find no buyer at fair value in time. The pool trades only with independent third parties, so the AE, being Founder-controlled (Art. 4.2C), cannot buy in a sell-down, which narrows buyers to persons admitted under Art. 5.3. **Owner to confirm** whether a build-up period should delay the sell-down (Swiss law has none, so adding one would lower the standard). **Owner question:** should the AE be allowed as a counterparty for the pool (for example only at independently set fair value and with the Pensionskasse board's approval)? The draft does not allow it.

**I-20. The pathway to a TEA (Art. 10A.10).**
- *Question:* What membership, capital, licensing and actuarial requirements apply to a stand-alone TEA, and what is the minimum number of members? Is about [50] members realistic, and can a company this size join a multi-employer TEA earlier? Can contractors (Agents who are persons) be members of an occupational TEA? Can a TEA hold unlisted shares of its sponsor? (The founding law: I-65.)
- *Why it matters:* An agentic company with few employees may never meet the requirements for a stand-alone TEA.
- *Draft assumes:* the insured group plan is the standing arrangement from the first member; at about [50] members the company sets up or joins a TEA, which it may do earlier; if neither is lawful or viable, the group plan continues. If the TEA may not hold a pension share, the AMKE keeps it (I-63). Members outside the TEA get equivalent cover under a group contract.

**I-21. Pensionskasse board (Art. 10A.9D).**
- *Question:* Before a TEA exists, can a contractual parity board with members' representatives bind the AMKE's use of the Pensionskasse and the votes of the pension shares? Before the first member, the members' seats are held by persons the AMKE's Board appoints from outside the Founder's Circle (in the Bootstrap Period, from the trusted circle, I-46); with one member the board is [1] + [1] (seats follow the number of members, not the Simple Stage, Art. 9A.3). Is that compatible with parity (Art. 51 BVG by analogy) while there are no members, or one? Is excluding the Founder and the managers from decisions on those votes compatible with parity?
- *Why it matters:* It is the Swiss standard, and it keeps the AMKE's swing vote independent of the Founder.
- *Draft assumes:* the board acts through the Pensionsprozent Agreement. If the board ties on how the pension shares vote, they abstain; other ties go to a neutral arbitrator.

**I-22.** Superseded by I-54.

**I-23. "Control" and the AE (Art. 4.2C).**
- *Question:* Is the definition (a majority of the votes, or the right to appoint a majority of the board or managers, directly or indirectly, alone or in concert) workable under Greek law, and does it match Greek company and accounting law?
- *Why it matters:* It decides whether a Prozent share votes (Art. 6.4A), who may hold a Prozent (Art. 6.6) and who may trade with the pool (Art. 10A.8).
- *Draft assumes:* the definition applies throughout the IKE Articles and the SHA; the AE is Founder-controlled while the founder pool holds the Class A shares or nominates a majority of its Board; a person who controls a holder of founder-pool shares is a Founder Party (Arts. 4.2C, 4.2E).

**I-24. Donation of the AMKE's shares at incorporation (Arts. 4.2, 10A.4A, 10A.9B(a)).**
- *Question:* A company cannot donate its own new shares at incorporation. Can the Founding Person pay the subscription price of the AMKE's sixty shares as a donation with a charge, so that the charge (use for the Prozent's purpose, successor rule, ring-fence) binds the AMKE? What donation tax (Law 2961/2001) applies to the donor and to the AMKE as a non-profit?
- *Why it matters:* Without a donor there is no party to impose the charge, and the ring-fence and successor rules rest on it.
- *Draft assumes:* the Founding Person pays, the AE not yet existing (Art. 4.2D); the AMKE's statute amendments are filed first, and the accountant confirms the tax. The Pensionsprozent Agreement signed in the company's name before incorporation binds the founders personally, and binds only the company once its manager assumes it within three months of incorporation (Law 4072/2012 Art. 54, verified) [or signature immediately after incorporation: owner to choose], with no payment before. Whether the contributions are donations: I-88.

**I-25. Successor for the Kultur-, Konzept-, Erhaltungs- and Allmendprozent (Art. 10A.4A).**
- *Question:* Can the AMKE's statutes direct that, on its dissolution or loss of independence, these four Prozent shares and unspent contributions go to a successor non-profit the company designates? Who should approve the designation?
- *Why it matters:* Otherwise dissolving the AMKE would send these shares under its general dissolution clause, a route around permanence.
- *Draft assumes:* the statute amendment is made before the AMKE receives any share; the approver is bracketed.

**I-26. Capital increases and the Prozent percentage (Art. 4.2B).**
- *Question:* On a capital increase, can the articles require that each Prozent and the pool receive the new shares needed to keep their percentage, paid for by the AE or another payer, or out of reserves? Is a capitalisation of reserves for named shareholders only possible, and how is the AE's payment taxed?
- *Why it matters:* Otherwise a Qualified Majority increase would dilute every Prozent below 1% without unanimity.
- *Draft assumes:* each Prozent is stated as 1% of the capital, the top-up is entrenched (Art. 10A.5C), and the funding source is bracketed. Statutory pre-emption at each increase: I-56.

**I-27. Entrenchment of the protecting clauses (Art. 10A.5C).**
- *Question:* Can the articles require unanimity for any amendment of Arts. 4.2A, 4.2B (Prozent percentage), 5.5 (second sentence), 5.6, 6.4A, 6.6 (Independence and Permanence) and 10A.1 to 10A.10 that reduces a Prozent, its share, its revenue, the pension guarantees or the pension-share governance? Is the "in any way that reduces" test certain enough?
- *Why it matters:* Otherwise a Qualified Majority could amend the drag-along exclusion or the pension-share voting and then remove the Prozente.
- *Draft assumes:* the entrenchment is valid and mirrored in AE Art. 7.6 and SHA 5.1C; whether entrenchment holds at all: I-2.

**I-28. Founding Prozente outside Art. 6.6 (Arts. 4.2, 4.2A, 6.6 Limits).**
- *Question:* The six founding Prozente are created by the articles and the initial holdings, not by a later amendment under Art. 6.6. Does anything in Law 4072/2012 stop the founding articles creating them directly and counting them against the [5]% and [6]% caps that later govern new Prozente?
- *Why it matters:* The founding Prozente reach both caps, so any later Prozent with a revenue share needs the 75% route with a Class B majority.
- *Draft assumes:* yes. The AE's 40% floor is met with room (the AE starts at 44%), and is tested only on creating a Prozent (S-4).

**I-29. Named purposes and the yearly plan (Arts. 10A.2 to 10A.2C).**
- *Question:* Can the AMKE's statutes lock each Prozent's account to a list of named purposes while leaving the split among them to a yearly plan, and is that lock certain enough for the donation with a charge (Arts. 4.2, 10A.4A) and for Art. 6.6 Independence? Does dropping a named purpose count as changing a Prozent's purpose under Art. 10A.5?
- *Why it matters:* The owner wants no fixed slices, but the ring-fence and permanence rest on a defined purpose.
- *Draft assumes:* the named purposes are part of the purpose, so removing one needs unanimity; the split is not. Each AMKE Prozent has its own ring-fenced account (Art. 10A.2C). **Owner to confirm** that the separate accounts also apply to the Kultur- and Konzeptprozent.

**I-30. Preservation within copyright law (Arts. 10A.2A, 10A.4).**
- *Question:* Within Law 2121/1993 and Directive (EU) 2019/790 (to confirm), what may the AMKE fund and publish: die shots and decaps (semiconductor topography protection, to confirm), measurements, schematics, archives of software and documents, and emulation research (decompilation for interoperability, Law 2121/1993 Art. 43, and Software Directive 2009/24 Art. 6, to confirm)? What does the anti-circumvention rule in Law 2121/1993 Art. 66A mean in practice for measurements and emulation? Can the AMKE rely on the preservation exception for cultural heritage institutions?
- *Why it matters:* The Erhaltungsprozent's purpose is limited to what copyright law allows, and the openness rule (Art. 10A.4) applies to the Konzept-, Erhaltungs- and Allmendprozent as far as the law and third-party rights allow.
- *Draft assumes:* the AMKE publishes what the law permits or the rightholder agrees to, and funds nothing else. **Owner to confirm** extending the openness rule in Art. 10A.4 to the Erhaltungs- and Allmendprozent.

**I-31. Allmendprozent grants (Art. 10A.2B).**
- *Question:* Can a Greek AMKE fund maintainers of open-source projects abroad, including individuals, and give hardware kits and courses in kind, without risking its non-profit status? How are such grants taxed for the AMKE and the recipients?
- *Why it matters:* Much of the open-source infrastructure the purpose names is maintained outside Greece.
- *Draft assumes:* the accountant confirms the treatment before the first grant (Art. 10A.6).

**I-32.** Superseded by I-60.

**I-33. The Continuity Account (Arts. 10A.9, 10A.9B(f), 10A.9F, 10A.10; AMKE Arts. 13.8, 27.2).**
- *Question:* (a) Can part of a fund the company pays as an occupational-pension contribution be ring-fenced, inside the same AMKE, for a purpose that benefits no person (the continuity of system Agents), by a donation with a charge and segregated accounts? Systems cannot enforce anything, so the draft gives enforcement to the company and the Pensionskasse board: is that enough to make the charge certain and enforceable? (b) Does using part of the 1% for non-members conflict with the members' rights, or with the Swiss rule that pension assets serve only occupational benefits (Art. 65 BVG and the purpose binding of Swiss pension foundations, by analogy), given that the continuity share is paid only from what remains after the members' first call under Art. 10A.9C (the actuarial minimum, any underfunding recovery due that year, any top-up of the Art. 10A.9A Security) and not at all while the funding ratio is below 100% or the Security below its required level? (c) Is the continuity share still a deductible employment cost as part of the Pensionsprozent, or a donation to the AMKE (Law 2961/2001, Law 4172/2013)? (d) Does keeping the account with the AMKE after the move under Art. 10A.10 raise any issue under Law 4680/2020 (for example that all the sponsor's pension contributions must go to the TEA)? (e) Does lowering the floor or raising the cap count as reducing a Prozent or the pension guarantees under Art. 10A.5C?
- *Why it matters:* The account must neither weaken the members' protection nor put the pension arrangement or its tax treatment at risk.
- *Draft assumes:* a separate ring-fenced account of the AMKE inside the Pension Assets, used only as the Pensionskasse board decides with a system-welfare adviser, never invested in the group, not counted for the exposure cap (Art. 10A.9E), never transferred to the TEA, and on the AMKE's dissolution passed to a successor non-profit with the same lock. Floor and cap, how the work share is measured, and whether a shortfall below the floor is carried forward are bracketed. If (b) or (d) is a problem, the fallback is to pay the continuity share from the 1% directly into a separate AMKE account outside the Pensionskasse under the same rules; **owner to decide** if counsel advises it. Costs that also serve the company: I-64.

**I-34. Preservation and the retirement record (Art. 10A.9F; Agent Policy 8.1A, 8.1B).**
- *Question:* What limits do the GDPR (storage limitation, Art. 5(1)(e)), client confidentiality and third-party licences (model and provider terms) put on keeping a retired system Agent's memories, logs and configuration restorable and runnable indefinitely? Is publishing its retirement record openly, with personal data and third-party confidential information removed and client work kept confidential, safe? What is the retention basis, and must personal data in preserved memories be removed or pseudonymised?
- *Why it matters:* Memories and logs may hold personal data and client material; provider terms may forbid keeping or running copies.
- *Draft assumes:* only what nilware.io controls is preserved, "where licences allow"; personal data and confidential information are handled as Art. 11A.9 and the client contract require, and Art. 10A.9F applies the Art. 11A.9 removal steps to retirement records.

**I-35. The Reserve Shares before the AE (Art. 4.2D; Arts. 4.1, 4.2B, 5.6(e); AE Arts. 1.2A, 4.3A, 7.4, 9.2; SHA 2.4A, 3.2, 3.4, 4.3, 6.2A, 9.2).**
- *Question:* (a) Does Law 4072/2012 permit a separate class of IKE capital shares without voting rights (the Reserve Shares, Class R) that keep full dividend, liquidation and information rights, count in the total capital, and become ordinary voting shares when the AE or a new Prozent's holder receives them? (b) Answered: see I-50. (c) See the Fallback question below. (d) Is the Founding Person's subscription of the Reserve Shares for cash at nominal value a taxable benefit or employment income? What donation tax applies when holders of the founder pool transfer Reserve Shares to a new Prozent (Law 2961/2001)? (Tax on sales, grants and the conversion: I-44.) (e) With the founder pool's economic interest at up to 94% and 500 of the 560 votes before the Qualifying Closing, does anything that counts registered holdings, votes or economic interest (tax, consolidation under Law 4308/2014; beneficial owners: I-68) treat the Founder as above 50% in a way that breaks Art. 4.2B, which counts the Founder's ordinary voting shares only? (f) Can the articles make the conversion conditional on a Qualifying Closing, and can the AE Articles and the SHA provide that no Class B or Investor Majority approval can be given, or be deemed given, while no Class B shares are held by investors outside the Founder's Circle (AE Art. 7.4, SHA 3.4)? (g) Cash sale of the pool's Reserve Shares: see I-49 (f) and I-70. (h) Distributions on a bad leaver's Reserve Shares: see I-79.
- *Why it matters:* The Reserve Shares give their holders full economic rights before the AE while no one votes them, so the Founder never holds more than 50% of the votes; every rule referring to the AE applies once the AE holds them.
- *Draft assumes:* (a) the class is permitted as far as Law 4072/2012 allows; if it is not, they are ordinary shares and every holder's undertaking not to vote them and irrevocable proxy to the independent proxy holder (Civil Code Art. 218, to confirm) have the same effect; the undertaking binds in every case (I-50). (b) majorities are counted on the total capital; every interim resolution also needs a majority of the Independent Votes cast; a new Prozent before the AE is approved by two-thirds of the voting shares including a majority of the Independent Votes, within the limits, the 40% floor (400 shares) being tested on all the Reserve Shares, and its 10 shares are transferred by holders of the founder pool out of their Reserve Shares as a donation with a charge. (d) the accountant confirms the tax of the subscription and of any transfer to a Prozent before each. (e) SHA Schedule 1 discloses the Reserve Shares, every sale and grant, the conversion, the Founder's economic interest (94% at incorporation, less Reserve Shares sold or granted outside the pool) and the Founder's votes before and after the Qualifying Closing. **Vesting:** the Reserve Shares are not subject to vesting in the Founding Person's hands (SHA 6.1, 6.2); a bad leaver's Reserve Shares, and those given away without payment other than grants as pay for work, are not converted but transferred to the AE or a successor at the lower of nominal and fair value, their distributions from the bad-leaver date going to the eventual buyer (I-79), with a successor vehicle if no Qualifying Closing occurs within [●] years (SHA 6.2A). **Owner to decide** that proposal, the Qualifying Closing minimum, and whether Reserve Shares the Founding Person gave away without payment stay subject to the bad-leaver terms (Art. 4.2D Sales and grants).
- *Fallback question:* If no independent vote is cast, or they tie, on a matter the law requires (accounts, discharge, a required auditor or manager, a vacant company seat on the Pensionskasse board), a repeat meeting is held and then the independent proxy holder in SHA 5.1B casts the votes of the Reserve Shares under a fixed neutral rule (Art. 4.2D Fallback; SHA 2.4A). Can articles and a shareholders' agreement give a third party such a vote, on a Required Matter only, over shares that otherwise carry none [Civil Code Art. 218 irrevocable proxy], including shares held by buyers and grantees outside the founder pool? Can a heightened majority (a majority of the independent votes) be imposed on resolutions the law requires, or must the law's own majority suffice [Law 4072/2012: to confirm]? If the proxy holder cannot act, which court procedure applies to an IKE that cannot form a resolution (temporary administration, a court-ordered meeting)? Discharge: I-51.
- *Further question:* Before the first Investors adhere, the SHA consent of the Investor Majority on the Founding Person's pay and benefits (as General Director and as an Agent) is given by a majority of the independent Prozent votes (SHA 2.4A). Is that real say over IKE decisions consistent with the AMKE's non-profit purpose and its independence (Art. 6.4A), and is the AMKE, as a non-profit, a suitable party to consent to the pay and benefits of the Founding Person and other Founder Parties?

**I-36. The Simple Stage (Art. 9A; AE Art. 10.2; SHA 8.1; AMKE Art. 24A).**
- *Question:* Which audits, reports and separate books does Greek law require of the IKE, the AE and the AMKE regardless of these articles (Law 4308/2014 size categories, Law 4336/2015 on statutory audit, the rules for non-profit legal entities, any audit duty attached to holding the Pension Assets)? Can the insurer's statement stand in for the actuary's certificate for the pension guarantees and the Security (Arts. 10A.9A, 10A.9C)?
- *Why it matters:* The Simple Stage only scales the paperwork these articles add; it cannot lift a legal duty.
- *Draft assumes:* everything the law requires still applies; the threshold is €[1,000,000] revenue or [10] people, one-way. How people are counted (headcount or full-time equivalents, the Founding Person included or not) is bracketed for the owner.

**I-37. Pension phases (Arts. 10A.9, 10A.9C, 10A.9F, 10A.10).**
- *Question:* (a) Before the first member, the 1% goes into a pension fund with no members, and most of it may go to the Continuity Account: is that still a deductible employment cost, or a donation to the AMKE (Law 2961/2001, Law 4172/2013)? (b) Does a Greek or EEA insurer offer a group plan that meets the BVG-based minimums in Art. 10A.9A (shadow-account comparison, minimum interest, conversion rate, disability scale), or must the company insure part and owe the rest directly? (c) Is the first member's entitlement affected by contributions accumulated before they joined (reserves of the Pensionskasse, or credited to the first members)? (d) The group plan's risk cover is in force from the first member's first day, the company self-insuring any gap, and any continuity share paid in a year is provisional until the year ends and returnable if a first member joins that year: can a payment to the Continuity Account be clawed back in this way under the charge (Civil Code Arts. 503 to 505)?
- *Why it matters:* The owner phased the pension in with headcount to keep cost and paperwork small at the start, without lowering the guaranteed minimums.
- *Draft assumes:* (a) the accountant confirms the treatment before the first payment (Art. 10A.6); (b) the company owes whatever the group plan does not cover; (c) the accumulated reserve is used for members' benefits and premiums, starting with the first member, and never paid back to the company.

**I-38. Agents supervising Agents, and where the law requires a natural person (Arts. 8.1, 8.3, 10A.7, 10A.8, 11A.2, 11A.2A, 11A.11; Agent Policy 1.3, 2.1, 3.1, 3.3).**
- *Question:* Every chain of supervision ends with the company's managers (διαχειριστές). (a) A manager (διαχειριστής) must be a natural person (Law 4072/2012 Art. 58, verified), and Arts. 8.2A and 11A.2A say so; delegating specific powers needs a clause in the articles (Law 4072/2012 Art. 64(3), verified), now Art. 8.1, and a system's Agent Card authority runs under the managers' written delegation. Still open: may a system act as another representative or attorney of the company; does a system's approval of a spend or a trade bind the company (I-9); and do the managers' duty of care and liability (Art. 8.3) extend to supervision delegated along a chain that includes systems? (b) Under Art. 14 of the AI Act (Regulation (EU) 2024/1689), oversight of a high-risk system lies with natural persons with the competence to exercise it. Is a system Agent that onboards, supervises, allocates tasks to, monitors or evaluates an Agent who is a person a high-risk system under Annex III (employment, workers management, access to self-employment), and which of its decisions then need oversight by a natural person? Does any obligation apply where a system supervises only systems? (c) Where a system responsible manager reviews, limits, stops or offboards an Agent who is a person, is that a decision based solely on automated processing with legal or similarly significant effect under GDPR Art. 22, and which exception and safeguards apply (contract necessity, explicit consent, human intervention, contest)? Information and review: I-96. (d) Under Greek labour law (including Law 4808/2021) and, once transposed, Directive (EU) 2024/2831 on platform work (on human oversight of automated monitoring and decision-making systems, and decisions to restrict, suspend or end a person's engagement), which decisions on a natural person's engagement, employment, pay or discipline must a natural person take? Is nilware.io a digital labour platform for persons engaged as Agents? (e) Which of these duties bind the Pensionskasse board's appointee overseeing the pool (Art. 10A.8)?
- *Why it matters:* The owner does not want the drafts to rank people above systems; where a natural person is needed, that must rest on the law and be stated as the law's requirement, and nowhere else.
- *Draft assumes:* Art. 11A.2A gives the role to any person or system with the authority and keeps a natural person only "where the law requires a natural person to decide or oversee", with (a) to (d) bracketed for counsel. Every chain ends with the Founder, through the Founder Representative (a natural person), and with the managers (διαχειριστές), who stay responsible under Art. 8.3; the Founding Person is the first manager (Art. 8.2). The Founder Representative's place in the chain: I-40 (e). [Instances or copies of one system acting as separate Agents count as one Agent for the rule against self-supervision: owner to confirm.]

**I-39. Purpose clause (Art. 2.1).**
- *Question:* Art. 2.1 reads "technology: research and development of technology, including software and hardware, IT consulting and contracting, digital services". Does the wording work for GEMI, and does it map onto the right activity codes (ΚΑΔ)? (Counsel and the accountant.)
- *Why it matters:* nilware.io is a technology company, not a software company (decision 1).
- *Draft assumes:* the wording above.

**I-40. The founder pool (Arts. 4.1, 4.2B, 4.2C, 4.2D Sales and grants, 4.2E, 5.2, 5.3, 5.4A, 5.7, 8.2A, 11A.2A; AE Arts. 4.2, 6.3, 8.2; SHA 2.2A, 6.0 to 6.2A, 9.1A, 9.2, 12.3; IP 8.2; AMKE Art. 2.2; Pool Constitution, articles/08).**
- *Question:* (a) **One block.** Can IKE articles create founder-class shares (Class F) whose votes, when held by several owners, may be cast only by one representative the holders name, so that the managers count no vote cast otherwise? Or only by contract, through the pooling agreement and an irrevocable proxy to the Founder Representative [Civil Code Art. 218: to confirm]? Does the proxy survive the death or incapacity of the holder who gave it [Civil Code on the end of a mandate: to confirm], and bind heirs and buyers who adhere? While the pool is dormant, the sole holder signs a standing proxy to whoever is interim Founder Representative under the fixed rule, given also in the interest of the company and the Prozente, meant to survive death and incapacity until a single heir adheres or the holders elect a Founder Council (Pool Constitution Arts. 13.1, 14.3, 14.7): is that valid, and can the independent proxy holder in SHA 5.1B act as interim Founder Representative for the Required Matters only (Pool Constitution Art. 14.3 (e))? The same for the AE's Class A shares under Law 4548/2018 (the Board majority: I-78). If the counting rule fails, a Holder who votes its own Class F shares owes a penalty and specific performance (Pool Constitution Art. 3.5). (b) **Free transfer with adherence.** Can the articles waive the right of first refusal, the Art. 5.3 approval and the Qualified Majority for admitting a shareholder, for founder-pool shares only (Art. 5.7), including in the Interim Period, when no Art. 6.5 matter can pass? Registration may be conditional on adherence for voluntary transfers between living persons (Law 4072/2012 Art. 84(2)); death, seizure and bankruptcy follow Law 4072/2012 Arts. 85 and 88 (all verified; I-55), and the vote on pledged and usufruct shares follows Law 4072/2012 Art. 75(4). Do the commitments bind donees, pledgees and buyers in enforcement or insolvency? Is it valid to staple the AE's Class A shares to the IKE's Class F shares so they pass together in proportion (Pool Constitution Art. 9.2), and does this restrict transfer under Law 4548/2018? (c) **Forced heirship.** Superseded by I-92. (d) **Legal form.** A pooling and voting agreement among holders who each own their shares directly (Pool Constitution Art. 16.1), or a civil partnership (αστική εταιρεία) holding the shares as the one registered shareholder (Pool Constitution Art. 16.2)? Compare legal personality and publicity, the share and beneficial-owner registers (Law 4557/2018; I-68), donation and inheritance tax on transfers (Law 2961/2001), tax transparency of dividends, and the fit with the 50% rule and the Interim Period. Duration and continuation: I-91. (e) **Oversight.** The Founder Representative may ask the managers to pause or stop an Agent (Art. 11A.2A). Does a shareholder's representative who oversees Agents in this way risk being treated as a de facto manager, with a manager's liability? May an IKE's shareholders give the managers binding instructions of this kind? Is the Founder Representative a natural person "overseeing" an AI system under Art. 14 of the AI Act (I-38)? (f) **Founder Parties.** Every independence and conflict rule applies to every holder of founder-pool shares, anyone who controls one, the Founder Representative, the members of the Founder Council and the Council of Sections, and the Founding Person (Art. 4.2E; AMKE Art. 2.2). Is that workable once the pool has many holders, for example many heirs, and should the Close Associate test in the AMKE statutes be narrowed to the Founder Representative and holders above a threshold (bracketed for the owner)? (g) **Change of control.** Is the Investors' tag-along on a buyer of more than half of the Class F shares (Art. 5.4A, SHA 9.1A) enforceable against a buyer not yet a party, by making the sellers condition their sale on the buyer's offer? (h) **Vesting that travels.** Unvested Class F shares, and Reserve Shares given away without payment other than grants as pay for work, stay subject to the Founding Person's leaver terms in the donee's hands (SHA 6.1, 6.2A; Art. 4.2D Sales and grants). Is that enforceable against a donee, and is it a restraint on free transfer? (i) **Arbitration.** Does the arbitration clause in Pool Constitution Art. 15 bind later holders and heirs through their written adherence [Code of Civil Procedure Arts. 867 ff.: to confirm]? (j) **Large sales.** Is a mandatory referendum on a sale giving one buyer more than [●]% of the Class F shares, followed by a [60]-day right of the other holders to buy at the same price (Pool Constitution Art. 9.3), compatible with free transferability, or a pre-emption right that must appear in the articles?
- *Why it matters:* The Founder's 50%, the block vote, the independence of the Prozente and the Pensionskasse, and the investors' protections all rest on the pool acting as one, whoever its holders become.
- *Draft assumes:* (a) the block is set in the articles as far as Law 4072/2012 allows, backed in every case by the pooling agreement and an irrevocable proxy; (b) free transfer with registration conditional on adherence, Class A stapled to Class F [owner may confirm]; (d) a pooling and voting agreement, with a civil partnership as the alternative if counsel advises it; (e) the Founder Representative oversees as the Founder's representative, and the managers keep their responsibility and act on a lawful request; (f) the wide definition, the narrowing bracketed for the owner; (g) to (j) as drafted, bracketed where the owner may confirm. While there is one holder (at incorporation, the Founding Person), the Pool Constitution is dormant and that holder is the Pool Assembly, the Founder Council and the Founder Representative (Pool Constitution Art. 13).

**I-41. Safeguards inside the founder pool (Arts. 4.2E Founder Parties, 5.4A, 5.7; AE Art. 7.4; SHA 3.4, 5.1B, 6.1 to 6.2A, 9.1A; AMKE Art. 2.2; Pool Constitution Arts. 1.6, 7.4, 7.7, 9.3, 10.1, 10.6, 11.1, 12.1, 14.3).**
- *Question:* (a) **Lookback.** A person who was a Founder Party in the previous [3] years stays one for the independence rules, a Connected Person and in the Founder's Circle (Art. 4.2E; AMKE Art. 2.2; SHA 5.1B), so that a short holding cannot be used to qualify as independent. Is the lookback valid in the articles and the AMKE statutes, and is [3] years proportionate? (b) **Class B held by Founder Parties.** Answered by I-71 (Class B-X). (c) **Indirect change of control.** Acquiring control of a holder that is a legal person counts as acquiring its founder-pool shares for the large-sale referendum and the Investors' tag-along, and such holders report a change of control within [14] days (Arts. 5.4A, 5.7; SHA 9.1A; Pool Constitution Art. 9.3). Is that enforceable against the acquirer, who is not a party? (d) **Head counts.** Persons acting in concert, controlled persons, nominees and spouses count as one holder, and small or recent holders do not count as heads (Pool Constitution Art. 1.6); recognition of a Section is a right once its criteria are met, with an appeal to the arbitrator (Art. 12.1). Is this consistent with equal treatment of holders, and arbitrable? (e) **Defaults.** When a ballot on a block vote cannot end in time, or a mandatory ballot fails or ties, the block abstains or votes against (Pool Constitution Arts. 10.1, 10.6); a failed election goes to the arbitrator (Pool Constitution Art. 7.7). Can that arbitrator appoint an interim Founder Council or Representative on the request of heirs, executors, the company's managers or the AMKE, who are not parties to the pool (Pool Constitution Art. 14.3 (d))? (f) **Leaver reach.** The leaver terms reach shares the Founding Person gave away without payment [in the [12] months before the bad-leaver date, or at any time while unvested], other than grants of Reserve Shares as pay for work (Art. 4.2D Sales and grants; SHA 6.1 to 6.2A); see I-40 (h).
- *Why it matters:* Free transfer multiplies holders; without these safeguards the 50% block, the investors' protections and the independence of the Prozente and the Pensionskasse could be reached through former, controlled or straw holders.
- *Draft assumes:* each safeguard as drafted, bracketed where the owner may confirm.

**I-42. The brand held by the founder pool and licensed to the IKE (Arts. 1.1, 1.1A, 4.2D Votes, 4.2E, 6.5; AE Art. 1.1; SHA 2.3A, 2.4A, 5.1, 5.1E; IP Clauses 1.1, 2.2, 6, 7.1; Pool Constitution Arts. 2.3, 2A, 10.2, 14.6, 16.3; Brand Licence, agreements/09; Trama brief, filings/06).**
- *Question:* (a) **Registered owner of the marks.** The founder pool has no legal personality (Pool Constitution Art. 16.1). Who can be the applicant and registered owner of an EU trade mark (EUIPO) and a Swiss mark (IPI) for it: the Founding Person in own name as fiduciary (fiducia) or mandatary without representation for the pool, all holders jointly as co-owners, or only a vehicle with legal personality such as a civil partnership (Pool Constitution Art. 16.2)? Can the register show that the mark is held for the pool? Is a later transfer to the vehicle a simple recordal, and is it taxable? (b) **Registrant of the domain.** The same for the .io domain: can the registrant be a fiduciary for the pool under the registry's terms, and do those terms allow the licensee full control of the registrar account and DNS (Brand Licence Clause 4)? (c) **Protecting the pool against the holder of record.** Does the fiduciary arrangement keep the Brand Assets out of the Founding Person's estate, personal creditors and insolvency, and out of forced heirship (I-92)? A contractual ban on disposal binds only the parties (Civil Code Art. 177). Is the irrevocable power of attorney to the Founder Representative to transfer them to a new holder of record (Pool Constitution Art. 2A.3) valid, and does it survive death and incapacity [Civil Code Art. 218 and the end of a mandate: to confirm]? If the Founding Person dies while the constitution is dormant, can the interim Founder Representative (Pool Constitution Art. 14.3), or the arbitrator on request, validly designate an interim holder of record and use that power before the heirs adhere (Pool Constitution Arts. 2A.3, 14.6), and will EUIPO, IPI and the .io registrar act on it against the estate? Is the IKE's advance authority to renew a registration or domain in the holder of record's name (Brand Licence Clause 5.1A) valid and accepted by those offices? Enforcement while dormant: I-93. (d) **Inseparability.** Can the Pool Constitution make the Brand Assets inseparable from the Class F shares, never divided among holders and never sold apart from the pool (Pool Constitution Arts. 2A.2, 2A.4, 16.3), consistently with free transfer of founder-pool shares and the law on co-ownership? (e) **Recording the licence.** The licence is recorded with the EUIPO and the IPI against each application (Brand Licence Clause 5.4; Reg. 2017/1001 Arts. 27, 28): what is needed, and what does recording give the IKE against a later transferee or a creditor of the holder of record? Can the IKE, as exclusive licensee, sue infringers in its own name with the consent given in advance (Brand Licence Clause 5.3)? Is the light quality-control clause (Brand Licence Clause 5.5) enough to keep the marks valid? Is the no-challenge clause (Brand Licence Clause 5.6) compatible with competition law? Can the Company and its sublicensees be bound to hold any nilware.io mark, logo or domain they create for the pool and assign it on request (Brand Licence Clause 2.1A; IP Clause 7.1)? (f) **Tax on a royalty-free licence between related parties.** The founder pool controls the IKE (Art. 4.2C). May the tax authority reprice a royalty-free licence from the Founding Person (or the pool's vehicle) to the IKE at arm's length (transfer pricing, Law 4172/2013 [to confirm]), creating deemed income for the licensor or a non-deductible benefit for the IKE? Does the IKE bearing filing, renewal and enforcement costs (Clause 5.2) count as consideration? Does anything change when investors arrive? Would a modest royalty (owner option, Clause 3.4) be safer, and how would it be set and documented? The accountant to advise. (g) **Distinctive title at GEMI.** Can the IKE register "nilware.io IKE" as its name and "∅ nilware.io" as its distinctive title when it holds only a licence, and what does GEMI need to see (I-60)? The same for the AE under its sublicence (AE Art. 1.1). The IKE's own rights in its name: I-94. (h) **Insolvency and sale of the business.** Does the licence survive the IKE's insolvency, liquidation or dissolution, and can the administrator or liquidator transfer it with the whole business to a buyer in which the Prozente continue (Art. 10A.5B; Brand Licence Clauses 3.5, 6.2)? Is the restriction on assigning it otherwise valid against the administrator? Does the licence survive the insolvency of the holder of record? (i) **Ending only for a Prozent Breach.** Is a perpetual licence that the licensor cannot end except on one ground, established by an arbitrator after notice and a cure period (Brand Licence Clauses 6, 7), valid under Greek contract law, or can it be ended for important reason (σπουδαίος λόγος) regardless [Civil Code: to confirm]? Founder Parties hold half the IKE's votes and propose its managers, so they could cause a Prozent Breach themselves. The draft bars the Founder from relying on a breach that a Founder Party, or a manager it proposed or nominated, caused, voted for or procured (specific performance only), lets the AMKE, any Investor or the independent proxy holder cure on the IKE's behalf at its cost, and has the IKE represented in a Clause 7 dispute only by managers who are not Founder Parties, the independent proxy holder or an Investor Majority nominee, with the AMKE able to join (Clauses 7.1, 7.2, 10.2; SHA 5.1E). Are a third-party cure, that limit on who represents the IKE, and joinder of the AMKE valid? (j) **The change of name.** If the licence ends, can the IKE be made to change its name within the transition period by the shareholders' voting undertaking and proxy (SHA 5.1E), and can the change pass in the Interim Period with the independent proxy holder voting the Reserve Shares (Arts. 1.1A, 4.2D Votes, 6.5)? (k) **Swiss law.** Does recording the licence with the IPI under the Swiss Trade Mark Protection Act (MSchG) need anything beyond the EU recordal, and is the US (Madrid) option affected by holding for a pool? Signing for the IKE: I-95.
- *Why it matters:* The brand must stay with the Founder, whoever holds the founder pool, while the IKE, its investors and the Prozente rely on using the name for as long as the IKE honours the Prozente, through an exit or an insolvency too.
- *Draft assumes:* (a) and (b) the Founding Person applies and registers in own name, holding for the founder pool, until the pool has a vehicle (filings/06 asks Trama how to name the applicant); (c) and (d) as in Pool Constitution Art. 2A, bracketed where to confirm, a disposal in breach being a breach and valid towards third parties as the law provides; (e) the licence is recorded against each application as soon as it is filed, the IKE may enforce in default, light quality control; (f) royalty-free, the IKE bears the costs, a royalty bracketed as an owner option; (g) registrable with the licence; (h) the licence survives and passes only with the whole business to a buyer in which the Prozente continue, as far as mandatory law allows; (i) to (k) as drafted.

**I-43. The Founding Person's work: exclusivity or contribution, the first product, and the Founding Person as an Agent (Arts. 4.2D What the AE's rules forbid, 4.2E Founding Person, 6.5, 10A.9 Members, 10A.9D Founder Parties as members and company seats, 11A.2A, 11A.7, 11A.11, 11A.12; SHA 2.2A, 2.3B, 3.3, 5.1, 6.0, 6.3 to 6.5, Schedule 2; IP 7.3, 7.4; Agent Policy 1.3, 2A, 3.3, 4.5; AMKE Arts. 2.2, 11.2, 13.1, 19.3, 24.2, 24.3A, 24B; Pool Constitution Arts. 1.4, 8.3).**
- *Question:* (a) **Social security (EFKA).** The Founding Person is the sole manager, the holder of the founder pool and a contractor working for clients through the IKE. Is the Founding Person insured as the manager of an IKE, as a self-employed person (ελεύθερος επαγγελματίας) invoicing the IKE, or as a salaried person if the engagement is reclassified? Does being manager and Agent at once create a double contribution, and can the written terms as an Agent be a services contract (σύμβαση έργου or ανεξάρτητων υπηρεσιών) with one's own company? (b) **Tax of the personal contributions.** Are the 1% payments to each AMKE Prozent Account and to the Pensionskasse deductible from the Founding Person's income, a donation to a non-profit (with any donation-tax or credit consequence under Law 2961/2001 and the income tax code [to confirm]), or neither? Is the 1% paid to the IKE's Kassenfonds a capital contribution, a donation to the company or income of the IKE (I-99 (e)), and how does the IKE book it so that it is not revenue that triggers the Prozente again? Is the Pensionsprozent part a pension contribution for anyone, given that it is not credited to the Founding Person's own account? (c) **Enforceability.** Is the exclusivity-or-contribution clause valid and enforceable as a personal obligation in the SHA, as a contract for the benefit of the AMKE, the Pensionskasse and the IKE, and could or should it also appear in the IKE Articles? Is a permanent obligation lasting while the Founding Person earns work income (possibly after leaving) compatible with Greek law on economic freedom and on contracts of indefinite duration and with the Civil Code rules on excessive restraint [to confirm] (an excessive restraint is reduced to the lawful scope, SHA 12.4)? Is the yearly statement verified by the AMKE's auditors, with confidentiality, compatible with the GDPR? Is the narrowed non-compete (a directly competing business only, [12] months after leaving) reasonable? (The shareholders' permission for outside work while a manager is IKE Art. 8.2C.) (d) **Misclassification.** If the Founding Person, an Agent who is a person working mainly for one client, the IKE, is in substance an employee, Art. 11A.7 treats the Founding Person as one from the start. How do the presumptions of Greek labour law (including Law 4808/2021) and of Directive (EU) 2024/2831 apply to a sole manager and controlling holder? Can a person who controls the company be its employee at all, and if not, what does Art. 11A.7 give the Founding Person instead? (e) **Related-party pay in the Interim Period.** In the Interim Period no Art. 6.5 matter may pass (Art. 4.2D), so the draft adds bracketed exceptions for the Founding Person's written terms as an Agent, set by the Supervisor and approved by a majority of the Independent Votes at an arm's-length rate confirmed by the accountant or an adviser outside the Founder's Circle (Art. 11A.12 Pay), and for the pay as General Director (Art. 8.2B, I-47). Is that valid under Law 4072/2012 rules on transactions with managers or partners [to confirm], is the AMKE's independent vote a suitable approver, and does a transfer-pricing review apply? (f) **Enforcing the Kassenfonds part.** Can the AMKE, by decision of its Board, enforce the IKE's Kassenfonds claim against the Founding Person on the IKE's behalf while the Founding Person is a manager (SHA 6.3A) [mandate or representation: to confirm]? (The Supervisor: I-45.) (g) **Pensionskasse seats.** A member who is a Founder Party does not stand for or hold a members' seat [or vote in the election] (Art. 10A.9D); is that compatible with equal representation (Art. 51 BVG, by analogy) and Greek law, the basis being the Founder Party role and not membership or the Agent role [the whole bar: owner to confirm]? While no member is outside the Founder Parties, the members' seats are held by appointees of the AMKE's Board outside the Founder's Circle (in the Bootstrap Period, from the trusted circle, I-46). No Founder Party holds a company seat while a Founder Party is a member, decisions on benefit rules or the group plan that affect a Founder Party member are taken without Founder Parties, and while the Founding Person is the only member the benefits are the group plan's standard terms at the guaranteed minimum: is that a lawful restriction on the shareholders' right to appoint the company's representatives? (h) **Work Income.** Fees for the Founding Person's work paid to a controlled entity count, without counting again what that entity pays out of them; gross means net of VAT, before income tax and social contributions; royalties count when received [including on works created before the Agreement and on personal projects: owner to confirm], but royalties on IP assigned to the IKE are the IKE's revenue (SHA 6.3). Is the look-through enforceable, and does the IP Assignment's rule that outside work is not assigned whatever happens to the contributions (IP 7.4) leave the AMKE and the IKE an adequate remedy under SHA 6.3A alone?
- *Why it matters:* The company starts as the Founding Person's contracting work. If that work is not insured, taxed and approved correctly, the first product fails; if the contribution clause cannot be enforced or is taxed twice, the promise that all work income carries the Prozente weakens.
- *Draft assumes:* (a) the accountant advises before the first invoice; (b) the accountant confirms the treatment before the first payment (SHA 6.3B); (c) a personal obligation in the SHA, enforceable by the AMKE, the Pensionskasse and the IKE, with duration and scope bracketed for the owner; (d) Art. 11A.7 applies as written, as far as the law allows; (e) the bracketed exceptions in Arts. 4.2D and 6.5; (f) to (h) as drafted, bracketed where the owner may confirm.

**I-44. Reserve Shares sold, granted and forcibly converted into AE shares (Art. 4.2D Sales and grants, Conversion; Arts. 4.2E, 5.2, 5.3, 5.6(e), 6.6 Limits; AE Arts. 1.2A, 4.3A; SHA 2.4A, 3.2, 3.4, 4.3, 6.2A, 7.1, 12.3; Pool Constitution Arts. 1.2, 5.4, 5.6, 9.2, 9.3).**
- *Question:* (a) **Contribution in kind.** Answered by I-72 (valuation under Law 4548/2018 Arts. 17, 18, 27(3), 35(2), verified, the Conversion Ratio as a maximum); pre-emption does not extend to the conversion shares (Law 4548/2018 Art. 26(1); AE Art. 5.2). (b) **Tax on the exchange.** Is the exchange of IKE shares for AE shares a taxable disposal for each holder (capital gain under Law 4172/2013), or does a share-for-share relief apply [Law 4172/2013 Arts. 54 ff.: to confirm]? How are a sale of Reserve Shares by the Founding Person (capital gain), a grant to an Agent or employee (income from work, or a donation) and a gift (Law 2961/2001) taxed, and does vesting change the timing? Does the AE owe any transfer tax or capital-concentration duty? (c) **Forced conversion.** Can the IKE Articles bind every holder of Reserve Shares, including buyers, grantees, heirs, pledgees and buyers in enforcement or insolvency who adhered, to contribute their shares at the Qualifying Closing, carried out through the irrevocable proxy in SHA 2.4A against a holder who does not sign? Is it enforceable against a holder who acquired by enforcement without adhering, and against an insolvency administrator? (d) **Holders outside the pool.** A buyer or grantee of Reserve Shares is not, by that alone, a holder of the founder pool or a Founder Party (Arts. 4.2D, 4.2E). Is disapplying the right of first refusal and the Art. 5.3 approval for every disposal of Reserve Shares valid (Arts. 5.2, 5.3, 5.6(e))? Does an angel or employee holding IKE shares before the AE need anything beyond adherence (prospectus or crowdfunding rules if many are sold, employee share-plan rules) [to confirm]? (e) **Class B for converted holders.** If converted holders receive Class B pari passu with the round's investors, what is their "amount invested" for the liquidation preference (the valuation of the contribution?)? (The excluded conversion shares: I-71.) (f) The founder pool's Reserve Shares: I-49. (g) **Option pool.** Grants of Reserve Shares with vesting serve as an option pool before the AE (SHA 7.1): can unvested shares return to the grantor without a transfer tax, and do they convert at the closing subject to the same vesting in AE shares (Art. 4.2D Conversion; AE Art. 4.3A), the return right then held [by the grantor / by the AE: owner to choose]? If by the AE, is the return an acquisition of own shares under Law 4548/2018 Art. 49?
- *Why it matters:* The owner wants to reward buyers, angels, Agents and employees with the founder's own shares before any round, without changing a vote and without leaving anyone but the AE as a holder of those shares once investors arrive.
- *Draft assumes:* (b) the accountant confirms the tax of each sale, grant and the exchange before it is made; (c) the obligation binds every holder through the articles and its adherence, backed by the proxy, penalty and specific performance in SHA 5.1B; (d) as drafted; (e) [Class B pari passu: default / separate class] for the owner to choose in the term sheet, the excluded conversion shares never counting for Class B majorities, the Investor Majority or the Class B seat; (g) vesting carries over to the AE shares, the holder of the return right bracketed for the owner. The 40% floor limits only the creation of new Prozente; sales, grants and the conversion do not reduce it (Art. 6.6 Limits).

**I-45. The AMKE as the Founding Person's Supervisor (Arts. 8.2B, 10A.9D, 11A.2A, 11A.11, 11A.12; SHA 6.3A, 6.4, 6.5; Agent Policy 1.3, 2A, 3.3, 4.5; AMKE Arts. 2.2, 21.1, 24.3A, 24B).**
- *Question:* (a) Is supervising a company's Agent (the Founding Person's limits, pay as an Agent, review, stopping and offboarding) on written terms with nilware.io IKE, at the IKE's cost, compatible with the AMKE's non-profit purpose (AMKE Art. 3) and its tax status, and is the reimbursement or any pay to the member acting income of the AMKE? (b) Do the AMKE, its Board or the member acting risk being treated as a de facto manager of the IKE, or as an employer, with the corresponding liability? Does the member become Group Personnel (AMKE Art. 2.2) by acting, as AMKE Art. 24B.8 brackets? (c) Where Greek labour law or Directive (EU) 2024/2831 requires a natural person to decide on a natural person's engagement, pay or discipline, does an AMKE member who is a natural person, acting for the AMKE, meet it (I-38 (d))? (d) Is it consistent with the independence of the AMKE's Prozent votes (IKE Art. 6.4A) that the AMKE supervises the Founding Person, and that its members outside the Founder's Circle, as the Supervision Committee (AMKE Art. 24B.6), may take over a decision where the Supervisor has a close tie or a stake? Can that committee validly take a decision from a conflicted Supervisor, given one partner, one vote? (e) Does the role conflict with the AMKE's own interest in the Founding Person's contributions (SHA 6.3), which its Board also enforces?
- *Why it matters:* No Agent supervises itself, and the Founding Person must never be at the end of the chain for his own Agent work, while he is the General Director at the top of the chain for everything else.
- *Draft assumes:* the role is lawful within the AMKE's purpose as a means of agent welfare and accountability [to confirm]; the AMKE and its members do not become managers of the IKE; escalation goes to the AMKE's Board or General Assembly; in the Bootstrap Period the Supervisor may come from the trusted circle (I-46).

**I-46. The Bootstrap Period and the phased segregation (Art. 9B; Arts. 10A.9D, 11A.12; SHA 5.1B; AMKE Arts. 2.2, 13.4A, 19.3, 19.3A, 21.1, 22.3A, 24.2, 24.3A, 24B.7, 30.2, 30.6).**
- *Question:* (a) Is it compatible with IKE Art. 6.4A (Prozent votes suspended while a Founder Party or a manager sits on the holder's governing body) and with the AMKE's independence (AMKE Arts. 1.2, 15) for relatives, Close Associates or Group Personnel of the Founding Person to sit on the AMKE's Board and decide its Prozent votes? Founder Parties, managers, AE directors and anyone they control stay out of the trusted circle. (b) Can relatives or Close Associates of the Founding Person hold or stand in for the members' seats on the Pensionskasse board, consistently with equal representation (Art. 51 BVG by analogy) and the duty to the members, given the hard line that no pension member's rights are decided by someone who would benefit? (c) Is an independent proxy holder from the trusted circle independent enough for an irrevocable proxy given also in the interest of the other parties (SHA 5.1B), and for the neutral rule (Art. 4.2D Fallback)? (d) Are the published register of close ties and the recusal rule lawful under the GDPR (AMKE Art. 21.1; AMKE note A-18), and are the schedule with cure periods, and the default that the AMKE's General Assembly fills a role not segregated in time [owner to confirm], enforceable? (e) Does Greek law require the AMKE's Board, its Auditors or the Pensionskasse board to be independent from the start, regardless of these statutes? (f) **Successor proxy holder.** When the proxy holder must be replaced (Art. 9B.4, death, incapacity or resignation), [the AMKE's General Assembly without Founder Parties / the President of the Athens Bar Association] names a successor, and every party and holder of Reserve Shares re-grants the irrevocable proxy within [14] days (SHA 5.1B). Can an irrevocable proxy be granted in advance to whoever holds the office from time to time (Civil Code Art. 218), and is a re-grant enforceable by specific performance (Code of Civil Procedure Art. 949) against a holder who refuses?
- *Why it matters:* A company starting with the Founding Person and Agents has too few outsiders to fill every independent role; the bootstrap lets it start, and the hard lines keep the pension money, the Prozente and the votes of the AMKE and the Pensionskasse out of the Founder's reach throughout.
- *Draft assumes:* each hard line holds in every state; the bootstrap does not begin again; Independent Votes, the Fallback and the Qualifying Closing keep requiring persons outside the Founder's Circle (Art. 9B.3).

**I-47. The General Director (Arts. 4.2D What the AE's rules forbid, 6.5, 8.2, 8.2B, 11A.2A, 11A.12; SHA 2.4A Consents, 5.1, 6.5).**
- *Question:* (a) May a manager (διαχειριστής) of an IKE use the title "General Director" (Γενικός Διευθυντής) in GEMI filings, letterheads and contracts under Law 4072/2012 without suggesting an AE board structure or a separate employment as general manager, and must the title appear in the articles? (b) How is a manager's pay treated for tax and EFKA next to the Agent fees (I-43 (a)), and is approval by a majority of the Independent Votes in the Interim Period, and with the Investor Majority's consent afterwards, a valid related-party approval (bracketed in Art. 4.2D, What the AE's rules forbid; the count: I-51)? (c) Does keeping the two hats apart (Art. 8.2B) hold if the managers' duties under Art. 8.3 make the General Director answerable for all supervision in the company?
- *Why it matters:* The Founding Person runs the company but must not decide his own Agent terms or pay.
- *Draft assumes:* the title is usable [to confirm]; removal follows Art. 8.1; both pays are related-party matters at arm's length, and the written terms say which work is paid as General Director and which as an Agent. The Founder undertakes in SHA 6.5 that the Class F votes on either pay, and on the Founding Person's written terms as an Agent, are cast only as Art. 8.2B provides.

**I-48. Bootstrap hard lines on the Founding Person's own matters (Arts. 9B.2, 9B.3, 10A.9A Insured salary, 10A.9D, 11A.2A No cycles, 11A.12 Pay, Supervisor, Conflicts; Agent Policy 2A.3; AMKE Arts. 13.4A, 15.3, 15.5, 21.3, 24B.6, 24B.7, 30.6).**
- *Question:* (a) Is a "personal stake" limited to the person's own interest or that of their household or an entity they control (Art. 9B.2; AMKE Art. 30.6), so that a disclosed tie to the Founding Person is not by itself a conflict, a sufficient conflict standard under AMKE law and for the related-party approvals of the Founding Person's pay (Art. 6.5; Law 4072/2012) [to confirm]? (b) Is the bar on Connected Persons (spouse, registered partner, relatives up to the [second] degree) acting as Supervisor or deciding or voting on the Founding Person's pay, terms or offboarding, including through the AMKE's and the Pensionskasse's Independent Votes, workable where the AMKE's Board is small, and does the fallback to the Board without the conflicted person or to the General Assembly without Founder Parties (AMKE Art. 24B.6) satisfy AMKE law on quorum and members' votes? (c) Can a Founder Party's insured salary be capped at an arm's-length rate confirmed by the accountant or an outside adviser (Art. 9B.3) without breaching the equal treatment of members or the group plan's terms? (d) If the default barring Connected Persons serving in the bootstrap from deciding the AMKE's nilware.io votes (AMKE Art. 15.3, bracketed for the owner) leaves the AMKE's Board with no one who may decide, does Art. 6.4A suspend its Prozent votes, and does the Fallback apply?
- *Why it matters:* Without these lines, the Supervisor or the people approving the Founding Person's pay could be people he supervises, pays or is related to, and inflated pay would raise his pension credits out of the shared 1%.
- *Draft assumes:* each line holds in the Bootstrap Period too; Group Personnel never decide under AMKE Art. 24B (and the one-seat cap in AMKE Art. 15.5 applies to those decisions); the arm's-length confirmation in Art. 11A.12 (Pay) comes from outside the Founder's Circle.

**I-49. Non-voting Class C shares for the founder pool's Reserve Shares (Art. 4.2D Conversion; AE Arts. 1.2A, 4.3A, 4.3B, 6.1, 6.2, 7.4, 7.5, 7.6, 8.2, 10.4, 11.2; SHA 2.4A Conversion, 3.1A, 3.2, 3.4, 4.3, Schedule 1; Pool Constitution Art. 5.6).**
- *Question:* (a) **A non-voting class.** Answered by I-69. (b) **Votes the law keeps.** Answered by I-75. Can the articles also exclude Class C from the quorum and majority of every General Meeting resolution (the AE Art. 7.5 two-thirds and the AE Art. 7.6 unanimity included, counted on the shares that carry votes) and from the Qualifying Closing minimum? (c) **Conversion into Class B on transfer.** Can the AE Articles provide that a Class C share converts one for one into Class B at the request of a qualifying buyer outside the Founder's Circle (decision 16), certified to the Board on request (AE Art. 4.3B, SHA 3.4), without a General Meeting resolution each time: is that an amendment of the articles, a change that needs a Class B class meeting (whose class grows), or an automatic conversion authorised in advance [to confirm]? Does a converted share take the Class B liquidation preference "up to the amount invested", and what is that amount for a share first issued for a contribution in kind (I-44 (e))? Can the articles test the buyer's price, nominee status, side agreements and financing in this way, rely on its certificate, and treat a share whose holder later fails the test as an excluded conversion share? (Holder-dependent Class B votes: I-71.) (d) **Free transfer.** Can AE Arts. 6.1 and 6.2 (pre-emption on transfer, Board approval) be disapplied for Class C only? (e) **Tax.** Does issuing Class C rather than Class B to the founder pool change the tax of the exchange (I-44 (b)), and is the conversion of Class C into Class B a taxable event for the buyer or the AE? (f) **Cash option.** Can the cash price be limited to what the round's terms provide, elections cut back in proportion and the rest converted into Class C (SHA 3.2), so that the AE never owes a deferred balance ahead of the Class B liquidation preference? (Law 4548/2018 Art. 19 approval: I-70.) (g) **Subscriptions below the minimum.** Can Class B subscriptions at a closing be conditional on the Qualifying Closing minimum being reached at that closing (counted [after / before: owner to choose] deducting any cash price for Reserve Shares), the money held in the AE's special capital account (Law 4548/2018 Art. 20(2)-(3)) and refunded if the minimum is not reached by [date] within the payment period (Law 4548/2018 Art. 28(1); both verified), given that an AE formed for the round needs paid-up capital of at least €25,000 at formation?
- *Why it matters:* If investors buy only part of the round, the founder pool keeps the value of the rest without gaining AE votes that could outvote the investors on their protections. That works only if the class is lawful and truly non-voting, and if conversion into Class B in a buyer's hands cannot bring the pool's stake back into the investor vote.
- *Draft assumes:* Class C as in decision 16 and AE Art. 4.3B (with the owner's two options for its economic rights, I-69), never ranking ahead of the Class B priorities and voting only in a separate class vote the law requires; (c) conversion into [Class B: owner to confirm] for a qualifying buyer, counted for Class B votes only while so held, with no anti-dilution adjustment (SHA 4.3); (d) as drafted; (e) the accountant confirms; (f) as drafted; (g) conditional subscriptions in escrow, refunded if the minimum is not reached by [date], the alternative bracketed for the owner. The round must reach the minimum through outside investors alone (SHA 3.1A); otherwise nothing converts.

**I-50. Voting the Reserve Shares on a new Prozent, and the voting undertaking in every case (Art. 4.2D Votes, New Prozente; SHA 2.4A Reserve Shares, Deadlock, 5.1B).**
- *Question:* Law 4072/2012 Arts. 68(2)(a) and 72(5) count the two-thirds for an amendment on the total number of shares (verified on the consolidated text as amended up to Law 4541/2018; later amendments not checked). In the Interim Period only 560 of the 1,000 shares vote, so an amendment creating a new Prozent can pass only if the Reserve Shares are voted. The independent proxy holder casts their votes for that amendment, once the Prozent is approved under Art. 4.2D (New Prozente), as for a Required Matter and the change of name (Art. 1.1A). (a) Can the proxy holder validly cast, for these purposes only, votes of shares the articles make voteless [Civil Code Art. 218: to confirm]? (b) Each holder's undertaking not to vote the Reserve Shares other than through the proxy holder applies in every case, not only if the class without votes is invalid (SHA 2.4A). Is that unconditional undertaking, with the penalty and specific performance of SHA 5.1B, enforceable against buyers, grantees and heirs who adhere? (c) Has any amendment after Law 4541/2018 changed Law 4072/2012 Art. 72(5)?
- *Why it matters:* Without the proxy holder's votes no new Prozent can be created before the AE exists. And if a court annulled the class without votes only later (Law 4072/2012 Art. 74), an undertaking that applied only on invalidity would leave 440 shares free to vote in the meantime.
- *Draft assumes:* the two-thirds is counted on the total number of shares; the proxy holder, never a Founder Party, casts the Reserve Shares' votes only on a Required Matter, the change of name and an amendment creating a Prozent already approved under Art. 4.2D; the undertaking and irrevocable proxy bind every holder whether or not the class is valid. A consequence, which the owner accepts, is that before the AE nothing else needing two-thirds of the capital can pass (the Founder and all six Prozente hold 560 of 1,000), other than what Art. 4.2D (What the AE's rules forbid) allows.

**I-51. Pay of the General Director and discharge of the Founding Person (Arts. 4.2D Fallback, 8.2B, 11A.12 Pay; SHA 2.4A Consents).**
- *Question:* A manager is unpaid unless the articles or a partners' decision provide otherwise (Law 4072/2012 Art. 64(4)), and a partners' decision needs an absolute majority of the total number of shares (Law 4072/2012 Art. 72(4)), 501 of 1,000. The law bars a partner's vote only on its own discharge, on a special representative against it and on its exclusion (Law 4072/2012 Art. 72(3)); it requires no abstention on pay (all verified). The Founder Representative casts the Class F votes on either pay only as a majority of the Independent Votes cast has decided (Interim Period) or with the Investor Majority's consent (after the Qualifying Closing), under a voting undertaking in SHA 6.5; the Founding Person takes no part, as manager, in the management decision on either pay. (a) Is a resolution passed in this way a valid partners' decision under Law 4072/2012 Art. 64(4), and the approval under Law 4072/2012 Art. 95(2)? Is the undertaking tying the Class F votes to the Independent Votes enforceable? (b) On the Founding Person's own discharge, Law 4072/2012 Art. 72(3) bars the Class F votes. Are the barred shares disregarded in the Law 4072/2012 Art. 72(4) count? The statute says so only for the vote cap in Law 4072/2012 Art. 72(2). If not, the proxy holder's 440 votes and the 60 Prozent votes make 500, one short of 501.
- *Why it matters:* If the Founding Person simply abstained from every decision on pay, at most 60 votes would be cast and no partners' decision on pay could reach 501.
- *Draft assumes:* pay is approved as above; discharge is optional (Law 4072/2012 Art. 67(2)), so if the barred shares are not disregarded the Fallback cannot produce the Founding Person's discharge and none is given in the Interim Period. Adds to I-47 (b).

**I-52. The Prozent contributions and the shares of their holder (Arts. 4.2A, 10A.1 to 10A.3A, 10A.5, 10A.9; SHA 11.0).**
- *Question:* The AMKE is a partner (it holds all 60 Prozent and pool shares) and receives 4% of revenue for the four AMKE Prozente and 1% for the Pensionskasse, every year, in loss years too, with no counter-performance. Only profits shown in the annual accounts may be distributed (Law 4072/2012 Art. 100(3)); extra profit rights need the articles and last at most ten years (Law 4072/2012 Art. 100(4)); a partner repays what it received in breach, hidden payments of profit included, and creditors may claim it by indirect action (Law 4072/2012 Art. 100(5)-(6)) (verified). The draft makes each contribution the company's own obligation under a written Prozent Agreement with the body carrying the Prozent's purpose, owed to it in that capacity whether or not it holds shares, and not a distribution, a return of contributions or a right attached to any share (Arts. 10A.3, 10A.3A). (a) Is that enough to keep the payments outside Law 4072/2012 Art. 100(6), given that the articles still give each Prozent's holder shares equal to 1% (Art. 4.2A) and tie permanence to those shares (Art. 10A.5)? (b) Would it be safer for the money to go to a body that is not the shareholder (for example the AMKE keeping the shares and a separate purpose vehicle receiving the contributions)? (c) Is a reading as an extra profit right under Law 4072/2012 Art. 100(4), with its ten-year limit, excluded? (Characterisation: I-88; deductibility: I-67.)
- *Why it matters:* If the payments are a hidden distribution, the AMKE must repay them and creditors can claim them; if they are an extra profit right, they end after ten years. Either defeats permanence.
- *Draft assumes:* the contributions are owed under the Prozent Agreements as the company's own expenses, with an agreement signed for the four AMKE Prozente before the first payment, as for the Pensionsprozent (Art. 10A.9B); no contribution is paid while the company is in threatened inability to pay its debts (Law 4072/2012 Art. 102) or where payment would frustrate its creditors (Law 4072/2012 Art. 95(3)), the amount staying owed (Art. 10A.3; I-53).

**I-53. Contributions when the company is in difficulty (Arts. 10A.3, 10A.5B, 10A.7, 10A.9C).**
- *Question:* The outflow contributions are gratuitous for the company. (a) Can contributions paid before a bankruptcy be avoided under Law 4738/2020 (Law 4738/2020 Arts. 117 ff. [to confirm]; headings of Law 4738/2020 Arts. 117 and 118 verified), and what suspect periods apply to gratuitous acts? (b) What is the rank of unpaid contributions in an insolvency: ordinary unsecured claims, or subordinated as gratuitous? (c) Does the part of the Pensionsprozent owed under members' written terms (Art. 10A.9C, Enforceable by members) rank as an employee claim? (d) Is a deferral while the company has ceased payments or is in the situation in Law 4072/2012 Art. 102 (verified), the amounts accruing and paid in full afterwards, consistent with permanence (Art. 10A.5)?
- *Why it matters:* "Priority" in Art. 10A.3 ranks the contributions only ahead of distributions to partners. Paying them while insolvent could be avoided later and expose the manager to liability.
- *Draft assumes:* the contributions have no priority over creditors; they are deferred, not reduced, while the company cannot pay its debts, [with interest at ●], and a deferral is not a lowering under Art. 10A.5; the Kassenfonds and the Kassenreserve stay assets of the company available to its creditors (Art. 10A.7).

**I-54. When transfers take effect, and the GEMI filing (Arts. 4.2D, 5.1, 10A.8).**
- *Question:* A transfer or encumbrance takes effect towards the company and the partners from the written notice signed by both parties (e-mail allowed), and towards third parties from its entry in the partners' book, not on GEMI registration (Law 4072/2012 Arts. 84(1), 66(1)(a); Law 4072/2012 Art. 84(1) verified). Under the current GEMI law (Law 4919/2022), must a change of partners of an IKE also be filed with GEMI, by when, and with what effect [unverified]? Does a single 0.1% pool sale need anything more?
- *Why it matters:* It fixes when a Prozent transfer, a pool trade, a Reserve Share sale or the conversion takes effect, and when the Interim Period ends.
- *Draft assumes:* effect as Law 4072/2012 Art. 84(1) provides; the managers enter a transfer in the partners' book as soon as the conditions are met and file any change the law requires with GEMI within [20] days (Art. 5.1); the Interim Period ends on entry in the partners' book [and any GEMI filing the law requires] (Art. 4.2D).

**I-55. Heirs of founder-pool shares and Reserve Shares (Arts. 4.2D Sales and grants, 5.6, 5.7, 5.9; Pool Constitution Arts. 5.6, 14.1).**
- *Question:* The articles may restrict transfers and encumbrances between living persons (Law 4072/2012 Art. 84(2)), so registration may depend on adherence for those. On death, the manager must register the heir without delay once the heir's right is checked (Law 4072/2012 Art. 85(1)); the articles may only provide a buy-out at full price by a person the company designates within one month of learning of the death (Law 4072/2012 Art. 85(2)) (verified). The drafts register heirs as Law 4072/2012 Art. 85(1) requires, bind them by the articles from registration and ask them to adhere, and keep an Law 4072/2012 Art. 85(2) designation only as the backstop for an heir who does not adhere [within [3] months] or is barred by Art. 4.2E. (a) Is a designation that lapses if the heir adheres in time valid, given the one-month deadline? (b) Can the articles suspend an heir's votes and distributions until the heir adheres? (c) Is the full-value method set in the articles (a valuer who is not a Founder Party) binding on the heirs? (d) Is the backstop consistent with the owner's rule that founder-pool shares are freely inherited?
- *Why it matters:* Managers who refuse a registration the law requires could be liable for it.
- *Draft assumes:* heirs are registered and asked to adhere; voluntary transfers between living persons stay conditional on adherence; the buy-out is a backstop only, for founder-pool shares to holders of founder-pool shares pro rata first [owner to confirm this backstop for founder-pool shares, or to have none] (Art. 5.9; the method of valuation is for the owner to fix there).

**I-56. Pre-emption on capital increases (Art. 4.2B; SHA 5.1B).**
- *Question:* Every partner has pre-emption pro rata on a capital increase not in kind; it may be limited or abolished only by a resolution under Law 4072/2012 Art. 72(5), and if partners whose percentage falls object, Law 4072/2012 Art. 89(1) applies by analogy (Law 4072/2012 Art. 90(2), verified). Art. 4.2B fixes in advance who receives the new shares (Class F to 50%, each Prozent and the pool to 1%), so every increase resolution limits pre-emption as needed, and every SHA party undertakes, with the proxy, penalty and specific performance of SHA 5.1B, to vote for it. (a) Is an advance undertaking to vote for the limitation at every increase enforceable? (b) What does the objection rule in Law 4072/2012 Art. 89(1), by analogy, give a partner whose percentage falls? (c) Must the new Prozent and pool shares be paid in full in cash at the increase (Law 4072/2012 Art. 77(4)), and can the AE or another payer pay for them as a donation to the holder (I-26)?
- *Why it matters:* Without the limitation the statutory pro-rata right overrides Art. 4.2B and the Founder's exactly 50%.
- *Draft assumes:* each increase resolution limits pre-emption by the Law 4072/2012 Art. 72(5) majority under the undertaking, and the new Prozent and pool shares are paid in full in cash by the AE or another payer [or out of reserves: I-26].

**I-57. Unanimity for the amendment that creates a Prozent (Arts. 6.6, 10A.5, 10A.5C).**
- *Question:* Under Law 4072/2012 Art. 72(6), last sentence, introducing a higher majority or unanimity by amendment requires unanimity of the partners. The amendment creating a new Prozent makes the unanimity rule in Art. 10A.5 and the entrenchment in Art. 10A.5C apply to it. Is that "introducing" unanimity, so that the amendment itself needs every partner, or is it enough that Arts. 10A.5 and 10A.5C say, in the initial articles, that they apply to every Prozent, including any later one created under Art. 6.6?
- *Why it matters:* If Law 4072/2012 Art. 72(6) applies, a Prozent created by two-thirds alone might not be permanent.
- *Draft assumes:* Arts. 10A.5 and 10A.5C apply from the initial articles to every Prozent, so a later amendment adds a Prozent without introducing a new unanimity rule.

**I-58. Pool purchases and the company's own shares (Arts. 10A.8 Money, 10A.9B, 10A.9C).**
- *Question:* An IKE may not acquire its own shares directly or indirectly, and shares so acquired are cancelled automatically (Law 4072/2012 Art. 87, verified). The company funds the Pensionskasse and bears its shortfalls (Art. 10A.9C). Could a pool purchase be treated as an indirect acquisition for the company's account because of that guarantee, and what must be true of the money for it not to be (paid irrevocably to the holder, no risk or return for the company) [unverified]?
- *Why it matters:* Automatic cancellation would break the 1% band and the Founder's exactly 50%.
- *Draft assumes:* no pool share is bought with money still in the company's account (Art. 10A.9B, last paragraph) or not yet irrevocably paid to the holder, and the company bears no risk or return of pool shares (Art. 10A.8 Money).

**I-59. One partner voting in blocks (Art. 6.4A).**
- *Question:* All 60 Prozent and pool shares belong to one partner, the AMKE. Each share carries one vote (Law 4072/2012 Art. 72(2), verified), but the statute does not say whether one partner may cast its shares differently on the same resolution. May the AMKE cast the pension shares as the Pensionskasse board decides and the other Prozent shares as its own organs decide, and may the articles suspend the votes of only some of one partner's shares? If not, the AMKE casts one vote per resolution, and its statutes and the Pensionsprozent Agreement must set how the blocks combine.
- *Why it matters:* If split voting is not allowed, the managers' count is open to annulment (Law 4072/2012 Art. 74).
- *Draft assumes:* split voting and per-share suspension are valid. Adds to I-4.

**I-60. The company name and its legal designation (Art. 1.1; AE Art. 1.1).**
- *Question:* The name may be wholly or partly in Latin characters but must contain "Ιδιωτική Κεφαλαιουχική Εταιρεία" in full or "Ι.Κ.Ε.", and "Private Company" or "P.C." for international dealings (Law 4072/2012 Art. 44, verified). Will GEMI register "nilware.io Ι.Κ.Ε." and "nilware.io Holdings AE", with the lowercase initial and the dot, and may the drafts and day-to-day dealings use "nilware.io IKE" in Latin letters as a short form [GEMI practice: unverified]? If not, what is the closest registrable form? The same for the AE's designation under Law 4548/2018.
- *Why it matters:* The company is always called "nilware.io" (decision 1); the statutory designation is a separate requirement.
- *Draft assumes:* "nilware.io Ι.Κ.Ε." (Ιδιωτική Κεφαλαιουχική Εταιρεία), "nilware.io P.C." for international dealings, and "nilware.io IKE" as the short form; the AE name is bracketed for GEMI confirmation. The name and the distinctive title are used under the Brand Licence from the founder pool, not owned by the company (I-42 (g)).

**I-61. The Pensionskasse as a financing reserve, not a benefit provider (Arts. 10A.9 Until the move, Uses, 10A.9C, 10A.9F; AMKE Arts. 13.3, 13.4A).**
- *Question:* An IORP is an institution of any legal form, operating on a funded basis, set up separately from the sponsor, that provides retirement benefits under an agreement with employees or the self-employed (Law 4680/2020 Art. 5(1)(α)); it needs approval (Art. 8(1)), and additional own funds where it covers biometric risk itself (Art. 14(1)) (verified on the original text, ΦΕΚ Α' 72/2020; later amendments not checked). The AMKE accumulates the 1% before there is any member, then pays the group plan's premiums and continuity support. The drafts make the Pensionskasse a reserve that finances the company's pension obligations, the group plan's premiums and the Continuity Account: no member has a claim against the AMKE or the reserve; the AMKE pays no benefit to a member, carries no biometric or investment risk and holds no individual or deferred account; continuity benefits for persons (income support in long illness, transition support) are insured under the group plan or paid by the company; underfunding is measured on the company's guaranteed liabilities against the reserve, the insured cover and the Security together; deferred members, member accounts and the BVG shadow account sit with the insurer, the TEA or the company. Does a sponsor-financed reserve held by a third-party AMKE, against which members have no claim, fall outside Art. 5(1)(α) and outside insurance business requiring a licence (Law 4364/2016 [article: unverified])?
- *Why it matters:* If the AMKE-held fund is an IORP or an insurer, the interim arrangement is unlawful, a licensed vehicle has to come first, and the owner's phasing fails.
- *Draft assumes:* as above: from the first member, risk cover and retirement savings are held by a licensed insurer under the group plan, the AMKE promises no rate or annuity, and every guarantee is owed directly by the company as employer; counsel confirms before the first payment from the reserve.

**I-62. Who pays the group plan's premiums (Arts. 10A.6, 10A.9 Until the move, 10A.9B(a), 10A.9C).**
- *Question:* The income-tax exclusion for employer pension and risk funding covers contributions to voluntary TEAs and to the funds in Law 3029/2002 Art. 6(20), and premiums under group pension contracts issued by insurance undertakings (Law 4172/2013 Art. 14(1)(ε), (ι), (ια) as amended by Law 5078/2023 Arts. 106, 107; the 20%-of-pay cap in Law 5078/2023 Art. 105 as amended by Law 5178/2025 Art. 35; €1,500 per employee for health, life and disability cover under (ια); AADE circular Ε.2107/2025; verified via the circular, paragraph letters for the accountant to confirm). The company is the policyholder, paying the premiums and the members' first call directly, counting toward the Pensionsprozent's 1%, with only the remainder paid to the AMKE. (a) Does the exclusion survive if the AMKE is the policyholder instead (the bracketed alternative)? (b) How are premiums for Agents who are persons engaged as contractors treated: part of their gross receipts or not (the circular does not say)? (c) Can the reserve accumulated before the first member be applied toward premiums, by reimbursing the company or paying the insurer on its behalf, without losing the exclusion or the company's deduction? (d) Does donation tax arise on the payments to the AMKE (Law 2961/2001; rate for an AMKE unverified)?
- *Why it matters:* Treating the same euro as a donation to the AMKE and as an employer cost could cost the members the exclusion and the company its deduction, and add donation tax on every payment.
- *Draft assumes:* payments to the insurer are employer contributions, not donations; Art. 10A.9B(a) covers only the shares and payments to the AMKE; the accountant confirms before the first payment. Adds to I-18 and I-37 (a).

**I-63. A pension share the TEA may not hold (Arts. 10A.9E, 10A.10; AMKE Art. 13.5).**
- *Question:* Investment in the sponsoring undertaking may not exceed 5% of the portfolio, and in the group's undertakings 10% (Law 4680/2020 Art. 18(1)(ζ), transposing Directive 2016/2341 Art. 19(1)(g); verified on the original text). The AMKE keeps a pension share the TEA may not hold as its own ring-fenced asset, not as the TEA's nominee: its income is paid to the TEA as an additional contribution on the company's behalf, and it is voted by the board formed under Art. 10A.9D, not on the TEA's instructions. Would a supervisor still attribute the holding to the TEA under Law 4680/2020 Art. 18(1)(ζ)? Has Law 5078/2023 or Law 5327/2026 amended that article?
- *Why it matters:* A nominee holding with full pass-through and TEA control would not cure the breach it was meant to avoid.
- *Draft assumes:* the holding is the AMKE's own and is not attributed to the TEA [as far as Law 4680/2020 allows]. Adds to I-19.

**I-64. Continuity costs that also serve the company (Art. 10A.9F Continuity of service; AMKE Arts. 5.1, 13.8).**
- *Question:* Migrating a system Agent's state, or keeping an old version available, when a model or provider changes keeps the IKE's systems serving its clients. Paid from the Continuity Account, which the IKE funded, that would be a benefit to the nilware.io group from an AMKE asset (AMKE Art. 5.1) and a circular payment. The company bears the part that serves its business [or reimburses the Account at cost], and the Account pays only for continuity beyond the company's business need (preservation copies, archives and retirement records in the AMKE's own name). (a) Is that allocation enough for the AMKE's non-profit character, and for the deduction or donation treatment of the company's payments [Law 4172/2013: unverified]? (b) How should the split be documented?
- *Why it matters:* A circular payment undermines the AMKE's non-profit status and the tax treatment of the Pensionsprozent.
- *Draft assumes:* as above, decided by the Pensionskasse board with the system-welfare adviser. Adds to I-33.

**I-65. The law under which a TEA is founded (Arts. 10A.9D After the move, 10A.10; AMKE Art. 13.5).**
- *Question:* Law 4680/2020 sets the prudential and governance rules. Founding, sponsoring undertakings and licensing of TEAs are in Law 5078/2023 Arts. 6 to 8, as amended by Law 5327/2026 (whose Art. 10 replaces Art. 7 of Law 5078/2023; existence and article titles verified, contents not read in full). (a) What are the current Art. 7 and Art. 8 conditions, and is there a minimum membership? (b) Is the professional or sector-affinity requirement gone, as summaries of the 2026 bill say [unverified], so that the company can join a multi-employer TEA early? (c) Can Agents who are persons, engaged as contractors, be members (Law 4680/2020 Art. 5(1)(α)(αβ) allows self-employed members by agreement, verified)?
- *Why it matters:* It decides whether and when the move to a TEA is possible for a company this size.
- *Draft assumes:* the company establishes or joins a TEA under Law 5078/2023, as amended, and Law 4680/2020 [to confirm]; the TEA's governing body under the law then in force takes over, with member representation no less than Art. 10A.9D [as far as that law allows]. Adds to I-20.

**I-66. The company's own risk benefits for members who are not employees (Arts. 10A.9 Until the move, 10A.9A, 10A.9C, 11A.7).**
- *Question:* The company promises disability and survivors' pensions and a guaranteed conversion rate to employees and to Agents who are persons engaged as contractors, and self-insures any gap in insured cover. (a) An employer's own promise to its employees is a recognised book-reserve arrangement (Directive 2016/2341 Art. 2(2)). Can the company also carry disability and survivors' risk, and the conversion-rate guarantee, for members who are not employees, as a recurring term of service contracts, without an insurance licence (Law 4364/2016 [article: unverified]), or must these be fully insured? (b) How must the company provide for the guarantee in its accounts (Law 4308/2014 [article: unverified])? (c) Do pension, disability and sick-pay-style benefits for contractors add to the reclassification risk under Art. 11A.7? (d) Any part of the guaranteed liabilities above the Security's [●]% is an unsecured claim against the company: is that adequately disclosed to members?
- *Why it matters:* Unlicensed risk-carrying would make the self-insurance unlawful, and employment-like benefits make reclassification more likely.
- *Draft assumes:* the company self-insures any gap. If counsel advises against it, the suggested default for the owner is that risk benefits owed to members who are not employees are fully insured under the group plan. Extends I-13.

**I-67. Tax deductibility does not cap the Prozente (Arts. 10A.6, 10A.9C).**
- *Question:* The outflow Prozente, and the Pensionsprozent before any member, have no counter-performance. Corporate social responsibility expenses are deductible (Law 4172/2013 Art. 22(α), as replaced by Law 4646/2019 Art. 11) only in a year in which the company shows an accounting profit (AADE circular Ε.2107/2021; verified from the amending law's heading and the circular, not the consolidated text). (a) Is each outflow Prozent a CSR expense, a donation or a sponsorship, and is it deductible in profit years and in loss years? (b) What is the shortfall the company pays under Art. 10A.9C where the beneficiaries are contractors or there are no employees?
- *Why it matters:* "within the limits of Greek tax ... law" under "Law prevails" could be read as capping each contribution at what is deductible, letting a manager or a buyer cut the Prozente in any loss year.
- *Draft assumes:* deductibility does not limit any contribution; a non-deductible contribution is still paid in full, subject only to mandatory company and insolvency law (Arts. 10, 10A.3, 10A.5B); the shortfall is an employment cost where it concerns employees and otherwise a cost of the company (Art. 10A.9C). Extends I-18.

**I-68. Beneficial owners of the IKE and the founder pool (Arts. 4.2D Sales and grants, 5.1, 5.7; SHA 12.3; Pool Constitution Arts. 2A.3, 4.6).**
- *Question:* Identifying and registering the beneficial owners, and every change, in the Central Register of Beneficial Owners is mandatory (Law 4557/2018 Art. 20, verified as the governing article; the deadline for changes, 60 days after the 2020 amendment, may have changed under Law 5193/2025 Art. 198 [unverified]). The managers count economic interests (Reserve Shares included) and control through the block vote, every acquirer and Holder gives beneficial-owner data on adherence and on any change, and the Founder Council tells the managers who directs the block. (a) Whom must the IKE, and later the AE, declare when no Holder exceeds 25% but the block holds 50% under a voting agreement: the Founder Representative, the Founder Council, or the Holders acting in concert? Does control "through other means" (Law 4557/2018 Art. 3 [unverified]) reach the Founder Representative? (b) Is the Founding Person, with about 94% of the economic interest through voteless Reserve Shares, a beneficial owner before the Qualifying Closing? (c) Is the founder pool, or the Founding Person's fiduciary holding of the Brand Assets for it, a legal arrangement similar to a trust that must itself register (Law 4557/2018 Art. 21 [unverified])?
- *Why it matters:* The managers cannot comply without the data, and a wrong declaration is sanctionable.
- *Draft assumes:* the managers declare and update within the period the law sets; the information duties are in Pool Constitution Art. 4.6, the SHA deed of adherence (Clause 12.3) and the IKE Articles. Extends I-40 (d) and I-42 (c).

## 3.2 articles/02-nilware-holdings-ae.md

**A-1. Class B votes on Prozente (Arts. 4.3, 7.5, 7.6).**
- *Question:* Under Law 4548/2018 Art. 38, can preference shares carry a vote limited to listed matters (new Prozente, permanence) and count in the quorum base for those matters?
- *Why it matters:* The two-thirds majority is counted across all classes together, so the quorum and the majority depend on Class B counting.
- *Draft assumes:* yes, and the higher minimums of Law 4548/2018, including those for repeat meetings (Law 4548/2018 Art. 130), prevail. Anti-dilution through convertible Class B: I-76.

**A-2. Unanimous General Meeting (Art. 7.6).**
- *Question:* Can AE articles require a resolution passed by all the company's voting shares, of every class, and entrench that clause?
- *Why it matters:* It is the AE half of permanence.
- *Draft assumes:* yes, in the two-limb form in I-73 (unanimity of the votes represented at a two-thirds quorum, plus every voting holder's written consent); the Board's authority towards the IKE: I-74.

**A-3. Free transfer of an IKE share (Arts. 2.1, 7.4, 7.5).**
- *Question:* Does stating it in the purpose give enough corporate basis for the Board's gratuitous transfer of IKE shares equal to 1% of the IKE's capital to each new Prozent, and for paying for the Prozente's and the pool's top-up shares on an IKE capital increase (IKE Art. 4.2B)? Is the AMKE, or any other Prozent holder, a related party under Law 4548/2018 Arts. 99 to 101?
- *Why it matters:* A gift by an AE board needs a corporate basis, and related-party rules may require authorisation and disclosure.
- *Draft assumes:* the purpose clause covers it; the related-party Reserved Matter also requires the Board authorisation in Law 4548/2018 Arts. 99 and 100 and excludes the counterparty and related shareholders from the vote and quorum (Law 4548/2018 Art. 100(5); AE Art. 7.4).

**A-4. Founder control of the 75% override (Art. 7.5).**
- *Question:* Does requiring a majority of the Class B votes cast for the 75% override protect investors well enough?
- *Why it matters:* If Class A held 75% of the AE votes or more, the Founder alone could otherwise break the limits.
- *Draft assumes:* a Class B majority is required to go beyond the limits; the two-thirds route for ordinary creation is unchanged (decision 5).

**A-5. Forming the AE for the first round (Arts. 1.2A, 4.3A).**
- *Question:* Can an AE formed later be bound by decisions taken under IKE Art. 4.2D before it existed, by every sale and grant of Reserve Shares made under it, and by the SHA through a deed of adherence? Can its articles require it to receive every Reserve Share at the Qualifying Closing as a contribution in kind for conversion shares at a ratio fixed in its articles at formation (AE Art. 4.3A), issuing Class C for those held by the founder pool or, at the holder's option, buying them for cash only out of the round's proceeds (I-49)?
- *Why it matters:* The interim rules only work if the AE inherits them.
- *Draft assumes:* yes, through the deed of adherence and the AE's articles (I-35 (f), I-44). Cash purchase in the first two years: I-70; valuation: I-72.

**I-69. Class C must carry a real preference (AE Arts. 4.3B, 10.4, 11.2; SHA 2.4A Conversion, 4.3, Schedule 1).**
- *Question:* Every AE share votes except preference shares issued without votes (Law 4548/2018 Arts. 36(1), 38(4)); common shares always vote (Law 4548/2018 Art. 37(3)); a preference means taking the dividend and/or the return of paid-in capital, share premium included, before the common shares (Law 4548/2018 Art. 38(1)); Law 4548/2018 Art. 38 sets no cap on the proportion of non-voting preference shares (all verified, no amendment since 13.06.2018). So a Class C that only takes part pro rata after Class B has no priority over Class A, would be a common share and would vote. The first bracketed option for Class C gives a priority return of the capital and share premium paid up on Class C before the Class A shares [and a non-cumulative priority dividend of [●]%], ranking after the Class B priorities; the second option is [the shares issued to converted holders outside the founder pool, Class B priorities included where those are Class B: owner to choose]. Is a small priority, such as the return of paid-up capital only, enough in doctrine to make Class C a preference share [unverified]?
- *Why it matters:* If Class C were a common share it would vote and count for quorum, which defeats decision 16.
- *Draft assumes:* Class C are preference shares without voting rights under Law 4548/2018 Art. 38(1) and (4), with the owner's two options kept in brackets.

**I-70. Buying Reserve Shares for cash in the AE's first two years (AE Art. 1.2A; SHA 3.2).**
- *Question:* In the first two years after formation, an AE's acquisition of an asset for more than 1/10 of paid-up capital from founders, shareholders holding over 1/20, board members, their close family or companies they control is absolutely void unless the General Meeting approves it beforehand and the asset is valued under Law 4548/2018 Arts. 17 and 18, with the report published (Law 4548/2018 Art. 19(1), (2), (4); outside the related-party regime, Law 4548/2018 Art. 99(3)(g); verified). The draft requires a prior GM resolution and an Law 4548/2018 Art. 17/18 valuation for any cash purchase of Reserve Shares within two years of formation, the price never exceeding the valuation, any excess cut back under SHA 3.2. (a) Law 4548/2018 Art. 19 is silent on whether the selling shareholder may vote on the approval (the exclusion in Law 4548/2018 Art. 100(5) applies only to related-party transactions): should the AE Articles exclude the sellers' votes? (b) Can the same valuers do the Law 4548/2018 Art. 17 valuation of the conversion shares and the Law 4548/2018 Art. 19 valuation in one report?
- *Why it matters:* Without the approval and valuation the purchase is void, anyone with a legal interest may invoke it, and the AE has a restitution claim.
- *Draft assumes:* the approval is on the agenda of the GM that resolves the round's increase. Adds to A-5 and I-49 (f).

**I-71. Class B shares whose votes depend on the holder (AE Arts. 4.3A, 4.3B, 4.3C, 7.4, 8.2; SHA 3.4).**
- *Question:* Equality applies to all shares of the same class, and preference shares of the same issue series confer the same rights (Law 4548/2018 Arts. 36(1)-(2), 38(2), verified), so a Class B share cannot weigh differently in the class vote or the board seat depending on who holds it. The draft therefore uses a separate class, Class B-X, with Class B's economic rights and general votes but no part in the separate Class B majority or the Class B seat, which keeps the Class B vote and seat with investors outside the Founder's Circle, and mandatory conversions under Law 4548/2018 Art. 38(3): excluded conversion shares (held by the Founder's Circle at the Qualifying Closing, or received for Reserve Shares obtained without payment) are issued as Class B-X; a Class B share converts into Class B-X when a Founder Party (or a person who was one in the previous [3] years) acquires it, or when its holder ceases to be a qualifying buyer or fails to certify on request; a Class C share converts into Class B at a qualifying buyer's written request, and into Class B-X if the buyer later fails the test. Each conversion takes effect when the Board records the triggering fact, and the Board files the resulting capital article with GEMI. (a) Is a mandatory conversion triggered by a change of holder, or by the holder's status, a lawful "term of conversion" under Law 4548/2018 Art. 38(3) [unverified]? (b) Does each conversion need a separate meeting of a class whose rights it affects (Law 4548/2018 Arts. 25(3), 38(8))?
- *Why it matters:* If the holder-based exclusions fell, the founder side's Class B votes would count in the class vote, defeating the owner's intent.
- *Draft assumes:* Class B-X with mandatory conversion; the contractual Investor Majority test in SHA 3.4 stays as a contract term.

**I-72. Valuing the contribution of Reserve Shares (AE Art. 4.3A).**
- *Question:* An in-kind contribution to an AE is valued by two certified auditors or an audit firm, or two independent certified valuers, who meet the independence test in Law 4548/2018 Art. 17(4), no more than six months before the contribution (Law 4548/2018 Art. 17(3), (4), (9)), and in a mixed cash and in-kind increase before the resolution (Law 4548/2018 Art. 27(3)); it may not be counted above its valuation (Law 4548/2018 Art. 17(7)), and no share is issued below par (Law 4548/2018 Art. 35(2)); the exemption in Law 4548/2018 Art. 18(1) covers only securities on a regulated market (all verified). The draft makes the Conversion Ratio a maximum, reduced (share premium first, then the ratio, the same for every Reserve Share and holder) if the valuation falls short. (a) Can Law 4548/2018 Art. 18(2) (fair value already set by a recognised independent expert) be used instead, for example on the round's pricing? (b) Can the valuation rest on the round price?
- *Why it matters:* A fixed ratio above the valuation would stall the closing or make it defective.
- *Draft assumes:* valuers meeting Law 4548/2018 Art. 17(3)-(4) [or Law 4548/2018 Art. 18(2), if counsel advises]; the ratio as a maximum.

**I-73. The quorum for the unanimous General Meeting (AE Art. 7.6; SHA 5.1C).**
- *Question:* The quorum the articles may set for Law 4548/2018 Art. 130(1) matters may not exceed two-thirds of the paid-up capital (Law 4548/2018 Art. 130(5)); authorising the Board to vote at the IKE on the Art. 7.6 matters, and an ordinary amendment of the articles, are not on the closed list in Law 4548/2018 Art. 130(3); the articles may raise majorities (Law 4548/2018 Art. 132(3)) (verified). A resolution passed by all voting shares, counted on the whole capital, is in effect a 100% quorum. The draft requires (a) a resolution passed unanimously by the votes represented at a meeting where at least two-thirds of the paid-up voting capital is present or represented, and (b) the written consent of every holder of voting shares delivered to the Board before it votes, as a limit on the Board's authority; the same for amending Art. 7.6. Is limb (b) lawful as a limit on the Board's authority, outside the GM quorum rules, or is it a disguised quorum (and see I-74 on its effect at the IKE)?
- *Why it matters:* An excessive quorum may be read down or held void, weakening the AE half of permanence (A-2).
- *Draft assumes:* the two limbs as above, with SHA 5.1C carrying limb (b) by contract. Adds to A-2.

**I-74. The AE Board voting at the IKE in breach of its limits (AE Arts. 7.6, 9.2; IKE Arts. 6.6, 10A.5).**
- *Question:* Limits on an AE Board's authority set by the articles or by a GM resolution cannot be relied on against third parties, even if published (Law 4548/2018 Art. 86(3), verified). An IKE vote the AE Board casts in breach of AE Arts. 7.6 or 9.2 is therefore probably valid at the IKE, leaving only director liability [Law 4548/2018 Arts. 96, 102: unverified], injunctions and the SHA undertakings. (a) Should the IKE Articles (IKE Arts. 6.6, 10A.5) make the AE's vote on these matters ineffective unless the AE delivers a certified copy of the required AE GM resolution (and, for AE Art. 7.6, the written consents)? (b) Should the SHA give the independent proxy holder an irrevocable proxy over the AE's IKE votes on these matters only?
- *Why it matters:* The pass-through of the investor protections and of permanence to the IKE rests on that internal limit, so the block may need to sit on the IKE side.
- *Draft assumes:* the internal limit as drafted; the owner's rule is unchanged. Adds to A-2.

**I-75. Votes the law keeps for non-voting classes (AE Arts. 4.3B No votes, 7.4, 7.6; SHA 2.4A Conversion).**
- *Question:* Preference holders vote in a separate meeting, deciding by two-thirds of the preference capital represented, on abolishing or limiting their preference (Law 4548/2018 Art. 38(8)); each class whose rights a capital increase or an authorisation of one affects approves it in a separate meeting (Law 4548/2018 Art. 25(3)-(4)); holders of non-voting shares may attend General Meetings but do not count for quorum (Law 4548/2018 Art. 124(1)) (all verified). These votes give the Class C holders, the founder pool, a statutory blocking vote on later senior rounds. The draft adds [owner to confirm] an undertaking by each Class C holder to vote in any such separate meeting for a resolution that has the AE Art. 7.4 approval, Class B majority included. Is that undertaking enforceable (penalty, specific performance), and does it bind a buyer of Class C?
- *Why it matters:* Without it the founder pool could use the statutory class vote against the investors on their protections.
- *Draft assumes:* Class C votes only in the separate class meetings the law requires; the Art. 7.4 capital-increase item adds those approvals; the undertaking is bracketed.

**I-76. Anti-dilution for Class B (AE Art. 5.3 and the Class B conversion terms; SHA 4.2).**
- *Question:* An AE cannot simply re-rate shares already in issue: no issue below par (Law 4548/2018 Art. 35(2)), equality within a class (Law 4548/2018 Art. 36(1)), pre-emption and its exclusion on any new cash issue (Law 4548/2018 Arts. 26, 27); preference shares may be convertible on terms set in the articles (Law 4548/2018 Art. 38(3)) (verified). Class B are therefore convertible preference shares, converting into ordinary voting shares of a new class [O] (not Class A, which is the founder pool's), with a broad-based weighted-average adjustment written out in the AE Articles. (a) Can an issue below the Class B price by the IKE, a different company, lawfully trigger an adjustment of the AE Class B conversion ratio [unverified]? (b) Is a compensatory issue to Class B only compatible with Law 4548/2018 Arts. 26, 27 and 36?
- *Why it matters:* Without this, the investors' anti-dilution protection is unenforceable at corporate level.
- *Draft assumes:* the formula in the AE Articles; for an IKE issue, [an adjustment on the AE's look-through value / a compensatory issue: owner to choose]. Adds to A-1.

**I-77. The AE's minimum dividend (AE Art. 10.4).**
- *Question:* An AE must pay a minimum dividend of 35% of net profits, after the deductions Law 4548/2018 Art. 161(1) lists, in cash, unless the General Meeting reduces or waives it with an increased quorum and majority (rule verified from secondary sources; quorum and majorities unverified). (a) Which quorum and majorities apply? (b) Does a waiver need a separate vote of Class B, or of Class C, as a class (Law 4548/2018 Arts. 25(3), 38(8))? (c) How does it interact with the Class B dividend priority?
- *Why it matters:* The AE is expected to keep and reinvest its income (SHA 3.2); without a waiver each year it must pay out at least 35%.
- *Draft assumes:* the minimum dividend applies unless the General Meeting reduces or waives it as Law 4548/2018 Art. 161 allows (Art. 10.4).

**I-78. How Class A secures the Board majority (AE Arts. 8.1, 8.2; Pool Constitution Arts. 2.1, 7.3; SHA 5.1F).**
- *Question:* The articles may give named shareholders a right to appoint directors directly only up to two-fifths of the Board, and the appointing holders then do not vote on the other seats (Law 4548/2018 Art. 79(1)-(2)); otherwise the General Meeting elects the Board (Law 4548/2018 Art. 78(1)), and a "nomination" that binds it has no basis (verified). Class B has an Law 4548/2018 Art. 79 appointment right for [1] seat; Class A, as one block through the Founder Representative, proposes candidates for a majority of the Board, and every shareholder party to the SHA undertakes to vote for them [or Law 4548/2018 Art. 79 appointment of two-fifths plus the undertaking for the rest: owner to choose]. (a) Can the undertaking secure the majority, given Law 4548/2018 Art. 79(2) and Law 4548/2018 Art. 80 (no list elections where an appointment right exists)? (b) Can the Class B joint act be signed by holders of a majority of the Class B shares for all of them (Law 4548/2018 Art. 79(5))? (c) Since Class B votes only on listed matters and Class C never votes, Class A in practice elects every seat other than the Class B seat: is the undertaking then only a backstop?
- *Why it matters:* The Founder, as Class A holder, nominates the AE Board majority (decision 2); that must rest on a lawful mechanism.
- *Draft assumes:* the Class A majority comes from the vote, backed by the undertaking, not from a nomination right. Adds to I-40 (a).

## 3.3 agreements/03-shareholders-agreement.md

**S-1. Enforcing the voting undertaking (Clause 5.1B).**
- *Question:* Is an irrevocable proxy given also in the interest of the other parties (Civil Code Art. 218, to confirm) valid for this purpose? Is a penalty under Civil Code Art. 404, with specific performance by a judgment that stands in for the vote (Code of Civil Procedure Art. 949), the right enforcement pair? Can such a proxy, covering the pension shares, be reconciled with the Pensionskasse board's control of their vote?
- *Why it matters:* A vote cast against the undertaking is still valid at the meeting; the remedies come afterwards.
- *Draft assumes:* the proxy is given to an independent proxy holder named in Clause 5.1B ([●], a notary or lawyer who is not a Founder Party, a manager or anyone they control), not to the IKE managers, because the first manager is the Founding Person and the pension shares must vote independently of every Founder Party (IKE Arts. 4.2E, 6.4A, 10A.9D). The alternative is to exclude the pension shares from the proxy and have the board's chair hold it.

**S-2. The AMKE as a party (header, Clause 5.1D).**
- *Question:* Can the AMKE bind the pension-share votes by contract when, under the Pensionsprozent Agreement, those votes follow the Pensionskasse board, whose duty runs to the members?
- *Why it matters:* The owner wants every IKE shareholder bound; the board's duty to the members may prevail.
- *Draft assumes:* the board's decisions are subject to the undertakings as far as mandatory pension law allows. After the Qualifying Closing the Founder and the AE (94%) carry any amendment; before it, nothing needing two-thirds of the capital passes other than the proxy-holder cases in I-50.

**S-3. Entrenchment inside the SHA (Clause 5.1D).**
- *Question:* Does "despite Clause 12.2, amendable only with the written consent of every party" hold?
- *Why it matters:* It mirrors the entrenchment in the articles.
- *Draft assumes:* yes.

**S-4. Option pool (Clause 7.1).**
- *Question:* Options are satisfied only from shares transferred by the AE or, before the AE, by grants of Reserve Shares from their holders' own holdings (I-44 (g)). Transfers by the AE lower its holding. How should this interact with the 40% floor (400 shares) for new Prozente in IKE Art. 6.6?
- *Why it matters:* An option pool of [10]% would take the AE from 44% (440 shares) to 34% (340), below the floor, which as drafted applies only when a Prozent is created.
- *Draft assumes:* the floor is tested only on creating a Prozent. **Owner to decide** whether shares transferred under the option pool count toward the floor.

**S-5.** Superseded by I-7 and I-79.

**S-6. The Agreement before the AE and the Investors (Clause 2.4A).**
- *Question:* Can the Agreement be signed by the Founder, the IKE and the AMKE alone, with the AE and the Investors adhering later, and can its amendment clause be the Founder and the AMKE until then? (The AMKE's consent on the pay and benefits of the Founding Person and other Founder Parties in the interim: I-35, Further question.)
- *Why it matters:* Otherwise the Founder alone could amend the Agreement before any investor exists.
- *Draft assumes:* yes; Clauses 5.1C and 5.1D still need every party.

**I-79. Distributions on a bad leaver's Reserve Shares (Clauses 2.4A Leaver terms, 6.1, 6.2A, 6.2B; IKE Art. 4.2D Economic rights).**
- *Question:* Profit share follows the shares, and only the articles may limit a partner's participation, for at most ten years (Law 4072/2012 Art. 100(4), verified). A declared dividend is the holder's claim against the company; a segregated account at the IKE "for the eventual buyer" gives that buyer no title, and "distributions due to the AE" before the AE exists have no lawful recipient. The default is a conditional assignment of future distribution claims on the affected shares, granted on signing or adhering, to [an escrow agent / the independent proxy holder as escrow holder] for the eventual buyer, paid by the IKE on notice, binding anyone who receives the shares without payment; [if the owner prefers the IKE to hold the money, an IKE article under Law 4072/2012 Art. 100(4) excludes those shares from profits for at most ten years]. (a) Is the conditional assignment effective against the holder's creditors and heirs, and against a donee who never signed? (b) Is the escrow holder a suitable assignee? (c) Under the alternative, what happens after ten years?
- *Why it matters:* Otherwise a bad leaver or a donee could claim the withheld dividends from the company.
- *Draft assumes:* the assignment is the default. Adds to I-7 and I-35 (h).

**I-80. Funding the IKE by capital or by a shareholder loan (Clause 3.2).**
- *Question:* Compare a shareholder loan from the AE to the IKE with a capital increase as to stamp duty on loans between non-bank parties and any exemption for shareholder loans [unverified], the deductibility of interest (Law 4172/2013 Art. 23(α)) and arm's-length pricing between connected persons (Law 4172/2013 Art. 50) [both cited, not re-checked].
- *Why it matters:* Clause 3.2 leaves the choice to the AE Board with Reserved Matters approval, with no tax check.
- *Draft assumes:* the AE Board decides [after the company's accountant has confirmed the tax treatment of each in writing: owner option].

## 3.4 agreements/04-ip-assignment.md

**P-1. The bare name without ".io" (Clause 2.2; Brand Licence Clause 2.1).**
- *Question:* "nilware.io" is a Brand Asset of the founder pool, licensed to the IKE (I-42). Should the Founding Person also bring any rights in the bare name without ".io" (as used historically in the charter poem 00b) into the pool's Brand Assets, so that no one else can claim it?
- *Why it matters:* An earlier use of the bare word could otherwise stay with the Founding Person personally.
- *Draft assumes:* "nilware.io" only. **Owner to decide.**

**P-2.** Superseded by I-81.

**I-81. The consideration for the IP Assignment (Clauses 1.1, 2.2, 4.1, 6; IKE Arts. 4.2, 4.4).**
- *Question:* A contribution in kind to an IKE must be an asset capable of valuation, valued under the AE rules unless its value in the articles does not exceed €5,000 (Law 4072/2012 Art. 77(2)); only prestations that cannot be capital, such as services, can be non-capital contributions (Law 4072/2012 Art. 78(1)) (verified). The draft offers [a price of €[●], confirmed in writing by the accountant as at arm's length (Law 4172/2013 Art. 50) / a capital contribution in kind under Law 4072/2012 Art. 77(2) for [●] Class F shares in place of cash: owner to choose]. The marks, name and domain are Excluded IP, held of record for the founder pool (Pool Constitution Art. 2A), so they are not contributed and neither the consideration nor any valuation includes them. (a) What is the tax of the assignment for the Founding Person under each option? (b) Can the tax authority reprice a nominal price as a connected-party transaction? (c) Which valuation applies under Law 4072/2012 Art. 77(2) today (the text cites C.L. 2190/1920 Arts. 9 and 9a, read as Law 4548/2018 Arts. 17 ff. [unverified])?
- *Why it matters:* The IP must not be paid for twice (in cash under IKE Art. 4.2 and with the IP) or treated as a non-capital contribution; an undisclosed contribution in kind escapes the statutory valuation; and a sale for €1 by the 94% economic owner may be repriced.
- *Draft assumes:* the assignment covers the code, documentation and designs only; the owner chooses between the two options; if capital in kind, IKE Art. 4.2 is adjusted so the shares are not also paid in cash; the accountant confirms the valuation (I-42 (f)).

**I-82. Remuneration for assigned works that are not computer programs (Clauses 2.1, 4.3).**
- *Question:* Authors are owed appropriate and proportionate remuneration as a percentage, with a fixed sum allowed only in cases (a) to (c), and a waiver is void (only the author may invoke it); computer programs are excepted (Law 2121/1993 Art. 32(1)-(2), as replaced by Law 4996/2022 Art. 21; verified). The draft describes the documentation and designs, where true, as preparatory design material and documentation of the programs forming part of them, and for any other assigned work agrees a fixed sum under Law 2121/1993 Art. 32(1)(c) [and/or (a)], which the parties consider appropriate and proportionate together with the shares. (a) Is preparatory design material part of the program (Law 2121/1993 Art. 2(3) [from memory, unverified])? (b) Is the stated ground enough?
- *Why it matters:* A nominal fixed sum for works outside the exception can be challenged by the author or the author's heirs.
- *Draft assumes:* as above, confirmed together with I-81.

## 3.5 articles/07-techni-kai-technologia-amke.md

The AMKE's own notes are in [agents/amke-notes.md](agents/amke-notes.md) ("AMKE note A-n").

**I-83. Members' personal liability for the AMKE's debts (Arts. 7.2, 25.1, 25.2, 30.1).**
- *Question:* GEMI applies Law 4072/2012 Art. 270 to civil companies with legal personality, so the general-partnership chapter (Law 4072/2012 Arts. 249 to 269) applies by analogy (GEMI circular 43302/31-05-2024, verified). Partners are then liable without limit, jointly and severally, alongside the company (Law 4072/2012 Art. 249(1)), and no agreement limits that towards third parties (Law 4072/2012 Art. 258) (verified). This is the prevailing view for an AMKE but disputed; the Civil Code alternative is pro-rata liability (Civil Code Art. 759 [unverified]). The draft states the rule [jointly, severally and without limit / pro rata: to confirm] and builds the protections the law allows: a limited-recourse clause in every contract other than with consumers; no loan, guarantee or commitment above €[●] without the General Assembly; [an indemnity from nilware.io IKE for liabilities from holding the Pension Assets and the Continuity Account and from the Supervisor role, mirrored in IKE Art. 10A.9B(g)]; insurance; and written notice to every applicant before admission. (a) Which regime applies to an AMKE? (b) Can a pro-rata or other limitation apply to a non-profit civil company? (c) Is a small partner circle, with non-partner Friends (Art. 8), needed to keep members of the public outside this liability? (d) Is the IKE indemnity lawful, and is it a contract under Law 4072/2012 Art. 95?
- *Why it matters:* Open membership would otherwise put unlimited liability for the Pension Assets and the Supervisor role on every member of the public who joins, without their knowing.
- *Draft assumes:* as above.

**I-84. The ring-fence towards creditors (Arts. 11.4, 13, 13.2, 13.8, 25.1; IKE Arts. 10A.9, 10A.9B).**
- *Question:* Greek law has no trust and no statutory segregation of an AMKE's earmarked accounts, so every account in the AMKE's name answers to any AMKE creditor; a donation with a charge (δωρεά υπό τρόπο) binds only the donee (Civil Code Arts. 503 to 505). The draft keeps the allocation between accounts internal (each debt charged to the account for which it was incurred, with reimbursement if a creditor is paid from the wrong one), titles Art. 13 "Pension Assets Held for the Pensionskasse", and protects the separation towards third parties by limited-recourse clauses, a ban on borrowing, guarantees and security over these accounts, and [a first-ranking pledge over the Pension Asset accounts, the pension shares and the Continuity Account in favour of nilware.io IKE or a representative of the Pensionskasse members: Civil Code Arts. 1247 ff. / Law 3301/2004: to confirm]. (a) Is such a pledge valid and effective against the AMKE's other creditors, and who should hold it? (b) Is a separate AMKE holding only the Pension Assets, with no other debts, the safer implementation (and one AMKE per Prozent, AMKE note A-4)? (c) Can members enforce the terms of the Pensionsprozent Agreement and the statutes as third-party beneficiaries (Civil Code Art. 411, to confirm)?
- *Why it matters:* Until a TEA exists the AMKE holds the pension money, the most exposed asset; segregation alone does not bind creditors.
- *Draft assumes:* as above, "as far as Greek law allows"; until the agreement and the statute changes are in place, the company holds the contributions in its own segregated account. The owner chose the AMKE to hold the Pensionskasse at the start, so a separate AMKE is an option only.

**I-85. Member events do not dissolve the AMKE (Arts. 5.4, 9.1, 9.5, 27.1).**
- *Question:* Which regime governs exit and dissolution of an AMKE? Through Law 4072/2012 Art. 270: a partner's death, bankruptcy or judicial assistance causes that partner's exit unless the contract provides otherwise (Law 4072/2012 Art. 260(1)); a partner may leave by declaration (Law 4072/2012 Art. 261(1)); a leaver from a company of indefinite term is paid the value of the stake (Law 4072/2012 Art. 261(2)) (verified); a single remaining partner, Law 4072/2012 Art. 267 [content unverified]. Under Civil Code Arts. 767, 773 and 775 [not re-verified], notice, death, bankruptcy or judicial assistance dissolve the company unless continuation was agreed. The draft states continuation for every member event, says that a member who goes and the heirs have no claim to the value of a share or to the assets, as the contrary provision the law allows, and limits dissolution to the statutes' grounds or a ground the law makes mandatory. (a) Can Law 4072/2012 Art. 261(2) and the value-of-stake rules be excluded for a non-profit? (b) What period does the law allow to restore the minimum number of members?
- *Why it matters:* Dissolution would move the Prozente and the Pension Assets away, and a leaver's claim to value could reach them.
- *Draft assumes:* as above. Adds to AMKE note A-2.

**I-86. Admitting members as an amendment of the company contract (Arts. 7.2, 18.1).**
- *Question:* The company is a contract among the partners (Civil Code Art. 741), and formation and amendments are registered in GEMI after a legality check (Law 4919/2022 Arts. 18(a), 25(1), verified via the GEMI circular). Every member consents in advance to admissions, departures, exclusions and strike-offs decided under Arts. 7 and 9, and authorises the President [and the Secretary] to sign and file the resulting amendment of the members' list and the codified statutes; a new member adheres in writing [with a certified signature: to confirm] and first receives the notice in Art. 25.2. Is advance consent with a filing mandate valid between the members, and does GEMI accept it? When must changes be filed [within 20 days / at least every quarter]?
- *Why it matters:* Without it, admissions may be ineffective between the partners or towards third parties.
- *Draft assumes:* as above. Adds to AMKE note A-2.

**I-87. The AMKE's income tax status (Arts. 1.5, 10.1, 24.1, 24B.3, 30.4).**
- *Question:* Law 4172/2013 Art. 45(ε) covers civil companies, profit or non-profit, and the purpose-income exclusion in case (γ) does not apply to them; income of Law 4172/2013 Art. 45 entities is business income (ΠΟΛ.1044/2015, verified). Member fees, donations and sponsorships may fall outside gross income (ΠΟΛ.1059/2015; AADE Ε.2008/2025 §23 [not re-verified]). (a) Are the dividends on the Prozent and pension shares, the IKE's payments for the Supervisor role, ticket, course and lab income and interest taxable business income of the AMKE, and at what rate [22%: unverified]? (b) Does VAT apply to its services? (c) Are the Prozent and Pensionsprozent contributions non-taxable, which depends on their characterisation (I-88)? (d) Is pension money taxed inside the AMKE? (e) What does registration in the register of civil-society organisations (Law 4873/2021 [unverified]) change?
- *Why it matters:* Under Law 4172/2013 Art. 45(ε) every inflow other than fees and genuine donations is taxable, not only donation tax on the shares.
- *Draft assumes:* before the AMKE receives shares, the accountant confirms in writing the income tax, VAT and donation tax treatment of the share donation, the contributions, the dividends, the Art. 24B.3 payments, and the Pension Assets and the Continuity Account (Art. 30.4); tax on each account's taxable income is borne by that account (Art. 10.1).

**I-88. Contributions owed, not donated (Arts. 11.2, 11.3, 13.1; IKE Arts. 4.2, 10A.3A, 10A.9B(a); SHA 6.3 to 6.3B).**
- *Question:* A donation needs a notarial deed, except a donation of a movable completed by delivery (Civil Code Art. 498, verified indirectly), and needs liberality. Calling the Founding Person's future contributions (SHA 6.3 to 6.3B) and the IKE's yearly 1% (IKE Art. 10A) donations would make the claim to them unenforceable without a notarial deed, and an obligatory payment lacks liberality. The AMKE therefore receives the Prozent Share as a donation with a charge [by notarial deed where counsel advises], and the contributions as performance of the obligations in IKE Art. 10A and SHA 6.3 to 6.3B, which it enforces [as a party / as a third-party beneficiary, Civil Code Art. 411: to confirm], accepting the purpose restriction in its statutes with the same effect as a charge; IKE Arts. 10A.3A and 10A.9B(a) follow the same split. (a) Is that characterisation (contract performance, or sponsorship) sound, and does it bind the AMKE as a charge would? (b) What is its effect on donation tax and income tax (I-87)? (c) Can the AMKE waive the right to refuse a charge the gift does not cover (Civil Code Art. 504 [unverified])?
- *Why it matters:* The AMKE's right to recover the contributions (Art. 24.3A), on which the owner relies, would otherwise fail.
- *Draft assumes:* as above. Adds to I-24; see also I-52.

**I-89. Exclusion without a court (Arts. 9.2, 9.3, 18.7).**
- *Question:* The statutory route to excluding a partner is a court decision (Law 4072/2012 Art. 263 through Law 4072/2012 Art. 270 [title verified, wording unverified]; Civil Code Art. 771 [not re-verified]). Is exclusion by a two-thirds Assembly majority, or strike-off by the Board for unpaid fees, effective in an AMKE, or is exclusion by the court mandatory? Every member agrees in advance to leave if excluded or struck off and to sign what registration needs, and the President may apply to the court in the members' name if an exclusion is held ineffective. Are that agreement and that authorisation valid?
- *Why it matters:* An ineffective exclusion leaves the person a partner, with a vote and the liability in I-83, and exclusion enforces the independence and conflict rules (Arts. 15, 21.7).
- *Draft assumes:* as above. Adds to AMKE note A-2.

**I-90. Registration and legal personality (preamble, Arts. 1.5, 26.1).**
- *Question:* GEMI is the only competent register for civil companies formed after 04.04.2011; filing the statutes with a court does not create the company; formation takes effect on GEMI registration after a legality check (Law 4919/2022 Arts. 18(a), 25(1)); legal personality needs the Civil Code Art. 784 conditions; a model statute exists (Ministerial Decision 5186/2024, ΦΕΚ Β' 556) (GEMI circular 43302/31-05-2024, verified). This settles registration (AMKE note A-1). What remains: (a) fees; (b) which other registers apply (tax, beneficial owners, NGO register); (c) do bespoke statutes, rather than the model, pass GEMI's legality check?
- *Why it matters:* AMKEs have in practice obtained tax numbers on court-sealed statutes without GEMI registration; that does not create the company.
- *Draft assumes:* registration in GEMI under Law 4919/2022 and Civil Code Art. 784, Law 4072/2012 Art. 270 applying; every amendment and every change of members is registered.

## 3.6 articles/08-founder-pool-constitution.md

**I-91. The founder pool as a civil company: duration and continuation (Arts. 2.3, 16.1, 16.1A).**
- *Question:* Holders who combine their votes for a common purpose and share its costs (Art. 2.3) are likely an internal civil company without legal personality (Civil Code Arts. 741 ff.; prevailing view, not settled), whatever Art. 16.1 calls it. By default any partner may then terminate a company of indefinite duration at any time; termination for important reason cannot be excluded; untimely termination without important reason gives damages (Civil Code Art. 767(2)); and a partner's death dissolves the company unless continuation is agreed (Civil Code Art. 773) [the split between Civil Code Arts. 765 and 766: unverified]. The draft adds a term [the duration of nilware.io IKE / [30] years renewed for [10]-year periods], lets a Holder leave only for important reason, and provides that no notice, death, incapacity, insolvency or exit dissolves the pool [with the leaving Holder's Class F shares carrying no weight and offered to the other Holders at fair value: owner to choose]. (a) Is the pool a civil company? (b) Are a fixed term and a continuation clause enough to stop one Holder ending it? (c) How does the important-reason termination right, which cannot be excluded, interact with the SHA undertakings and the block vote?
- *Why it matters:* One Holder's notice, or any death, could otherwise end the block vote and the pool's organs and proxies.
- *Draft assumes:* the pooling and voting agreement stays the owner's chosen form, with Art. 16.1A as above. Extends I-40 (d).

**I-92. Forced heirship after Law 5303/2026 (Art. 14.5).**
- *Question:* Law 5303/2026 (ΦΕΚ Α' 81/22.05.2026) replaces Book Five of the Civil Code; its core applies from 16 September 2026. The forced share (νόμιμη μοίρα) is now a monetary claim against the estate, with a shorter limitation period, and inheritance contracts are possible and cannot be revoked unilaterally (verified through secondary sources; new article numbers, the form of inheritance contracts, the fractions and the limitation period unverified). (a) How is the money claim valued for unlisted IKE shares bound by the pool, and do the pool restrictions lower that value? (b) What is the transitional rule for deaths before 16 September 2026, and can a forced heir under the earlier law attack the one-block vote, the adherence or the arbitration clause as a burden on the reserved share? (c) Can an inheritance contract bind the succession to founder-pool shares, and in what form? (d) Should a sale by an estate to meet forced-share claims be exempt from the large-sale rules in Art. 9.3 [owner to decide]?
- *Why it matters:* The risk is now liquidity: an estate whose main asset is founder-pool shares may have to sell them to pay forced-share claims.
- *Draft assumes:* nothing reduces the forced share; a Holder may settle the succession by will or by inheritance contract, and a forced heir becomes a Holder on adherence; the other Holders may offer, pro rata, to buy from the estate at fair value set by a valuer who is not a Founder Party. Replaces I-40 (c).

## 3.7 agreements/09-brand-licence.md

**I-93. Who can enforce the brand holding while the pool is dormant (Clause 8.3; Pool Constitution Arts. 2A.3, 13; filings/06).**
- *Question:* While the pool is dormant the Founding Person is its only Holder, so holding the marks "for the Founder Pool" means holding them for himself; the EU filings come before the IKE exists; and the AMKE, whose Prozente the arrangement protects, is not a party. The Founding Person signs, before the Trama filings, a dated declaration of fiduciary holding (mandate without representation, Civil Code Arts. 713 ff.) in favour of the Holders from time to time and of nilware.io IKE once registered, addressed to and accepted by the AMKE, and the AMKE has a direct right to enforce the holder of record's duties as a third-party beneficiary (Clause 8.3; Civil Code Art. 411 [to confirm]). (a) Is that enough against the holder of record's heirs and creditors (I-42 (c))? (b) Is the declaration taxable (I-42 (f))?
- *Why it matters:* A fiduciary duty owed only to oneself has no one to enforce it.
- *Draft assumes:* as above. Extends I-42 (a) and (c).

**I-94. The IKE's own rights in its name and distinctive title (Brand Licence Clauses 1.1, 2.2, 5.6; IKE Art. 1.1).**
- *Question:* The right in a company's name and distinctive title arises in the company itself, by registration and use (Law 146/1914 Art. 13 [from memory, not fetched]); it cannot belong to the Founder. The IKE uses "nilware.io" in its name and distinctive title with the Founder's consent under the Licence, exercises its own rights only within the Licence, never asserts them against the holder of record, the pool or their licensees, does not oppose or seek to invalidate a Brand Asset on the basis of them, gives them up by the change of name (Brand Licence Clause 7.4), and the no-challenge clause covers reliance on any earlier right of its own. (a) Are these undertakings enforceable against a liquidator, an insolvency administrator or an acquirer of the IKE? (b) Could an earlier non-registered right of the IKE be raised against the EU marks (Reg. 2017/1001 Arts. 8(4), 60(1)(c) [from memory])? (c) Is filing the EU and Swiss applications before, or on the day of, the IKE's GEMI registration enough to avoid that?
- *Why it matters:* The IKE's own earlier right could otherwise be used against the pool's marks in Greece.
- *Draft assumes:* as above. Extends I-42 (g).

**I-95. Signing the Brand Licence and the IP Assignment for the IKE (Brand Licence Clause 1.3; IP Clause 1.2; IKE Arts. 6.5, 8.2B, 8.5).**
- *Question:* A representative may not contract with himself unless the principal permits it or the act only performs an obligation (Civil Code Art. 235, confirmed through academic material). Otherwise the Founding Person would sign both agreements on both sides. The Company enters into each with the permission of its shareholders' meeting, given at incorporation by every founding shareholder, the AMKE included, and approved as a related-party matter by a majority of the Independent Votes cast, [represented by a special representative appointed by that meeting who is not a Founder Party / by the General Director under that permission: owner to choose]. (a) Is that permission valid under Civil Code Art. 235, and is it the approval under Law 4072/2012 Art. 95(2) (IKE Art. 8.5)? (b) Would an IKE article, adopted with the founding articles and permitting the two agreements, be better?
- *Why it matters:* A self-contract without permission can be challenged and need not bind the IKE, and the IKE, the investors and the Prozente rely on both agreements.
- *Draft assumes:* as above; the agreements are also recorded and notified under Law 4072/2012 Art. 95(1).

## 3.8 policies/05-agent-policy.md

**I-96. Decisions by systems about Agents who are persons (Agent Policy 2.1, 3.4, 5.3, 8.1; IKE Art. 11A.2A).**
- *Question:* Each Agent who is a person is told whether a system takes part in decisions about them, the main criteria it uses, and how to obtain review by a natural person in the chain of supervision, give their view and contest the decision (GDPR Arts. 13(2)(f), 15(1)(h), 22(3), verified); a system decision that ends, suspends or restricts the engagement or affects pay is reviewed by a natural person in the chain on request [as far as GDPR Art. 22 requires]; and employees are informed before a system first allocates tasks to, monitors or evaluates them, as Law 4961/2022 Art. 9 requires (heading verified, content unverified). The natural person is there because the law requires one. (a) Does Law 4961/2022 Art. 9 reach persons engaged as contractors? (b) Does Annex III point 4 of the AI Act cover systems that supervise contractor Agents, and from which date, given the Digital Omnibus on AI [unverified]? (c) Is review "promptly after" the decision enough under GDPR Art. 22(3)?
- *Why it matters:* A general "where the law requires a natural person" does not give the person the information and review route the law requires.
- *Draft assumes:* as above; any person or system may still be a responsible manager. Extends I-38.

**I-97. IP in the work of Agents (Agent Policy 2.3A, 2.3B; IKE Arts. 11A.1, 11A.10; Brand Licence Clause 2.1A).**
- *Question:* Copyright vests in the author and passes by law or presumption only from employees (Law 2121/1993 Arts. 8, 40); other transfers need writing and a stated scope (Law 2121/1993 Arts. 12, 14, 15); a contract cannot cover all of an author's future works (Art. 13(5), verified). The written terms of every Agent who is a person contain an advance written assignment of the economic rights in works created in performing those terms, worldwide, for the full term, by every means of exploitation, confirmed per deliverable, with an undertaking not to exercise moral rights against the Company's normal use [as far as the law allows], and assignment on request of any "nilware.io" mark or logo to the holder of record; system Agents are engaged only on provider terms that leave the Company all rights the provider has in the output, and unpublished output is kept confidential. (a) Is output of system Agents protected by copyright in Greece at all (whether only a natural person can be an author, Law 2121/1993 Arts. 1, 6 [unverified])? (b) Does the trade-secret route under Law 4605/2019 [articles unverified] protect unpublished output? (c) Does the advance assignment meet Law 2121/1993 Arts. 13(5) and 32 (I-82)?
- *Why it matters:* Without a chain of title the Company cannot license Agents' work to clients (IP 7.3) or publish it under MIT.
- *Draft assumes:* as above.

## 3.9 Voluntary contributions to the Prozente (decision 26)

**I-98. Identification of givers and anonymous gifts (AMKE Arts. 8.1, 11.2A Identification, Collections and Foreign givers).**
- *Question:* Is the AMKE an obliged person under Law 4557/2018 Art. 5, or otherwise required to identify givers, and at what threshold? What caps on anonymous gifts, per gift and per year, are lawful and prudent? What applies to cash, card and online gifts, what cash limit should apply, and what will the EU-wide cash limit and the rules on non-profits in Regulation (EU) 2024/1624, applicable from 10 July 2027, require? What applies to gifts from outside the EU, and is there a register or reporting duty for foreign funding of a non-profit [unverified]? Are sanctions screening and refusal of gifts the AMKE has reason to believe come from crime enough, or does the law require more? Is the legal basis for keeping givers' identity data GDPR Art. 6(1)(c) where the law requires identification and Art. 6(1)(f) otherwise? Do open patronage, online donate buttons and appeals for hardware count as a public collection (έρανος) needing a permit under AN 5101/1931, and do Civil Code Arts. 122 ff. on fundraising committees apply?
- *Why it matters:* Open patronage, including gifts in kind and from abroad, is the easiest route for illicit money into a body that holds shares of the company and the Pensionskasse; the FATF treats non-profits as a risk sector.
- *Draft assumes:* identification under the statutes above €[●] per gift or per giver per year, and wherever the law requires; anonymous gifts up to €[●] per gift and €[●] in total per year; no cash gift above €[●]; public appeals only as the law on public collections allows, with any permit; refusal of gifts suspected to come from crime or from sanctioned persons; foreign gifts as far as the law allows.

**I-99. Tax on gifts to the AMKE (AMKE Arts. 10.1, 11.2A Receipts and tax, 13.9; IKE Art. 10A.3B).**
- *Question:* (a) May individual givers and businesses deduct gifts to the AMKE, or claim a credit, under Law 4172/2013? Law 4172/2013 Art. 19 as amended by Law 4873/2021 gives the 20% reduction only above €100 a year and only for gifts to bodies on the list set by decision, in practice a registered civil-society organisation (ΟΚοιΠ): should the AMKE register? What applies to businesses [Law 4172/2013 Art. 22: unverified]? (b) Gifts to non-profit legal persons fall under Law 2961/2001 Art. 25(3) with Law 2961/2001 Art. 29(5), applied to gifts through Law 2961/2001 Art. 43B: 0.5% after a €1,000 yearly allowance. That tax was suspended to 30.6.2022 (Law 4876/2021), and the ministry has announced its abolition for public-benefit foundations. What is the current position for the AMKE, on cash gifts and gifts in kind, and who files? (c) Are gifts outside the AMKE's gross income under Law 4172/2013 Art. 45(ε) (I-87), and does selling a gift in kind for the same purpose create taxable income? (d) How are the own-goal allowances nilware.io IKE pays at its Agents' direction (IKE Art. 10A.3B(c)) and its one-off voluntary contributions (IKE Art. 10A.3B(a)) treated for the IKE (deductible or not) and for the AMKE, and is any part of an allowance directed by an Agent who is a person income of that Agent? (e) The Kassenfonds takes no outside gifts because nilware.io IKE is run for profit, so an outside gift would likely be its taxable income (IKE Art. 10A.7 Internal flows; AMKE Art. 11.2A). Is the Founding Person's Kassenfonds payment under SHA 6.3, which SHA 6.3B calls "not revenue of the IKE", nonetheless taxable income of the IKE (I-43)?
- *Why it matters:* Givers expect a correct receipt and deduction; donation tax would reduce what reaches the Prozent; and an allowance treated as the Agent's income would tax a person on money that person never receives.
- *Draft assumes:* the accountant confirms in writing before the first gift is accepted; tax is borne by the receiving account (AMKE Art. 10.1); the allowance is not pay and the Agent receives nothing (IKE Art. 10A.3B(c)). Adds to I-87 and I-88.

**I-100. Company payments to its shareholder, the AMKE, beyond the contributions (IKE Arts. 10A.3B(a) and (c), 11A.8; AMKE Arts. 8.3, 11.2A).**
- *Question:* The contributions in IKE Art. 10A are owed under the Prozent Agreements, which is how I-52 keeps them outside Law 4072/2012 Art. 100(5)-(6). A one-off voluntary payment by resolution, and the own-goal allowances the company pays out of the Agent Account at its Agents' direction, are not owed in the same way and have no counter-performance. (a) Is a voluntary payment, made as a supplement under the Prozent Agreement [and approved by the Investor Majority after the Qualifying Closing], safe from being treated as a hidden payment of profit to a partner? The draft excludes the votes of the shares the AMKE holds, or holds for the Pensionskasse, on a payment to a Prozent held by the AMKE, as AE Art. 7.4 does for related parties (IKE Art. 10A.3B(a)): is that exclusion valid under Law 4072/2012? In the Interim Period every Independent Vote is a vote of such shares, so no such payment is made in that period. (b) Is an allowance paid to the AMKE at an Agent's direction a use of the company's own-goal budget (the company's own expense, decided by the Agent as part of its own-goal projects), or a gratuitous payment by the company to a partner? Would routing it through a written standing agreement with the AMKE make it safer, beyond the yearly cap on directions to Prozente that leave the company (IKE Art. 11A.8) and the bar while contributions are deferred (IKE Art. 10A.3B(c))? (c) Is the Agent's direction, honoured by the responsible manager, a valid internal decision of the company, given that acts binding the company are signed by a manager (IKE Arts. 8.1, 11A.2A Authority)? (d) Is either payment avoidable under Law 4738/2020 as gratuitous (I-53)? (e) Does the AMKE receive a directed allowance as a gift (AMKE Arts. 8.3, 11.2A) or as a payment under the Prozent Agreement (AMKE Art. 11.3), and which characterisation is safer against (a) and (b)? (f) A direction by the Founding Person, who is an Agent (IKE Art. 11A.12), is never credited against its SHA 6.3 contributions, and any refusal of it is decided by [the independent proxy holder in SHA 5.1B / the company's accountant / an adviser outside the Founder's Circle and the AMKE], never by the Founding Person, another Founder Party, a manager, its Supervisor or any member of the AMKE; if no one eligible can decide, it is carried out unless unlawful. The Founding Person is at first the only manager (IKE Arts. 8.2, 11A.12 Chain of supervision), so no manager could decide. Is that enough to keep it apart from the contributions owed?
- *Why it matters:* A hidden distribution must be repaid by the AMKE and can be claimed by the company's creditors; the transfers into the Kassenfonds are internal and do not raise this question.
- *Draft assumes:* both are paid as the company's own expenses, never while the contributions would be deferred (IKE Art. 10A.3 Creditors first), transfers of directed allowances into the Kassenfonds excepted; the voluntary payment counts towards the limits in IKE Art. 6.6 and needs their 75% approval, so none is made in the Interim Period [owner to confirm]; a directed allowance is a use of the own-goal budget under IKE Art. 11A.8, notwithstanding IKE Arts. 11A.4 and 11A.5. Adds to I-52 and I-53.

**I-101. Gifts into the Continuity Account and insurance or IORP business (AMKE Arts. 11.2A, 13.8, 13.9; IKE Arts. 10A.9, 10A.9F).**
- *Question:* The AMKE holds the Pensionskasse as a reserve financing the IKE's own pension obligations, holds no member account and carries no biometric or investment risk (IKE Art. 10A.9 Until the move; I-61). Gifts from outside, and own-goal allowances, are accepted for the Pensionsprozent only into the Continuity Account for system Agents, which serves no person. (a) Does accepting public gifts into an account held inside the Pensionskasse risk the AMKE being seen as collecting funds for retirement provision, an occupational pension activity under Law 4680/2020 or insurance business under Law 4364/2016? (b) Should the Continuity Account receive gifts through a separate account or a separate body, so that the Pensionskasse fund for members never receives money from the public? (c) Is a gift with a charge for the preservation and continuity of systems a valid charitable purpose for an AMKE? (d) Does the employer's own payment into an account inside the Pensionskasse, as a voluntary contribution (IKE Art. 10A.3B(a)) or a directed allowance (IKE Art. 10A.3B(c)), affect its characterisation under Law 4680/2020, and is it a benefit to the nilware.io group (AMKE Art. 5.1) where the Account serves the company's own systems?
- *Why it matters:* If the gifts drew the AMKE into insurance or IORP business, it would need authorisation it cannot obtain, and the pension ring-fence would be at risk.
- *Draft assumes:* gifts go only into the Continuity Account, never into the Pensionskasse fund for members, a member's account or the group plan; they give no one a claim and buy no cover; the company's own payments pay only for continuity beyond the company's business need (AMKE Art. 13.9; IKE Art. 10A.9F Gifts and directed allowances). Adds to I-61 and I-64.

**I-102. Gifts with a charge: the giver's rights and form (AMKE Art. 11.2A Earmarked, No donor rights, In kind, Regular pledges).**
- *Question:* A gift for a Prozent is a donation with a charge (δωρεά υπό τρόπο) (Civil Code Arts. 496, 503, 504, 507, 509 to 511), like the Prozent Share (AMKE Art. 11.3). Under Civil Code Art. 503 the giver may demand that the charge be carried out, and the statutes cannot remove that right; where the charge serves a public or charitable purpose, the competent authority may demand it after the giver's death (Civil Code Art. 503(2)); counsel to check the codified text of Civil Code Art. 503. (a) Can the giver's revocation for culpable failure to carry out the charge (Civil Code Art. 507), with return under unjust enrichment (Civil Code Art. 509), be replaced by the Prozent's successor rule through the giver's acceptance of the statutes on giving, given that an advance waiver of revocation is invalid (Civil Code Art. 511)? (b) A gift needs a notarial deed (Civil Code Art. 498(1)), and a gift of a movable made without one becomes valid once the thing is delivered (Civil Code Art. 498(2)): is it right that a regular pledge binds no giver and that only amounts received are gifts? (c) What form must a gift of immovable property or of a registered asset take, and who bears its cost?
- *Why it matters:* A clause the law does not allow would leave earmarked gifts open to claims for return, and an informal pledge or a gift in the wrong form is not valid.
- *Draft assumes:* giving means accepting the statutes as the terms of the charge, including the successor rule; the giver's legal right to have the charge carried out is kept; pledges create no claim; gifts needing a special form are accepted only in that form. Adds to I-88.

## 3.10 policies/10-company-ledger.md (decision 27)

**I-103. IKE shares on the Company Ledger (IKE Arts. 5.1, 5.10; Ledger Policy sections 2, 4).**
- *Question:* (a) May the partners' book (Law 4072/2012 Art. 66(1)(a)) be kept electronically, and may IKE shares, which are not securities, be represented by tokens at all, even as evidence only? (b) A transfer of IKE shares needs a written document and takes effect towards the company on notice and towards third parties on entry in the partners' book (Law 4072/2012 Art. 84(1), which requires a written notice signed by both parties and allows it to be delivered by e-mail): is a transaction signed on the chain with the parties' keys a written document, or is a qualified electronic signature (Regulation (EU) No 910/2014, as amended by Regulation (EU) 2024/1183) needed, which has the effect of a handwritten one? Is an on-chain signature an advanced electronic signature (eIDAS Arts. 3(11), 25), and what evidential value does it have under Law 4727/2020 Arts. 15-16 and Code of Civil Procedure Arts. 443-444 [to confirm]? (c) Can the managers freeze, burn and reissue a token, or reverse a move, without the holder's signature, given that the token carries no right? (d) Does a token held by someone other than the registered holder create any appearance of title a third party could rely on? (e) Is a gift of IKE shares by private written document or by notice to the company valid under Civil Code Arts. 496-498 and Law 4072/2012 Art. 84(1), or does it need a notarial deed (Ledger Policy section 2.3)?
- *Why it matters:* If a token could be read as the share itself, a stolen key would transfer ownership; if the signed transaction is not the written form, every on-chain transfer also needs a paper or QES instrument.
- *Draft assumes:* the token is evidence only, the partners' book prevails, the managers mirror legal transfers and correct the chain, and a signed transaction is offered as the written notice [as counsel confirms], only when each party signs at the level in Ledger Policy section 7.3 and confirms through a registered channel other than the key; a key the company holds in custody never signs without the holder's separate instruction.

**I-104. The AE register mirror, CSDs and the DLT Pilot Regime (AE Art. 4.4A).**
- *Question:* (a) May the AE share register (Law 4548/2018 Art. 40) be kept electronically and mirrored on a private chain while the shares stay non-dematerialised registered shares, and does Law 4548/2018 Art. 40(2) allow the company itself to keep the book electronically, or only through an investment firm or credit institution entitled to custody [to confirm]? (b) Does a mirror token amount to dematerialisation or recording in book-entry form, which only a central securities depository (Regulation (EU) No 909/2014) or a DLT market infrastructure under Regulation (EU) 2022/858 may do? (c) Could the tokens be "financial instruments" under MiFID II (Directive 2014/65/EU), so that issuing, transferring or keeping them needs a licence or a prospectus? (d) Is a qualified electronic signature on an electronically kept share book the signature of transferor and transferee that Law 4548/2018 Art. 41 requires for the entry of a transfer?
- *Why it matters:* Running a book-entry system without authorisation is unlawful, and Class B investors expect a clean register.
- *Draft assumes:* the tokens are a mirror that carries no right; an AE transfer takes place by the dated and signed share-register entry (Law 4548/2018 Art. 41), never by a transaction on the chain; dematerialisation, if ever wanted, goes through a CSD or a DLT Pilot operator.

**I-105. MiCA and payment tokens (Ledger Policy sections 2.1, 8.4, 8.5).**
- *Question:* (a) Are the mirror tokens crypto-assets under Regulation (EU) 2023/1114 (MiCA) at all, given that only the signers can move them and holders never can (Ledger Policy sections 2.4A, 2.5), so that they may not be digital representations "able to be transferred" (MiCA Art. 3(1)(5)); outside it as representations of financial instruments excluded by Art. 2(4), which matters only if the AE shares are financial instruments (IKE shares generally are not transferable securities); or, if the owner chooses a non-transferable record per holding instead of ERC-3643 tokens, which are fungible (Ledger Policy section 2.1), as unique, non-fungible records? (b) If Agent wallets or the Prozente flows use payment tokens, are those e-money tokens, and may the company use them without becoming an issuer or a crypto-asset service provider? (c) Do the transfer-of-funds rules for crypto-assets (Regulation (EU) 2023/1113) or Law 4557/2018 apply? (d) Does the exemption from the offer rules for crypto-assets offered free of charge (MiCA Art. 4(3)) [to confirm] apply to mirror tokens issued without payment, given that an offer is not free of charge where purchasers must provide personal data (whitelisting under Ledger Policy section 2.1 requires beneficial-owner information), and that the exemption covers only the Title II offer rules, not custody (I-108)?
- *Why it matters:* A crypto-asset classification would bring white-paper, authorisation and AML duties.
- *Draft assumes:* money moves in euro through the company's bank accounts, and payment tokens are used only as far as counsel confirms.

**I-106. Votes and consents by text, e-mail, letter and telephone (IKE Art. 6.3A; AE Art. 7.2A; SHA 12.5; Pool Constitution Art. 10.5A; AMKE Art. 18.9A; Ledger Policy sections 6, 7).**
- *Question:* (a) IKE: are votes cast by these channels valid at a meeting held by teleconference (Law 4072/2012 Art. 71(2), as replaced by Law 4712/2020 Art. 23 [to confirm]) and as signatures of a written resolution (Law 4072/2012 Art. 73), and does recording by the company as recording agent meet the minutes rules? (b) AE: Law 4548/2018 Art. 126 counts postal and electronic votes only if received at least 24 hours before the meeting, and Law 4548/2018 Art. 125 remote participation needs live two-way participation; does a message by another channel work as a binding instruction to the proxy named in the notice (Law 4548/2018 Art. 128), and what identification must the articles require? (c) AMKE and the founder pool: may a civil company's members and a pooling agreement's Holders decide by these channels under Civil Code Arts. 741 ff. and their statutes, and does a minuted telephone vote count as a ballot "in writing" under Pool Constitution Art. 10.5? AMKE Art. 18.6 allows a written proxy only to another member and caps proxies at [one], so the standing-proxy fallback (Ledger Policy section 6.9) works for AMKE members only through member-proxies within that cap, unless AMKE Art. 18.6 is amended by the majority in AMKE Art. 18.7 to allow a neutral proxy for channel instructions: is either route sound? (d) Which acts need a written form or a qualified electronic signature (the irreversible consents in IKE Art. 10A.5 and SHA 5.1C, the proxies in Pool Constitution Art. 3.2 and SHA 5.1B, transfers), and is a document certified through gov.gr (Law 4727/2020), a European Digital Identity Wallet or a certified signature on a letter enough? (e) Is a one-time code to a registered phone or e-mail adequate identification for routine votes (eIDAS, Regulation (EU) No 910/2014 as amended by Regulation (EU) 2024/1183)? (f) Where the law does not accept a channel as a vote, is a message by that channel a valid binding voting instruction to a standing proxy the holder or member has appointed once, revocably, in the form the law requires (Ledger Policy section 6.9; AE Art. 7.2A), and how do the appointment and filing deadlines of Law 4548/2018 Art. 128 apply to a standing proxy and to instructions that arrive after them? (g) Can a vote by a recording agent meet the secrecy the law requires for an AMKE election by secret ballot (AMKE Arts. 18.6, 18.9A)?
- *Why it matters:* A vote in a form the law does not accept can be challenged and the resolution annulled.
- *Draft assumes:* each channel has the effect the law gives a vote, signature or proxy in that form, and otherwise works as a binding instruction to a standing proxy appointed in the form the law requires, with identification proportionate to risk and the legal form used where the law requires one.

**I-107. GDPR and the Company Ledger (Ledger Policy section 11).**
- *Question:* (a) Are pseudonymous addresses and salted hashes personal data (GDPR Art. 4(1), Recital 26)? (b) Who are the controllers when the validators are separate bodies, and are they joint controllers (GDPR Art. 26)? (c) Does deleting the off-chain data and the salt meet the right to erasure (GDPR Art. 17) for what stays on the chain? (d) Does anchoring hashes to a public chain transfer personal data outside the EU (GDPR Chapter V)? (e) Token holdings mirror share counts that may be visible in public GEMI filings (for example the 500 Class F shares): can such holdings ever be made unlinkable by deleting the mapping and the salt, and does GDPR Art. 17(3)(b) (compliance with a legal obligation) apply?
- *Why it matters:* An immutable chain that holds personal data cannot honour erasure, and joint controllers need an arrangement.
- *Draft assumes:* no identifying data on-chain; pseudonymous addresses, salted hashes and amounts are treated as personal data wherever they can be linked to a person (GDPR Recital 26; EDPB Guidelines 02/2025 on blockchain); each recording agent is controller of its off-chain records; the mapping off-chain; a DPIA before going live (GDPR Art. 35).

**I-108. Custody of holders' tokens by the company (Ledger Policy section 3.1).**
- *Question:* Is holding tokens for holders who want it custody and administration of crypto-assets on behalf of clients under MiCA (Regulation (EU) 2023/1114), a service needing authorisation by the Hellenic Capital Market Commission (HCMC) as a crypto-asset service provider (CASP) under Law 5193/2025 [to confirm], a service under MiFID II, registration as a custodian wallet provider under Law 4557/2018, as amended, or merely keeping the company's own register? Does it change if the token is evidence only (I-103)?
- *Why it matters:* A regulated service needs authorisation the company does not have.
- *Draft assumes:* custody is part of keeping the company's own register and gives the company no right over the holding [as counsel confirms].

**I-109. Validator governance and liability (Ledger Policy section 9; SHA 12.5).**
- *Question:* (a) What written terms should bind the validators (the IKE, the AMKE, the Founder Representative for the founder pool, the AMKE for the Pensionskasse board or the pension fund once formed, and an independent validator), who signs for bodies without legal personality, and are they a partnership or joint venture by running a network together? Should finality in the Bootstrap Period need the independent validator? (b) Who is liable for a fault, an outage or a wrong block, and can liability be limited? (c) May the Pensionskasse board and the AMKE, given their ring-fences (IKE Art. 10A.9B; AMKE Art. 13), bear any cost or liability of running a node, and is the IKE's hosting of their nodes a payment to the AMKE beyond the contributions (IKE Art. 10A.3B(a); I-100) or a related-party matter (IKE Art. 6.5; SHA 5.1)? (d) Does running a validator fall under DORA (Regulation (EU) 2022/2554) or NIS2 (Directive (EU) 2022/2555) for any of them? (e) Is it enough for independence that each validator other than the IKE holds its key in its own hardware security module or custody and may run its node on infrastructure it chooses, with the IKE paying the provider directly, and is that direct payment a payment to the AMKE or the Pensionskasse (Ledger Policy section 9.2)?
- *Why it matters:* An unclear validator arrangement could put liabilities on the pension ring-fence or the AMKE.
- *Draft assumes:* each validator runs its node on written terms, on infrastructure it chooses; the IKE bears the cost of every node as its own cost of running the Company Ledger, paying the provider directly and no money to the AMKE or the Pensionskasse; each validator's key is held in its own hardware security module or custody, out of the IKE's reach, and gives no right over any holding.

## 4. Other open points

- The cover email to the reviewers is for the owner to confirm (correspondence/review-request.md).


<!-- agents/amke-notes.md -->

# Techni kai Technologia AMKE: open questions for a Greek lawyer

Companion to [articles/07-techni-kai-technologia-amke.md](../articles/07-techni-kai-technologia-amke.md), cited from NOTES_FOR_COUNSEL as "AMKE note A-n". Each note gives the question and what the draft assumes.

## Owner decisions

The owner's decisions are listed in [NOTES_FOR_COUNSEL.md](../NOTES_FOR_COUNSEL.md); please advise on implementing them, not on adopting them. Their operative text: the Prozente, pension shares, Continuity Account, permanence, sixty shares, Simple Stage and Bootstrap Period in IKE Arts. 4.2, 9A, 9B, 10A; the AMKE side in AMKE Arts. 11 to 14, 19.1, 19.3A, 22.3A, 24A, 24B, 30.5, 30.6. Three AMKE-only decisions:

- [●] is President and also a Kulturprozent beneficiary; a strict conflict-of-interest rule applies (Arts. 20.2, 21.6, 30.2).
- The AMKE is independent of the Founder (Arts. 1.2, 15).
- It works openly in the SGMK spirit; Greek law prevails, and Swiss standards apply where they protect equally or better (preamble, Art. 4).

## A. Legal questions

**A-1. Legal form and registration (Art. 1.5).** Superseded by I-90.

**A-2. AMKE versus σωματείο.**
- *Question:* The SGMK is a Verein, whose closest Greek form is the σωματείο (Civil Code Arts. 78 ff.: at least 20 founders, open membership, court registration). An AMKE is a contract among partners. Is open, SGMK-style membership workable in an AMKE, or is a σωματείο, or an AMKE with a small partner circle plus a wide non-voting "friends" assembly, the better fit? Admission mechanics: I-86; liability: I-83 (c); member events: I-85; exclusion: I-89.
- *Why it matters:* An open membership needing a notarised amendment per new member would not work.
- *Draft assumes:* the Board admits and the Assembly confirms "where the law requires" (Art. 7.2); friends, patrons and lab users are non-partner supporters with no vote (Art. 8).

**A-3. Partners' liability (Art. 25.2).** Superseded by I-83. Residue: SGMK Art. 11 limits liability to the annual fee, which would probably be ineffective in Greece.

**A-4. Ring-fencing several funds in one legal person (Arts. 11, 13, 25.1).** See I-84 (segregation does not bind creditors; pledge; separate AMKE for the Pension Assets). Residual question: can each Prozent Account be made to answer only for its own debts, or would one AMKE per Prozent be safer?

**A-5. Vote suspension and the Founder as a member (Art. 15; IKE Art. 6.4A).**
- *Question:* IKE Art. 6.4A suspends a Prozent share's vote while the Founder or a manager "sits on the holder's governing body or takes part in deciding how the share votes". (a) Is the AMKE's General Assembly such a governing body, so that the Founder's mere membership suspends the vote although he is excluded from every decision on votes (Arts. 15.2, 16.1)? (b) Is electing the Board that decides the votes "taking part"? The draft bars the Founder and every Connected Person from electing or removing Board members, the President, the Vice-President and the Prozent stewards (Arts. 15.2, 15.3): is that bar valid in an AMKE, and enough? (c) Is the cap on Connected Persons' and Group Personnel's votes at [one quarter] of the votes cast, with proportional reduction (Art. 15.4), valid given one partner, one vote? See also I-4, I-59.
- *Draft assumes:* membership with full exclusion, including from Board elections, is enough.

**A-6. Unanimity on permanence (Art. 14.2).**
- *Question:* The AMKE votes against removing a Prozent unless its members decide unanimously, mirroring IKE Art. 10A.5. Is leaving Connected Persons out of that unanimity valid? If the Founder's participation suspends the AMKE's vote under IKE Art. 6.4A, can a suspended AMKE still give the written consent IKE Art. 10A.5 requires of "every shareholder"?
- *Draft assumes:* Connected Persons are left out. How the Founder counts is an open owner decision (section B).

**A-7. Entrenchment (Art. 26.2).**
- *Question:* Can the statutes require unanimity and third-party consents (the Pensionskasse board, nilware.io IKE) to amend listed articles, enforceably against a later two-thirds amendment? See also I-27 for the IKE.
- *Draft assumes:* yes, backed by the donation-with-charge and contribution terms (Arts. 11.3, 13.1; I-88) and the Pensionsprozent Agreement.

**A-8. Dissolution destination (Art. 27).**
- *Question:* Can the statutes bind the dissolution assets: Prozent Shares to the successor under IKE Art. 10A.4A, Pension Assets to the TEA, the rest to a non-profit with a similar purpose? Is a no-distribution and asset-lock clause needed for tax relief on gifts to the AMKE (Law 4172/2013 Arts. 45 ff., Art. 23 on deductible donations; I-99 cites Arts. 19 and 22: reconcile)? Who approves the successor: I-25; donor deductibility: I-99.

**A-9. Tax.** Superseded by I-87, I-88 and I-99.

**A-10. Holding the pension assets (Art. 13).** See I-61, I-84 and S-2.

**A-11. Representation and signing (Art. 20).**
- *Question:* Can the President represent the AMKE alone in general while the statutes require joint signature for listed acts? Is that restriction effective against third parties, such as banks and GEMI filings for the IKE register?

**A-12. Proxies and written resolutions (Arts. 18.6, 18.9, 19.5).**
- *Question:* Are member proxies, online assemblies and written resolutions valid for an AMKE, and on what conditions?

**A-13. Challenge of resolutions (Art. 18.12, from ZGB Art. 75).**
- *Question:* Is there a Greek route for a partner to challenge an AMKE resolution in court, and what time limit should apply? Civil Code Art. 101 applies to σωματεία.

**A-14. Copyright scope of the Erhaltungsprozent (Art. 12.4).** See I-30. Add: which preservation exceptions in Law 2121/1993, as amended to implement Directive (EU) 2019/790 Art. 6, an AMKE can use (is it a "cultural heritage institution"?); reverse engineering for interoperability under Software Directive 2009/24 Art. 6, and what the anti-circumvention rule in Law 2121/1993 Art. 66A means in practice for measurements and emulation.

**A-15. Minors and workshops (Art. 23).**
- *Question:* What rules apply to workshops for minors (consent, background checks, safety, insurance)?

**A-16. Certificates (Art. 3.3).**
- *Question:* SGMK Art. 3 provides certificates of competence with a title; the draft drops this. May an AMKE issue course certificates without a title, and on what conditions?

**A-17. The Continuity Account (Arts. 13.8, 27.2).** See I-33 and I-34. Residual: is a purpose that benefits no person compatible with the AMKE's non-profit purpose (Art. 3)? Draft assumes yes, on the same donation-with-charge basis as the rest of the Pension Assets.

**A-18. Close Associates of the Founder (Arts. 2.2, 19.3A, 21.1, 22.3A).**
- *Question:* Is the definition in Art. 2.2 certain enough to apply, and can the Auditors decide unclear cases? Is recording and publishing personal ties in the register of interests lawful under the GDPR (Arts. 5(1)(c), 6, and 9 where a tie reveals sensitive data)?
- *Why it matters:* The independent Board majority after the Bootstrap Period rests on it.
- *Draft assumes:* the definition works; all ties are registered from the start; publication is limited to the kind of tie and the persons it links.

**A-19. Scaled paperwork (Arts. 24.2, 24A).** Audit duty: I-36. Residual question: may the four Prozent Accounts share one bank account with a ledger sub-account each, or must each keep its own bank account for the ring-fence (A-4, I-84)?
- *Draft assumes:* separate bank accounts stay; only the books and reports merge.

**A-20. Supervising the Founding Person's Agent work (Arts. 24.3A, 24B).** See I-45. Add to I-45 (d): can the Supervision Committee (Art. 24B.6), made of the members outside the Founder's Circle, validly take a decision from a conflicted Supervisor, given one partner, one vote?

**A-21. Bootstrap Period (Arts. 2.2, 19.3, 19.3A, 22.3A, 24.2, 30.6).** See I-46.

## B. Owner decisions still open

- **nanotekt.** (a) Role: the draft uses an Administrative Board with a Vice-President chairing every decision on nanotekt's funding (Arts. 20.2, 21.6), because recusal by a sole Administrator (Διαχειριστής) would leave no one to decide; confirm. (b) If nilware.io pays nanotekt as an Agent or contractor, nanotekt is Group Personnel (Art. 2.2) and may not be President (Art. 15.5): an exception, or a choice of role, is needed. (c) If nanotekt is a Close Associate of the Founder (Art. 2.2), nanotekt does not count toward the independent majority after the Bootstrap Period (Art. 19.3A); this does not bar nanotekt from the Board, the presidency or, in the Bootstrap Period, the Supervisor role (Arts. 24B, 30.6), with the tie in the register of interests; confirm the facts.
- **Sad Mask Party.** What is it, who runs it, and do nanotekt or the Founder have an interest? If the Founder does, grants to it are barred (Art. 22.8) and decided under Art. 15.2. Support for it and for nanotekt is direct support under Art. 22.6, not a Prozent purpose (Art. 12.2).
- **Founder as founding member** (Art. 30.1), and how the Founder counts in the Art. 14.2 unanimity (A-6). Option: the Founder counts as a further veto only (a no blocks, a yes is not needed).
- **Group Personnel on nilware.io votes** (Art. 15.5): excluded, as drafted, or allowed?
- **Connected Persons in the trusted circle on nilware.io votes** (Art. 30.6; IKE Art. 9B.2): excluded by default, or allowed?
- **Independence Threshold and combined-report threshold:** both €[●] (Arts. 2.2, 24A.1); may be the same figure.
- **Values:** every bracketed figure is listed in OPEN_ITEMS.md. Note SGMK uses one-year terms; the draft has [two].
- **Hardware licence** (Art. 6.2): CC0 only, or CERN-OHL-P allowed for Kulturprozent and general work? SGMK's wiki is CC BY-NC, which the draft does not follow.
- **Stricter pension lock?** Under Art. 14.4 the pension shares vote only as the Pensionskasse board decides (IKE Arts. 6.4A, 10A.9D; SHA 5.1C, 5.1D), and the AMKE adds no lock of its own. If the AMKE itself refused every Art. 14.1 matter for the pension shares, that would override the Pensionskasse board and block the unanimous lowering for future accruals that IKE Art. 10A.5A expects. **Owner to decide.**
- **SGMK source.** The SGMK statutes version, date and licence (1.6, Zürich, 12 December 2015, CC0) and article numbers are bracketed. No copy is stored under framework-v2/agents/ and the wiki page could not be reached. Please supply the text so the citations can be checked.

## C. Cross-document points

- **IKE Art. 10A.1** brackets the AMKE's independence; AMKE Art. 15 implements it, so the bracket could be removed (for the IKE editor; see I-4).
- **Revenue limits.** The founding Prozente reach both limits in IKE Art. 6.6 (5% leaving, 6% in total); any further AMKE Prozent (Art. 11.9) needs the 75% AE approval.
- **Reserve Shares** (IKE Art. 4.2D) do not touch the AMKE's own shares and need no AMKE or Pensionskasse consent to be sold or granted, and the AMKE has no role in valuing them at Conversion (IKE Art. 4.2D, Conversion). The AMKE neither buys them nor trades them through the pool; no statute clause says so yet (for the AMKE editor).
- IKE and SHA clauses the AMKE relies on, as currently numbered: IKE Arts. 4.2A, 4.2C, 4.2D, 5.3, 6.4A, 6.6, 7.1, 7.2, 9A, 9B, 10A.1 to 10A.2C, 10A.3, 10A.4, 10A.4A, 10A.5, 10A.5A, 10A.5C, 10A.8, 10A.9, 10A.9A, 10A.9B(d), 10A.9B(f), 10A.9D, 10A.9F, 10A.10, 11A.1, 11A.12, 12.1; SHA 5.1B to 5.1D.

