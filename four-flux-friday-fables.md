# Four Fables

subtitle
:   Four Flux Friday Fables
author
:   Kingdon Barrett

institution
:   Weaveworks
content-source
:   Flux Friday

date
:   2021-04-23
allotted-time
:   60m
start-time
:   2021-04-23T10:00:00-04:00
end-time
:   2021-04-23T11:00:00-04:00

# Four Fabulous Flux Fables

  * Jenkins + Flux
  * What is GitOps?
  * GitOps Hands-On Overview
  * GitOps Best Practices

# Jenkins

  * We love using Jenkins
  * {::wait/}Invested
  * {::wait/}Ecosystem
  * {::wait/}Use Jenkins for Everything

# Jenkins

  * Pipelines
  * {::wait/}Workflows
  * {::wait/}Hogwash

# Jenkins + Flux (1/3)

  * Jenkins-CI
  * Flux-CD
  * {::wait/}CI - Build OCI Images
  * {::wait/}CD - Deploy OCI Images

# Jenkins + Flux (2/3)

  * There is no intersection
  * {::wait/}Use one tool for one job
  * {::wait/}Other tool use for other

# Jenkins + Flux (3/3)

  * Thanks for coming to my TED Talk

# Jenkins + Flux (4/...)

  * Not the whole story
  * There is some new information we can share

# Jenkins + Flux

  * What is GitOps?
  * {::wait/}(according to Flux?)

# Jenkins + Flux

  * Declarative
  * Pull-based
    * (or Push-based){::wait/}
  * {::wait/}Revision Control (Git)
  * {::wait/}Automation reconciles (closed loop)

# Jenkins + Flux

  * What is GitOps?
  * Declarative, Pull-based
  * {::wait/}Image Automation - Write to Git
  * {::wait/}Git - Single Source of Truth

# Flux

  * Image Update Automation
  * {::wait/}Select Latest Image By (...)
  * {::wait/}Sortable Image Tags
  * {::wait/}{branch}-{sha}-{ts}

# Flux v2

  * image-reflector-controller
  * {::wait/}image-automation-controller

# Flux v2

  * ImagePolicy
  * {::wait/}SemVer
  * {::wait/}Alphabetical (CalVer)
  * {::wait/}Numerical

# Flux (v2)

  * Tagging/Version
  * {::wait/}5.2.9 - SemVer (Production)
  * {::wait/}dev-29abc8fe-997 (Development)
  * {::wait/}Numerical Build ID

# Jenkins + Flux v1

  * Select Latest Image By Build Time
  * {::wait/}Image Layer Metadata (pull)
  * {::wait/}Deprecated Feature

# Jenkins + Flux v1

  * {::wait/}Deprecated Feature
  * {::wait/}Very inefficient implementation
  * {::wait/}Rate limited by Docker Hub
  * {::wait/}Inflated Image Pull User Numbers

# Jenkins + Flux v2

  * ~~Latest Image By Build Time~~
  * Deprecated Feature
  * {::wait/}Use Sortable Image Tags

# Jenkins

  * How to actually build container images
  * In 2016-2020: Use Privileged Pod, mount /var/run/docker.sock
  * {::wait/}Assume Kubernetes host runs Docker
  * {::wait/}(no -- bad!)

# Jenkins (in 2021 and beyond)

  * buildkitd, cli for kubernetes
  * {::wait/} (rootless containers!)
  * {::wait/}unprivileged userns
  * {::wait/}Most vulnerable kernel code (?)

# CI-Cluster

  * Multi-tenancy is hard
  * {::wait/}Jenkins may break some rules
  * {::wait/}Keep Well Separated from Production
  * {::wait/}Don't feed after midnight, no water

# Laugh Break

  * {::wait/}Backhanded Letters of Reference
  * {::wait/}“You would be fortunate to get this person to work for you.”

# Laugh Break

  * Backhanded Letters of Reference
  * {::wait/}“There is nothing you can teach him.”

# Laugh Break

  * Backhanded Letters of Reference
  * {::wait/}“I refer him with no qualifications whatsoever.”

# Laugh Break

  * Backhanded Letters of Reference
  * The Lexicon of Intentionally Ambiguous Recommendations (L.I.A.R.) Paperback – October 1, 2003

# Story Time

  * Jenkins + Flux Tutorial
  * {::wait/}(Anything) + Flux
  * {::wait/}GitHub Actions 🥳 🧇

# Jenkins - Build Docker Images

  * {::wait/}Maybe don't?
  * {::wait/}Jenkins-X
  * {::wait/}More k8s-centric build tools
  * {::wait/}You can use it
  * {::wait/}😩 Weary Face Emoji

# Jenkins

  * How are you building images?
  * {::wait/}Examples
  * {::wait/}Declarative Jenkinsfile
  * {::wait/}(privileged pod, assume Docker)

# Jenkins

  * Q & A - Audience

# Talks

  * More Talks, All Day Long

# What is GitOps?

  * Intro to GitOps
  * Slides
  * https://docs.google.com/presentation/d/137O--3pOy8kAjoHUa2-L0Dctwa9uIF7PQWUcab5Jw0w/edit#slide=id.gd143cf9a61_0_0

# GitOps Hands-On Overview

  * https://eks.handson.flagger.dev/prerequisites/

# GitOps Best Practices

  * https://www.gitops.tech/
