Site reliability engineering @ google
=====================================

Incentives:

- Hire only **coders** and let them leave the project if they wish.
- Have a written **service level agreement (SLA)** for the service, and measure performance against it
- Use **error budgets** as your launch criteria
- make the system **scale**
- **Common staffing pool**, every SRE costs a DEV, and the converse
- Cap SRE **operational load** at 50%, usually ~30%
- **Practice, practice, practice**. Done right, it is fun.
- **Post mortems** are blameless


System in practice:

- error budgets result out of the SLA (i.e. 99,99% uptime)
- SREs handle errors in the deployed site. If the errors exceed the amount the SREs can handle, DEVs are forced to resolve these errors.
- DEVs resolving errors results in less new features being developed because of the lack of personel --> **self-regulating system**
- Unused error budgets are spend for "triggered errors", for example nodes get taken out of the system to learn/test the resilience of the application.


Further information:

- Ben Treynors "Keys to Site reliability engineering" keynote: https://www.usenix.org/conference/srecon14/technical-sessions/presentation/keys-sre
- Interview with Ben Treynor: https://landing.google.com/sre/interview/ben-treynor.html


Related google job offers:

https://www.google.com/about/careers/search#t=sq&q=j&d=site%20reliability&li=10&j=site%20reliability
