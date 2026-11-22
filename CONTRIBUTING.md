## Contributing

This file contains general guidelines for how to contribute to HEMA Ratings projects. Each project may contain additional rules or guidelines.

## General guidelines

Keep pull requests small and self-contained, with commit messages describing not only the "what", but also the "why" of any proposed changes.

## 🟢 Green — Contributions welcome 

Any of the following can be worked on immediately, and contributors are free to open a pull request without first discussing with the HEMA Ratings team:

* Issues opened by the HEMA Ratings team
* Improvements that rely on the existing data model
* GUI bugs
* Minor bugs like logic or math bugs

In order to avoid several people working on the same thing independently, please open an issue before you start your work.


## 🟡 Discuss before contributing

Any of the following require a discussion with the HEMA Ratings team before starting work:

* New features
* Improvements to existing features that require pulling existing data into views/feature where the data isn't already used

## 🔴 Red — Serious discussion needed

Any of the following will require a serious discussion and the involvement of the HEMA Ratings as part of the development process:

* Changes to the data model
* Changes to the ratings calculator
* Features that touch multiple projects

## ⚫ Black — Probably won't implement

Suggestions of features that will result in adding more workload to the HEMA Ratings team to maintain will probably be rejected.

An example of a deceptively simple change that has been suggested several times is adding club history to fighters. Adding club history would require making some fairly minor changes to the database and the public-facing website, but it would also probably require changes to several of the following:

* The data template
* The submitter
* The admin tools
* Upstream event organizer software

Most importantly it would probably also add work to the HEMA Ratings team, as it's hard to imagine an implementation of this feature that doesn't require additional manual work by the HEMA Ratings team in order to keep the history updated. 
