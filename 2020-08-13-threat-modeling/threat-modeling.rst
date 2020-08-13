:title: Threat Modeling & Security Hygiene
:author: r4v5
:css: threatmodeling.css
:data-transition-duration: 100

.. title: Welcome and Threat Modeling

----

Intro to Threat Modeling & Security Hygiene
===========================================

----

Threat Modeling
===============

* What information do I want to keep secret?
* From whom?
* What do I have to lose if it gets out?

----

Threat Modeling
===============

Company that just designed a new product
----------------------------------------

**What information do they want to keep secret?**

All of the R&D details a competitor would need to clone their product

**From whom?**

Their competitors

**What do they have to lose if it gets out?**

Marketplace advantage, and lots of money

----

Threat Modeling
===============

LGBT youth living with conservative family
------------------------------------------

**What information do they want to keep secret?**

Their sexual identity, any relationships they may have

**From whom?**

Their family members and their family's circle of friends

**What do they have to lose if it gets out?**

The ability to live in that house, financial support, possibly their life

----

Threat Modeling
===============

Activists/organizers
--------------------

**What information do they want to keep secret?**

Their identity, their future actions/plans, the identities of fellow organizers

**From whom?**

Police, armed white supremacists

**What do they have to lose if it gets out?**

Legal repercussions/state repression, their lives

----

Adversaries
===========

Who is your adversary?

* How motivated are they?
* What are they technically capable of?
* What resources do they have at their disposal?
* Are they bound by the rule of law?

----

Adversaries
===========

Company that just designed a new product
----------------------------------------
Industrial espionage from other companies

* Bribing your employees
* Digging through your trash
* Physically breaking into your offices
* Hacking your computer systems
* Impersonating you to your suppliers to get samples shipped to them

----

Adversaries
===========

LGBT youth living with conservative family
------------------------------------------

"Snooping"

* Reading your texts/Facebook messages/email
* Location tracking ('Find my iPhone' et al)
* Browser history reading
* Logging every keystroke on your computer
* Impersonating you online to your friends
* Googling you/monitoring your online footprint

----

Adversaries
===========

Activist
--------

Widespread government surveillance of protest actions

* Seized cellular phone data (Cellebrite/Graykey)
* Cell tower simulators (Stingrays)
* Undercover officers/criminal informants
* Security cameras/image recognition software

White supremacist vigilantes

* Generally not extremely technical, but sometimes
* Lots of obsessive digging, though
* Not bound by law

----

"Nothing to hide"
=================

It is impossible to know beforehand what information is dangerous to share
--------------------------------------------------------------------------

----

Security Hygiene
================

Regardless of threat model, there are a few things that are general best practices

----

Use a unique, strong password for each thing
============================================
Attackers do "credential stuffing":

using your hacked LinkedIn password for your GMail (haveibeenpwned.com)

* Use passwords that are *random* and *unique*, because 'word list' generation is easy now

How you do this depends on threat model

* Password Manager software (e.g. Lastpass, 1Password, Keepass)

* Paper Notebook + Diceware

----

Install updates
============================================
Yeah the industry sucks and sometimes updates have bugs or remove features

They also include important security patches

* Equifax security breach in 2017 was because one server was unpatched

  * Update that fixed the bug was released March 7
  
  * Hacked in May

----

Use full disk encryption where possible
============================================
* Windows's "BitLocker" for Windows Pro/Ed (not in Home)
* MacOS "FileVault"
* Linux "LUKS"

----

Thank you
=========

