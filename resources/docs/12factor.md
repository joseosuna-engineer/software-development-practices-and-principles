# The Twelve Factors


<img src="..//images/12-fact.PNG" align="left"  width="200" />

The [twelve-factor](resources/docs/12factor.md) methodology can be applied to apps written in any programming language, and which use any combination of backing services (database, queue, memory cache, etc). <br />

From https://12factor.net




**I. Codebase** <br />
One codebase tracked in revision control, many deploys <br />

**II. Dependencies** <br />
Explicitly declare and isolate dependencies <br />

**III. Config** <br />
Store config in the environment <br />

**IV. Backing services** <br />
Treat backing services as attached resources <br />

**V. Build, release, run** <br />
Strictly separate build and run stages <br />

**VI. Processes** <br />
Execute the app as one or more stateless processes <br />

**VII. Port binding** <br />
Export services via port binding <br />

**VIII. Concurrency** <br />
Scale out via the process model <br />

**IX. Disposability** <br />
Maximize robustness with fast startup and graceful shutdown <br />

**X. Dev/prod parity** <br />
Keep development, staging, and production as similar as possible <br />

**XI. Logs** <br />
Treat logs as event streams <br />

**XII. Admin processes** <br />
Run admin/management tasks as one-off processes <br />
