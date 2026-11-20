# 02 --- SDLC, Agile & DevOps Lifecycle

## 🟢 P1 --- Fundamentals

### Q1. What is SDLC?

**Answer:**

> SDLC stands for Software Development Life Cycle. It is a structured
> process used to plan, develop, test, deploy, and maintain software.
> Typical stages include requirement gathering, planning, design,
> development, testing, deployment, and maintenance.

------------------------------------------------------------------------

### Q2. What is Agile?

**Answer:**

> Agile is a software development approach that focuses on iterative
> development, frequent delivery, collaboration, and continuous customer
> feedback. Instead of delivering everything at once, the team delivers
> smaller increments of working software.

------------------------------------------------------------------------

### Q3. What is Scrum?

**Answer:**

> Scrum is an Agile framework that organizes work into fixed-length
> iterations called sprints. It uses practices such as sprint planning,
> daily scrum, sprint review, and retrospective to help teams deliver
> and continuously improve.

------------------------------------------------------------------------

### Q4. What is a Sprint?

**Answer:**

> A sprint is a fixed time period in which a Scrum team works on a
> selected set of tasks from the product backlog. A sprint commonly
> lasts between one and four weeks.

------------------------------------------------------------------------

### Q5. What is DevOps?

**Answer:**

> DevOps is a combination of culture, practices, processes, and
> automation that improves collaboration between development and
> operations teams. Its goal is to deliver software faster, more
> reliably, and more consistently.

------------------------------------------------------------------------

### Q6. What is the DevOps lifecycle?

**Answer:**

> The DevOps lifecycle generally includes planning, coding, building,
> testing, releasing, deploying, operating, monitoring, and continuous
> feedback. These stages form a continuous loop rather than a one-time
> process.

------------------------------------------------------------------------

### Q7. What is CI?

**Answer:**

> Continuous Integration is the practice of frequently integrating code
> changes into a shared repository and automatically building and
> testing those changes. It helps detect integration and code issues
> early.

------------------------------------------------------------------------

### Q8. What is Continuous Delivery?

**Answer:**

> Continuous Delivery is the practice of automatically building,
> testing, and preparing software so that it can be released to
> production at any time. Production deployment may still require manual
> approval.

------------------------------------------------------------------------

### Q9. What is Continuous Deployment?

**Answer:**

> Continuous Deployment automatically deploys code to production after
> it passes the required automated checks, without requiring manual
> approval for every release.

------------------------------------------------------------------------

### Q10. Continuous Delivery vs Continuous Deployment?

  -----------------------------------------------------------------------
  Continuous Delivery                 Continuous Deployment
  ----------------------------------- -----------------------------------
  Automatically prepares software for Automatically releases software
  release                             

  Production approval may be required No manual approval required

  Code is always deployable           Successful changes are
                                      automatically deployed
  -----------------------------------------------------------------------

------------------------------------------------------------------------

# 🟠 P2 --- Important

### Q11. What is the difference between Agile and Waterfall?

> Waterfall follows a mostly sequential development process where stages
> are completed one after another. Agile uses iterative development,
> allowing teams to deliver smaller increments frequently and adapt to
> changing requirements.

------------------------------------------------------------------------

### Q12. What is the difference between DevOps and Agile?

> Agile primarily focuses on improving software development through
> iterative delivery and feedback. DevOps extends the focus across
> development, deployment, operations, automation, and monitoring to
> improve the complete software delivery lifecycle.

------------------------------------------------------------------------

### Q13. Is DevOps a tool?

> No. DevOps is not a single tool or technology. It is a combination of
> culture, practices, processes, and automation. Tools such as Git,
> Jenkins, Docker, Kubernetes, Terraform, and AWS help implement DevOps
> practices.

------------------------------------------------------------------------

### Q14. Why is automation important in DevOps?

> Automation makes processes faster, repeatable, and consistent while
> reducing manual errors. It can automate activities such as testing,
> building, deployment, infrastructure provisioning, and monitoring.

------------------------------------------------------------------------

### Q15. Why is CI/CD important?

> CI/CD reduces manual work and enables teams to deliver software more
> frequently and reliably. Automated builds and tests also help detect
> problems earlier in the development lifecycle.

------------------------------------------------------------------------

# 💎 P3 --- Higher-value questions

### Q16. A developer says, "My code works on my machine, but it fails in production." How can DevOps help?

Think about:

``` text
Environment consistency
        ↓
Containers
        ↓
Infrastructure as Code
        ↓
Automated testing
        ↓
CI/CD
        ↓
Monitoring
```

**Interview answer:**

> DevOps helps reduce environment differences through practices such as
> containerization and Infrastructure as Code. CI/CD can automatically
> build and test the application in a consistent environment before
> deployment, while monitoring helps identify issues after deployment.

------------------------------------------------------------------------

### Q17. Why shouldn't everything be deployed manually?

> Manual deployment is slower, difficult to reproduce, and more prone to
> human error. Automation makes deployments consistent, repeatable,
> auditable, and easier to roll back.

------------------------------------------------------------------------

### Q18. What happens when a deployment fails?

This is where your future troubleshooting mindset starts.

A good approach is:

``` text
Identify failure
      ↓
Check pipeline logs
      ↓
Identify failed stage
      ↓
Check application/infrastructure
      ↓
Rollback if required
      ↓
Fix root cause
      ↓
Redeploy
```
