<!--
author:   ICoBC - International Council on Badges and Credentials
email:    info@icobc.net
version:  1.0.0
language: en
narrator: UK English Female
comment:  A two-hour Knowledge course that explains what the European Digital Identity Wallet is, what eIDAS 2.0 requires, how wallet content and holder control work, and who does what in your organisation.

@style
:root { --icobc-navy:#02375B; --icobc-orange:#F78222; --icobc-cyan:#5DCAE7; --icobc-lime:#B1CF37; --icobc-mist:#F1F5F8; --icobc-line:#D8E2E9; --icobc-muted:#4F6576; }
body { font-family: "Open Sans", Arial, sans-serif; }
h1, h2, h3, h4 { color: var(--icobc-navy); }
a { color: var(--icobc-navy); }
table th { background: var(--icobc-mist); color: var(--icobc-navy); }
blockquote { border-left: 4px solid var(--icobc-orange); background: var(--icobc-mist); padding: 8px 16px; }
@end
-->

# Digital Identity and the EUDI Wallet: Essentials

What the European Digital Identity Wallet is, what it changes for credentials, and what it leaves unchanged.

## About this course

This course explains the European Digital Identity Wallet (EUDI Wallet) in plain terms. You learn what a wallet is, what it holds, who takes part in a wallet exchange, how the holder stays in control, and where Europe and Germany stand. The course is vendor-neutral and teaches concepts, rules and the reasons behind them.

**Who it is for**

- Learning and development and corporate academy leads
- HR, talent acquisition and mobility teams
- HR and learning technology owners
- Programme and micro-credential leads
- Quality, registry and admissions staff
- Education IT and credential operations
- Professional bodies and sector associations
- Policy makers and public agencies
- Earners and learners

**Learning outcomes**

After this course you can:

1. Explain what eIDAS 2.0 requires from Member States and by when.
2. Distinguish person identification data, attestations of attributes and other credentials held in a wallet.
3. Explain selective disclosure and holder control with an education or employment example.
4. Identify who in your organisation would act as issuer, holder support or relying party.

**Workload:** self-paced, about 2 hours of notional learning. There are no prerequisites.

**Assessment:** a knowledge check with 12 questions, including scenario items. Each module also has a short quiz with feedback.

**Badge:** "Digital Identity and the EUDI Wallet: Essentials (Knowledge, L1)", alignment code ICSF-IDWL-L1-K. The evidence is a passed knowledge check. The badge shows that you passed a check of your understanding of the concepts. It does not prove competence in a job.

**Framework alignment:** ICoBC Credentialing Skills Framework (ICSF), skill IDWL "Digital identity and wallets" (VRITE pillar: Trustworthiness), level L1 "Contribute", stage K "Knowledge".

| Outcome | Module | How it is assessed |
|---|---|---|
| 1. Explain what eIDAS 2.0 requires from Member States and by when | From eID to wallet; Status in Europe and in Germany (dated unit) | Module quizzes; knowledge check questions 1 to 3 |
| 2. Distinguish person identification data, attestations of attributes and other credentials | What a wallet holds | Module quiz; knowledge check questions 4 to 6 |
| 3. Explain selective disclosure and holder control with an education or employment example | Privacy by design in the wallet | Module quiz; knowledge check questions 7 to 9 |
| 4. Identify who in your organisation would act as issuer, holder support or relying party | Issuers, holders and relying parties | Module quiz; knowledge check questions 10 to 12 |

<details><summary>Facilitator notes</summary>

The self-paced course can be used alone. For a half-day workshop, use the practice activities as group tasks and add a 30-minute organisation mapping session after Module 3. Ask participants to bring a list of the credentials their organisation issues and the processes in which people prove who they are. Check the dated unit in Module 5 before every delivery, because wallet plans change.

</details>

## From eID to wallet

### Why a wallet at all

Many people already prove who they are online. They use a national electronic identity (eID), a bank login or an account with a large platform. Each of these works in its own place. An eID card usually works with public services. A bank login works with the bank. A platform account works where the platform is accepted.

A digital identity wallet is an application, held and controlled by a person, that stores digital proofs about that person and presents them to others when the person chooses. The proofs can be an official identity record, a degree, a work contract confirmation or a training certificate. The wallet lets the person decide what to show, to whom and when.

Three terms help here:

- An **account** is a record kept by an organisation. The organisation controls it and can change or close it.
- A **PDF** is a file. It can be copied and edited, and a reader cannot easily check who issued it or whether it is still valid.
- A **wallet credential** is a digital record signed by an issuer and stored by the holder. A verifier can check the signature and the status without calling the issuer each time.

### What eIDAS 2.0 is

eIDAS is the EU regulation on electronic identification and trust services. The 2014 version created rules for electronic signatures, seals and cross-border recognition of national eID schemes. The revised regulation, often called eIDAS 2.0, adds the European Digital Identity Framework. Its central requirement is that Member States offer citizens, residents and businesses a digital identity wallet.

<!-- VERIFY: Regulation (EU) 2024/1183 amending Regulation (EU) No 910/2014; entry into force 20 May 2024. -->

### Key requirements in outline

The notes for this course give you these anchor facts:

- Each Member State must offer at least one wallet by 24 December 2026.
- Regulated private sectors must accept the wallet about one year after issuance starts.
- Readiness varies widely between Member States.

Regulation is supported by technical specifications, an architecture and reference framework, and implementing acts. These documents define what wallets must do and how they connect to issuers and verifiers.

<svg viewBox="0 0 800 450" width="100%" role="img" xmlns="http://www.w3.org/2000/svg">
  <title>From eID and accounts to a wallet</title>
  <desc>Three boxes from left to right: national eID and logins in separate places, then eIDAS 2.0 as the legal step, then the EUDI Wallet that the holder controls.</desc>
  <rect x="0" y="0" width="800" height="450" fill="#FFFFFF"/>
  <rect x="30" y="120" width="210" height="200" rx="6" fill="#F1F5F8" stroke="#D8E2E9" stroke-width="2"/>
  <text x="135" y="160" text-anchor="middle" font-family="Open Sans, Arial, sans-serif" font-size="16" font-weight="bold" fill="#02375B">Before</text>
  <text x="135" y="195" text-anchor="middle" font-family="Open Sans, Arial, sans-serif" font-size="14" fill="#02375B">National eID</text>
  <text x="135" y="225" text-anchor="middle" font-family="Open Sans, Arial, sans-serif" font-size="14" fill="#02375B">Bank login</text>
  <text x="135" y="255" text-anchor="middle" font-family="Open Sans, Arial, sans-serif" font-size="14" fill="#02375B">Platform account</text>
  <text x="135" y="295" text-anchor="middle" font-family="Open Sans, Arial, sans-serif" font-size="14" fill="#4F6576">Separate silos</text>
  <line x1="245" y1="220" x2="300" y2="220" stroke="#02375B" stroke-width="2"/>
  <polygon points="300,212 316,220 300,228" fill="#02375B"/>
  <rect x="320" y="120" width="170" height="200" rx="6" fill="#B1CF37" stroke="#02375B" stroke-width="2"/>
  <text x="405" y="175" text-anchor="middle" font-family="Open Sans, Arial, sans-serif" font-size="16" font-weight="bold" fill="#02375B">eIDAS 2.0</text>
  <text x="405" y="210" text-anchor="middle" font-family="Open Sans, Arial, sans-serif" font-size="14" fill="#02375B">EU regulation</text>
  <text x="405" y="235" text-anchor="middle" font-family="Open Sans, Arial, sans-serif" font-size="14" fill="#02375B">Member States</text>
  <text x="405" y="260" text-anchor="middle" font-family="Open Sans, Arial, sans-serif" font-size="14" fill="#02375B">must offer a wallet</text>
  <line x1="495" y1="220" x2="550" y2="220" stroke="#02375B" stroke-width="2"/>
  <polygon points="550,212 566,220 550,228" fill="#02375B"/>
  <rect x="570" y="120" width="200" height="200" rx="6" fill="#FFFFFF" stroke="#02375B" stroke-width="2"/>
  <text x="670" y="160" text-anchor="middle" font-family="Open Sans, Arial, sans-serif" font-size="16" font-weight="bold" fill="#02375B">After</text>
  <text x="670" y="195" text-anchor="middle" font-family="Open Sans, Arial, sans-serif" font-size="14" fill="#02375B">EUDI Wallet</text>
  <text x="670" y="225" text-anchor="middle" font-family="Open Sans, Arial, sans-serif" font-size="14" fill="#02375B">Held by the person</text>
  <text x="670" y="255" text-anchor="middle" font-family="Open Sans, Arial, sans-serif" font-size="14" fill="#02375B">Holder decides</text>
  <text x="670" y="285" text-anchor="middle" font-family="Open Sans, Arial, sans-serif" font-size="14" fill="#4F6576">what to share</text>
  <text x="400" y="400" text-anchor="middle" font-family="Open Sans, Arial, sans-serif" font-size="14" fill="#4F6576">Navy marks the holder and the core idea; lime marks policy.</text>
</svg>

### What a wallet changes and what it leaves unchanged

A wallet changes where credentials live and who controls the presentation. It makes checking faster and gives the holder a record of what was shared.

A wallet leaves several things unchanged:

- Issuers still decide who earns a credential and on what basis.
- Quality assurance, assessment and accreditation still sit with the bodies that run them.
- A credential is still only as good as the issuer's rules and evidence.
- Employers and institutions still decide what they accept and why.

Holding a credential in a wallet does not make it more valid. It makes it easier to present and check.

**Worked example: Two organisations, one question**

At a corporate academy, a learning lead asks whether the new wallet will replace the learning management system. The answer is no. The learning management system keeps records, learning paths and reports. The wallet gives learners a way to hold and present a completion credential outside the academy's systems.

At a university, the registrar asks whether the wallet changes who may award a degree. It does not. The university still awards degrees under its own rules and national law. The wallet gives graduates a way to hold a digital copy of the award that an employer can check.

**Practice activity: Account, PDF or wallet credential**

List three proofs your organisation handles today, for example a training certificate, an employee ID or a degree confirmation. For each one, write down:

1. Where it is stored today (an account, a PDF, a paper copy or something else).
2. Who can check it and how.
3. What would change if the person held it as a signed credential in a wallet.

Keep your list for Module 3.

**Question 1.** What is a digital identity wallet?

[( )] A database kept by an employer with all employee records
[(X)] An application controlled by a person that stores signed digital proofs and presents them when the person chooses
[( )] A PDF file with a scanned copy of an identity document
[( )] A social media profile verified by a platform

****
A wallet is controlled by the holder. An employer database or a platform profile is controlled by an organisation, and a scanned PDF carries no signature that a verifier can check.
****

**Question 2.** What does eIDAS 2.0 require from Member States?

[( )] To replace all national identity cards within one year
[( )] To ban private identity providers
[(X)] To offer citizens, residents and businesses at least one digital identity wallet
[( )] To store all credentials in one central EU database

****
The core requirement is that each Member State offers at least one wallet. The regulation does not create a central credential database and does not ban private providers.
****

**Question 3.** Which statement about validity is correct?

[( )] A credential in a wallet is automatically more trustworthy than a paper one
[( )] A wallet makes every issuer equally reliable
[( )] A wallet removes the need for quality assurance
[(X)] A credential is only as trustworthy as the issuer's rules and evidence, whatever the format

****
The wallet changes storage and presentation. Trust still depends on the issuer, its assessment rules and its accreditation or recognition.
****

## What a wallet holds

### Three kinds of content

A wallet can hold different kinds of digital proofs. The EUDI framework distinguishes several of them. For this course, we use three groups, shown as three compartments of one wallet.

**1. Person identification data (PID).** PID is a core set of attributes that identifies a natural person, such as name, date of birth and nationality. Member States provide PID through the wallet. It is the official identity record.

<!-- VERIFY: Exact mandatory PID attribute set is defined in the implementing acts and the Architecture and Reference Framework; check current version before listing attributes. -->

**2. Electronic attestations of attributes.** An attestation of attribute is a statement from an issuer about a characteristic of the holder, for example "holds a master's degree", "is licensed to practise" or "is employed by organisation X". The framework distinguishes qualified attestations, issued by qualified trust service providers, and attestations issued by or for public sector bodies. Other attestations are also possible.

**3. Other credentials.** A wallet can also hold other digital credentials that are not formal attestations in the legal sense. Examples are a course completion badge, a membership card or an event pass. Their legal weight depends on the issuer and the rules that apply. An open badge from a training provider is useful for many purposes, yet it carries a different legal status than a qualified attestation.

### Formats and protocols

Wallets need agreed technical formats and exchange protocols. The specifications for the EUDI Wallet include:

- **OpenID4VC**, a family of protocols for issuing and presenting credentials.
- **SD-JWT VC**, a credential format that supports selective disclosure.
- **ISO mdoc**, a credential format developed for mobile documents, such as the mobile driving licence.

This is the status of these technologies: they are specified for the EUDI Wallet, while tooling and education profiles are still maturing. You do not need to learn the technical details at this level. You need to know that formats and protocols exist, that they are standardised, and that they determine whether credentials from different issuers work in different wallets.

<!-- VERIFY: Confirm which formats the current Architecture and Reference Framework lists as mandatory or recommended before stating any as required. -->

### Education credentials in wallets

DC4EU is a European pilot project on education credentials in wallets. It has published pilot artefacts, including user journeys and data models based on the European Learning Model (ELM). National adoption of education credentials in wallets is at an early stage. Treat the pilot material as a source of examples, and check with your national authority before assuming that your credentials will be accepted in a wallet.

### Credentials are not the same as identity

A degree attestation does not identify a person by itself. It states a fact about a holder. To connect the fact to a person, a verifier may ask for PID as well, or may rely on cryptographic binding between the attestation and the holder's wallet. This is why the three compartments work together.

<svg viewBox="0 0 800 450" width="100%" role="img" xmlns="http://www.w3.org/2000/svg">
  <title>A wallet with three compartments</title>
  <desc>One wallet outline with three labelled compartments: person identification data, attestations of attributes, and other credentials.</desc>
  <rect x="0" y="0" width="800" height="450" fill="#FFFFFF"/>
  <rect x="100" y="50" width="600" height="340" rx="6" fill="#F1F5F8" stroke="#02375B" stroke-width="2"/>
  <text x="400" y="85" text-anchor="middle" font-family="Open Sans, Arial, sans-serif" font-size="18" font-weight="bold" fill="#02375B">EUDI Wallet (held by the person)</text>
  <rect x="130" y="110" width="170" height="240" rx="6" fill="#B1CF37" stroke="#02375B" stroke-width="2"/>
  <text x="215" y="150" text-anchor="middle" font-family="Open Sans, Arial, sans-serif" font-size="16" font-weight="bold" fill="#02375B">1. PID</text>
  <text x="215" y="180" text-anchor="middle" font-family="Open Sans, Arial, sans-serif" font-size="14" fill="#02375B">Person identification</text>
  <text x="215" y="200" text-anchor="middle" font-family="Open Sans, Arial, sans-serif" font-size="14" fill="#02375B">data</text>
  <text x="215" y="240" text-anchor="middle" font-family="Open Sans, Arial, sans-serif" font-size="14" fill="#02375B">Name</text>
  <text x="215" y="262" text-anchor="middle" font-family="Open Sans, Arial, sans-serif" font-size="14" fill="#02375B">Date of birth</text>
  <text x="215" y="284" text-anchor="middle" font-family="Open Sans, Arial, sans-serif" font-size="14" fill="#02375B">Nationality</text>
  <text x="215" y="320" text-anchor="middle" font-family="Open Sans, Arial, sans-serif" font-size="14" fill="#02375B">Lime: public</text>
  <rect x="315" y="110" width="170" height="240" rx="6" fill="#5DCAE7" stroke="#02375B" stroke-width="2"/>
  <text x="400" y="150" text-anchor="middle" font-family="Open Sans, Arial, sans-serif" font-size="16" font-weight="bold" fill="#02375B">2. Attestations</text>
  <text x="400" y="180" text-anchor="middle" font-family="Open Sans, Arial, sans-serif" font-size="14" fill="#02375B">of attributes</text>
  <text x="400" y="240" text-anchor="middle" font-family="Open Sans, Arial, sans-serif" font-size="14" fill="#02375B">Degree</text>
  <text x="400" y="262" text-anchor="middle" font-family="Open Sans, Arial, sans-serif" font-size="14" fill="#02375B">Licence to practise</text>
  <text x="400" y="284" text-anchor="middle" font-family="Open Sans, Arial, sans-serif" font-size="14" fill="#02375B">Employment status</text>
  <text x="400" y="320" text-anchor="middle" font-family="Open Sans, Arial, sans-serif" font-size="14" fill="#02375B">Cyan: education</text>
  <rect x="500" y="110" width="170" height="240" rx="6" fill="#F78222" stroke="#02375B" stroke-width="2"/>
  <text x="585" y="150" text-anchor="middle" font-family="Open Sans, Arial, sans-serif" font-size="16" font-weight="bold" fill="#02375B">3. Other</text>
  <text x="585" y="180" text-anchor="middle" font-family="Open Sans, Arial, sans-serif" font-size="14" fill="#02375B">credentials</text>
  <text x="585" y="240" text-anchor="middle" font-family="Open Sans, Arial, sans-serif" font-size="14" fill="#02375B">Course badge</text>
  <text x="585" y="262" text-anchor="middle" font-family="Open Sans, Arial, sans-serif" font-size="14" fill="#02375B">Membership card</text>
  <text x="585" y="284" text-anchor="middle" font-family="Open Sans, Arial, sans-serif" font-size="14" fill="#02375B">Event pass</text>
  <text x="585" y="320" text-anchor="middle" font-family="Open Sans, Arial, sans-serif" font-size="14" fill="#02375B">Orange: employer</text>
  <text x="400" y="425" text-anchor="middle" font-family="Open Sans, Arial, sans-serif" font-size="14" fill="#4F6576">Colours are examples of typical issuers; the legal status depends on the issuer and the rules.</text>
</svg>

**Worked example: Sorting a wallet in two settings**

A corporate academy issues a completion credential for an internal leadership programme. Is it PID? No, because it does not identify the person as a natural person. Is it a qualified attestation? Not unless a qualified trust service provider issues it. It is an "other credential" that the employer may accept internally and that the holder can show to others who choose to trust it.

A university issues a bachelor's degree credential as a signed digital record. This is an attestation of an attribute about the holder, "holds this degree". Whether it counts as a qualified or public sector attestation depends on how the university and national rules set it up. The student's PID, issued by the state, sits in a different compartment.

**Practice activity: Sort the compartments**

Sort these items into PID, attestation of attribute or other credential. Write one sentence of reasoning for each.

1. Full legal name and date of birth, issued by the state.
2. Confirmation that a person holds a vocational qualification, issued by a college.
3. A badge for attending a one-day internal workshop.
4. Confirmation of current employment from an employer.
5. A professional body membership card.

Compare your answers with a colleague. Some items depend on the rules in your country, so note the points where you are unsure.

**Question 4.** Which item is person identification data?

[( )] A degree confirmation from a university
[(X)] A set of attributes such as name, date of birth and nationality that identifies a natural person
[( )] A workshop attendance badge
[( )] An employer's confirmation of a job title

****
PID identifies the person. A degree, a badge and a job title confirmation are statements about attributes or achievements of an already identified person.
****

**Question 5.** A training provider issues a signed completion badge. What is the most careful description?

[( )] It is automatically a qualified electronic attestation of attributes
[( )] It replaces the holder's person identification data
[(X)] It is a credential whose legal status depends on the issuer and the rules that apply
[( )] It has no value because it is not issued by a state

****
Many useful credentials are not qualified attestations. Their value depends on the issuer's reputation, the quality of the assessment and what the receiving party accepts.
****

**Question 6.** What is the status of the formats OpenID4VC, SD-JWT VC and ISO mdoc?

[( )] They are finished, and all education profiles are complete
[( )] They are only used in non-European wallets
[( )] They are optional and have no link to the EUDI Wallet
[(X)] They are specified for the EUDI Wallet, while tooling and education profiles are still maturing

****
These technologies are specified for the EUDI Wallet. Education profiles and tools are still developing, so check current status before you plan a project.
****

## Issuers, holders and relying parties

### The three roles

A wallet exchange involves three roles. The same organisation can hold more than one role in different situations.

- The **issuer** creates and signs a credential and gives it to the holder. Examples are a university issuing a degree, an employer issuing an employment confirmation or a state issuing PID.
- The **holder** is the person who stores the credential in a wallet and decides when to present it.
- The **relying party** receives a presentation from the holder and decides whether to accept it. Examples are an employer checking a degree, a bank checking identity or a university checking an entry qualification.

A fourth function sits around these roles: **holder support**. Holders need help to install the wallet, recover from a lost device, understand a request and report a problem. An organisation that issues credentials usually answers questions from holders about those credentials. This help desk role is easy to forget.

### How the flow works

1. The holder asks the issuer for a credential, or the issuer offers one.
2. The issuer checks the facts, signs the credential and sends it to the holder's wallet.
3. Later, a relying party sends a request describing what it needs.
4. The wallet shows the holder the request. The holder agrees or declines.
5. If the holder agrees, the wallet sends a presentation to the relying party.
6. The relying party checks the issuer's signature, the credential's status and whether it trusts the issuer.

The relying party does not need to phone the issuer for each check. The trust relies on signatures and on lists or registries of trusted issuers.

### Trust and registration

A relying party has to know which issuers it can trust. The EU framework provides for trusted lists and, for relying parties, registration so that the wallet can show the holder who is asking for data and why. Details come from the implementing acts and national arrangements.

<!-- VERIFY: Describe relying party registration and trusted list arrangements only as far as the current implementing acts confirm; avoid naming specific articles. -->

### Roles in your own organisation

The important question for your work is not abstract. It is: who would do this in our organisation?

- **Issuer:** the unit that owns the facts and the rules, for example registry, admissions, certification, HR records or the academy's programme team. The issuer needs authority, quality rules and a way to revoke or update a credential.
- **Holder support:** the unit that answers questions, for example a service desk, learner support, HR service centre or credential operations team.
- **Relying party:** the units that receive and check credentials, for example talent acquisition, admissions, onboarding, compliance or mobility teams.

The same organisation often holds all three roles. A university issues degrees, checks entry qualifications and supports its own students. A company issues internal certifications and checks external qualifications of new hires.

### Agents and the wallet

AI assistants and software agents can act on behalf of a person, for instance to fill in forms or prepare an application. A person's wallet holds that person's identity and credentials. An AI agent has its own identity and its own limits of authority. Keep these apart. The wallet belongs to the person, and the person remains accountable for what is shared. If an agent is allowed to request or present something, that permission needs to be explicit, limited and recorded. An agent does not become the holder simply because it uses the person's device.

<!-- VERIFY: The EUDI framework does not define agent identity in the current specifications as far as known; keep statements general and check before adding specifics. -->

<svg viewBox="0 0 800 450" width="100%" role="img" xmlns="http://www.w3.org/2000/svg">
  <title>Flow from issuer to holder to relying party</title>
  <desc>Three boxes in a row: an issuer in cyan, the holder with a wallet in navy outline, and a relying party in orange. Arrows show issuing a credential and presenting selected data. A holder support box sits below the holder.</desc>
  <rect x="0" y="0" width="800" height="450" fill="#FFFFFF"/>
  <rect x="30" y="130" width="200" height="130" rx="6" fill="#5DCAE7" stroke="#02375B" stroke-width="2"/>
  <text x="130" y="175" text-anchor="middle" font-family="Open Sans, Arial, sans-serif" font-size="16" font-weight="bold" fill="#02375B">Issuer</text>
  <text x="130" y="205" text-anchor="middle" font-family="Open Sans, Arial, sans-serif" font-size="14" fill="#02375B">University, college,</text>
  <text x="130" y="225" text-anchor="middle" font-family="Open Sans, Arial, sans-serif" font-size="14" fill="#02375B">employer, state</text>
  <rect x="300" y="130" width="200" height="130" rx="6" fill="#FFFFFF" stroke="#02375B" stroke-width="2"/>
  <text x="400" y="175" text-anchor="middle" font-family="Open Sans, Arial, sans-serif" font-size="16" font-weight="bold" fill="#02375B">Holder</text>
  <text x="400" y="205" text-anchor="middle" font-family="Open Sans, Arial, sans-serif" font-size="14" fill="#02375B">Person with a wallet</text>
  <text x="400" y="225" text-anchor="middle" font-family="Open Sans, Arial, sans-serif" font-size="14" fill="#02375B">Decides what to share</text>
  <rect x="570" y="130" width="200" height="130" rx="6" fill="#F78222" stroke="#02375B" stroke-width="2"/>
  <text x="670" y="175" text-anchor="middle" font-family="Open Sans, Arial, sans-serif" font-size="16" font-weight="bold" fill="#02375B">Relying party</text>
  <text x="670" y="205" text-anchor="middle" font-family="Open Sans, Arial, sans-serif" font-size="14" fill="#02375B">Employer, admissions,</text>
  <text x="670" y="225" text-anchor="middle" font-family="Open Sans, Arial, sans-serif" font-size="14" fill="#02375B">service provider</text>
  <line x1="235" y1="175" x2="290" y2="175" stroke="#02375B" stroke-width="2"/>
  <polygon points="290,167 306,175 290,183" fill="#02375B"/>
  <text x="262" y="160" text-anchor="middle" font-family="Open Sans, Arial, sans-serif" font-size="14" fill="#02375B">1 Issue</text>
  <line x1="505" y1="175" x2="560" y2="175" stroke="#02375B" stroke-width="2"/>
  <polygon points="560,167 576,175 560,183" fill="#02375B"/>
  <text x="532" y="160" text-anchor="middle" font-family="Open Sans, Arial, sans-serif" font-size="14" fill="#02375B">2 Present</text>
  <line x1="670" y1="265" x2="670" y2="330" stroke="#D8E2E9" stroke-width="2"/>
  <line x1="670" y1="330" x2="130" y2="330" stroke="#D8E2E9" stroke-width="2"/>
  <line x1="130" y1="330" x2="130" y2="265" stroke="#D8E2E9" stroke-width="2"/>
  <text x="400" y="320" text-anchor="middle" font-family="Open Sans, Arial, sans-serif" font-size="14" fill="#4F6576">3 Relying party checks signature, status and trust in the issuer</text>
  <rect x="300" y="360" width="200" height="60" rx="6" fill="#F1F5F8" stroke="#02375B" stroke-width="2"/>
  <text x="400" y="387" text-anchor="middle" font-family="Open Sans, Arial, sans-serif" font-size="14" fill="#02375B">Holder support</text>
  <text x="400" y="407" text-anchor="middle" font-family="Open Sans, Arial, sans-serif" font-size="14" fill="#4F6576">Help with the wallet</text>
  <line x1="400" y1="265" x2="400" y2="355" stroke="#02375B" stroke-width="2" stroke-dasharray="6 4"/>
</svg>

**Worked example: Roles in a corporate academy and in a college**

In a corporate academy, the programme team signs and issues a completion credential for a compliance course. The HR service centre answers questions from employees who cannot find the credential in their wallet. Talent acquisition acts as a relying party when it checks a candidate's qualification, and the onboarding team does the same for a licence needed for a role.

In a college, the registry issues diplomas and transcripts. The learner support desk helps students with wallet questions. The admissions office acts as a relying party when it checks a prior qualification from another institution, and the placement office checks identity and age of applicants for work placements.

**Practice activity: Map your organisation**

Use the list from Module 1. For each credential or proof, write:

1. Who would be the issuer.
2. Who would give holder support.
3. Who would be the relying party.
4. One question you cannot answer yet, for example who owns revocation.

Share the map with one colleague from another team.

**Question 7.** In a wallet exchange, which role decides whether to accept a presentation?

[( )] The issuer
[( )] The holder
[(X)] The relying party
[( )] The wallet application itself

****
The relying party receives the presentation and decides whether to accept it. The holder decides what to present, and the issuer decides what to issue.
****

**Question 8.** A registry signs and issues digital diplomas. Which role does it hold in that moment?

[( )] Relying party
[(X)] Issuer
[( )] Holder
[( )] Holder support only

****
The registry creates and signs the credential, so it acts as issuer. It may also give holder support and act as a relying party in other situations.
****

**Question 9.** An AI agent prepares a job application for a person. Which statement is correct?

[( )] The agent becomes the holder of the person's wallet
[( )] The agent's identity and the person's identity are the same thing
[( )] No permission is needed because the agent uses the person's device
[(X)] The wallet belongs to the person, and any authority given to the agent should be explicit, limited and recorded

****
The agent has its own identity and limits of authority. The person remains the holder and stays accountable for what is shared.
****

## Privacy by design in the wallet

### Holder control

The wallet is built so that the holder has control. In practice this means:

- The holder decides whether to accept a credential and whether to keep it.
- The holder sees each request and decides whether to answer it.
- The holder sees who is asking and what data they ask for.
- The holder can often see a record of past presentations.

These features do not remove all risk. They give the person a clear point of decision.

### Selective disclosure

Selective disclosure means that the holder shares only the parts of a credential that a relying party needs. A related idea is data minimisation, which requires that a party asks only for what it needs.

Take a degree credential with several attributes: name, degree title, grade, date of award and institution. A relying party that needs to know whether a candidate holds a bachelor's degree does not need the grade. With selective disclosure the holder can show the degree title and institution and keep the grade private.

A simple case is age. A service needs to know that a person is over 18. The service does not need the date of birth. A wallet can present only the statement "over 18", signed by the issuer. This is sometimes called an attribute-based proof.

### Why SD-JWT VC and ISO mdoc matter here

Formats such as SD-JWT VC and ISO mdoc support selective disclosure by design. A credential in these formats can be split into separate attributes, and the holder reveals only the chosen ones. The relying party can still check that those attributes were signed by the issuer. A plain PDF cannot do this. A PDF is shown whole or not at all.

### Limits and risks

Selective disclosure helps, though it does not solve everything.

- A relying party can still ask for too much. Registration and holder awareness help, and national supervision applies.
- Several presentations of the same credential may let parties link a person across contexts. The framework includes measures to reduce linkability, and their details are technical and still evolving.
- A holder can be pressured to share more than is needed. Rules and good practice for relying parties matter.
- Wallets do not remove the need for good records management by issuers and relying parties.

<!-- VERIFY: Confirm which unlinkability mechanisms the current specifications require; do not claim a specific cryptographic method. -->

### Control over deletion and revocation

A holder can usually delete a credential from the wallet. An issuer can revoke or suspend a credential, for example after an error or a withdrawal of a licence. A relying party checks status at the time of presentation. The holder controls what is shared, and the issuer controls whether the credential is still valid.

<svg viewBox="0 0 800 450" width="100%" role="img" xmlns="http://www.w3.org/2000/svg">
  <title>Selective disclosure of a degree credential</title>
  <desc>A credential with five attributes on the left. Two attributes, degree title and institution, are marked as shared. Three attributes, name, grade and date of award, are marked as kept private. An arrow leads to a relying party that receives only the shared attributes.</desc>
  <rect x="0" y="0" width="800" height="450" fill="#FFFFFF"/>
  <rect x="40" y="60" width="330" height="320" rx="6" fill="#F1F5F8" stroke="#02375B" stroke-width="2"/>
  <text x="205" y="95" text-anchor="middle" font-family="Open Sans, Arial, sans-serif" font-size="16" font-weight="bold" fill="#02375B">Degree credential in the wallet</text>
  <rect x="65" y="115" width="280" height="40" rx="6" fill="#5DCAE7" stroke="#02375B" stroke-width="2"/>
  <text x="205" y="141" text-anchor="middle" font-family="Open Sans, Arial, sans-serif" font-size="14" fill="#02375B">Degree title: shared</text>
  <rect x="65" y="165" width="280" height="40" rx="6" fill="#5DCAE7" stroke="#02375B" stroke-width="2"/>
  <text x="205" y="191" text-anchor="middle" font-family="Open Sans, Arial, sans-serif" font-size="14" fill="#02375B">Institution: shared</text>
  <rect x="65" y="215" width="280" height="40" rx="6" fill="#FFFFFF" stroke="#02375B" stroke-width="2" stroke-dasharray="6 4"/>
  <text x="205" y="241" text-anchor="middle" font-family="Open Sans, Arial, sans-serif" font-size="14" fill="#02375B">Grade: kept private</text>
  <rect x="65" y="265" width="280" height="40" rx="6" fill="#FFFFFF" stroke="#02375B" stroke-width="2" stroke-dasharray="6 4"/>
  <text x="205" y="291" text-anchor="middle" font-family="Open Sans, Arial, sans-serif" font-size="14" fill="#02375B">Date of award: kept private</text>
  <rect x="65" y="315" width="280" height="40" rx="6" fill="#FFFFFF" stroke="#02375B" stroke-width="2" stroke-dasharray="6 4"/>
  <text x="205" y="341" text-anchor="middle" font-family="Open Sans, Arial, sans-serif" font-size="14" fill="#02375B">Name: kept private</text>
  <line x1="375" y1="160" x2="470" y2="160" stroke="#02375B" stroke-width="2"/>
  <polygon points="470,152 486,160 470,168" fill="#02375B"/>
  <text x="425" y="145" text-anchor="middle" font-family="Open Sans, Arial, sans-serif" font-size="14" fill="#02375B">Holder agrees</text>
  <rect x="500" y="100" width="260" height="140" rx="6" fill="#F78222" stroke="#02375B" stroke-width="2"/>
  <text x="630" y="140" text-anchor="middle" font-family="Open Sans, Arial, sans-serif" font-size="16" font-weight="bold" fill="#02375B">Relying party</text>
  <text x="630" y="170" text-anchor="middle" font-family="Open Sans, Arial, sans-serif" font-size="14" fill="#02375B">Receives degree title</text>
  <text x="630" y="190" text-anchor="middle" font-family="Open Sans, Arial, sans-serif" font-size="14" fill="#02375B">and institution only</text>
  <text x="630" y="215" text-anchor="middle" font-family="Open Sans, Arial, sans-serif" font-size="14" fill="#02375B">Checks the issuer's signature</text>
  <text x="400" y="420" text-anchor="middle" font-family="Open Sans, Arial, sans-serif" font-size="14" fill="#4F6576">Solid frame: shared. Dashed frame: kept private. Illustrative example.</text>
</svg>

**Worked example: Showing what is needed and no more**

An HR department wants to confirm that a new hire holds a required safety certification. The certificate credential lists the holder's name, the certification title, the issue date, the expiry date and the assessment score. HR asks for the title and the expiry date only. The employee sees the request in the wallet, agrees and shares those two attributes. HR does not receive the score. HR checks the signature of the training provider and the status of the certificate.

A university admissions office wants to confirm that an applicant holds a qualifying prior award. The applicant's credential also lists grades for each module. The office asks for the award title and the awarding institution. The applicant shares those two attributes. The module grades stay in the wallet.

**Practice activity: Ask for less**

Choose one process in your organisation in which a person shows a document, for example a recruitment check, an enrolment check or an access check. Write down:

1. What the document shows today.
2. What the receiver really needs to know.
3. Which attributes you would request and which you would not.
4. How you would explain the request to the holder in one sentence.

**Question 10.** What is selective disclosure?

[( )] Deleting a credential after one use
[(X)] Sharing only the attributes of a credential that the relying party needs
[( )] Encrypting a PDF with a password
[( )] Sending a credential to the issuer for review

****
Selective disclosure lets the holder reveal chosen attributes while the relying party can still check the issuer's signature on them.
****

**Question 11.** A relying party needs to know whether an applicant holds a bachelor's degree. Which request follows data minimisation?

[( )] The complete credential with all grades and personal details
[( )] A scan of the original certificate
[(X)] The degree title and the awarding institution only
[( )] The applicant's date of birth and home address

****
Data minimisation means asking only for what the decision needs. Degree title and institution answer the question, while grades and other details do not.
****

**Question 12.** Who decides whether a presentation is sent from the wallet?

[( )] The relying party
[( )] The issuer
[(X)] The holder, after seeing the request
[( )] The regulator

****
The holder sees the request and decides whether to agree. The relying party decides afterwards whether to accept what it receives.
****

## Status in Europe and in Germany (dated unit)

Status as of November 2026; check before publishing.

### What is fixed in law

The revised eIDAS Regulation sets a clear deadline for Member States. Each Member State must offer at least one wallet by 24 December 2026. The regulation also provides that regulated private sectors must accept the wallet about one year after issuance starts. The detailed scope of these sectors comes from the regulation and its implementing acts.

<!-- VERIFY: Confirm the 24 December 2026 deadline and the acceptance obligations, including which sectors are covered, against the consolidated text of Regulation (EU) No 910/2014 as amended. -->

### What varies

Readiness varies widely between Member States. Some countries are far advanced in piloting and rollout. Others are earlier in their preparation. A person who moves between countries, or an organisation that works across borders, should not assume that every wallet has the same functions on the same day.

Large-scale pilots have tested wallet use in several areas, among them education credentials, payments and travel. These pilots have produced user journeys, data models and lessons. They are inputs to the work and do not replace the legal requirements.

### Germany

Germany plans its state wallet, called "d-you", for 2 January 2027, with basic functions first. This date is a plan. Treat it as a planned date that may change, and check the current position with the responsible federal authority before you communicate it to your own audiences.

<!-- VERIFY: Confirm the planned date, the name "d-you" and the scope of basic functions with official German government sources before publication. -->

What basic functions first means in practice is that early wallet use will probably focus on identification and a small number of services. Education and employment credentials in the wallet may come later and in stages. Plan for a gradual path rather than a single switch.

### Education credentials

DC4EU has published pilot artefacts, including user journeys and data models based on the European Learning Model. National adoption of education credentials in wallets is at an early stage. Many institutions still issue PDFs, paper certificates and open badges, and these will stay in use for years. The wallet adds a new channel and does not remove the others overnight.

### What this means for planning

- Keep your existing credential processes running.
- Learn which of your credentials could become wallet credentials first, for example those with clear legal status and a registry as source.
- Follow the work of your national authority and your sector body.
- Check the dates in this unit before you rely on them. Dated facts change.

<svg viewBox="0 0 800 450" width="100%" role="img" xmlns="http://www.w3.org/2000/svg">
  <title>Timeline of key wallet dates</title>
  <desc>A horizontal timeline with two dates: 24 December 2026, when Member States must offer at least one wallet, and 2 January 2027, the planned start of the German state wallet with basic functions. A third marker, about one year after issuance starts, shows when regulated private sectors must accept the wallet.</desc>
  <rect x="0" y="0" width="800" height="450" fill="#FFFFFF"/>
  <line x1="60" y1="230" x2="740" y2="230" stroke="#02375B" stroke-width="2"/>
  <circle cx="200" cy="230" r="14" fill="#B1CF37" stroke="#02375B" stroke-width="2"/>
  <text x="200" y="185" text-anchor="middle" font-family="Open Sans, Arial, sans-serif" font-size="16" font-weight="bold" fill="#02375B">24 December 2026</text>
  <text x="200" y="270" text-anchor="middle" font-family="Open Sans, Arial, sans-serif" font-size="14" fill="#02375B">Member States must offer</text>
  <text x="200" y="290" text-anchor="middle" font-family="Open Sans, Arial, sans-serif" font-size="14" fill="#02375B">at least one wallet</text>
  <circle cx="400" cy="230" r="14" fill="#B1CF37" stroke="#02375B" stroke-width="2"/>
  <text x="400" y="185" text-anchor="middle" font-family="Open Sans, Arial, sans-serif" font-size="16" font-weight="bold" fill="#02375B">2 January 2027</text>
  <text x="400" y="270" text-anchor="middle" font-family="Open Sans, Arial, sans-serif" font-size="14" fill="#02375B">Germany plans its state</text>
  <text x="400" y="290" text-anchor="middle" font-family="Open Sans, Arial, sans-serif" font-size="14" fill="#02375B">wallet, basic functions first</text>
  <circle cx="620" cy="230" r="14" fill="#F78222" stroke="#02375B" stroke-width="2"/>
  <text x="620" y="185" text-anchor="middle" font-family="Open Sans, Arial, sans-serif" font-size="16" font-weight="bold" fill="#02375B">About one year later</text>
  <text x="620" y="270" text-anchor="middle" font-family="Open Sans, Arial, sans-serif" font-size="14" fill="#02375B">Regulated private sectors</text>
  <text x="620" y="290" text-anchor="middle" font-family="Open Sans, Arial, sans-serif" font-size="14" fill="#02375B">must accept the wallet</text>
  <text x="400" y="370" text-anchor="middle" font-family="Open Sans, Arial, sans-serif" font-size="14" fill="#4F6576">Status as of November 2026; check before publishing. Lime: policy. Orange: employers and companies.</text>
</svg>

**Worked example: A planning note in two settings**

A corporate academy plans its credential strategy for 2027. The academy keeps issuing PDF certificates and open badges. It notes that regulated sectors it serves may need to accept the wallet about a year after issuance starts, so it checks which of its clients fall into those sectors. It lists internal credentials that might later be offered as wallet credentials and asks its IT team to follow the standards work.

A college with students in several countries notes that wallet readiness differs between Member States. It keeps verification routes that work without a wallet, and it asks its registry to compare its diploma data with the ELM-based data models from the DC4EU pilot.

**Practice activity: Date check**

Write a short planning note of five lines for your own organisation. It should state the 24 December 2026 deadline, the planned German date as a plan, what you do not yet know, who will check the dates before the next update, and one credential you would look at first. Add the date on which you wrote the note.

**Question 13.** By when must Member States offer at least one EUDI Wallet?

[( )] 1 January 2025
[( )] 30 June 2026
[(X)] 24 December 2026
[( )] 31 December 2028

****
The deadline for offering at least one wallet is 24 December 2026.
****

**Question 14.** What is the status of the German state wallet date of 2 January 2027?

[( )] It is a legal deadline set by the EU
[(X)] It is a plan for the state wallet "d-you", with basic functions first, and needs checking before use
[( )] It is the date on which all private companies must accept the wallet
[( )] It is the end date of the DC4EU pilot

****
Germany plans its state wallet for 2 January 2027 with basic functions first. This is a planned date, so check current official information before you repeat it.
****

**Question 15.** What is the best description of national adoption of education credentials in wallets?

[( )] Complete across all Member States
[( )] Not planned anywhere
[(X)] At an early stage, with pilot artefacts such as user journeys and ELM-based data models published
[( )] Limited to Germany

****
Pilot artefacts exist, and national adoption is at an early stage. Plan for a gradual path and keep existing credential processes.
****

## Assessment and badge

### Knowledge check

This is the final knowledge check for the badge "Digital Identity and the EUDI Wallet: Essentials (Knowledge, L1)". It has 12 questions, including scenario items. Each question has four options and one correct answer. Read each question carefully and choose one option.

**Question 1.** What does eIDAS 2.0 require from Member States?

[( )] To create a single EU database of all citizens' credentials
[(X)] To offer citizens, residents and businesses at least one digital identity wallet
[( )] To abolish national identity cards
[( )] To make all universities issue wallet credentials

****
The core requirement is the offer of at least one wallet. The regulation does not create a central credential database.
****

**Question 2.** By when must Member States offer at least one EUDI Wallet?

[( )] 2 January 2027
[( )] 1 January 2025
[(X)] 24 December 2026
[( )] 31 December 2030

****
The deadline is 24 December 2026. The German date of 2 January 2027 is a national plan, not the EU deadline.
****

**Question 3.** Scenario: A colleague says that Germany must have all wallet functions live on 2 January 2027 because the EU requires it. What is the most accurate reply?

[( )] The colleague is correct, because 2 January 2027 is the legal deadline
[( )] The colleague is correct, because the wallet must include all education credentials from the start
[(X)] Germany plans its state wallet for 2 January 2027 with basic functions first, while the EU deadline for offering at least one wallet is 24 December 2026
[( )] There is no deadline for wallets in the EU

****
The EU deadline and the German plan are different things. The German plan foresees basic functions first, and the details need checking before use.
****

**Question 4.** Which item is person identification data (PID)?

[( )] A completion badge from a one-day workshop
[( )] A confirmation of current employment
[(X)] Core attributes such as name, date of birth and nationality that identify a natural person
[( )] A membership card of a professional body

****
PID identifies the person. The other items are statements about achievements, status or membership.
****

**Question 5.** A university issues a signed digital record stating that a person holds a master's degree. How is it best described?

[( )] Person identification data
[(X)] An attestation of an attribute about the holder
[( )] A replacement for the holder's national identity record
[( )] An account kept by the university

****
The record states a fact about an already identified holder, so it is an attestation of an attribute.
****

**Question 6.** Scenario: A training provider issues a signed badge for a short course. An employer asks whether the badge is a qualified electronic attestation of attributes. What is the most careful answer?

[( )] Yes, because all signed credentials are qualified attestations
[( )] No, and therefore it has no value
[( )] Yes, because it is stored in a wallet
[(X)] Not automatically. Its legal status depends on the issuer and the rules that apply, and the employer decides how much weight to give it

****
Storage in a wallet does not set legal status. Many useful credentials are other credentials, and the receiving party decides what it accepts.
****

**Question 7.** What is selective disclosure?

[( )] Sending a credential to a regulator for approval
[( )] Deleting a credential after it has been shown once
[(X)] Sharing only those attributes of a credential that the relying party needs
[( )] Showing a credential only to the issuer

****
Selective disclosure lets the holder reveal chosen attributes, and the relying party can still check the issuer's signature.
****

**Question 8.** Scenario: An HR team wants to confirm that a candidate holds a required certification. The credential lists name, certification title, issue date, expiry date and score. Which request best follows data minimisation?

[( )] The whole credential, to keep a full record
[( )] A photograph of the candidate's certificate and passport
[(X)] The certification title and the expiry date
[( )] The score and the candidate's home address

****
The decision needs to know that the certification exists and is valid. Title and expiry date answer this, and the score is not needed.
****

**Question 9.** Why is a PDF different from a wallet credential for selective disclosure?

[( )] A PDF is always more secure
[( )] A PDF can be split into attributes by the verifier
[(X)] A PDF is shown whole or not at all, and a reader cannot easily check the issuer's signature on parts of it
[( )] A PDF is issued only by states

****
A signed credential in a format that supports selective disclosure lets the holder reveal parts while keeping them verifiable. A PDF generally does not.
****

**Question 10.** In a wallet exchange, who creates and signs a credential and gives it to the holder?

[( )] The relying party
[( )] The holder
[(X)] The issuer
[( )] The wallet manufacturer

****
The issuer creates and signs the credential. The holder stores it, and the relying party receives and checks presentations.
****

**Question 11.** Scenario: A college wants to plan for wallets. Its registry signs diplomas, its learner support desk answers student questions, and its admissions office checks qualifications from other institutions. Which assignment of roles is correct?

[( )] Registry: relying party; learner support: issuer; admissions: holder
[( )] Registry: holder; learner support: relying party; admissions: issuer
[(X)] Registry: issuer; learner support: holder support; admissions: relying party
[( )] Registry: holder support; learner support: issuer; admissions: holder

****
The registry creates and signs, so it is the issuer. The support desk helps holders, and admissions receives and checks, so it is a relying party.
****

**Question 12.** Scenario: A person allows an AI assistant to prepare job applications. Which statement is correct?

[( )] The assistant becomes the holder of the person's wallet
[( )] The assistant's identity and the person's identity are the same
[(X)] The wallet belongs to the person, and any authority given to the assistant should be explicit, limited and recorded
[( )] The relying party should treat the assistant as the issuer

****
The person remains the holder and stays accountable for what is shared. The assistant has its own identity and limits of authority.
****

### Rubric

| Criterion | Evidence | Meets the standard when |
|---|---|---|
| Regulatory basis (outcome 1) | Questions 1 to 3 | The learner states what eIDAS 2.0 requires of Member States and gives the 24 December 2026 deadline, and separates it from the German plan |
| Wallet content (outcome 2) | Questions 4 to 6 | The learner tells person identification data, attestations of attributes and other credentials apart |
| Holder control (outcome 3) | Questions 7 to 9 | The learner explains selective disclosure and data minimisation with an education or employment example |
| Roles (outcome 4) | Questions 10 to 12 | The learner identifies issuer, holder support and relying party in an organisation and keeps a person's wallet apart from an AI agent's authority |

### Pass rule

You pass the knowledge check with at least 9 of 12 questions correct (75 per cent). You may repeat the check. Read the explanations after each question before you try again.

### Evidence for the badge

The evidence for the badge "Digital Identity and the EUDI Wallet: Essentials (Knowledge, L1)" (alignment code ICSF-IDWL-L1-K) is a passed knowledge check. The badge records that you passed a check of your understanding of the concepts in this course. It does not prove competence in a job.

<details><summary>Facilitator notes</summary>

For cohort delivery, run the knowledge check as a closed-book individual task of about 20 minutes. Use the scenario items (3, 6, 8, 11 and 12) as discussion prompts afterwards. Record the pass result in the learning platform as the badge evidence. Check the dated unit in Module 5 and the status statements against current official sources before each cohort starts.

</details>

## Sources and further reading

Status as of November 2026; check before publishing.

**Official texts and public bodies**

- Regulation (EU) No 910/2014 on electronic identification and trust services (eIDAS), as amended by Regulation (EU) 2024/1183 establishing the European Digital Identity Framework. Published in the Official Journal of the European Union and available through EUR-Lex.
- European Commission, European Digital Identity (EUDI) Wallet pages, including the Architecture and Reference Framework and the implementing acts.
- The European Commission's digital strategy website, section on the European Digital Identity.
- Federal Government of Germany and the responsible federal ministry for the German state wallet plans. Check the current official announcements for dates and scope.

**Standards bodies and specifications**

- OpenID Foundation, OpenID for Verifiable Credential Issuance and OpenID for Verifiable Presentations specifications (OpenID4VC family).
- IETF, specification work on SD-JWT and SD-JWT-based verifiable credentials.
- ISO/IEC 18013-5, mobile driving licence (mDL) application, which defines the mdoc data model.

**Education credentials**

- European Commission, European Learning Model (ELM) and Europass pages.
- DC4EU consortium, public deliverables and pilot artefacts on education credentials in wallets.

**Framework**

- ICoBC Credentialing Skills Framework (ICSF), skill IDWL "Digital identity and wallets", available from the International Council on Badges and Credentials.

<!-- VERIFY: Add exact URLs only after checking each link against the official site. This file lists sources without URLs on purpose. -->
````
