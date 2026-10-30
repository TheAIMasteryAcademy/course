# Azure costs and cleanup

Read this once before your first Azure demo. It takes two minutes and can save you real money.

## Which account to use

- **Azure free account:** a starting credit for your first 30 days, some popular services free for 12 months, and some services that are always free. A card is needed to sign up. When the credit runs out, paid services stop unless you upgrade to pay-as-you-go.
- **Azure for Students:** for full-time university students. A smaller credit and no card needed.

Offers change, so check the current terms on the Azure website before you sign up.

## Five rules for this course

1. **One resource group per episode.** Name it `rg-aimastery-s<season>-ep<episode>`, for example `rg-aimastery-s0-ep03`. Cleaning up is then one delete.
2. **Set a budget on day one.** In Cost Management, create a small monthly budget (we use 10 US dollars) with an alert at 80%. Episode 2 shows how.
3. **Stop compute when you stop working.** Azure Machine Learning compute instances keep charging while they run. Turn on idle shutdown, and stop them when you finish.
4. **Delete when the episode is done.** A stopped compute instance can still cost a little for its disk. When you finish an episode, delete its resource group.
5. **Check Cost Management once a week.** It takes a minute and catches surprises early.

## Never share secrets

Do not post keys, connection strings, passwords, subscription IDs or tenant IDs in Discussions, screenshots or issues. If one leaks, rotate it in the Azure portal straight away.
