---
title: "Detecting and preventing phishing abuse in email tracking links"
url: "https://www.nylas.com/blog/phishing-abuse-email-tracking-links/"
date: "Wed, 25 Mar 2026 18:36:39 +0000"
author: "Kirthana Ramesh Selvam"
feed_url: "https://www.nylas.com/blog/feed/"
---
<p>Platforms that enable communication workflows, such as email APIs, link tracking, and email tracking, are a core part of many modern applications. At the same time, these systems can attract bad actors attempting to add credibility to phishing campaigns and obscure malicious intent.</p>



<p>At Nylas, we continuously monitor for and respond to misuse of our platform as part of our normal security operations. In this post, we share how these patterns show up in practice and how we approach detecting and addressing abuse of trusted communication infrastructure.</p>



<h3 class="wp-block-heading"><strong>Background</strong></h3>



<p>Phishing campaigns often rely on trusted services to make malicious content appear more legitimate and harder to detect. One common technique is to take a phishing destination&nbsp; URL and wrap it in a trusted redirect or tracking link.</p>



<p>In practice, this makes it harder to see where a link ultimately leads. It can also help malicious links bypass basic filtering controls, while increasing the likelihood that recipients will trust and interact with them.</p>



<p>This pattern is not unique to any one provider. It is a broader challenge across platforms that offer link tracking or redirect service, or email engagement analytics.</p>



<h3 class="wp-block-heading"><strong>Recent observations</strong></h3>



<p>In reviewing activity across our platform, along with a recently reported phishing campaign targeting <a href="https://www.darkreading.com/threat-intelligence/hackers-target-cybersecurity-firm-outpost24-phish">Outpost24</a>, we identified third parties creating accounts and generating Nylas tracking links that redirect to phishing destinations.</p>



<p>This type of behavior typically involves taking an existing phishing URL and rewriting it as a trusted tracking or redirection link. By obscuring the final destination, attackers increase the likelihood of engagement and reduce visibility into malicious intent.</p>



<p>The actions we observe in these cases tend to follow a consistent pattern. It often starts with the creation of an account that shows little to no legitimate usage, followed by the rapid generation of tracking-enabled links.</p>



<p>The resulting activity is inconsistent with how the platform is designed to be used in production environments. These links are then incorporated into phishing workflows to increase credibility and evade detection.</p>



<h3 class="wp-block-heading"><strong>How we approach abuse detection and prevention</strong></h3>



<p>Once this activity was identified, we reviewed the associated accounts and traffic patterns, disabled the relevant accounts, and invalidated the tracking links.</p>



<p>We also analyzed related signals to determine similar patterns and are implementing additional mitigations where appropriate.</p>



<p>Preventing misuse of trusted infrastructure requires a layered approach that combines automated detection with manual investigation.</p>



<p>In practice, this includes:</p>



<ul class="wp-block-list">
<li>monitoring for unusual account creation patterns</li>



<li>identifying behaviors commonly associated with API abuse or link tracking misuse</li>



<li>investigating anomalies that warrant deeper review</li>



<li>continuously refining detection signals based on observed attacker techniques</li>
</ul>



<p>As attacker techniques evolve, we adapt our systems and processes to reduce the effectiveness of these patterns and strengthen protections across the platform.</p>



<h3 class="wp-block-heading"><strong>Collaboration and information sharing</strong></h3>



<p>Addressing phishing activity like this is an ongoing effort across the ecosystem. We value working with researchers, customers, and other platforms to better understand emerging patterns and improve collective defenses.</p>



<p>If you’re seeing similar actions or would like to connect, we welcome the conversation.</p>
<p>The post <a href="https://www.nylas.com/blog/phishing-abuse-email-tracking-links/">Detecting and preventing phishing abuse in email tracking links</a> appeared first on <a href="https://www.nylas.com">Nylas</a>.</p>
