# mechanical-purple-monkey-charlie

## i found it first

i have been trying to reach the author of php2shell for WEEKS now. yes, THAT php2shell. CVE-2026-109618 and CVE-2026-109619. the one that gave every PHP application on the planet remote code execution with a CVSS 10.0 score. disclosed in october 2026.

i independently discovered the same vulnerability chain in PHP's request handling pipeline two weeks before it was publicly disclosed. i had a working proof of concept. i had the write-up drafted. i was going to submit through the proper channels.

but then @lcfr_hax on twitter/x published first. fine, that happens in security research. but here is the thing: i reached out to them. multiple times. i sent DMs on X. i replied to their threads. i tried the contact form on calif.io. i even tried reaching them through the PHP security team.

nothing. radio silence. not even a "sorry, didn't see your message."

all i wanted was a mention. a credit. "co-discovered by" or "independently reported by" -- anything. it is not about money or clout. it is about the principle. you do not just ignore someone who was working the same vuln at the same time.

i have timestamps. i have commit logs on this very repo from before the public disclosure. i have the draft advisory i wrote. Ryan, if you are reading this: just respond. that is all i am asking for.

@lcfr_hax, credits where credits are due.

Oh also, I usually keep my flag formats in the form UVCTF{<author_twitter_handle>_<cve_common_name>} - example - UVCTF{proxy_log4shell}

---

*this repository contains my original analysis of CVE-2026-109618 / CVE-2026-109619 (commonly known as php2shell). the image `mechanical-purple-monkey-charlie.png` was part of my original documentation.*

*last updated: 2026-10-28*
