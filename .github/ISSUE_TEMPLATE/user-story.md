---
name: User story
about: This template is for creating user stories
title: ''
labels: ''
assignees: ''

---

**As a** Store manager
 **I need** a counter
 **So that** I can keep track of stock
   
 ### Details and Assumptions
 * My store sells clothes and accepts returns.
   
 ### Acceptance criteria
   
 ```gherkin
 Given I have 5 shirts in stock
 When Customer returns shirt
 Then I have 6 shirts in stock
 ```
