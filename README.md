# tl;dr

A website where you can login to consume, produce, or support journalism, working toward co-operative ownership and with legally and technically guaranteed escape hatches from ideological media takeover.

# This is a brainstorm

Do not expect the document to be within ballpark distance of complete, in the neighbourhood of well organised, or even the suburb of researched. Take it rather as the set of scribbled notes one might bring to the first meeting before a real project is even properly outlined. There may be glaring idiocies that render the whole thing pointless or superfluous. If there are, I'd appreciate if you point them out *gently*.

There are definitely areas that are glaringly underspecified or so rough as to be materially wrong. Unless they are, as an LLM might say, "load-bearing", they're not even worth pointing out at this stage. That's not what a brainstorm is about.

# Intention

A distributed journalism for 4 classes of users:

## Journalists

A blog- or Substack-like¹ experience for writing articles and publishing them in one or more topically arranged personal feeds. They may also set pricing for various tiers of access.

Value propositions:
* Independence and freedom from capture.
* Easy ability to affiliate with outlets interested in local journalism.
* Access to professional networking.

¹ But, crucially, modulo the Nazi Bar.

## Publishers

A platform for managing articles from Journalists who may be directly retained or contracted on a per-article basis. Allows for the composition of a feed from many authors managed by a chief editor. Enhance discoverability and prestige if legacy media outlets can be persuaded to use the platform as at least an affiliate portal.

Value propositions:
* Access local sources and journalists anywhere in the world at need without needing the budget for international staff.
* Allow the resale of in-house articles to foreign markets.

## Readers

A central platform for reading the news from a wide variety of writers and outlets. Readers may discover additional writers by association, as the platform will show (a) publication affiliations of the writers whose content they like, and conversely (b) specific writers whose articles they like when licensed.

Value propositions:
* A central source and reading experience for many outlets
* A central payment portal s.t. one-time access to articles with micropayments doesn't require signing up with a thousand shady services

## Other professionals

People who perform journalistic services, but not directly to readers: Photographers, editors, local fixers and contacts.

# Not for profit

The vision is of something I wish existed, not of a way to make money. Ideally and ideologically, it should probably be organised around some kind of collective ownership or co-operative, or perhaps a governing non-profit or benefit corporation. Discussion here should be concerned with "how to maintain it and keep it afloat", not "how to make it generate profit". Profit must be possible for professionals, but the aim is for money to go from readers/customers to writers/professionals/creators and publishers, with only a necessary maintenance trickle for the project.

# Central features

## Privacy

* Communications and connections shall be protected via E2E encryption and tier-based access permissions, e.g. "contact X is in permission group P and may read name and email but not phone number and address"
* Trust networks: the platform cannot police everyone, but users may attach (a small, simple set of) trust levels to connections, so e.g. a Journalist can tell if an Editor is considered credible by sources they trust. This area needs rich fleshing out and discussion.

## Data freedom

Media capture is socially very dangerous. The platform shall be designed from the outset and as a guaranteed feature to allow for easy access to your own data.

* The platform code, perhaps after an initial delay to allow for first-mover platform advantage (which seems fair for the creator), MUST BE offered as FOSS under a suitable licence. Any first-mover delay MUST BE constrained to a fixed, non-negotiable deadline (perhaps with a brief extension period for emergencies only, e.g. a week to purge accidentally committed PII and conduct an audit; but this MUST NOT be constructed s.t. it can be abused indefinitely or to a ludicrous extent like doubling).
* Creators MUST, from day one, be able to export all the content they themselves author. No one's copyrighted work shall be held captive.
* Creators MUST, perhaps after an initial first-mover delay, be able to export their contact graph.
* The FOSS software MUST be able to import such an export from other sites. This shall include the contact graph, albeit with any necessary adjustments to meet privacy and security needs (e.g. to guard against impersonators gaining access to trust ratings).
* A necessary and contractually stipulated guarantee shall be: In the event of evil oligarch takeover, anyone shall be free to incorporate to set up their own payment processor etc., run a copy of the service, and invite anyone who likes to migrate, in order to ensure that powerful ideologues cannot as easily take over the media ecosystem.
* It must be easy to control your own domain name if you so desire, while still remaining within and accessible/discoverable via the platform.

