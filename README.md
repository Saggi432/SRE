# SRE

Service Level Objectives from the SRE Book - https://landing.google.com/sre/books/

"It's impossible to manage a service correctly, let alone well, without understanding which behaviors really matter for that service and how to measure and evaluate those behaviors. To this end, we would like to define and deliver a given level of service to our users, whether they use an internal API or a public product.

"We use intuition, experience, and an understanding of what users want to define service level indicators (SLIs), objectives (SLOs), and agreements (SLAs). These measurements describe basic properties of metrics that matter, what values we want those metrics to have, and how we'll react if we can't provide the expected service. Ultimately, choosing appropriate metrics helps to drive the right action if something goes wrong, and also gives an SRE team confidence that a service is healthy.

"An SLI is a service level indicator—a carefully defined quantitative measure of some aspect of the level of service that is provided.

"Most services consider request latency — how long it takes to return a response to a request — as a key SLI. Other common SLIs include the error rate, often expressed as a fraction of all requests received, and system throughput, typically measured in requests per second. Another kind of SLI important to SREs is availability, or the fraction of the time that a service is usable. It is often defined in terms of the fraction of well-formed requests that succeed. Durability — the likelihood that data will be retained over a long period of time — is equally important for data storage systems. The measurements are often aggregated: i.e., raw data is collected over a measurement window and then turned into a rate, average, or percentile."
