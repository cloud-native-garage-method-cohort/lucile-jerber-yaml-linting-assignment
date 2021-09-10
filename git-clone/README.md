1. YAML is the format used by Kubernetes and Tekton. Find an open source Tekton Task for Linting YAML files. 

**2. Next, create a public repository in the cohort's GitHub organization.**

**3. In that repository put a mixture of valid and invalid YAML files.** 

4. Create a Pipeline that uses git-clone and the Task you found to lint the YAML files in your repository. 

5. Correct your invalid YAML and commit that to the repository you made. 

6. Re-run your pipeline. 

7. Make a commit to the assignments repository with two files: (1) your Pipeline YAML and (2) a text file, named yaml-linting-pipeline.log, that contains the Logs of your pipeline run.