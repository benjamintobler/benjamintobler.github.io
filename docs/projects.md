Coordinated development of DB engine client and storage API development.
Teams based in Palo Alto and Seattle.
Client used RPC stack I developed.
Evolved API and guided development decisions enabling the new remote team to contribute effectively.

Aurora RPC implementation and optimization.
Profiled and optimized hot path to achieve close to line rate RPC capability.
Avoided classes of mallocs in C++ std library implementation.
Avoided other operations requiring cross thread syncronization.

Control plane data store live migration from DDB to Aurora Postgres.
Development velocity case for new API and flexiblity vs cost.
Identified and addresses business and cost and supporting team use cases.
Built cost model.
Identified key performance and availability criteria.
Developed corresponding benchmarks and tests.
Successfully motivated for project.
Successfully executed project that required signicant engineering resources.
Delivered in timeline to ensure minimal impact on feature velocity.
Enabled fast API evolution, analytic business queries and easier operational insight.

10K connection support for Java pre JDK support for non-blocking I/O.
Use JNI to access Windows completion port API.
Enabled customers to use single transaction processor to serve thousands of ATMs and POS terminals.

Vender independent HSM API.
Java API to EFT cryptographic operations.
Supported 3 different HSM products.
Enabled simple HSM access through EFT SDK for internal and customer developers.

Load shedder. Dynamic request rate limiter using PID controller.
Set point and process variable are request latency. 
Proportion accounts for current severity of load.
Integral accounts for history of load.
Derivative accounts for predicated future load based on rate of load change.
Provided defence in-depth.

Extended microservice generator by developing service framework SDK for OCI control plane teams.
Determined actual need by collaboration and source code repository auditing.
Delivered ephemeral object, e.g. idempotency tokens & operation identifiers, G and tombstoning.
Suite of service resilience mechanism, e.g. PID based load shedder & circuit breaker.

