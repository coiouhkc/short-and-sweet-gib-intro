---
marp: true
title: Short and sweet intro to GIB
description: Short and sweet intro to GIB
theme: uncover
paginate: true
_paginate: false



---

# Short and sweet

## Intro to GIB (gitflow-incremental-builder)

---

# Intro, reason & background

* monorepo vs. polyrepo

<!-- 
* build times
* gradle-like
* only what's changed
-->

---

# Demo 1

## Simulation using plain maven

<!--
mvn clean install

mvn clean install -am -pl :sub1

mvn clean install -amd -pl :sub1

mvn clean install -am -pl :sub3

mvn clean install -amd -pl :sub3

mvn clean install -am -pl :sub4

mvn clean install -amd -pl :sub4
-->

---

# Demo 2

## GIB

<!--

git checkout -b feature/test-gib

mvn clean install

mvn clean install -Dgib.buildAllIfNoChanges=true

# change sub1/pom.xml

mvn clean install

# reset

# change sub3/pom.xml

# reset

# change sub4/pom.xml

-->

---

# Links

* https://github.com/gitflow-incremental-builder/gitflow-incremental-builder
* https://github.com/gitflow-incremental-builder/gitflow-incremental-builder?tab=readme-ov-file#configuration

---

# Q&A