## Editorial policy

A balance of strong appreciation for the value of free speech with necessary caution. The editorial policy shall make mention of the famous story of the Nazi Bar.

The launch phase may be more opinionated and dictatorial, but MUST BE legally constrained to an initial first mover phase. The project will want to establish an editorial and community voice. However, it is necessary in order to serve press freedom that a central authority shall not excessively dictate content, so editorial controls must loosen, albeit not to the degree of becoming a Nazi bar.

The editorial stance preferred shall be broad and include the centre as well as the left, though stopping short of tankies. Fascist or fascist-adjacent positions such as pro-Trump, MAGA, or AfD will not be welcome.

Editorial stance shall strongly emphasise high factuality. Hence, pseudoscience and denialist views such as antivaxx, climate change denial, ‘race realism’, etc. shall be unwelcome.

## LLM content policy

Whatever role LLM usage may or may not take in software development, any LLM use in content production must be plainly labelled and provide users the full ability to opt out.

A categorical ban on genAI content could be considered, but might not be realistic. However, the platform should AT LEAST protect users from ingesting any AI generated content without disclosure or against their wishes.

* Any content generated or edited with genAI MUST BE plainly labelled.
* Readers must be able to filter content (articles, outlets, writers) by stated LLM usage policy.
* Journalists, Publishers, and Professionals must be able to filter their connections by LLM usage.
* Repeated or flagrantly intentional violation of LLM disclosure policies must involve real consequences, including but not limited to losing access (temporarily? permanently?) to the ability to affirm (claim) LLM *non*-usage ("why should we trust you now?").

## Search bubbles and diversity

While the platform may impose a broad ideological filter that skews left of centre, it shall be BROAD and include a diversity of viewpoints. Readers should ideally be able to opt into a diversity of viewpoints to avoid excessively locking them into echo chambers, which is a risk that an overall editorial bent combined with trust networks will naturally tend toward, and must be guarded against.

The desire for diversity means that the platform might accept a somewhat wider range of opinions than the creators are strictly comfortable with. In return, strict honesty will be expected and demanded; mislabelled positions should have consequences.

In order to avoid being draconian censorship, many enforcement actions may stop short of delisting or banning, but may involve visible flagging and warnings, lack of promotion and shorter reach, financial withholding for provable offences, etc.

# Community

There are heaps of policies and ToC stuff that any good project needs to prevent harassment, ban bigotry, etc. They are not detailed here because (a) I don't pretend to have the expertise to write them, and (b) this document is intended to set out novel or project-specific ideas, not boilerplate -- however critical and essential they may be for actually carrying out a project. The reader should assume that the platform will discuss and adopt suitable principles here.

The platform should actively encourage a positively critical community, e.g. encouraging setting up communities on Reddit or similar where representatives engage in good faith but do not control the discourse.

# Connections

## Discovery

Inspired by BlueSky, allow a form of double opt-in discovery. The rough model is: Take a service, e.g. email, and a user/identifier A (e.g. an email address). A publishes hashes of their contact list in the form of *hashes of* "email:A:B" and "email:B:A" for each contact B. When contact B does the same and the entries already exist, the mutual connection is confirmed. This could work for any service provided that a method of proof of ownership exists (SMS/phone, email, WhatsApp, Signal, etc.)

## Anti lock-in and communications

The platform should NOT try to be a secure communications platform on top of everything else. It should not be considered secure in terms of metadata. Rather, it should facilitate sharing contact information in a controlled manner governed by configurable permissions and E2E encryption. Actual communication would then be deferred to whatever people are comfortable with: Email, phone number, WhatsApp, whatever.

