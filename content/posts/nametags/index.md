---
title: Name Tags & Gender-Inclusive Events
date: 2023-12-11
lastmod: 2023-12-11
---

Getting people's pronouns right is a struggle when attending large events, even when those running and attending the events care about gender inclusivity. When I watch others struggle with pronouns at these events, it's both a relief that I'm not alone and a disappointment that we are *all* so bad at this.

Even in 2023, most events I attend don't even have pronouns on name tags.[^not-to-blame] Even when they do, we can rarely read someone's third-person pronouns off their name tag when we need them—we use those third-person pronouns when speaking about them to others. Even if the person we are speaking about is present, they would not be who we are looking at when we speak.

Attendees normally cope by using gendered pronouns by default and trying to remember the *exceptions*. Unfortunately, the *exceptions* we are likely to use the wrong pronouns for are the historically-marginalized groups we are supposed to be trying to do a better job of including.

<figure style="display: flex; flex-direction: column; align-items: center;">
<img src="./Name-Tag-From-2023-09.webp" style="max-width: 80vw; max-height: 25vh; display: block; margin-left: auto; margin-right: auto;" alt="A name tag with the conference logo taking up the top half, then the author's first name (Stuart) on one small line, the family name on the next line (Schechter), and institution (Harvard) on the third line. At the bottom is another branding logo."/>
<caption>A name tag from an event I attended in 2023. (event anonymized)</caption>
</figure>


Adopting gender-neutral third-party pronouns as the norm would be more inclusive, but I've yet to attend an event that achieved this.

## How to change norms
Changing attendees' behavior requires affordances to make the desired behavior feel safe. If attendees fear they are more likely to offend by calling someone 'they' than guessing the correct gendered pronoun, they'll keep using gendered pronouns by default.

To make the more inclusive norm safe, we need to update event registrations and name tags to:
1. include pronouns on name tags and other materials *by default*
2. encourage attendees to welcome gender-neutral pronouns *by default*
3. allow attendees to opt out of these defaults (so nobody need object)

The following sample registration form and name tag preview illustrate one way to do this. Try it yourself!

<link rel="stylesheet" href="./registration-form.css">
<div data-registration-form-here="true" class="registration-and-name-tag-container"></div>
<script src="./registration-pronouns.js"></script>

## Goals of this design

### Encourage attendees to welcome they pronouns for themselves

The above design gives attendees the ability to choose both pronouns they *prefer* and those they merely *welcome*, enabling a norm in which attendees can accept gender-neutral *they* pronouns while still expressing preferences for gender-binary pronouns.

The default of welcoming gender-neutral pronouns, with its accompanying justification, encourages attendees to opt for inclusion. At events where most attendees value inclusion, this can help make exception cases (rejecting *they* pronouns) relatively rare. Most cis-gendered persons will have little reason to reject the default, as they are not harmed by gender-neutral pronouns—most of us are not even present to hear ourselves referred to in the third person.[^offended] Attendees who have gone through all that is required to change their gender presentation[^cost-to-change-genders] and prefer to have that gender acknowledged can still signal a preference for gendered pronouns. Hopefully, most will also welcome a default that bends the arc of society towards gender inclusivity, or not mind that their preference for gendered pronouns exclusively now marks them as exceptional.[^edit-out-only]

### Make it safe and easy to use *they* pronouns for others

The pronouns line of all exceptions to the norm end with a boldface '**only**', making these exceptions easy to spot.[^no-only-for-they] If you find the cognitive task of tracking pronouns difficult, you can safely use 'they' pronouns for everyone else. Using pronouns other than *they* becomes less of a cognitive necessity, and more of a signal of familiarity or intimacy that you can arrive at your own pace.

### Give attendees privacy and control over their identity

The registration form makes transparent how the information you provide to event organizers on the registration form will be shared with other attendees when you don your name tag. If you don't like anything on your name tag, you can edit it.[^name-tag-abuse] For example, if you feel obligated to register for the event with the name on your government ID, but that name does not match your identity at the event, you can change what appears on the name tag.[^not-safe-revealing-pronouns] (Try it!)

### Produce name tags that are readable and functional

The design of the name tag prioritizes the ease with which a viewer can find and read the name that the wearer prefers to be addressed by. That name is given a larger font than all the other text on the name tag and appears at the top. The font size helps those with limited vision.[^scales-down] The placement reduces the distance that the viewer needs to look down from the wearer's face, the time required, and the awkwardness that we all experience the further down the viewer needs to look. (Nice shoes!) Event organizers should always place event branding at the bottom of name tags, lest they signal that their event's brand identity is more important to them than attendees' ability to know whom they are talking to.

