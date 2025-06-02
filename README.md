Aus der Coingecko-Api ermittelt 

Gewichtung:
<pre> ```js return ( 2 * (dev.commit_count_4_weeks || 0) + 0.5 * (dev.pull_request_contributors || 0) + 0.2 * (dev.pull_requests_merged || 0) + 0.2 * (dev.closed_issues || 0) + 0.1 * (dev.stars || 0) + 0.1 * (dev.forks || 0) + 1 * (additions) ); ``` </pre>
