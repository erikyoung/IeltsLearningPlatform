# Project *Name of App*

*Name of App* is a Ruby on Rails application that provides a community to help students who want to have support from teachers or other students to improve their writing skills for preparing IELTS Exam.

- Submitted by: ETM Team
- URL: 

## User Stories

#### Coin

* [ ] Coin is the reward for a teacher after correcting a writing of a student.
* [ ] For each task the teacher requires an amount of coin, and wait for accepting from the student.
* [ ] The student can have a discount from the system and pay a part of the required amount from the teacher.
* [ ] User can buy coin to top up their account.
* [ ] User can exchange their coins into money.
* [ ] For each transaction User need to give their 4 digits PIN code to confirm.
* [ ] User receive an notification email after every transaction.
* [ ] User can check their transaction history.
* [ ] User can send coin to their friend or other member.

#### Task

There are two types of writing task in a IELTS Exam
  - Summarize, describe or explain a table, graph, chart or diagram in at least 150 words
  - Letter writing task of at least 150 words
  - Short essay task of at least 250 words

* [ ] User can create/edit/delete their own task before publish it.
* [ ] If the task is type 1, User can upload an image file of the table, graph, chart or diagram.
* [ ] User can publish their task for other students to submit their writing.
* [ ] User can see all published task and start writing then submit it.


#### Writing

* [ ] User can submit the writing of their own task.
* [ ] By submitting a writing, User can choose public (all others can read it) or private (only who wrote it and the owner of the task can read it)
* [ ] By submitting a writing User can also choose "Ask for help" so that other User can give an offer to correct the writing. A writing with "Ask for help" status is automatically public writing.
* [ ] Before submitting a writing, User can save it as a draft, and only he/she can see it.

#### Offer

* [ ] Teachers can offer a price (an amount of coin) to correct the writing with status "Ask for help".
* [ ] Student who wrote it can see the profile of the teachers who offer him an price, including how many jobs the teacher has done, rating from the students who worked with the teacher.
* [ ] Student can choose a teacher for helping him to correct his writing if his account has enough coin to pay for the teacher.

#### Correcting

* [ ] After closing the deal, Teacher can start working on Student's writing.
* [ ] Teacher can make highlights, comments, suggestions on the writing.
* [ ] To finish Teacher can give a score and final comment for the writing.
* [ ] Student can receive the result after Teacher submit his correcting.
* [ ] Student can confirm it and give the Teacher a rating for his work, the coin will be automatically send from Student's account to the teacher.
* [ ] Student can refuse the result if it doesn't satisfy him, he must give an reason for that and the admin can review it and give them final decision. (Quality Control)

#### Users

* [ ] User can sign up by providing their email, password and name.
* [ ] User can login using an email and password.
* [ ] Users can be both teacher (who correct the writing task) or student (who submit their text).
* [ ] There are Admin roles to manage the system.

#### Admin

* [ ] Admin can get reports of transaction, statistics of the system.
* [ ] Admin can review special case like Student refused Teacher's work.
* [ ] Admin can activate, deactivate User
* [ ] Admin can search User by name, email, phone to check User Profile
* [ ] Admin can top up User's account (in case of wiring money to system's account or giving cash).


## Video Walkthrough

Here's a walkthrough of implemented user stories:

![Video Walkthrough](/app/assets/xxx.gif)

## License

    Copyright 2017 ETM Team

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
