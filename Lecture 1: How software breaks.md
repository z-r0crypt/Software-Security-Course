- [Part 1: Terminology](#part-1-terminology)




##### Part 1: Terminology
  * Understanding how software typically breaks is a requirement for successful secure design.
  * A way software can break is known as a weakness. A single security issue is known as a vulnerability. The weakness is exploited via one or more vulnerabilities. (Often the necessary software and activities required is called an exploit.) When you fix a security issue, you fix a vulnerability or you redesign the system not to exhibit the weakness.
  * In practice, only exploitable vulnerabilities matter. There can be weaknesses and vulnerabilities that cannot be exploited. Hence, the existence of a vulnerability is not always a proof of exploitability.
  * The act of exploitation is one type of an attack. Note that an “attack” does not imply a malicious intent: If I am testing a system legally, I am still attacking it.
> Discussion: Given the attacker, who is the defender?

  * A security risk can exist whether or not there is a weakness. A risk is a probability (likelihood) of a system having a weakness, and the impact of someone exploiting a vulnerability.
  * In many cases, the choice of whether or not to treat a risk boils down to the loss expectancy of the risk, compared to the cost of treating the risk. The tricky part here is to be able to quantify the likelihood of the risk event, which in security is usually much harder than quantifying the impact.
  * A threat is an actor that may exploit a vulnerability (or an event that someone does it). The terminology of a threat varies a bit according to source. If you want to be specific and talk about the person, talk about threat actors or something like that.
  * Weaknesses are catalogued by CWE. Vulnerabilities are catalogued by CVE.
  * Vulnerabilities are security bugs or flaws. These can be implementation-level, design-level, or even business-case level, or span several levels.
  * The way to deliver the exploit is an attack vector. The more exposure the system has, the larger attack surface it has. Usually, if a system is complex, it has more attack vector possibilities and a larger attack surface. We will get into these concepts more closely in sessions 4 and 5.
> Discussion: How could adding a security feature make a system less secure?

  * The difference between an architecture-level and implementation-level issue is fluid.
> Discussion: If your WordPress blog is hacked, is it WordPress’ bug, or was it your fault because you made the architectural decision to use WordPress?
