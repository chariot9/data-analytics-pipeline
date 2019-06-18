# Build a Big Data Analytics Pipeline
### Context
Design A Google Analytic like Backend System. We need to provide Google Analytic like services to our customers. Pls provide a high level solution design for the backend system. Feel free to choose any open source tools as you want.

### Critical Parameters of the System
-	Handle large write volume: Billions write events per day
-	Handle large read/query volume: Millions merchants want to get insight about their business. Read/Query patterns are time-series related metrics.
-	Show Low Latency: Provide realtime metrics and provide metrics to customers with at most one hour delay.
-	SLA: run with minimum downtime.
-	Be economical: have the ability to reprocess historical data in case of bugs in the processing logic.
-	Be scalable
-	Be flexible
