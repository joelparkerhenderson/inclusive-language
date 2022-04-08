# Search and suggest tool

The technical plan is to create a software tool that can search input text then output suggestions.

The tool reads an input corpus:

    * a text file that uses the JSON format

    * a list of search groups

Each search group has:

    * a short list of related words and/or phrases, such as "businessman", "businesswoman".

    * a probability score of 0 to 1, intended to indicate "how likely is this search to need attention?"

    * a short list of desired replacements, such as "businessperson", "professional", "executive".

The purpose of the input corpus is to enable anyone, anywhere, to create their own preferred words, scores, and replacements.

  * This kind of neutrality and flexibility are mission-critical for success across many organizations, languages, and priorities.

The tool calculates a document's attention-needed score by summing the discovered words' scores.

  * For example, suppose the world "chairman" has a probability of 0.8, representing that we are mostly confident the word needs attention, yet could be an official title that we don't want to change, such as "Chairman of the Board". A document that contains 5 instances of "chairman" would score 5 * 0.8 = 4.0.

  * The scoring enables any team to run the tool on all the team's documents, score them accordingly, then work on them over days/weeks/months. The scoring can be re-calculated any time. Good progress looks like the total score decreasing over time.

The tool is to be implementable in any mainstream programming language.

  * We aim to write the reference implementation with the Rust programming language, because Rust provides high security, high speed, and high capabilities for multi-prong deployment, including into the cloud such as using Amazon Web Services, or on-site, such as using a company's internal server hardware.

The tool is to be free open source.

  * We aim to use the GPL license, so anyone can use it, edit it, revise it, and share it.

  * The license named "GPL-2.0-or-later" is fully compatible with Linux, the largest open source project in the world.
