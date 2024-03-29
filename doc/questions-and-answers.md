# Questions and Answers

<blockquote>
"Using gender-inclusive language means speaking and writing in a way that does not discriminate against a particular sex, social gender or gender identity, and does not perpetuate gender stereotypes. Given the key role of language in shaping cultural and social attitudes, using gender-inclusive language is a powerful way to promote gender equality and eradicate gender bias." - The United Nations
</blockquote>


## What are introductions to inclusive language, gender bias, and psychological safety?

* Introductions about
[inclusive language](https://wikipedia.org/wiki/Inclusive_language) by
[Buffer](https://buffer.com/resources/inclusive-language-tech/),
[Detroit Labs](https://www.detroitlabs.com/blog/2020/06/11/inclusive-language-in-technology/),
[Forbes](https://www.forbes.com/sites/forbestechcouncil/2020/04/03/why-inclusive-language-matters-in-tech/?sh=7e99b84e6017),
[IBM](https://www.ibm.com/blogs/think/2020/08/words-matter-driving-thoughtful-change-toward-inclusive-language-in-technology/),
[Northwestern](https://www.it.northwestern.edu/about/it-projects/dei/glossary.html).

* Introductions about
[gender bias](https://wikipedia.org/wiki/Gender_bias) at
[Amazon](https://www.bloomberg.com/news/articles/2021-03-01/amazon-is-sued-for-alleged-racial-and-gender-discrimination),
[Facebook](https://theintercept.com/2021/04/09/facebook-algorithm-gender-discrimination/),
[GitHub](https://medium.com/gender-equality-in-tech/the-truth-about-githubs-gender-bias-b92a1d6310d3),
[Twitter](https://www.dailydot.com/debug/bechdel-test-twitter/),
[Uber](https://edubirdie.com/examples/gender-equality-analysis-of-the-problem-at-uber/),
[Wikipedia](https://wikipedia.org/wiki/Gender_bias_on_Wikipedia).

* Introductions about
[psychological safety](https://wikipedia.org/wiki/Psychological_safety) by
[Harvard](https://www.jstor.org/stable/2666999),
[Google](https://rework.withgoogle.com/guides/understanding-team-effectiveness/steps/foster-psychological-safety/),
[McKinsey](https://www.mckinsey.com/business-functions/people-and-organizational-performance/our-insights/psychological-safety-and-the-critical-role-of-leadership-development),
[Microsoft](https://workplaceinsights.microsoft.com/productivity/high-performing-teams-need-psychological-safety-heres-how-to-create-it/).


## Why does inclusive language matter?

<b>Question: "Why does inclusive language matter to me, or my team, or my company?”</b>

<b>Answer: Because inclusive language is better for teamwork.</b>

One of my teams presented our client with our technology plan to use Martin Fowler's "Strangler" pattern.

* The client’s project manager took me aside privately.

* She told me that the “Strangler” language had upset two of the women executives.

* The women were having flashbacks to when they were assaulted and literally strangled.

We asked:

* Does it matter to these people that the name “Strangler” is based on a plant? No.

* Does it matter to these people that “Strangler” is a technology term? No.

* Does it matter to the client that teammates are upset? Yes.

We learned:

* Language can harm your teammates, even if you can’t see it.

* Adapt your language, because if you don’t, you can harm your own points.

* Team psychological safety is a powerful lever to improve your ways of working.

We changed the wording immediately, and then I advised Martin Fowler.


## Why replace "mother/father" with "parent/guardian"?

<b>Question: “Why replace 'mother/father' with 'parent/guardian’?</b>

<b>Answer: Because inclusive language is easier for the real world.</b>

Inclusive language makes it easier to model the complexity of the real world, and also makes it easier for technical people to implement applications and integrations.

The first time I saw the inclusive language change from "mother/father" to "parent/guardian”, we were creating a U.S. Department of Education web application.

We discovered:

* Some children have two mothers, or two fathers, or more than two parents because of remarriages or fostering or adoption, or a parent who’s commonly known as the mother yet is actually the aunt or grandmother, or a parent who is gender transitioning and is simultaneously the biological mother and the legal father.

* Some requirements for the language “parent/guardian” were because of regulations, such as government laws, or foster-care intakes, or administration policies, or district rulings, or education sector practices, or agency auditing compliance needs.

We interviewed our stakeholders:

* Most end-users tended to say things like “I’m her mother”, and that was fine with our stakeholders because it’s the users' own language. This held true even if the person wasn’t the biological mother or legal mother. Flexibility matters.

* Most sector-experts tended to say “parent/guardian”, and that was fine with our stakeholders because it aligned with the wider context, including regulations. Interoperability matters.

We determined:

* The words “mother/father” weren't actually needed in the application by anyone.

* The words “parent/guardian” were actually needed in the application because of regulations.

* We estimated that doing it both ways would likely cost us hundreds of extra hours, and confuse stakeholders, and lead to technical mismatches for integrations, and lead to domain driven design confusion for regulations.

We learned:

* Inclusive language is easier in many cases for describing the real world.

* Inclusive language is much easier for business analysis such as domain driven design.

* Inclusive language is much easier for implementations doing integrations and regulations.


## Why rename git branches from "master" to "main"?

<b>Question: ”If you name your git repository default branch "main’ then I will happily use it, but what reason would there be for me to change my own git repositories?”</b>

<b>Answer: Because inclusive language is smarter for defaults, and defaults may help you and your users.</b>

Most git repository creators don't have a reason to do anything other than the default branch name. So it's great when git, GitHub, GitLab, and others can all make the default more helpful by changing from "master" to "main".

* More new repositories will do this by default, and more old repositories will replace “master” with “main”.

* A reason you may want to change your own git repositories, now or later, is because you prefer to use the same default branch name as other git projects, or want to use the same default as the git program itself.

* A reason for you to change is to make it easier for newcomers to use their own default tools and understandings with your repositories. New git tools expect a “main” branch by default, and newcomers to your code will look first for a “main” branch.

Transitioning from “master/slave” to “main/replica” helps with a frustrating problem that some technical professionals have when they are with non-technical colleagues.

* When an IT person says “master” or “slave” to a non-technical colleague, and the colleague isn’t aware of the technical meaning, then the colleague may have a starkly negative first impression.

* We once had a technical person describe a data priortization process as “the master beats all the slaves”. The non-technical colleagues recoiled in shock.

* It makes special sense to use inclusive language for a default, because this practice tends to keep people out of trouble by default.


## Should offensive language be allowed?

<b>Question: “If a developer’s package name uses a name that offends people should that be allowed?”</b>

<b>Answer: Yes because of free speech, but be aware that inclusive language is a requirement for many kinds of users".</b>

Free speech in its broadest sense says yes, a developer should be allowed to use any package name.

However, many kinds of users will choose to ban/block/veto packages with names that could cause harm.

For example, one of my teams evaluated a package with the name "Upskirt”.

* Our client company pointed us to current news about criminals snapping “upskirt” photos of women by using surreptitious cameras and harassing interactions.

* Our client company and our team banned the “Upskirt” package because the name was offensive to us. The client company also said the name would create risks of lawsuits or investigations.

* One of the companies involved in the “Upskirt” ecosystem later faced a lawsuit for sexual harrassment, which triggered an investigation, that led to a major resignation.

Risk management practitioners ban package names like these because there’s no package that’s worth the risks:

* Risk of creating a hostile work environment

* Risk of a sexual harrassment lawsuit

* Risk of an internal investigation that turns up such errors of judgement.


## Is this specific to one culture or one language?

<b>Comment: “The emotional charge is pretty specific to a single culture, while English is used by a large part of the world as a second language. It's ok to try to right the wrongs you are guilty of, but please stop trying to project that guilt to other cultures.”</b>

<b>Answer: Inclusive language is multicultural and multilingual.</b>

It turns out that inclusive-langauge researchers and advocates do see these kinds of emotional charges among many cultures and many languages, not just one culture and not just one language.

* The United Nations is working on gender-inclusive language across all six official UN languages: Arabic, Chinese, English, French, Spanish, Russian.

* The specifics can vary by language and by culture, because of grammar rules, phrasing choices, translation intent, cultural sensitivities, workplace regulations, and more.

* Internationalization and multiculturalism are complex areas, and benefit from high-trust communication and high-trust collaboration.


## Is this a high up declaration?

<b>Comment: “I have never seen a request to rename something because a majority of black/trans/female people considered the term offensive. The way it works is that a person or institution high up declares a term offensive."</b>

<b>Answer: What I've experienced is the opposite, where change happens because of junior people speaking up.</b>

On one team, it was a Black junior software developer who took me aside, privately, and raised their concerns that "white-list/black-list" was frustrating to them because it focused on “white” as good and “black” as bad.

* We looked for solutions together and opened discussion among our teammates.

* 100% of the Black developers wanted the change. So did most everyone else.

* A few people didn’t want the change because it would add some work, and wasn’t the longtime convention in our security documentation.

The team decided to change to the inclusive language "accept-list/reject-list".

* We made the change on our own work, made it successful, then shared our recommendations up the chain of command.

* When junior people speak up and advocate for change, then they can achieve a tipping point which can make a team more-successful and more-progressive. These kinds of changes can then go upward in the organization.

* I've experienced this kind of upward change firsthand, many times, with multiple companies, in multiple countries, and relating to multiple areas of gender, race, culture, orientation, marital status, addiction issues, family planning reasons, and more.
