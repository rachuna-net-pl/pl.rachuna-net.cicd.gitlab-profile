::include{file=.gitlab/badges.md}
# ![](https://gitlab.com/pl.rachuna-net/infrastructure/terraform/modules/gitlab-project/-/raw/main/images/gitlab.png){height=20px} Gitlab CI/CD

Pełna dokumentacja opisana jest na mojej stronie https://docs.rachuna-net.pl/projects/gitlab/Gitlab-CI/

**GitLab CI/CD** to wbudowany w GitLab system do automatyzacji budowania, testowania i wdrażania aplikacji. Procesy definiuje się w pliku `.gitlab-ci.yml`, który określa etapy (stages) i zadania (jobs). Pipeline’y uruchamiają **GitLab Runnery**, które wykonują kod i raportują wyniki. Dzięki CI/CD można zautomatyzować testy i wdrożenia, co usprawnia rozwój oprogramowania.

# Lista procesów
::include{file=docs/pipelines.md}

---
::include{file=docs/components.md}

::include{file=docs/main.md}
::include{file=.gitlab/contributions.md}
::include{file=.gitlab/license.md}
::include{file=.gitlab/authors.md}
