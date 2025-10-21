# Kgateway governance

Kgateway is dedicated to building a feature-rich, fast and flexible next-generation API gateway. This governance document details how the project is run. All members of the kgateway community must abide by the project's [Code of Conduct](CODE-OF-CONDUCT.md). 

## Values

The kgateway project embraces the following values:

* Openness: Communication and decision-making happens in the open and is discoverable for future
  reference. As much as possible, all discussions and work take place in public
  forums and open repositories.
* Fairness: All stakeholders have the opportunity to provide feedback and submit
  contributions, which will be considered on their merits.
* Community over Product or Company: Sustaining and growing our community takes
  priority over shipping code or sponsors' organizational goals.  Each
  contributor participates in the project as an individual.
* Inclusivity: We innovate through different perspectives and skill sets, which
  can only be accomplished in a welcoming and respectful environment.
* Participation: Responsibilities within the project are earned through
  participation, and there is a clear path up the contributor ladder into leadership
  positions.

## Roles and membership

Our governance builds on top of definitions from other documents, review the following files for relevant information:

* [CONTRIBUTOR_LADDER.md](./CONTRIBUTOR_LADDER.md) for the different roles with the project.
* [MAINTAINERS.md](./MAINTAINERS.md) for the project maintainers, including their organizational affiliation.
* [Code of Conduct](./CODE-OF-CONDUCT.md) for our code of conduct.

## Voting

While most business in kgateway is conducted by "[lazy consensus](https://community.apache.org/committers/lazyConsensus.html)",
periodically the Maintainers may need to vote on specific actions or changes. The following rules govern our voting process, unless otherwise stated for a specific purpose.

* A vote begins when someone adds a GitHub issue comment or PR comment containing the `/vote` command.
* A vote is cast when a user emotes thumbs-up (👍) or thumbs-down (👎) on the specific "vote" created by the git-vote bot on the GitHub issue/PR.
* A simple majority of eligible votes (as defined by the `@kgateway-dev/eligible-voters` team in GitHub) decides the vote outcome.
* No single company should have more than six eligible voters. It is the responsibility of each company to determine which affiliated maintainers are the eligible voters.
* Voting must be open for at least one week or until the required threshold is met, whichever is sooner.
* Only votes by eligible voters will count towards the final tally, but everyone is welcome to cast a non-binding vote to show their support.
* If the vote is done within a PR, then the vote refers to the most recent commit at the time the vote is created. If there is any further commit to the PR, a new vote must be created.

## Changes to governance

<!---
TODO: Enumerate what, precisely, constitutes a change in governance. I think it's clear editing this file, in any significant way, would count. Adjusting at least certain things wrt to the maintainer lifecycle also would likely constitute a governance change because this would directly impact who is, and is not, able to vote as well as who may be eligible or not in the future.
-->
All changes to our governance model require a vote by the maintainers. The proposed change will be submitted as a PR against the kgateway community repository. Voting will proceed according to the rules established for simple conflict resolution, with the sole exception being the threshold for acceptance.

* Any change requires a 2/3 super majority to be accepted.

## Vendor-neutrality

Kgateway is committed to [vendor-neutrality](https://contribute.cncf.io/maintainers/community/vendor-neutrality/). Our governance process has been designed to limit the influence of individual companies in furtherance of this goal. If you have concerns about the vendor-neutrality of the project please open an issue in this repository or join our [community meeting](https://calendar.google.com/calendar/u/1?cid=ZDI0MzgzOWExMGYwMzAxZjVkYjQ0YTU0NmQ1MDJmODA5YTBjZDcwZGI4ZTBhZGNhMzIwYWRlZjJkOTQ4MzU5Y0Bncm91cC5jYWxlbmRhci5nb29nbGUuY29t) to discuss.
