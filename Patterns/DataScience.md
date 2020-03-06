# Lean & Agile Practices:

1. We're a company, just starting out on our DataScience / Machine Learning journey.
2. We don't have it all figured out yet. 
3. We're still filling the Data Warehouse / Data Lake with stuff.
4. But in terms of infrastructure, we are using GCP Cloud and going "server less" where possible, Ex: BigQuery

These two pics will continue to be displayed until awareness improves. I.e. until the end of the AI hype. :-)
![](https://github.com/ankumar/Architecture/blob/master/images/The%20AI%20Hierarchy%20of%20Needs.png)
### The AI Hierarchy of Needs - https://hackernoon.com/the-ai-hierarchy-of-needs-18f111fcc007
![](https://github.com/ankumar/Architecture/blob/master/images/Hidden%20Technical%20Debt%20in%20ML%20Systems.png)
### Paper, Hidden Technical Debt in Machine Learning Systems - https://papers.nips.cc/paper/5656-hidden-technical-debt-in-machine-learning-systems.pdf
* **Most data-powered features lack the black box. There is usually better ROI for simpler functionality and automation of existing workflows.***

### 1. Strive to get from a push-based workflow (fill the lake) to a pull-based. i.e select use cases of business value and ingest the data they need into the lake.
### 2. Take use cases all the way and show value before embarking on new use cases.
### 3. Implement only what the use cases need, but first paint a clear long-term goal picture. Each step should take you towards this goal.
### 4. Only security and privacy needs proactive implementation. The rest can wait.
### 5. There is a tradeoff between data speed and innovation speed. Use the slowest form of integration your use cases can tolerate. Batch >> streaming >> microservices. Gravitate towards batch.
### 6. Use simple technology and don't over-engineer. New, shiny things make very little difference.
### 7. The only "new" technology that you need is a workflow orchestrator. They are simple, and glue your fragile components together to a robust system. 
### 8. Align your teams along the use cases, not by functionality. During the first year or two, each team should be able to deliver use cases from raw data to business value.
### 9. Make cross-functional teams, with sufficient combination of skills to be autonomous.
### 10. As a counter weight to entropy caused by autonomy, make conscious decisions on architecture and technology selections.
### 11. Constantly fight against entropy and limit heterogeneity and degrees of freedom.
### 12. Avoid components that cannot be managed through source code.
### 13. Keep your datasets immutable. Never change a dataset, unless there was a bug, and it is incorrect.
### 14. Collect and store raw data without processing first. 
### 15. For collected personal data, split the PII out and make a link to the personal data to prepare for deletion.
### 16. Separate integration from computation. Computation should be performed without awareness of coordinates, and be easily testable. Data transfer and integration should be a separate step. E.g. for egress, first save results to a lake dataset, then copy to a destination database
### 17. When collecting events, avoid processing, improving quality, or reordering. Collect the raw events and partition by arrival time, then curate events in batch (or stream) processes. Curation needs depend on downstream use, and you should avoid making a global decision.