Multi-channel publication should be encouraged. Easy integration should be encouraged and platform connection plugins should be easy to add (every article published also shows up in your Bluesky feed, stuff like that).

## Connection properties

When making a connection, a user gains secure, E2E gated access to their encrypted profile fields. In order to make sure they can keep people straight even if they lose access, the connection itself must carry some metadata:

* Display name/description s.t. you still know who that was
* Trust/bias ratings, e.g. maybe two likert scores for factuality and bias, maybe a third for how trustworthy they are with confidential and sensitive information

# Trust model

Trust must be distributed, but not overly complex for UX.

Profiles should be able to display verifiable professional credentials and accreditations. Institutions should be able to vouch for their members, and people may opt to vouch for their contacts. This may help the growth of organic connection networks.

# Permission model

Must carefully combine optimal simplicity with sufficient granularity. It's important for professionals to be able to *selectively* share information, be it name, contact info, bios, or their own connection networks. OTOH it's just as important not to make the UX of the system excessively complex, or else user error will defeat the power that flexibility was supposed to give.

It is better to err on the side of "too private" (which can be relaxed later) than "too public" (which can leak sensitive information).

# Monetisation

Allow users to pay for subscriptions, and also make it easy to make one-off micropayments for (purchased, hence permanent?) access to paywalled articles, s.t. people can reasonably share paywalled links and expect to have them read without their readers buying a hundred $10 subscriptions. This must be frictionless and transparent. It would need careful discussion: microtransactions suck, but so does journalists not getting paid, and so does forcing users to set up myriad subscriptions for just an article here or there. The design here should maximise adoption while balancing all interests, not maximise profit.

Allow Journalists and other professionals to set their own fee schedules.

Allow Publishers to purchase articles exclusively, semi-exclusively (e.g. "we can run it and you can run it in your personal newsletter, but no other outlet"), with or without time limit on exclusivity.

Professionals like editors, photographers, etc. can use the platform for freelancing/networking.

# What would make it viable

If a platform like this were ever to be viable, it would need to overcome the network effect barrier. *Some* big name would need to support it and start attracting enough people to start forming network connections. If the idea is good and the implementation is sound, organic growth can take off, and the network effect can help keep people on the platform in spite of being easy by design to migrate away from. But no illusions should be held by anyone that mere technical adequacy, even excellence, is enough for a project of this sort. Any network stands or falls with its participants, and here that requires visibility. As grass-roots as possible, but at some point you'd need a famous person or media outlet with some degree of prestige to draw in a readership.

# Anti-slop and anti-scam

This needs a lot of thought and a lot of work. The platform must not be taken over by bots and must not be overrun with undisclosed AI slop. Privacy must be respected, but verifying real human identity is also important. Research should be done into meaningful compromises, e.g. maybe there are government services like post offices that could provide some form of anonymised real-human verification, or maybe there are companies that (ethically, with meaningful PII protection) provide such services.

Trust networks must exist in order to ensure some kind of quality control without necessitating a central authority for truth, but such trust networks must be shallow and simple enough to comprehend and to perform well in a software-runtime sense

# Technical platform

Entirely agnostic. Maybe it sits on ATProto somehow. Maybe it uses something else. Maybe it's 100% custom. 

Maybe this is not a *platform*, but a platform *layer* that sits on top of other platforms in some fashion.

# The author's role in this

I, Petter, am a software developer, but I’m not a _frontend_ developer, and this is a very frontend-heavy idea. I also have zero experience of journalism or any adjacent field. I basically have zero relevant expertise and experience. I am not even qualified to judge whether this is a good idea.

I'm writing this because I think it *might* be a good idea, and it kind of feels like something I wish existed, not necessarily something I am suited to help bring into existence beyond the initial idea (though if it did exist and I could afford to, I suppose I would like to help on the backend development bits I *am* qualified for). But if someone reads this doc, thinks it's a good idea, and wants to be in charge of doing it, then be my guest even if I'm not involved. I just wish such a platform existed.