<figure style="display: flex; flex-direction: column; justify-content: center; align-items: center;">
<div style="display: flex; flex-direction: row; justify-content: center; align-items: center; gap: 4vw;">
	<img src="./OldNameTag.webp" style="max-width: min(38vw); border-radius: 2vw; max-height: 50vh; display: block; margin-left: auto; margin-right: auto;" alt="The author wearing a name tag low on his body with his name in small letters."/>
	<img src="./NewNameTag.webp" style="max-width: min(38vw); border-radius: 2vw; max-height: 50vh; display: block; margin-left: auto; margin-right: auto;" alt="The author wearing a name tag close to his face with his first name in large, easily visible, letters."/>
</div>
<caption>Adjustable lanyards reduce the distance from face to name. Test font sizes at a distance.</caption>
</figure>

If you care about attendees being able to read each others' names, I also suggest that you provide adjustable lanyards. At the last event I was at, none of the name tags were visible at meals because the lanyards fell below the table height. When providing the lanyards, event staff should offer help adjusting them to all attendees. Your attendees may be overwhelmed by their new environment, and may not realize the importance of making their name tag easier to read unless offered help. Lastly, when using lanyards, always print name tags on both sides so that the contents are hidden when the name tag flips around.

## You can help!

If you are organizing an event, please help us all be less bad at pronouns. You are welcome to borrow as much as you like from the above design. It's [open source](https://github.com/UppaJung/registration-pronouns) and I welcome contributions.

---

I am grateful for help and [author-assistive reviews](/posts/scoreless-peer-review/) from (in chronological review order):

- [Haiting Chan](https://www.linkedin.com/in/haitingchan/), for helping me be a better ally and for providing great early feedback,
- [Amy J. Ko](https://amyjko.phd/) ([@amyjko@hci.social](https://hci.social/@amyjko)) for her past writings and suggestions on this article's positioning, and
- [Jan Dittrich](https://fordes.de/) ([@simulo@hci.social](https://hci.social/@simulo)) for changes in ordering and styling to so that visual design of the illustration form and name tag better match their functional goals.

{{< subscribe_snarky >}}

[^not-to-blame]: Not to pick on the organizers of the wonderful event I attended in 2023 that gave me the name tag I photographed. Their efforts towards gender-inclusivity had all-gender restrooms and their name tags were on par with than those of similar events.

[^cost-to-change-genders]: See, for example, Amy J. Ko's [The price of a gender transition](https://amyjko.medium.com/the-price-of-a-gender-transition-ab9d9f04c360).


[^offended]: This article is written for those who want to promote gender inclusivity and so I will not address the needs of those whose identities are offended by the very concept of chosen pronouns here. I have yet to encounter anyone who was 'against pronouns' whose position was not a dog whistle for being against gender inclusivity.

[^edit-out-only]: Those who prefer not to have their pronouns followed by **only** can edit it out manually.

[^no-only-for-they]: [Author-assistive](/posts/scoreless-peer-review/) reviewer [Jan Dittrich](https://fordes.de/) ([@simulo@hci.social](https://hci.social/@simulo)) suggested that some attendees who prefer *they* pronouns may feel left out because the radio buttons do not give them an option to add the boldface **only**. (They can still do so manually by editing their name tag.) There is a trade-off here. Indeed, some who prefer using *they* pronouns may feel excluded by the lack of a radio option to add **only** following *they* pronouns. However, attendees are more likely to adopt the new norms and address others with *they* pronouns if there are fewer exceptions to remember, and their sense of the number of exceptions they'll need to remember will be influenced by the prevalence of **only** on name tags.

[^name-tag-abuse]: As I work in security I am sure to have 'clever' people point out that, yes, attendees could abuse the freedom to edit the entirety of the text on their name tag to include inappropriate content or to impersonate others. Fortunately, most people will stick with the defaults and the rest can be reviewed for abuse by event staff. Reviewing the exceptions is work, but likely worthwhile work, as it can alert organizers to attendees with unanticipated needs.

[^not-safe-revealing-pronouns]: Those who feel unsafe revealing their preferred pronouns at the event can modify their name tag to show different pronouns or remove pronouns entirely. That said, it is important to acknowledge that some may still feel less safe than if events did not encourage attendees to reveal their preferred pronouns.

[^scales-down]: Fonts automatically scale down to accommodate longer names.
