- title : RUN Suggestions
- description : Suggestions for RUN Improvements
- author : David Cumps
- theme : solarized
- transition : default

***

### Suggestions for RUN Improvements

<ul>
<li class="fragment roll-in">Observations</li>
<li class="fragment roll-in">Suggestions</li>
</ul>

***

### Observations

<p class="fragment roll-in">Took on a spectator role to see the current situation</p>

<ul>
<li class="fragment roll-in">Project diversity</li>
<li class="fragment roll-in">Project quality</li>
</ul>

***

### Project diversity

<p class="fragment roll-in">Each project has their own solution to common tasks:</p>

<ul>
<li class="fragment roll-in">Building the project</li>
<li class="fragment roll-in">Deploying the project</li>
<li class="fragment roll-in">Following up requests & issues</li>
<li class="fragment roll-in">Responding to anomalies</li>
</ul>

---

### Building the project

<p class="fragment roll-in">Projects are currently build using:</p>

<ul>
<li class="fragment roll-in">Manual processes</li>
<li class="fragment roll-in">Custom scripts, run locally</li>
<li class="fragment roll-in">TeamCity<span class="fragment roll-in">, CruiseControl</span><span class="fragment roll-in">, TFS</span></li>
</ul>

---

### Deploying the project

<p class="fragment roll-in">Current ways projects deploy their deliverables:</p>

<ul>
<li class="fragment roll-in">Manual process</li>
<li class="fragment roll-in">Custom scripts, run locally</li>
<li class="fragment roll-in">Fragile documentation, inter-department</li>
</ul>

---

### Following up requests & issues

<p class="fragment roll-in">Teams manage their tasks using:</p>

<ul>
<li class="fragment roll-in">Word of mouth</li>
<li class="fragment roll-in">Excel<span class="fragment roll-in">, Post-its</span><span class="fragment roll-in">, Email</span><span class="fragment roll-in">, TFS</span></li>
<li class="fragment roll-in">External tools (e.g. Trello, ...)</li>
<li class="fragment roll-in">Jira<span class="fragment roll-in">, SM7</span><span class="fragment roll-in">, HP ALM</span></li>
</ul>

---

### Responding to anomalies

<p class="fragment roll-in">Current possibilities to come aware of anomalies:</p>

<ul>
<li class="fragment roll-in">Word of mouth</li>
<li class="fragment roll-in">Phone<span class="fragment roll-in">, Email</span></li>
<li class="fragment roll-in">Jira<span class="fragment roll-in">, SM7</span></li>
</ul>

<p class="fragment roll-in">Worst case takes days to reach the correct people</p>

***

### Project quality

<p class="fragment roll-in">Different levels of quality exist:</p>

<ul>
<li class="fragment roll-in">Documentation</li>
<li class="fragment roll-in">Coding practices</li>
<li class="fragment roll-in">Testing practices</li>
<li class="fragment roll-in">Monitoring<span class="fragment roll-in">, Debugging</span></li>
<li class="fragment roll-in">Versioning<span class="fragment roll-in">, Release management</span></li>
</ul>

<p class="fragment roll-in">All of this eventually goes into production!</p>

---

### Documentation

<p class="fragment roll-in">Documentation is currently:</p>

<ul>
<li class="fragment roll-in">Not present at all...</li>
<li class="fragment roll-in">Text files<span class="fragment roll-in">, Word</span></li>
<li class="fragment roll-in">Sharepoint<span class="fragment roll-in">, Athena</span></li>
</ul>

---

### Coding practices

<ul>
<li class="fragment roll-in">Different skill levels</li>
<li class="fragment roll-in">Different review practices
<ul>
<li class="fragment roll-in">No reviews at all...</li>
<li class="fragment roll-in">Half yearly review</li>
<li class="fragment roll-in">Peer review</li>
</ul></li>
</ul>

---

### Testing practices

<p class="fragment roll-in">Several variations of testing exists:</p>

<ul>
<li class="fragment roll-in">Manual testing</li>
<li class="fragment roll-in">Unit tests</li>
<li class="fragment roll-in">Integration tests</li>
</ul>

<p class="fragment roll-in">These are either run manually, or automated</p>

---

### Monitoring

<p class="fragment roll-in">Monitoring exists, this is either:</p>

<ul>
<li class="fragment roll-in">Minimally implemented</li>
<li class="fragment roll-in">Implemented only on an infrastructure level</li>
<li class="fragment roll-in">Functionally implemented</li>
</ul>

---

### Debugging

<p class="fragment roll-in">To find out information about a system there is:</p>

<ul>
<li class="fragment roll-in">Nothing foreseen</li>
<li class="fragment roll-in">Basic documentation with SQL queries</li>
<li class="fragment roll-in">Log files</li>
<li class="fragment roll-in">Dedicated debug screens</li>
</ul>

***

### Suggestions

<p class="fragment roll-in">Successful approaches from various projects</p>

<ul>
<li class="fragment roll-in">Project management</li>
<li class="fragment roll-in">Project follow-up</li>
<li class="fragment roll-in">Project quality</li>
</ul>

***

### Project Management

<p class="fragment roll-in">Provide dependable ways to build and deploy</p>

<ul>
<li class="fragment roll-in">Avoids human error</li>
<li class="fragment roll-in">Avoids slight deviations</li>
<li class="fragment roll-in">Increases trust in project</li>
<li class="fragment roll-in">Facilitate easier maintenance</li>
</ul>

---

### Building

<p class="fragment roll-in">Provide a limited set of supported choices which:</p>

<ul>
<li class="fragment roll-in">Should be able to fetch and build successfully</li>
<li class="fragment roll-in">Should be able to run automatically by build server</li>
</ul>

<p class="fragment roll-in">Having this in place will facilitate:</p>

<ul>
<li class="fragment roll-in">Easier maintenance</li>
<li class="fragment roll-in">Better developer introduction/handover</li>
</ul>

---

### Deploying

<p class="fragment roll-in">Provide single deployment strategy</p>

<ul>
<li class="fragment roll-in">No manual deployments</li>
<li class="fragment roll-in">Support different environments</li>
<li class="fragment roll-in">Support quick feedback loop</li>
</ul>

<p class="fragment roll-in">Facilitates trust in deployed versions</p>

***

### Project Follow-up

<p class="fragment roll-in">Provide clear and user-friendly way to:</p>

<ul>
<li class="fragment roll-in">Get project status<span class="fragment roll-in"> (Scrum / Kanban)</span></li>
<li class="fragment roll-in">Keep track of internal progress</li>
<li class="fragment roll-in">Link progress to code and deployment</li>
</ul>

***

### Project Quality

<p class="fragment roll-in">Reviews are currently done by people who will not maintain it</p>

<p class="fragment roll-in">Involvement is not continuous and too late</p>

<p class="fragment roll-in">No feedback to increase skill levels</p>
