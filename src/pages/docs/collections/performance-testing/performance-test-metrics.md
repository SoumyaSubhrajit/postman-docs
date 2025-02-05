---
title: "View metrics for performance tests"
updated: 2023-10-16
contextual_links:
  - type: section
    name: "Additional resources"
  - type: subtitle
    name: "Videos"
  - type: link
    name: "Load Testing Your APIs"
    url: "https://youtu.be/a5hWE4hMOoY"
  - type: subtitle
    name: "Blog posts"
  - type: link
    name: "Test your API’s performance by simulating real-world traffic with Postman"
    url: "https://blog.postman.com/postman-api-performance-testing/"
---

During a [performance test](/docs/collections/performance-testing/testing-api-performance/), all requests are sent from your computer where you are running the Postman desktop app. You can view real-time metrics such as the average response time, error rate, and throughput. You can also customize the performance test graph to focus on the requests or test metrics you're most interested in.

## Contents

* [View performance metrics](#view-performance-metrics)
* [Customize the performance view](#customize-the-performance-view)

## View performance metrics

The **Summary** tab displays performance metrics in real time so you can observe how your API performs under load.

<img alt="Viewing performance metrics" src="https://assets.postman.com/postman-docs/v10/performance-test-graph-v10-18a.jpg"/>

You can view the following information about the performance test:

* Name of the collection being run and the active environment (if any). Select the name to open the collection or environment.
* The number of virtual users (VU). Each virtual user simulates the behavior of a real-world user by running the collection in a repeating loop, in parallel with other virtual users.
* Start time, duration, load profile (fixed, ramp up, spike, or peak), and [data file](/docs/collections/performance-testing/performance-test-data-files/) (if used).
* **Total requests sent** - The total number of requests sent across all virtual users.
* **Requests/second** - The number of requests sent each second during the performance test, a measure of throughput.
* **Avg. response time** - The response time in milliseconds of all requests averaged together.
* **Error rate** - The percentage of requests that result in an error. Responses other than 2xx responses are considered errors.

From the **Summary** tab, you can take the following actions:

* Select **Stop** to stop the performance test.
* Select **Run Again** to configure and start the performance test again.
* To get a link to the performance report, select the share icon <img alt="Share icon" src="https://assets.postman.com/postman-docs/icon-share.jpg#icon" width="16px">. Select **Copy Link** to copy the link to your clipboard. You can share the link with your teammates so they can view the results of the performance test.
* To download a copy of the performance report in PDF or HTML format, select the more actions icon <img alt="More actions icon" src="https://assets.postman.com/postman-docs/icon-more-actions-v9.jpg#icon" width="16px"> and select **Export PDF report** or **Export HTML report**. The report shows response time and throughput, slowest requests, requests with the most errors, metrics for each request, and a list of errors.
* To view a list of all past performance runs for the collection, select the more actions icon <img alt="More actions icon" src="https://assets.postman.com/postman-docs/icon-more-actions-v9.jpg#icon" width="16px"> and select **View all runs**.
* To open a request, select the name of a request.

## Customize the performance view

The **Summary** tab displays a graph with real-time metrics for virtual users, requests per second, average response time, and error rate percentage.

Hover over a point on the graph to view more details.

<img alt="Getting performance details" src="https://assets.postman.com/postman-docs/v10/performance-test-hover-v10-15.jpg" width="600px"/>

Select a metric in the legend below the graph to show or hide that metric in the graph.

<img alt="Getting performance details" src="https://assets.postman.com/postman-docs/v10/performance-test-show-legend-v10-15.jpg" width="600px"/>

Use the dropdown lists to view data for a specific request. You can also select the response time metrics you want to view. The following metrics are available:

* **Avg. response** - The response time in milliseconds of all requests averaged together.
* **Min response** - The lowest observed response time.
* **Max response** - The highest observed response time.
* **99th percentile** - 99% of all response times are equal to or less than this value.
* **95th percentile** - 95% of all response times are equal to or less than this value.
* **90th percentile** - 90% of all response times are equal to or less than this value.

To change the graph back to the default view, select **Reset**.

<img alt="Viewing metrics for a request" src="https://assets.postman.com/postman-docs/v10/performance-test-request-v10-15.jpg" width="500px"/>

To view details for a section of the graph, select a point on the graph. The table below the graph shows total requests, throughput, response time, and error metrics for each request during the selected time period. To change the graph back to the default time period, select **Clear Filter**.

<img alt="Viewing a time period" src="https://assets.postman.com/postman-docs/v10/performance-test-zoom-v10-15.jpg" width="620px"/>
